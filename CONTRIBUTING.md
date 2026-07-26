# Contributing

Core Platform Signals uses organization-level product planning and repository-level implementation.

## Before opening work

1. Confirm that the change belongs to the platform core, a Domain Pack, a Connector, a contract, or deployment infrastructure.
2. Link the change to an approved issue or architecture decision.
3. Avoid adding domain-specific concepts to the platform core unless they are expressed through generic platform abstractions.

## Development principles

- Preserve tenant isolation.
- Version public contracts and policy definitions.
- Include evidence and lineage for evaluation outputs.
- Prefer deterministic rules for deterministic problems.
- Treat AI output as probabilistic and policy-governed.
- Emit usage events for billable or quota-controlled operations.
- Add observability for every asynchronous boundary.
- Keep secrets, customer data, and production payloads out of Git.

## Pull requests

A pull request should be focused, testable, and linked to an issue. It must describe contract changes, migration impact, tenant-isolation impact, metering impact, and security implications when applicable.
