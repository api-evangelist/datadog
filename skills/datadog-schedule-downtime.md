---
generated: '2026-09-23'
method: generated
name: datadog-schedule-downtime
description: Schedule a Datadog downtime window that mutes matching monitors, confirm it, and cancel it early when the maintenance ends.
api: openapi/datadog-schedules-api-openapi.yml
operations: [CreateDowntime, GetDowntime, CancelDowntime]
source: >-
  Grounded in openapi/datadog-schedules-api-openapi.yml (CreateDowntime),
  openapi/datadog-get-api-openapi.yml (GetDowntime), and
  openapi/datadog-cancel-api-openapi.yml (CancelDowntime). Every operationId
  is verified verbatim. Mirrors arazzo/datadog-schedule-downtime-workflow.yml.
---

# Schedule a Datadog downtime

Announce planned maintenance to Datadog so matching monitors do not page while it is running — then cancel the downtime when maintenance ends.

## Auth
- `DD-API-KEY` + `DD-APPLICATION-KEY`. Requires `monitors_downtime` (and `monitors_read` for the confirmation step).
- Base URL: `https://api.{site}`.

## Steps
1. **Create the downtime** — `CreateDowntime` (`POST /api/v2/downtime`). JSON:API body with `type: downtime` and attributes including `monitor_identifier` (scope query or explicit `monitor_id`), `schedule.start`, `schedule.end` or `schedule.recurrences[]`, `message`, and `notify_end_states`. Capture `data.id`.
2. **Read it back** — `GetDowntime` (`GET /api/v2/downtime/{downtime_id}`). Confirm `attributes.status` is `active` (or `scheduled` when in the future) and that `scope` matches the intended tags.
3. **Cancel early when maintenance ends** — `CancelDowntime` (`DELETE /api/v2/downtime/{downtime_id}`). Successful cancellation returns `204 No Content`. Datadog resumes evaluating the muted monitors on the next check.

## Notes
- No first-class MCP tool for downtime scheduling — this is a governance path. Use OAuth-scoped credentials via the MCP Server plus `monitors_downtime`.
- For a recurring maintenance window, prefer `schedule.recurrences[]` over creating a downtime per occurrence.
- To list every downtime for auditing, call `ListDowntimes` (`GET /api/v2/downtime`) — captured in `openapi/datadog-all-api-openapi.yml`.

## Errors
- `400 Bad Request` — invalid schedule (end before start, unknown timezone).
- `403 Forbidden` — missing `monitors_downtime`.
- `404 Not Found` — downtime id already cancelled or from a different org.
