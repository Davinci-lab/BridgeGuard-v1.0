# BridgeGuard

BridgeGuard is a defensive runtime security system for cross-chain bridge operations.

This public repository is intentionally a **showcase pack**, not the product source tree. It demonstrates the value, operating model, and defensive scenarios covered by BridgeGuard without exposing implementation code, private connectors, production configuration, secrets, proprietary rules, or deployment material.

## What BridgeGuard Demonstrates

- Runtime invariant monitoring for bridge events.
- Defensive attack replay using public, historical incident patterns.
- Explainable risk decisions for operators and auditors.
- Scenario-based evidence that risky bridge activity can be flagged before escalation.
- Operator-facing outputs suitable for review, escalation, and compliance workflows.

## What Is Public Here

- High-level capability matrix.
- Sanitized scenario descriptions.
- Public security boundaries.
- Non-reproducible architecture overview.
- Sample evidence format with no live credentials, payloads, or private logic.

## What Is Intentionally Not Public

- Backend, frontend, worker, and connector source code.
- Risk scoring formulas, proprietary rule weights, and production policies.
- API keys, tokens, RPC URLs, webhook URLs, private endpoints, or account data.
- Deployment manifests, database migrations, CI workflows, and operational runbooks.
- Exploit payloads or instructions that could be used offensively.

## Defensive Scope

BridgeGuard is defensive-only. It does not custody funds, sign transactions, move assets, or provide exploit tooling. Its purpose is to help bridge teams, auditors, insurers, and security researchers identify suspicious bridge activity and reason about operational risk.

## Demo Materials

- [Capability Matrix](docs/capability-matrix.md)
- [Demo Scenarios](docs/demo-scenarios.md)
- [Public Architecture](docs/public-architecture.md)
- [Security Boundaries](docs/security-boundaries.md)
- [Sample Evidence Pack](docs/sample-evidence-pack.md)
- [Sanitized Scenario Data](demo/scenarios.json)

## Commercial And Private Evaluation

Private evaluations can include the full operator console, API, connectors, and deployment guidance under an appropriate agreement. The public repository remains limited to safe demonstration material.
