---
name: datadog-update-existing-incident
description: Update an existing incident and optionally its integration metadata.
api: openapi/datadog-existing-api-openapi.yml
operations:
- UpdateIncident
- UpdateIncidentIntegration
generated: '2026-09-23'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/datadog-existing-api-openapi.yml ; every operationId checked against the contract
---

# datadog-update-existing-incident

Update an existing incident and optionally its integration metadata.

## Steps

1. 1. Call `UpdateIncident` with the incident fields to modify (e.g., `title`, `status`, `fields`).
2. 2. If integration metadata needs to be changed, call `UpdateIncidentIntegration` with the integration fields (e.g., `metadata`, `type`).

## Rules

- Auth: Provide `DD-API-KEY` and `DD-APPLICATION-KEY` headers (apiKeyAuth and appKeyAuth).
- Auth: Bearer token may be used via `Authorization: Bearer <token>` (bearerAuth).
