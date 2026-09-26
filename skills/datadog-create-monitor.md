---
generated: '2026-09-23'
method: generated
name: datadog-create-monitor
description: Validate a monitor configuration, create it, and read it back — the safe path to standing up a Datadog monitor from an agent.
api: openapi/datadog-monitors-api-openapi.yml
operations: [validateMonitor, createMonitor, getMonitor]
source: >-
  Grounded in openapi/datadog-monitors-api-openapi.yml and
  openapi/datadog-monitor-validation-api-openapi.yml. Every operationId is
  verified verbatim in the corresponding split-per-tag spec. Auth per
  authentication/datadog-authentication.yml. Mirrors arazzo/datadog-create-monitor-workflow.yml.
---

# Create a Datadog monitor

Stand up a Datadog monitor safely: validate the configuration first, then create it, then read it back to confirm the query and thresholds persisted.

## Auth
- Send both `DD-API-KEY` and `DD-APPLICATION-KEY` request headers (`apiKeyAuth` + `appKeyAuth` in the spec). The MCP Server forwards the caller's OAuth-scoped credentials for the equivalent tool (`create_datadog_monitor`).
- Base URL: `https://api.{site}` (defaults to `https://api.datadoghq.com`; other sites include `us3.datadoghq.com`, `us5.datadoghq.com`, `ap1.datadoghq.com`, `datadoghq.eu`, `ddog-gov.com`).

## Steps
1. **Validate the configuration** — `validateMonitor` (`POST /api/v1/monitor/validate`). Send the exact `type`, `query`, `name`, `message`, `tags`, and `options.thresholds` payload you intend to persist. A `200` means the query parses and the thresholds are consistent. Any `400` here means the create will fail — do not proceed.
2. **Create the monitor** — `createMonitor` (`POST /api/v1/monitor`). Reuse the validated payload verbatim. Capture `id` from the response body.
3. **Read the monitor back** — `getMonitor` (`GET /api/v1/monitor/{monitor_id}`) with the id from step 2. Confirm `query`, `message`, `options.thresholds`, and `tags` match what you sent.

## Notes
- Prefer the `alerting` MCP toolset (`create_datadog_monitor`, `validate_datadog_monitor`) so RBAC (`monitors_write`) is enforced by Datadog.
- Idempotency: the create call is NOT idempotent — repeated POSTs create separate monitors. Guard with a tag such as `agent:<run-id>` and `search_datadog_monitors` before creating.
- To adjust an existing monitor's thresholds, use the sibling workflow `arazzo/datadog-tune-monitor-thresholds-workflow.yml`.

## Errors
- `400 Bad Request` — invalid query, unsupported monitor `type`, or missing threshold value. Message body includes `errors[]`.
- `403 Forbidden` — the caller lacks `monitors_write`. See `authentication/datadog-authentication.yml`.
- `429 Too Many Requests` — inspect `X-RateLimit-Reset`. See `rate-limits/datadog-rate-limits.yml`.
