# Datadog (datadog)
Datadog is a monitoring and observability platform for cloud-scale applications providing infrastructure monitoring, APM, log management, security monitoring, and incident management with 800+ integrations.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/datadog/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - APM, Cloud, DevOps, Infrastructure, Logging, Monitoring, Observability, Security

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-17

## APIs

85 APIs covering Metrics, Monitors, Dashboards, Events, Logs, APM, Synthetics, Incidents, SLOs, Security, Hosts, Containers, Service Checks, and more.

See [apis.yml](apis.yml) for the complete inventory.

## Features

| Name | Description |
|------|-------------|
| Infrastructure Monitoring | Monitor servers, containers, databases, and cloud services. |
| APM and Distributed Tracing | Trace requests across microservices. |
| Log Management | Collect, process, and analyze logs from any source. |
| Real User Monitoring | Monitor front-end performance and user experience. |
| Synthetic Monitoring | Proactive API tests, browser tests, and workflows. |
| Security Monitoring | Detect threats and misconfigurations. |
| Dashboards | Custom dashboards with drag-and-drop widgets. |
| Alerting | Monitors with thresholds, anomaly detection, and notifications. |
| Incidents | Incident response with timeline and postmortems. |
| Service Level Objectives | Define and track SLOs with error budgets. |
| CI/CD Visibility | Monitor pipeline performance and deployments. |
| Cloud Cost Management | Track and optimize cloud costs. |

## Use Cases

| Name | Description |
|------|-------------|
| Full-Stack Observability | Correlate metrics, traces, and logs across the stack. |
| Container Monitoring | Monitor Kubernetes and Docker environments. |
| Cloud Infrastructure | Monitor AWS, Azure, GCP, and hybrid clouds. |
| Application Performance | Identify bottlenecks with distributed tracing. |
| Log Analytics | Centralize logs for troubleshooting and compliance. |
| Incident Management | Automate detection, response, and resolution. |
| DevOps Automation | Integrate monitoring into CI/CD pipelines. |
| Security Posture | Monitor cloud misconfigurations and compliance. |

## Solutions

| Name | Description |
|------|-------------|
| Datadog Infrastructure | Infrastructure monitoring with 800+ integrations. |
| Datadog APM | Application performance with tracing and profiling. |
| Datadog Logs | Log management with indexing and analytics. |
| Datadog Security | Cloud security posture and threat detection. |

## Artifacts

### OpenAPI

6 OpenAPI specs in [openapi/](openapi/).

### JSON Schema

61 standalone JSON Schema files in [json-schema/](json-schema/).

### JSON Structure

61 JSON Structure files in [json-structure/](json-structure/).

### JSON-LD

- [Datadog Context](json-ld/datadog-context.jsonld) — 61 types, 106 properties

### Examples

61 example JSON files in [examples/](examples/).

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Monitors](capabilities/shared/monitors.yaml) — 7 operations for alert monitor CRUD and mute/unmute
- [Metrics](capabilities/shared/metrics.yaml) — 8 operations for metric submission, querying, and tag config
- [Events](capabilities/shared/events.yaml) — 4 operations for event creation and search
- [Logs](capabilities/shared/logs.yaml) — 5 operations for log submission, search, and aggregation
- [Incidents](capabilities/shared/incidents.yaml) — 9 operations for incident CRUD and team management
- [Dashboards](capabilities/shared/dashboards.yaml) — 4 operations for dashboard list items
- [Synthetics](capabilities/shared/synthetics.yaml) — 2 operations for synthetic test concurrency
- [Hosts](capabilities/shared/hosts.yaml) — 1 operation for host coverage analysis

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Monitoring and Alerting](capabilities/monitoring-and-alerting.yaml) | Monitors + Metrics + Hosts + Dashboards | 15 | SRE / DevOps Engineer |
| [Incident Management](capabilities/incident-management.yaml) | Incidents + Events + Monitors | 14 | Incident Commander / On-Call |
| [Log Analytics](capabilities/log-analytics.yaml) | Logs + Events | 9 | Platform Engineer / Developer |
| [Synthetic Testing](capabilities/synthetic-testing.yaml) | Synthetics + Monitors | 10 | QA Engineer / SRE |

## Vocabulary

- [Datadog Vocabulary](vocabulary/datadog-vocabulary.yaml) — 10 resources, 2 APIs, 5 domains, 5 personas

## Rules

- [Datadog Spectral Rules](rules/datadog-spectral-rules.yml) — 19 rules

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
