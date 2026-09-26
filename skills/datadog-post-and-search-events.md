---
generated: '2026-09-23'
method: generated
name: datadog-post-and-search-events
description: Post a Datadog event and search it back — the event-bus round trip for change tracking, deploys, and agent-driven annotations.
api: openapi/datadog-events-api-openapi.yml
operations: [CreateEvent, SearchEvents, ListEvents]
source: >-
  Grounded in openapi/datadog-events-api-openapi.yml (CreateEvent,
  SearchEvents, ListEvents). Every operationId is verified verbatim. Mirrors
  arazzo/datadog-post-and-search-events-workflow.yml.
---

# Post and search Datadog events

Attach a semantic event to your Datadog timeline (deploy, config change, agent action) and search for it once it's indexed.

## Auth
- `DD-API-KEY` + `DD-APPLICATION-KEY`. Requires `events_read` for search; write scope is implicit on API-key auth.
- Base URL: `https://api.{site}`.

## Steps
1. **Post the event** — `CreateEvent` (`POST /api/v2/events`). JSON:API document with `data.type: event` and attributes: `title`, `text`, `tags[]` (include a scoped `agent:<run-id>` tag), `category` (`change`, `alert`, etc.), and `source_type_name`. Capture `data.id`.
2. **Search for the event** — `SearchEvents` (`POST /api/v2/events/search`). Body includes `filter.query` (e.g., `"tags:agent:<run-id>"`), `filter.from`, `filter.to`, and `sort`. Poll with a bounded delay — indexing latency is seconds-scale.
3. **Optional list** — `ListEvents` (`GET /api/v2/events`) for a paginated view without a search query, useful for auditing what an org has emitted recently.

## Notes
- MCP tool: `search_datadog_events` (backs both SearchEvents + ListEvents). See `mcp/datadog-tool-crosswalk.yml`.
- `CreateEvent` is idempotent when the same `title`, `text`, `timestamp`, and `aggregation_key` are provided — reuse `aggregation_key` to fold retries into one visible event.
- `category=change` events participate in Change Tracking; pair with the `arazzo/datadog-post-and-search-events-workflow.yml` when reporting agent-initiated deploys.

## Errors
- `400 Bad Request` — malformed JSON:API body or invalid `category`.
- `403 Forbidden` — reads require `events_read`.
- `429 Too Many Requests` — inspect `X-RateLimit-Reset`.
