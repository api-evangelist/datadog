---
name: datadog-get-incident-details
description: Retrieve an incident and its associated todos.
api: openapi/datadog-get-api-openapi.yml
operations:
- GetIncident
- ListIncidentTodos
- GetIncidentTodo
generated: '2026-09-23'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/datadog-get-api-openapi.yml ; every operationId checked against the contract
---

# datadog-get-incident-details

Retrieve an incident and its associated todos.

## Steps

1. 1. Call `GetIncident` with path parameter `incident_id`.
2. 2. Call `ListIncidentTodos` with path parameter `incident_id`.
3. 3. Call `GetIncidentTodo` with path parameters `incident_id` and `todo_id`.

## Rules

- Auth: include either `DD-API-KEY` (apiKeyAuth) or `DD-APPLICATION-KEY` (appKeyAuth) header, or use bearer token (bearerAuth).
- No rate limit is documented; on exhaustion the API returns no specific HTTP status.
