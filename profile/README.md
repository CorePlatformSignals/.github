# Core Platform Signals

**From events to explainable decisions.**

Core Platform Signals is an enterprise-grade, multi-tenant platform for converting operational data into features, signals, scores, evaluations, decisions, and actions.

```text
Data → Event → Feature → Signal → Score → Evaluation → Decision → Action
```

The platform is domain-neutral. Industry and product knowledge is delivered through installable **Domain Packs** and **Connectors**.

## Initial reference domains

- **Connected Operations Intelligence** for IoT, fleet, smart assets, telemetry, and CoreLink Platform
- **Engineering Intelligence** for software delivery, DevOps, and DevPulse
- **Editorial Intelligence** for newsrooms, publishing workflows, and semantic content analysis

These are the first reference implementations, not the boundaries of the platform.

## Architecture

The platform is divided into three planes:

- **Control Plane**: organizations, tenants, workspaces, schemas, policies, models, packs, entitlements, and audit
- **Data Plane**: ingestion, normalization, feature computation, signal detection, scoring, evaluation, and action dispatch
- **Intelligence Plane**: statistical models, semantic retrieval, embeddings, machine learning, LLMs, and model governance

## Core principles

- Domain-neutral platform core
- Open standards and explicit contracts
- Event-driven and replayable processing
- Explainable results with evidence and lineage
- Multi-tenancy and isolation by design
- Deterministic rules before probabilistic AI
- Model and policy versioning
- Usage metering and commercial entitlement separation
- Cloud, dedicated, and on-premise deployment paths

## Standards and technologies

CloudEvents, AsyncAPI, OpenAPI, MQTT 5, Kafka-compatible streaming, PostgreSQL, pgvector, ClickHouse, OpenMeter, OpenTelemetry, and Keycloak.

## Repositories

| Repository | Purpose | Visibility |
|---|---|---|
| `platform` | Product monorepo containing control plane, data plane, console, runtimes, connectors, and initial domain packs | Private |
| `contracts` | Public event, API, schema, and Domain Pack contracts | Public |
| `deployment` | Docker Compose, Helm, Terraform, operational profiles, and environment configuration | Private |
| `examples` | Public integration examples and reference event producers/consumers | Public |
| `.github` | Organization profile, contribution defaults, issue templates, and governance files | Public |

## Product status

Core Platform Signals is currently in the **foundation and architecture phase**. The first development milestone is an end-to-end deterministic pipeline for the three initial reference domains.

## Security

Do not report security vulnerabilities through public issues. Follow the security policy published in the relevant repository.
