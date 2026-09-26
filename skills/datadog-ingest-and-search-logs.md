---
generated: '2026-09-23'
method: generated
name: datadog-ingest-and-search-logs
description: Submit structured log events to Datadog, wait for indexing, then search them back — the round-trip an agent needs to verify log ingestion.
api: openapi/datadog-logs-api-openapi.yml
operations: [SubmitLog, ListLogs, AggregateLogs]
source: >-
  Grounded in openapi/datadog-logs-api-openapi.yml (SubmitLog, ListLogs) and
  openapi/datadog-aggregate-api-openapi.yml (AggregateLogs). Every operationId
  is verified verbatim. Mirrors arazzo/datadog-ingest-and-search-logs-workflow.yml.
---

# Ingest and search Datadog logs

Push a log event to Datadog and confirm it becomes searchable via the log intake -> index -> search round-trip.

## Auth
- `DD-API-KEY` is sufficient for `SubmitLog` (writes). `DD-APPLICATION-KEY` is required for `ListLogs` / `AggregateLogs` (reads).
- **Two hosts.** SubmitLog goes to the intake host `https://http-intake.logs.{site}`; ListLogs / AggregateLogs go to the API host `https://api.{site}`. Agents that share a single `base_url` will get the wrong endpoint for one of them.

## Steps
1. **Submit the log event** — `SubmitLog` (`POST /api/v2/logs`). Body is a JSON array of log entries with `ddsource`, `service`, `hostname`, `message`, and free-form JSON attributes. Optional gzip: set `Content-Encoding: gzip`. `202 Accepted` means intake accepted the batch — not that indexing has completed.
2. **Wait for indexing.** Datadog log indexing has second-scale latency; poll with a bounded delay before searching.
3. **Search the log event** — `ListLogs` (`POST /api/v2/logs/events/search`). Body includes `filter.query`, `filter.from`, `filter.to`, `sort`, and `page.limit`. Use a specific enough `filter.query` (e.g. include a `agent:<run-id>` tag you set on submit) to isolate the round-trip.
4. **Aggregate for analytics** — `AggregateLogs` (`POST /api/v2/logs/analytics/aggregate`) when you want counts / group-bys instead of raw events (e.g., `compute.aggregation=count`, `group_by[].facet=service`).

## Notes
- MCP equivalents: `search_datadog_logs` (backs `ListLogs`), `analyze_datadog_logs` (backs `AggregateLogs`). SubmitLog is intake-only — agents do not need an MCP tool for it and Datadog does not expose one.
- Long queries (>10s wall time) may return `X-Datadog-Received-Later-Than-Deadline: true`. Retry with a smaller `filter.from/to` window.
- For durable storage, pair with `arazzo/datadog-create-log-archive-workflow.yml`.

## Errors
- `400 Bad Request` — intake payload not a JSON array, or `message` exceeds 1 MB.
- `403 Forbidden` — reads require `logs_read_data` (and `logs_read_index_data` per index).
- `413 Payload Too Large` — batch >5 MB compressed / 5 MB per entry.
