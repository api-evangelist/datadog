# Datadog (datadog)

Datadog is a monitoring and analytics platform that helps organizations gain insight into their infrastructure, applications, and services. It allows users to collect, visualize, and analyze real-time data from a variety of sources, including servers, databases, and cloud services. Datadog's platform enables companies to track performance metrics, troubleshoot issues, and optimize their systems for peak efficiency.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/datadog/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/datadog/refs/heads/main/apis.yml)

## Tags

- Analytics
- Dashboards
- Monitoring
- Platform
- T1
- Visualizations

## Timestamps

- **Created:** 2024/04/14
- **Modified:** 2026-05-19

## APIs

### Datadog API

The Datadog API is an HTTP REST API. The API uses resource-oriented URLs to call the API, uses status codes to indicate the success or failure of requests, returns JSON from all requests, and uses standard HTTP response codes. Use the Datadog API to access the Datadog platform programmatically.

- **Human URL:** [https://docs.datadoghq.com/api/latest/](https://docs.datadoghq.com/api/latest/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Monitoring
- Observability

#### Properties

- [OpenAPI](openapi/datadog-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.datadoghq.com/api/latest/)
- [Authentication](https://docs.datadoghq.com/api/latest/authentication/)

### Datadog Metrics API

The Metrics API allows you to post metrics data to be graphed on Datadog dashboards, query metrics from any time period as timeseries or scalar values, and modify tag configurations for metrics. It also supports viewing tags and volumes for metrics.

- **Human URL:** [https://docs.datadoghq.com/api/latest/metrics/](https://docs.datadoghq.com/api/latest/metrics/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Metrics
- Monitoring
- Timeseries

#### Properties

- [OpenAPI](openapi/datadog-metrics-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/datadog-metric-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Documentation](https://docs.datadoghq.com/api/latest/metrics/)
- [Reference](https://docs.datadoghq.com/metrics/)

### Datadog Logs API

The Logs API allows you to search and send log events to the Datadog platform over HTTP. It supports querying and aggregating log data from the Log Management product.

- **Human URL:** [https://docs.datadoghq.com/api/latest/logs/](https://docs.datadoghq.com/api/latest/logs/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Log Management
- Logs
- Search

#### Properties

- [OpenAPI](openapi/datadog-logs-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/datadog-log-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Documentation](https://docs.datadoghq.com/api/latest/logs/)
- [Reference](https://docs.datadoghq.com/logs/)

### Datadog Events API

The Event Management API allows you to programmatically post events to the Events Explorer and fetch events from the Events Explorer. Events represent notable changes or activity within your monitored infrastructure.

- **Human URL:** [https://docs.datadoghq.com/api/latest/events/](https://docs.datadoghq.com/api/latest/events/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Event Management
- Events

#### Properties

- [OpenAPI](openapi/datadog-events-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/datadog-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Documentation](https://docs.datadoghq.com/api/latest/events/)
- [Reference](https://docs.datadoghq.com/service_management/events/)

### Datadog Monitors API

The Monitors API allows you to create, update, delete, and mute monitors that watch a metric or check and notify your team when a defined threshold has been exceeded.

- **Human URL:** [https://docs.datadoghq.com/api/latest/monitors/](https://docs.datadoghq.com/api/latest/monitors/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Alerting
- Monitors
- Notifications

#### Properties

- [OpenAPI](openapi/datadog-monitors-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/datadog-monitor-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Documentation](https://docs.datadoghq.com/api/latest/monitors/)
- [Reference](https://docs.datadoghq.com/monitors/)

### Datadog Dashboards API

The Dashboards API allows you to create, update, delete, and retrieve dashboards and dashboard lists. It also supports organizing, finding, and sharing dashboards with your team and organization.

- **Human URL:** [https://docs.datadoghq.com/api/latest/dashboards/](https://docs.datadoghq.com/api/latest/dashboards/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Dashboards
- Visualizations

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/dashboards/)
- [Reference](https://docs.datadoghq.com/dashboards/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Incidents API

The Incidents API allows you to manage incident response, as well as associated attachments, metadata, and todos. It also supports creating, updating, deleting, and retrieving services associated with incidents.

- **Human URL:** [https://docs.datadoghq.com/api/latest/incidents/](https://docs.datadoghq.com/api/latest/incidents/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Incident Management
- Incidents

#### Properties

- [OpenAPI](openapi/datadog-incidents-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://docs.datadoghq.com/api/latest/incidents/)
- [Reference](https://docs.datadoghq.com/service_management/incident_management/)

### Datadog Synthetics API

The Synthetics API allows you to manage API tests and browser tests programmatically. Datadog Synthetics uses simulated user requests and browser rendering to help ensure uptime, identify regional issues, and track application performance.

- **Human URL:** [https://docs.datadoghq.com/api/latest/synthetics/](https://docs.datadoghq.com/api/latest/synthetics/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Synthetics
- Testing
- Uptime

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/synthetics/)
- [Reference](https://docs.datadoghq.com/synthetics/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Service Level Objectives API

The Service Level Objectives API provides a framework for defining clear targets around application performance. SLOs help teams provide a consistent customer experience, balance feature development with platform stability, and improve communication with internal and external users.

- **Human URL:** [https://docs.datadoghq.com/api/latest/service-level-objectives/](https://docs.datadoghq.com/api/latest/service-level-objectives/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Reliability
- Service Level Objectives
- SLOs

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/service-level-objectives/)
- [Reference](https://docs.datadoghq.com/monitors/service_level_objectives/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Security Monitoring API

The Security Monitoring API allows you to create and manage security rules, signals, and filters. It provides programmatic access to Datadog Cloud SIEM capabilities for threat detection and security signal management.

- **Human URL:** [https://docs.datadoghq.com/api/latest/security-monitoring/](https://docs.datadoghq.com/api/latest/security-monitoring/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Security
- Security Monitoring
- SIEM

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/security-monitoring/)
- [Reference](https://docs.datadoghq.com/security/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Service Definition API

The Service Definition API allows you to create, update, retrieve, and delete service definitions in the Datadog Service Catalog. It supports the v2.2 schema and earlier; for v3.0 schema use the Software Catalog endpoints.

- **Human URL:** [https://docs.datadoghq.com/api/latest/service-definition/](https://docs.datadoghq.com/api/latest/service-definition/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Service Catalog

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/service-definition/)
- [Reference](https://docs.datadoghq.com/tracing/service_catalog/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Software Catalog API

The Software Catalog API allows you to create, update, retrieve, and delete Software Catalog entities using the v3.0 schema. It provides a unified catalog for tracking ownership, reliability, and performance of all software components.

- **Human URL:** [https://docs.datadoghq.com/api/latest/software-catalog/](https://docs.datadoghq.com/api/latest/software-catalog/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Software Catalog

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/software-catalog/)
- [Reference](https://docs.datadoghq.com/service_catalog/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Users API

The Users API allows you to create, edit, and disable users within your Datadog organization. It supports role assignment and user management for access control purposes.

- **Human URL:** [https://docs.datadoghq.com/api/latest/users/](https://docs.datadoghq.com/api/latest/users/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Account Management
- Users

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/users/)
- [Reference](https://docs.datadoghq.com/account_management/users/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Roles API

The Roles API is used to create and manage Datadog roles, the global permissions they grant, and which users belong to them. Roles provide role-based access control for Datadog resources and features.

- **Human URL:** [https://docs.datadoghq.com/api/latest/roles/](https://docs.datadoghq.com/api/latest/roles/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Access Control
- RBAC
- Roles

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/roles/)
- [Reference](https://docs.datadoghq.com/account_management/rbac/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Key Management API

The Key Management API allows you to manage your Datadog API and application keys. It provides endpoints to create, list, update, and delete both API keys and application keys for your organization.

- **Human URL:** [https://docs.datadoghq.com/api/latest/key-management/](https://docs.datadoghq.com/api/latest/key-management/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- API Keys
- Application Keys
- Authentication

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/key-management/)
- [Reference](https://docs.datadoghq.com/account_management/api-app-keys/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Organizations API

The Organizations API allows you to create, edit, and manage your Datadog organizations. It supports multi-org account configurations where a parent organization manages one or more child organizations.

- **Human URL:** [https://docs.datadoghq.com/api/latest/organizations/](https://docs.datadoghq.com/api/latest/organizations/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Account Management
- Organizations

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/organizations/)
- [Reference](https://docs.datadoghq.com/account_management/multi_organization/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Downtimes API

The Downtimes API gives you greater control over monitor notifications by allowing you to globally exclude scopes from alerting. Downtime settings can be scheduled with start and end times to prevent alerting for specified Datadog tags.

- **Human URL:** [https://docs.datadoghq.com/api/latest/downtimes/](https://docs.datadoghq.com/api/latest/downtimes/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Alerting
- Downtimes
- Monitors

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/downtimes/)
- [Reference](https://docs.datadoghq.com/monitors/notify/downtimes/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog RUM API

The RUM API allows you to manage Real User Monitoring applications and search or aggregate RUM events over HTTP. It provides access to session data, user interactions, and frontend performance metrics.

- **Human URL:** [https://docs.datadoghq.com/api/latest/rum/](https://docs.datadoghq.com/api/latest/rum/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Real User Monitoring
- RUM
- Session Replay

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/rum/)
- [Reference](https://docs.datadoghq.com/real_user_monitoring/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog APM Retention Filters API

The APM Retention Filters API allows you to manage configuration of APM retention filters for your organization. Retention filters control which traces are indexed and retained for analysis and require Admin rights to interact with.

- **Human URL:** [https://docs.datadoghq.com/api/latest/apm-retention-filters/](https://docs.datadoghq.com/api/latest/apm-retention-filters/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- APM
- Retention
- Tracing

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/apm-retention-filters/)
- [Reference](https://docs.datadoghq.com/tracing/trace_pipeline/trace_retention/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Usage Metering API

The Usage Metering API allows you to get hourly, daily, and monthly usage across multiple facets of Datadog. It is available to all Pro and Enterprise customers, with usage data delayed by up to 72 hours.

- **Human URL:** [https://docs.datadoghq.com/api/latest/usage-metering/](https://docs.datadoghq.com/api/latest/usage-metering/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Billing
- Metering
- Usage

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/usage-metering/)
- [Reference](https://docs.datadoghq.com/account_management/billing/usage_details/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Spans API

The Spans API allows you to search and aggregate spans from your Datadog platform over HTTP. It supports querying distributed tracing data collected by Datadog APM.

- **Human URL:** [https://docs.datadoghq.com/api/latest/spans/](https://docs.datadoghq.com/api/latest/spans/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- APM
- Spans
- Tracing

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/spans/)
- [Reference](https://docs.datadoghq.com/tracing/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Processes API

The Processes API allows you to query processes data for your organization. It provides access to live process information collected from hosts running the Datadog Agent.

- **Human URL:** [https://docs.datadoghq.com/api/latest/processes/](https://docs.datadoghq.com/api/latest/processes/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Infrastructure
- Processes

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/processes/)
- [Reference](https://docs.datadoghq.com/infrastructure/process/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Teams API

The Teams API allows you to view and manage teams within Datadog. Teams can be associated with incidents, dashboards, and other resources to organize ownership and collaboration within your organization.

- **Human URL:** [https://docs.datadoghq.com/api/latest/teams/](https://docs.datadoghq.com/api/latest/teams/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Account Management
- Teams

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/teams/)
- [Reference](https://docs.datadoghq.com/account_management/teams/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Workflow Automation API

The Workflow Automation API allows you to automate end-to-end processes by connecting Datadog with the rest of your tech stack. It supports over 1,000 out-of-the-box actions including integrations with AWS, JIRA, ServiceNow, GitHub, and OpenAI.

- **Human URL:** [https://docs.datadoghq.com/api/latest/workflow-automation/](https://docs.datadoghq.com/api/latest/workflow-automation/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Automation
- Workflows

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/workflow-automation/)
- [Reference](https://docs.datadoghq.com/service_management/workflows/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Case Management API

The Case Management API allows you to view and manage cases and projects within Datadog Case Management. Cases can be created from monitors, security signals, and other alert sources to track investigation and remediation work.

- **Human URL:** [https://docs.datadoghq.com/api/latest/case-management/](https://docs.datadoghq.com/api/latest/case-management/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Case Management
- Cases

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/case-management/)
- [Reference](https://docs.datadoghq.com/service_management/case_management/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Observability Pipelines API

The Observability Pipelines API allows you to collect and process logs within your own infrastructure and route them to downstream integrations. It provides programmatic management of pipeline configurations.

- **Human URL:** [https://docs.datadoghq.com/api/latest/observability-pipelines/](https://docs.datadoghq.com/api/latest/observability-pipelines/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Logs
- Observability Pipelines

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/observability-pipelines/)
- [Reference](https://docs.datadoghq.com/observability_pipelines/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Sensitive Data Scanner API

The Sensitive Data Scanner API allows you to create, update, delete, and retrieve sensitive data scanner groups and rules. It enables automated detection and redaction of sensitive data within logs, APM events, and RUM events.

- **Human URL:** [https://docs.datadoghq.com/api/latest/sensitive-data-scanner/](https://docs.datadoghq.com/api/latest/sensitive-data-scanner/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Data Privacy
- Security
- Sensitive Data

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/sensitive-data-scanner/)
- [Reference](https://docs.datadoghq.com/sensitive_data_scanner/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog AWS Integration API

The AWS Integration API allows you to configure your Datadog-AWS integration directly through the Datadog API. It supports managing AWS accounts, metrics collection, and log forwarding configuration.

- **Human URL:** [https://docs.datadoghq.com/api/latest/aws-integration/](https://docs.datadoghq.com/api/latest/aws-integration/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- AWS
- Cloud
- Integrations

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/aws-integration/)
- [Reference](https://docs.datadoghq.com/integrations/amazon_web_services/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog GCP Integration API

The GCP Integration API allows you to configure your Datadog-Google Cloud Platform integration directly through the Datadog API. It supports managing GCP projects, service accounts, and metrics collection settings.

- **Human URL:** [https://docs.datadoghq.com/api/latest/gcp-integration/](https://docs.datadoghq.com/api/latest/gcp-integration/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Cloud
- GCP
- Google Cloud
- Integrations

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/gcp-integration/)
- [Reference](https://docs.datadoghq.com/integrations/google_cloud_platform/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog CI Visibility Pipelines API

The CI Visibility Pipelines API allows you to search or aggregate CI Visibility pipeline events and send them to your Datadog site over HTTP. It provides insight into the performance and reliability of CI/CD pipelines.

- **Human URL:** [https://docs.datadoghq.com/api/latest/ci-visibility-pipelines/](https://docs.datadoghq.com/api/latest/ci-visibility-pipelines/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- CI
- CI/CD
- Pipelines

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/ci-visibility-pipelines/)
- [Reference](https://docs.datadoghq.com/continuous_integration/pipelines/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Network Device Monitoring API

The Network Device Monitoring API allows you to fetch devices and interfaces and their attributes. It provides programmatic access to network topology and performance data collected from network devices.

- **Human URL:** [https://docs.datadoghq.com/api/latest/network-device-monitoring/](https://docs.datadoghq.com/api/latest/network-device-monitoring/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Infrastructure
- Network
- Network Device Monitoring

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/network-device-monitoring/)
- [Reference](https://docs.datadoghq.com/network_monitoring/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog On-Call API

The On-Call API allows you to configure and manage Datadog On-Call schedules, escalation policies, and teams. It also supports triggering and managing on-call pages directly through the Datadog API.

- **Human URL:** [https://docs.datadoghq.com/api/latest/on-call/](https://docs.datadoghq.com/api/latest/on-call/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Incident Management
- On-Call
- Paging

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/on-call/)
- [Reference](https://docs.datadoghq.com/service_management/on-call/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog DORA Metrics API

The DORA Metrics API allows you to search and send events for DORA Metrics to measure and improve software delivery performance. It tracks deployment frequency, lead time for changes, change failure rate, and time to restore service.

- **Human URL:** [https://docs.datadoghq.com/api/latest/dora-metrics/](https://docs.datadoghq.com/api/latest/dora-metrics/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- CI/CD
- DevOps
- DORA Metrics

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/dora-metrics/)
- [Reference](https://docs.datadoghq.com/dora_metrics/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Cloud Cost Management API

The Cloud Cost Management API allows you to set up, edit, and delete Cloud Cost Management accounts for AWS and Azure. Cost data can be queried using the Metrics endpoint with the cloud_cost data source.

- **Human URL:** [https://docs.datadoghq.com/api/latest/cloud-cost-management/](https://docs.datadoghq.com/api/latest/cloud-cost-management/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Cloud
- Cloud Cost Management
- FinOps

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/cloud-cost-management/)
- [Reference](https://docs.datadoghq.com/cloud_cost_management/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Hosts API

The Hosts API allows you to search for hosts by name, alias, or tag and retrieve host totals. Hosts live within the past 3 hours are included by default, with a retention of 7 days.

- **Human URL:** [https://docs.datadoghq.com/api/latest/hosts/](https://docs.datadoghq.com/api/latest/hosts/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Hosts
- Infrastructure

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/hosts/)
- [Reference](https://docs.datadoghq.com/infrastructure/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Tags API

The Tags API allows you to assign tags to hosts, returning a mapping of tags to hosts for your entire infrastructure. Tags can be used to filter and group resources across Datadog.

- **Human URL:** [https://docs.datadoghq.com/api/latest/tags/](https://docs.datadoghq.com/api/latest/tags/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Infrastructure

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/tags/)
- [Reference](https://docs.datadoghq.com/getting_started/tagging/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Containers API

The Containers API allows you to get all containers for your organization. It provides programmatic access to container data collected from hosts running the Datadog Agent.

- **Human URL:** [https://docs.datadoghq.com/api/latest/containers/](https://docs.datadoghq.com/api/latest/containers/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Containers
- Infrastructure

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/containers/)
- [Reference](https://docs.datadoghq.com/infrastructure/containers/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Container Images API

The Container Images API allows you to get all container images for your organization. It provides visibility into the container images running across your infrastructure.

- **Human URL:** [https://docs.datadoghq.com/api/latest/container-images/](https://docs.datadoghq.com/api/latest/container-images/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Container Images
- Containers
- Infrastructure

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/container-images/)
- [Reference](https://docs.datadoghq.com/infrastructure/containers/container_images/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Notebooks API

The Notebooks API allows you to interact with Datadog Notebooks programmatically. Notebooks combine graphs and text in a linear, cell-based layout for exploring and sharing stories with your data.

- **Human URL:** [https://docs.datadoghq.com/api/latest/notebooks/](https://docs.datadoghq.com/api/latest/notebooks/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Collaboration
- Notebooks

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/notebooks/)
- [Reference](https://docs.datadoghq.com/notebooks/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Dashboard Lists API

The Dashboard Lists API allows you to interact with dashboard lists through the API to organize, find, and share all of your dashboards with your team and organization.

- **Human URL:** [https://docs.datadoghq.com/api/latest/dashboard-lists/](https://docs.datadoghq.com/api/latest/dashboard-lists/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Dashboard Lists
- Dashboards

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/dashboard-lists/)
- [Reference](https://docs.datadoghq.com/dashboards/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Logs Pipelines API

The Logs Pipelines API allows you to manage pipelines and processors that operate on incoming logs, parsing and transforming them into structured attributes for easier querying.

- **Human URL:** [https://docs.datadoghq.com/api/latest/logs-pipelines/](https://docs.datadoghq.com/api/latest/logs-pipelines/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Log Processing
- Logs
- Pipelines

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/logs-pipelines/)
- [Reference](https://docs.datadoghq.com/logs/log_configuration/pipelines/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Logs Indexes API

The Logs Indexes API allows you to manage configuration of log indexes for your organization. Log indexes define how logs are filtered, aggregated, and stored for retention and querying.

- **Human URL:** [https://docs.datadoghq.com/api/latest/logs-indexes/](https://docs.datadoghq.com/api/latest/logs-indexes/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Indexes
- Log Management
- Logs

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/logs-indexes/)
- [Reference](https://docs.datadoghq.com/logs/log_configuration/indexes/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Logs Metrics API

The Logs Metrics API allows you to manage configuration of log-based metrics for your organization. It provides the ability to generate metrics from log data for cost-effective long-term analysis.

- **Human URL:** [https://docs.datadoghq.com/api/latest/logs-metrics/](https://docs.datadoghq.com/api/latest/logs-metrics/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Log-Based Metrics
- Logs
- Metrics

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/logs-metrics/)
- [Reference](https://docs.datadoghq.com/logs/log_configuration/logs_to_metrics/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Logs Archives API

The Logs Archives API allows you to manage logs archives that forward all ingested logs to cloud storage systems. It supports configuration of archive destinations and rehydration settings.

- **Human URL:** [https://docs.datadoghq.com/api/latest/logs-archives/](https://docs.datadoghq.com/api/latest/logs-archives/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Archives
- Logs
- Storage

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/logs-archives/)
- [Reference](https://docs.datadoghq.com/logs/log_configuration/archives/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Logs Custom Destinations API

The Logs Custom Destinations API allows you to manage custom destinations that forward all ingested logs to external destinations such as Elasticsearch, Microsoft Sentinel, and HTTP endpoints.

- **Human URL:** [https://docs.datadoghq.com/api/latest/logs-custom-destinations/](https://docs.datadoghq.com/api/latest/logs-custom-destinations/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Custom Destinations
- Log Forwarding
- Logs

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/logs-custom-destinations/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Logs Restriction Queries API

The Logs Restriction Queries API allows you to manage restriction queries that control which logs the logs_read_data permission grants read access to, enabling fine-grained log access control by role.

- **Human URL:** [https://docs.datadoghq.com/api/latest/logs-restriction-queries/](https://docs.datadoghq.com/api/latest/logs-restriction-queries/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Access Control
- Logs
- RBAC

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/logs-restriction-queries/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Spans Metrics API

The Spans Metrics API allows you to manage configuration of span-based metrics for your organization. It provides the ability to generate metrics from spans for cost-effective long-term analysis of APM data.

- **Human URL:** [https://docs.datadoghq.com/api/latest/spans-metrics/](https://docs.datadoghq.com/api/latest/spans-metrics/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- APM
- Metrics
- Spans

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/spans-metrics/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Service Checks API

The Service Checks API allows you to submit a list of service checks to Datadog. Service checks can be submitted up to 10 minutes in the past and are used to monitor the status of services.

- **Human URL:** [https://docs.datadoghq.com/api/latest/service-checks/](https://docs.datadoghq.com/api/latest/service-checks/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Monitoring
- Service Checks

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/service-checks/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Snapshots API

The Snapshots API allows you to take graph snapshots. Snapshots are PNG images generated by rendering a specified widget and capturing it once the data is available.

- **Human URL:** [https://docs.datadoghq.com/api/latest/snapshots/](https://docs.datadoghq.com/api/latest/snapshots/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Graphs
- Snapshots
- Visualizations

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/snapshots/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog IP Ranges API

The IP Ranges API provides a list of IP prefixes belonging to Datadog. It returns available prefix information for Agent, API, and APM endpoints along with IPv4 and IPv6 prefixes.

- **Human URL:** [https://docs.datadoghq.com/api/latest/ip-ranges/](https://docs.datadoghq.com/api/latest/ip-ranges/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Infrastructure
- IP Ranges
- Network

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/ip-ranges/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog IP Allowlist API

The IP Allowlist API is used to manage the IP addresses that can access the Datadog API and web UI. It allows you to configure IP address restrictions for your organization.

- **Human URL:** [https://docs.datadoghq.com/api/latest/ip-allowlist/](https://docs.datadoghq.com/api/latest/ip-allowlist/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Access Control
- IP Allowlist
- Security

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/ip-allowlist/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Audit API

The Audit API allows you to search your Audit Logs events over HTTP. It returns Audit Logs events that match an audit search query, providing visibility into actions taken within your organization.

- **Human URL:** [https://docs.datadoghq.com/api/latest/audit/](https://docs.datadoghq.com/api/latest/audit/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Audit
- Audit Logs
- Compliance

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/audit/)
- [Reference](https://docs.datadoghq.com/account_management/audit_trail/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog APM API

The APM API provides endpoints for working with Application Performance Monitoring services and tracing data. It supports querying service-level metrics and trace data collected by Datadog APM.

- **Human URL:** [https://docs.datadoghq.com/api/latest/apm/](https://docs.datadoghq.com/api/latest/apm/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- APM
- Application Performance
- Tracing

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/apm/)
- [Reference](https://docs.datadoghq.com/tracing/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Webhooks Integration API

The Webhooks Integration API allows you to configure the Datadog-Webhooks integration directly through the Datadog API. It supports creating, updating, and deleting webhook endpoints and custom variables.

- **Human URL:** [https://docs.datadoghq.com/api/latest/webhooks-integration/](https://docs.datadoghq.com/api/latest/webhooks-integration/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Integrations
- Notifications
- Webhooks

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/webhooks-integration/)
- [Reference](https://docs.datadoghq.com/integrations/webhooks/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog SLO Corrections API

The SLO Corrections API allows you to create, update, and delete corrections for Service Level Objectives. SLO corrections adjust SLO status calculations to account for planned maintenance or known issues.

- **Human URL:** [https://docs.datadoghq.com/api/latest/service-level-objective-corrections/](https://docs.datadoghq.com/api/latest/service-level-objective-corrections/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Reliability
- SLO Corrections
- SLOs

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/service-level-objective-corrections/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog AWS Logs Integration API

The AWS Logs Integration API allows you to configure log collection from AWS services and manage your Datadog-AWS Logs integration. It supports listing and managing AWS log collection configurations.

- **Human URL:** [https://docs.datadoghq.com/api/latest/aws-logs-integration/](https://docs.datadoghq.com/api/latest/aws-logs-integration/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- AWS
- Integrations
- Logs

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/aws-logs-integration/)
- [Reference](https://docs.datadoghq.com/integrations/amazon_web_services/#log-collection)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Azure Integration API

The Azure Integration API allows you to configure your Datadog-Azure integration directly through the Datadog API. It supports managing Azure tenants, host filters, and metrics collection settings.

- **Human URL:** [https://docs.datadoghq.com/api/latest/azure-integration/](https://docs.datadoghq.com/api/latest/azure-integration/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Azure
- Cloud
- Integrations

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/azure-integration/)
- [Reference](https://docs.datadoghq.com/integrations/azure/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Slack Integration API

The Slack Integration API allows you to configure your Datadog-Slack integration directly through the Datadog API. It supports managing Slack channels for monitor notifications and alerts.

- **Human URL:** [https://docs.datadoghq.com/api/latest/slack-integration/](https://docs.datadoghq.com/api/latest/slack-integration/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Integrations
- Notifications
- Slack

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/slack-integration/)
- [Reference](https://docs.datadoghq.com/integrations/slack/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog PagerDuty Integration API

The PagerDuty Integration API allows you to configure your Datadog-PagerDuty integration directly through the Datadog API. It supports managing PagerDuty services and scheduling configurations.

- **Human URL:** [https://docs.datadoghq.com/api/latest/pagerduty-integration/](https://docs.datadoghq.com/api/latest/pagerduty-integration/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Incident Management
- Integrations
- PagerDuty

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/pagerduty-integration/)
- [Reference](https://docs.datadoghq.com/integrations/pagerduty/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Opsgenie Integration API

The Opsgenie Integration API allows you to configure your Datadog-Opsgenie integration directly through the Datadog API. It supports managing Opsgenie services and alert routing.

- **Human URL:** [https://docs.datadoghq.com/api/latest/opsgenie-integration/](https://docs.datadoghq.com/api/latest/opsgenie-integration/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Incident Management
- Integrations
- Opsgenie

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/opsgenie-integration/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Cloudflare Integration API

The Cloudflare Integration API allows you to manage your Datadog-Cloudflare integration directly through the Datadog API. It supports listing and managing Cloudflare accounts and their associated resources.

- **Human URL:** [https://docs.datadoghq.com/api/latest/cloudflare-integration/](https://docs.datadoghq.com/api/latest/cloudflare-integration/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- CDN
- Cloudflare
- Integrations

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/cloudflare-integration/)
- [Reference](https://docs.datadoghq.com/integrations/cloudflare/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Fastly Integration API

The Fastly Integration API allows you to manage your Datadog-Fastly integration accounts and services directly through the Datadog API. It supports listing and managing Fastly accounts.

- **Human URL:** [https://docs.datadoghq.com/api/latest/fastly-integration/](https://docs.datadoghq.com/api/latest/fastly-integration/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- CDN
- Fastly
- Integrations

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/fastly-integration/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Confluent Cloud API

The Confluent Cloud API allows you to manage your Datadog-Confluent Cloud integration accounts and account resources directly through the Datadog API. It supports monitoring Kafka clusters and related services.

- **Human URL:** [https://docs.datadoghq.com/api/latest/confluent-cloud/](https://docs.datadoghq.com/api/latest/confluent-cloud/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Confluent Cloud
- Integrations
- Kafka

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/confluent-cloud/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Okta Integration API

The Okta Integration API allows you to configure your Datadog-Okta integration directly through the Datadog API. It supports listing and managing Okta accounts and their configurations.

- **Human URL:** [https://docs.datadoghq.com/api/latest/okta-integration/](https://docs.datadoghq.com/api/latest/okta-integration/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Identity
- Integrations
- Okta

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/okta-integration/)
- [Reference](https://docs.datadoghq.com/integrations/okta/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Microsoft Teams Integration API

The Microsoft Teams Integration API allows you to configure your Datadog-Microsoft Teams integration directly through the Datadog API. It supports managing Teams channels for notifications and alerts.

- **Human URL:** [https://docs.datadoghq.com/api/latest/microsoft-teams-integration/](https://docs.datadoghq.com/api/latest/microsoft-teams-integration/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Integrations
- Microsoft Teams
- Notifications

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/microsoft-teams-integration/)
- [Reference](https://docs.datadoghq.com/integrations/microsoft-teams/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Jira Integration API

The Jira Integration API allows you to configure your Datadog-Jira integration directly through the Datadog API. It supports managing Jira issue templates and project configurations.

- **Human URL:** [https://docs.datadoghq.com/api/latest/jira-integration/](https://docs.datadoghq.com/api/latest/jira-integration/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Integrations
- Issue Tracking
- Jira

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/jira-integration/)
- [Reference](https://docs.datadoghq.com/integrations/jira/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Error Tracking API

The Error Tracking API allows you to search issues within your organization programmatically. It returns a list of issues that match a given search query using event search syntax.

- **Human URL:** [https://docs.datadoghq.com/api/latest/error-tracking/](https://docs.datadoghq.com/api/latest/error-tracking/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Debugging
- Error Tracking

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/error-tracking/)
- [Reference](https://docs.datadoghq.com/error_tracking/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Application Security API

The Application Security API provides protection against application-level attacks that aim to exploit code-level vulnerabilities such as SSRF, SQL injection, Log4Shell, and XSS.

- **Human URL:** [https://docs.datadoghq.com/api/latest/application-security/](https://docs.datadoghq.com/api/latest/application-security/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Application Security
- AppSec
- Security

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/application-security/)
- [Reference](https://docs.datadoghq.com/security/application_security/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog CSM Threats API

The CSM Threats API provides endpoints for managing Cloud Security Management Workload Protection agent rules. It monitors file, network, and process activity to detect real-time threats to your infrastructure.

- **Human URL:** [https://docs.datadoghq.com/api/latest/csm-threats/](https://docs.datadoghq.com/api/latest/csm-threats/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Cloud Security
- CSM
- Threats

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/csm-threats/)
- [Reference](https://docs.datadoghq.com/security/cloud_security_management/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog CSM Agents API

The CSM Agents API allows you to get the list of all Cloud Security Management agents running on your hosts and containers. It provides visibility into agent coverage across your infrastructure.

- **Human URL:** [https://docs.datadoghq.com/api/latest/csm-agents/](https://docs.datadoghq.com/api/latest/csm-agents/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Agents
- Cloud Security
- CSM

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/csm-agents/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Service Scorecards API

The Service Scorecards API allows you to create and manage scorecard rules and outcomes. Scorecards help formalize your organization's best practices and track service compliance against defined criteria.

- **Human URL:** [https://docs.datadoghq.com/api/latest/service-scorecards/](https://docs.datadoghq.com/api/latest/service-scorecards/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Best Practices
- Scorecards
- Service Catalog

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/service-scorecards/)
- [Reference](https://docs.datadoghq.com/internal_developer_portal/scorecards/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Service Dependencies API

The Service Dependencies API allows you to get a list of services from APM and their dependencies. Services are filtered by environment and primary tag to map your service topology.

- **Human URL:** [https://docs.datadoghq.com/api/latest/service-dependencies/](https://docs.datadoghq.com/api/latest/service-dependencies/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- APM
- Dependencies

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/service-dependencies/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Powerpack API

The Powerpack API allows you to create, update, delete, and retrieve Powerpacks. Powerpacks are templated groups of dashboard widgets that scale graphing expertise as reusable building blocks.

- **Human URL:** [https://docs.datadoghq.com/api/latest/powerpack/](https://docs.datadoghq.com/api/latest/powerpack/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Dashboards
- Powerpacks
- Widgets

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/powerpack/)
- [Reference](https://docs.datadoghq.com/dashboards/widgets/powerpack/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Embeddable Graphs API

The Embeddable Graphs API allows you to create and manage embeddable graph snapshots that can be shared outside of Datadog. It supports creating, revoking, and listing embeddable graphs.

- **Human URL:** [https://docs.datadoghq.com/api/latest/embeddable-graphs/](https://docs.datadoghq.com/api/latest/embeddable-graphs/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Embeds
- Graphs
- Visualizations

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/embeddable-graphs/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog RUM Metrics API

The RUM Metrics API allows you to manage configuration of RUM-based metrics for your organization. It provides the ability to generate metrics from Real User Monitoring data.

- **Human URL:** [https://docs.datadoghq.com/api/latest/rum-metrics/](https://docs.datadoghq.com/api/latest/rum-metrics/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Metrics
- Real User Monitoring
- RUM

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/rum-metrics/)
- [Reference](https://docs.datadoghq.com/real_user_monitoring/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Domain Allowlist API

The Domain Allowlist API allows you to manage the email domain allowlist for your organization. It supports getting and updating the list of allowed email domains.

- **Human URL:** [https://docs.datadoghq.com/api/latest/domain-allowlist/](https://docs.datadoghq.com/api/latest/domain-allowlist/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Access Control
- Domain Allowlist
- Security

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/domain-allowlist/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Restriction Policies API

The Restriction Policies API allows you to manage restriction policies associated with Datadog resources including dashboards, notebooks, security rules, SLOs, workflows, and more.

- **Human URL:** [https://docs.datadoghq.com/api/latest/restriction-policies/](https://docs.datadoghq.com/api/latest/restriction-policies/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Access Control
- RBAC
- Restriction Policies

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/restriction-policies/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog AuthN Mappings API

The AuthN Mappings API is used to automatically map groups of users to roles in Datadog using attributes sent from Identity Providers. It enables federated authentication to role mapping.

- **Human URL:** [https://docs.datadoghq.com/api/latest/authn-mappings/](https://docs.datadoghq.com/api/latest/authn-mappings/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Authentication
- Identity
- Mappings

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/authn-mappings/)
- [Reference](https://docs.datadoghq.com/account_management/authn_mapping/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Integrations API

The Integrations API allows you to manage Datadog integrations programmatically. It provides endpoints for configuring and managing third-party service integrations within your organization.

- **Human URL:** [https://docs.datadoghq.com/api/latest/integrations/](https://docs.datadoghq.com/api/latest/integrations/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Integrations

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/integrations/)
- [Reference](https://docs.datadoghq.com/integrations/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog CI Visibility Tests API

The CI Visibility Tests API allows you to search or aggregate CI Visibility test events over HTTP. It provides insight into the performance and reliability of your test suites.

- **Human URL:** [https://docs.datadoghq.com/api/latest/ci-visibility-tests/](https://docs.datadoghq.com/api/latest/ci-visibility-tests/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- CI
- CI/CD
- Tests

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/ci-visibility-tests/)
- [Reference](https://docs.datadoghq.com/continuous_integration/tests/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Agentless Scanning API

The Agentless Scanning API provides visibility into risks and vulnerabilities within your hosts, running containers, and serverless functions without requiring teams to install Agents.

- **Human URL:** [https://docs.datadoghq.com/api/latest/agentless-scanning/](https://docs.datadoghq.com/api/latest/agentless-scanning/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Agentless Scanning
- Cloud Security
- Vulnerabilities

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/agentless-scanning/)
- [Reference](https://docs.datadoghq.com/security/cloud_security_management/setup/agentless_scanning/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Static Analysis API

The Static Analysis API provides access to static analysis and dependency scanning results. It supports querying code analysis data for your organization.

- **Human URL:** [https://docs.datadoghq.com/api/latest/static-analysis/](https://docs.datadoghq.com/api/latest/static-analysis/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Code Quality
- Security
- Static Analysis

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/static-analysis/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Entity Risk Scores API

The Entity Risk Scores API provides security risk assessments for entities like cloud resources, identities, or services based on detected signals, misconfigurations, and identity risks.

- **Human URL:** [https://docs.datadoghq.com/api/latest/entity-risk-scores/](https://docs.datadoghq.com/api/latest/entity-risk-scores/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Cloud Security
- Risk Scores
- Security

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/entity-risk-scores/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog API Management API

The API Management API allows you to create and manage APIs from OpenAPI specifications. It supports the Datadog API Catalog for tracking API performance, security, and ownership.

- **Human URL:** [https://docs.datadoghq.com/api/latest/api-management/](https://docs.datadoghq.com/api/latest/api-management/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- API Catalog
- API Management

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/api-management/)
- [Reference](https://docs.datadoghq.com/api_catalog/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Datadog Cloud Workload Security API

The Cloud Workload Security API provides endpoints for managing workload protection rules and agent configurations. It monitors file, network, and process activity to detect real-time threats.

- **Human URL:** [https://docs.datadoghq.com/api/latest/cloud-workload-security/](https://docs.datadoghq.com/api/latest/cloud-workload-security/)
- **Base URL:** `https://api.datadoghq.com`

#### Tags

- Cloud Workload Security
- Runtime Protection
- Security

#### Properties

- [Documentation](https://docs.datadoghq.com/api/latest/cloud-workload-security/)
- [Reference](https://docs.datadoghq.com/security/cloud_security_management/)
- [Postman Collection](collections/datadog-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-events.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-events.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-incidents.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-incidents.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-logs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-logs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-metrics.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-metrics.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/datadog-monitors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/datadog-monitors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [LinkedIn](https://www.linkedin.com/company/datadog)
- [Website](https://www.datadoghq.com/)
- [Portal](https://docs.datadoghq.com/api/)
- [Documentation](https://docs.datadoghq.com/)
- [Authentication](https://docs.datadoghq.com/api/latest/authentication/)
- [GitHub Organization](https://github.com/DataDog)
- [Blog](https://www.datadoghq.com/blog/)
- [Support](https://www.datadoghq.com/support/)
- [Status Page](https://status.datadoghq.com/)
- [Pricing](https://www.datadoghq.com/pricing/)
- [Login](https://app.datadoghq.com/)
- [Sign Up](https://www.datadoghq.com/free-datadog-trial/)
- [JSON-LD](json-ld/datadog-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/datadog-metric-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/datadog-monitor-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/datadog-log-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/datadog-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Products](https://www.datadoghq.com/product/)
- [Customers](https://www.datadoghq.com/customers/)
- [Pricing](https://www.datadoghq.com/pricing/)
- [Integrations](https://docs.datadoghq.com/integrations/)
- [About](https://www.datadoghq.com/about/leadership/)
- [Blog](https://www.datadoghq.com/blog/)
- [Login](https://app.datadoghq.com/account/login)
- [Login](https://app.datadoghq.com/account/login)
- [Login](https://app.datadoghq.com/account/login)
- [Sign Up](https://us5.datadoghq.com/signup)
- [Support](https://www.datadoghq.com/support/)
- [Certifications](https://www.datadoghq.com/certification/overview/)
- [Privacy Policy](https://www.datadoghq.com/privacy/)
- [Security](https://www.datadoghq.com/security/)
- [Trust](https://trust.datadoghq.com/)
- [Partners](https://www.datadoghq.com/partner/network/)
- [Documentation](https://docs.datadoghq.com/)
- [Portal](https://docs.datadoghq.com/api/latest/)
- [Getting Started](https://docs.datadoghq.com/getting_started/)
- [Authentication](https://docs.datadoghq.com/api/latest/authentication/)
- [Status Page](https://status.datadoghq.com/)
- [GitHub Organization](https://github.com/DataDog)
- [Rate Limits](https://docs.datadoghq.com/api/latest/rate-limits/)
- [Developer  Portal](https://docs.datadoghq.com/developers/)
- [S D Ks](https://docs.datadoghq.com/developers/libraries/)
- [Terms of Service](https://www.datadoghq.com/legal/terms/)
- [Agent](https://docs.datadoghq.com/agent/)
- [Community](https://community.datadoghq.com/)
- [Authorization  Scopes](https://docs.datadoghq.com/api/latest/scopes/)
- [Using the  A P I](https://docs.datadoghq.com/api/latest/using-the-api/)
- [Learning  Center](https://learn.datadoghq.com/)
- [Events](https://www.datadoghq.com/events-webinars/)
- [Marketplace](https://www.datadoghq.com/marketplacepartners/)
- [Postman Workspace](https://www.postman.com/datadog/datadog-s-public-workspace/overview)
- [Getting Started](https://docs.datadoghq.com/getting_started/api/)
- [Learning  Resources](https://www.datadoghq.com/learn/)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)
- [M C P Server](https://www.datadoghq.com/blog/introducing-datadog-code-security-mcp/)
- [L L Ms Txt](https://docs.datadoghq.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** http://apievangelist.com
