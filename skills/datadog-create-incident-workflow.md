---
name: datadog-create-incident-workflow
description: Create a new incident and attach related todos and integrations.
api: openapi/datadog-create-api-openapi.yml
operations:
- CreateIncident
- CreateIncidentTodo
- CreateIncidentIntegration
generated: '2026-09-23'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/datadog-create-api-openapi.yml ; every operationId checked against the contract
---

# datadog-create-incident-workflow

Create a new incident and attach related todos and integrations.

## Steps

1. 1. Call `CreateIncident` with the incident payload (requires `DD-API-KEY` and `DD-APPLICATION-KEY` headers).
2. 2. Call `CreateIncidentTodo` with `incident_id` path parameter and todo details (requires `DD-API-KEY` and `DD-APPLICATION-KEY` headers).
3. 3. Call `CreateIncidentIntegration` with `incident_id` path parameter and integration metadata (requires `DD-API-KEY` and `DD-APPLICATION-KEY` headers).

## Rules

- Authentication: include both `DD-API-KEY` and `DD-APPLICATION-KEY` headers for all requests.
- All endpoints return standard HTTP error codes on failure; handle non‑2xx responses accordingly.
