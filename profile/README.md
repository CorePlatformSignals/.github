# Core Signal

**From operational data to explainable decisions.**

Core Signal is an enterprise-grade, multi-tenant intelligence platform that turns operational data into evidence-backed signals, evaluations, decisions and governed actions.

```text
Data/Event → Context → Metric/Feature → Signal → Score → Evaluation → Decision → Action
```

The platform core is domain-neutral. Product and industry knowledge is delivered through versioned **Domain Packs**, while source-specific integration is delivered through **Connectors**.

## Reference domains

- **Editorial Intelligence** — Newsroom production commitments and semantic analysis
- **Engineering Intelligence** — DevPulse delivery and review-flow risks
- **Commerce Intelligence** — Kasbify/Digikala profit, leakage, return and SLA risk
- **Connected Operations** — CoreLink device health, telemetry and work-order signals

## First milestone

The Foundation MVP is a batch-first deterministic pipeline. Its first vertical is **Newsroom Commitment Monitor**: ingest publication events, measure monthly commitments, forecast shortfalls, emit evidence-backed risk evaluations, and reconcile production quantities with OpenMeter.

## Architecture

- **Control Plane:** tenants, workspaces, subjects, identity, definitions, policies, packs, entitlements and audit
- **Data Plane:** ingestion, validation, metrics, signals, scores, evaluations, decisions and action dispatch
- **Intelligence Plane:** statistics, semantic retrieval, embeddings, ML/LLMs and model governance

Core Signal detects and explains. Governed agents may recommend or choose an action. Integration services such as Composio may execute approved actions. Source platforms retain transactional ownership.

## Principles

- deterministic rules before probabilistic AI
- evidence, lineage and validity windows for decision-grade outputs
- multi-tenancy and isolation by design
- open, versioned and replayable contracts
- batch-first MVP with streaming added by measured need
- usage metering separated from operational truth
- no autonomous agents or arbitrary in-cluster plugins in Foundation MVP

## Repositories

| Repository | Purpose | Visibility |
|---|---|---|
| [Platform](https://github.com/CorePlatformSignals/Platform) | Runtime, console, connectors and Domain Packs | Private |
| [Contracts](https://github.com/CorePlatformSignals/Contracts) | Event, schema, API and pack contracts | Private |
| [Deployment](https://github.com/CorePlatformSignals/Deployment) | Deployment profiles and operations | Private |
| [.github](https://github.com/CorePlatformSignals/.github) | Organization profile and governance | Public |

## Status

The project is in the **Foundation and architecture phase**. Initial implementation is tracked in the Platform and Contracts repositories.
