---
name: datadog-create-and-retrieve-event
description: Create a new event in Datadog and then retrieve it by its ID.
api: openapi/datadog-events-api-openapi.yml
operations:
- CreateEvent
- getEvent
generated: '2026-09-23'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/datadog-events-api-openapi.yml ; every operationId checked against the contract
---

# datadog-create-and-retrieve-event

Create a new event in Datadog and then retrieve it by its ID.

## Steps

1. 1. Call `CreateEvent` with the required request body fields (e.g., `title`, `text`, `priority`, `tags`).
2. 2. Capture the `event_id` returned in the response.
3. 3. Call `getEvent` with the path parameter `event_id` to retrieve the created event.

## Rules

- Auth: include either `DD-API-KEY` (apiKeyAuth) and `DD-APPLICATION-KEY` (appKeyAuth) headers, or use `bearerAuth` token.
- Errors: on failure the API returns standard HTTP error codes (e.g., 4xx for client errors, 5xx for server errors).
