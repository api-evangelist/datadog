---
generated: '2026-09-23'
method: generated
name: datadog-manage-api-keys
description: Create a Datadog API key, retrieve it by id, and list existing keys — the safe rotation flow for an agent given `api_keys_write`.
api: openapi/datadog-create-api-openapi.yml
operations: [CreateAPIKey, GetAPIKey, ListAPIKeys]
source: >-
  Grounded in openapi/datadog-create-api-openapi.yml (CreateAPIKey),
  openapi/datadog-get-api-openapi.yml (GetAPIKey), and
  openapi/datadog-all-api-openapi.yml (ListAPIKeys). Every operationId is
  verified verbatim. Mirrors arazzo/datadog-manage-api-keys-workflow.yml.
---

# Manage Datadog API keys

Rotate the credentials your agents present without leaving the Datadog control plane.

## Auth
- `DD-API-KEY` + `DD-APPLICATION-KEY` required. The caller needs `api_keys_write` for creates and `api_keys_read` for gets / lists.
- Base URL: `https://api.{site}` (`api.datadoghq.com` default).

## Steps
1. **List existing keys** — `ListAPIKeys` (`GET /api/v2/api_keys`). Supports `filter[name]`, `filter[category]`, `filter[created_at][start|end]`. Returns key metadata (no secret material).
2. **Create the new key** — `CreateAPIKey` (`POST /api/v2/api_keys`). Body is a JSON:API document `{ "data": { "type": "api_keys", "attributes": { "name": "<label>", "category": "customer" } } }`. The response returns `attributes.key` — this is the ONLY response that includes the raw secret. Store it immediately.
3. **Read the key back** — `GetAPIKey` (`GET /api/v2/api_keys/{api_key_id}`). Confirms the key exists and returns its metadata (again, no raw secret).
4. **Retire the old key** (out-of-band) — use `DeleteAPIKey` (`DELETE /api/v2/api_keys/{api_key_id}`) once dependent services have switched to the new key. See `openapi/datadog-delete-api-openapi.yml`.

## Notes
- No MCP tool wraps CreateAPIKey by design — key issuance is a governance action. Agents that must rotate should be given a scoped OAuth grant via the MCP Server plus a human-in-the-loop confirmation.
- `attributes.remote_config_read_enabled=true` is required if the key must be used by the Datadog Agent's remote configuration path.
- Every create / delete lands in Audit Trail with `event_name=UpdateAPIKey`/`CreateAPIKey`.

## Errors
- `403 Forbidden` — missing `api_keys_write`.
- `409 Conflict` — a key with the same `name` in the same `category` already exists.
- `422 Unprocessable Entity` — JSON:API `data.type` missing or malformed.
