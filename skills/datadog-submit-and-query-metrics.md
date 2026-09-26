---
generated: '2026-09-23'
method: generated
name: datadog-submit-and-query-metrics
description: Submit a custom metric time series to Datadog, then query it back with a scoped filter to confirm the write reached the query surface.
api: openapi/datadog-metrics-api-openapi.yml
operations: [SubmitMetrics, queryMetricsTimeseries, QueryTimeseriesData]
source: >-
  Grounded in openapi/datadog-metrics-api-openapi.yml (SubmitMetrics,
  queryMetricsTimeseries) and openapi/datadog-across-api-openapi.yml
  (QueryTimeseriesData). Every operationId is verified verbatim. Mirrors
  arazzo/datadog-submit-and-query-metrics-workflow.yml.
---

# Submit and query Datadog metrics

Ship a custom metric to Datadog and read it back — the smallest end-to-end proof that your metric surface is healthy.

## Auth
- `DD-API-KEY` for `SubmitMetrics`; `DD-API-KEY` + `DD-APPLICATION-KEY` for the query endpoints.
- Base URL: `https://api.{site}` (defaults to `api.datadoghq.com`).

## Steps
1. **Submit the metric batch** — `SubmitMetrics` (`POST /api/v2/series`). Body is `{ "series": [ { "metric": "<name>", "type": <count|gauge|rate>, "points": [{"timestamp": <unix>, "value": <n>}], "tags": ["env:<>","service:<>"] } ] }`. Gzip is supported via `Content-Encoding: gzip`. `202 Accepted` means the batch reached ingestion.
2. **Query the metric timeseries** — `queryMetricsTimeseries` (`POST /api/v2/query/timeseries`) with `data.attributes.queries[0].query` set to something specific like `avg:<name>{agent:<run-id>}` and `data.attributes.from`/`to` bracketing the write. Alternate alias: `QueryTimeseriesData` (same path).
3. **Confirm.** The returned `data.attributes.values[0]` should contain the point you wrote — subject to Datadog's ~30s aggregation delay.

## Notes
- MCP tools that touch metrics: `get_datadog_metric` (metadata), `get_datadog_metric_context` (tags), `search_datadog_metrics` (metric name search). Submission does not have an MCP tool by design.
- Keep tag cardinality bounded — high-cardinality writes trigger downsampling in the query path.
- For metadata edits (unit, description), pair with `arazzo/datadog-manage-metric-metadata-workflow.yml`.

## Errors
- `400 Bad Request` — malformed series (unknown `type`, missing `points`).
- `413 Payload Too Large` — batch above the 5 MB compressed limit.
- `429 Too Many Requests` — inspect `X-RateLimit-Reset`. Query throttling applies per site.
