---
generated: '2026-09-23'
method: generated
name: datadog-create-incident
description: Declare a Datadog incident, read it back, and follow up with an attributes patch to reflect status/severity changes.
api: openapi/datadog-create-api-openapi.yml
operations: [CreateIncident, GetIncident, UpdateIncident, ListIncidents]
source: >-
  Grounded in openapi/datadog-create-api-openapi.yml (CreateIncident),
  openapi/datadog-get-api-openapi.yml (GetIncident, ListIncidents),
  openapi/datadog-existing-api-openapi.yml (UpdateIncident). Every
  operationId is verified verbatim in its split-per-tag spec. Mirrors
  arazzo/datadog-create-incident-workflow.yml.
---

# Declare and manage a Datadog incident

Turn an actionable alert into a tracked incident: create it, confirm it, then patch severity / status as the response evolves.

## Auth
- `DD-API-KEY` + `DD-APPLICATION-KEY` on every call, or route through the Datadog MCP Server (`get_datadog_incident`, `search_datadog_incidents`). Incident writes require `incident_write`.
- Base URL: `https://api.{site}` (`api.datadoghq.com` by default).

## Steps
1. **Create the incident** — `CreateIncident` (`POST /api/v2/incidents`). Body is a JSON:API document with `type: incidents` and `attributes.customer_impact_scope`, `attributes.title`, and `attributes.fields.severity`. Capture the returned `data.id`.
2. **Read the incident back** — `GetIncident` (`GET /api/v2/incidents/{incident_id}`) with the id from step 1. Confirm `attributes.public_id`, `attributes.severity`, and `attributes.state`.
3. **Update severity or status** — `UpdateIncident` (`PATCH /api/v2/incidents/{incident_id}`). Send only the changed attributes (`state: resolved`, updated severity, or new `fields`). This is JSON:API — `data.type` and `data.id` are required in the body.
4. **List recent incidents** — `ListIncidents` (`GET /api/v2/incidents`) with `include=commanders,users` to enumerate the current queue for the org.

## Notes
- Prefer `SearchIncidents` (`GET /api/v2/incidents/search`) with a `query` filter over paginating `ListIncidents` for scoped lookups (e.g., by service, tag, state).
- The MCP tool `search_datadog_incidents` covers both list and search variants. See `mcp/datadog-tool-crosswalk.yml`.
- Attachments (links, notebooks, postmortems) are managed by the sibling workflow `arazzo/datadog-manage-incident-attachments-workflow.yml`.

## Errors
- `422 Unprocessable Entity` — JSON:API body malformed (missing `data.type`, unknown attribute). Inspect the returned `errors[]`.
- `403 Forbidden` — caller lacks `incident_write` or `incident_read`.
- `429 Too Many Requests` — respect `X-RateLimit-Reset`.
