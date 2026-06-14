# Datadog GraphQL Schema

## Overview

This conceptual GraphQL schema models the Datadog observability and monitoring platform. Datadog does not currently expose a public GraphQL API; this schema is a structured representation of the core domain types derived from the Datadog REST API at https://docs.datadoghq.com/api/latest/. It is intended to serve as a reference for teams building integrations, tooling, or internal GraphQL layers on top of Datadog's REST endpoints.

## Source

- REST API Docs: https://docs.datadoghq.com/api/latest/
- GitHub Organization: https://github.com/DataDog
- Base URL: https://api.datadoghq.com

## Domain Coverage

The schema covers the following Datadog product areas:

### Metrics and Infrastructure
- `Metric`, `MetricSeries`, `MetricTag`, `MetricMetadata` — timeseries metric definitions, submissions, and tag/metadata management
- `Host`, `HostMute` — infrastructure host inventory and mute configurations

### Dashboards and Visualization
- `Dashboard`, `DashboardWidget`, `WidgetDefinition` — dashboard containers and widget placements
- `TimeseriesWidget`, `QueryValueWidget`, `TableWidget` — specific widget type definitions

### Monitors and Alerting
- `Monitor`, `MonitorState`, `MonitorThreshold`, `MonitorRecovery` — alert rule definitions and threshold configurations
- `Alert`, `AlertEvent` — triggered alert instances and event records
- `Downtime`, `DowntimeSchedule` — maintenance window scheduling

### Service Level Objectives
- `SLO`, `SLOHistory`, `SLOThreshold`, `SLOCorrection` — SLO definitions, burn rate history, and correction windows

### Application Performance Monitoring
- `APMTrace`, `TraceQuery`, `SpanFilter` — distributed trace capture and search
- `APMService`, `APMResource`, `APMError` — service topology, resource endpoints, and error aggregations

### Log Management
- `Log`, `LogIndex`, `LogPipeline`, `LogProcessor`, `LogFilter` — log ingestion, indexing, and pipeline processing
- `LogArchive`, `LoggingPath` — archive destinations and routing paths

### Security
- `SecuritySignal`, `SecurityRule`, `SecurityFinding`, `SecurityVulnerability` — SIEM signals, detection rules, and vulnerability findings

### Infrastructure Map and Events
- `InfrastructureMap` — topology view of infrastructure entities
- `Event`, `EventQuery` — event stream entries and search filters

### Incident Management
- `Incident`, `IncidentTimeline`, `IncidentTeam` — incident lifecycle, timeline entries, and team assignments

### Identity and Access Management
- `User`, `UserPermission`, `Team`, `Role` — user accounts, permission grants, and role definitions
- `Organization`, `APIKey`, `AppKey`, `AccessRequest` — org management and credential lifecycle

### Integrations and Webhooks
- `Integration`, `Webhook` — third-party integration configurations and outbound webhooks

### Billing and Cost
- `UsageSummary`, `Usage`, `BillableSummary`, `CloudCost` — metered usage data and cost attribution

### Service Catalog
- `ServiceCatalog`, `ServiceDefinition` — software catalog entries and ownership metadata

## Query Patterns

The schema exposes a top-level `Query` type supporting:

- `metrics(filter: MetricFilter)` — list and filter metrics
- `hosts(filter: HostFilter)` — search hosts by name, tag, or alias
- `dashboards` — list all dashboards
- `dashboard(id: ID!)` — fetch a single dashboard
- `monitors(filter: MonitorFilter)` — list monitors by state, tag, or type
- `monitor(id: ID!)` — fetch a single monitor
- `slos(filter: SLOFilter)` — list SLOs
- `slo(id: ID!)` — fetch an SLO with history
- `logs(query: LogQuery!)` — search log events
- `events(query: EventQuery!)` — search the event stream
- `traces(query: TraceQuery!)` — search APM traces
- `incidents(filter: IncidentFilter)` — list incidents
- `incident(id: ID!)` — fetch an incident with timeline
- `users` — list organization users
- `teams` — list teams
- `roles` — list roles
- `organization` — fetch organization details
- `apiKeys` — list API keys
- `appKeys` — list application keys
- `usageSummary(startMonth: String!, endMonth: String)` — retrieve usage metering data
- `cloudCosts(filter: CloudCostFilter)` — query cloud cost data
- `serviceCatalog` — list service catalog entries
- `securitySignals(filter: SecurityFilter)` — search security signals
- `integrations` — list configured integrations

## Mutation Patterns

- `createMonitor(input: CreateMonitorInput!)` — create a new monitor
- `updateMonitor(id: ID!, input: UpdateMonitorInput!)` — update a monitor
- `deleteMonitor(id: ID!)` — delete a monitor
- `muteMonitor(id: ID!, input: MuteInput!)` — mute a monitor
- `createDowntime(input: CreateDowntimeInput!)` — schedule a downtime
- `cancelDowntime(id: ID!)` — cancel a downtime
- `createDashboard(input: CreateDashboardInput!)` — create a dashboard
- `updateDashboard(id: ID!, input: UpdateDashboardInput!)` — update a dashboard
- `deleteDashboard(id: ID!)` — delete a dashboard
- `createSLO(input: CreateSLOInput!)` — create an SLO
- `updateSLO(id: ID!, input: UpdateSLOInput!)` — update an SLO
- `createIncident(input: CreateIncidentInput!)` — declare an incident
- `updateIncident(id: ID!, input: UpdateIncidentInput!)` — update an incident
- `resolveIncident(id: ID!)` — mark an incident resolved
- `createUser(input: CreateUserInput!)` — invite a user
- `createAPIKey(input: CreateAPIKeyInput!)` — create an API key
- `deleteAPIKey(id: ID!)` — delete an API key
- `createWebhook(input: CreateWebhookInput!)` — register a webhook
- `createSLOCorrection(input: CreateSLOCorrectionInput!)` — add an SLO correction window

## Authentication

Datadog REST API authentication uses:
- `DD-API-KEY` header — identifies the organization
- `DD-APPLICATION-KEY` header — identifies the user/application context

These would be passed as HTTP headers in any GraphQL gateway implementation layered over the REST API.

## Schema File

The accompanying `datadog-schema.graphql` file contains the full type definitions for all named types in this domain model.
