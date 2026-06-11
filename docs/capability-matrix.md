# Capability Matrix

| Capability | Public Demonstration | Private Implementation |
| --- | --- | --- |
| Invariant monitoring | Shows the classes of safety checks BridgeGuard evaluates. | Rule engine, calibration, state handling, and production policies are private. |
| Attack replay | Uses sanitized historical patterns to demonstrate defensive detection. | Replay engine, event normalization, and full scenario library are private. |
| Risk decisioning | Displays operator-oriented decision categories and explanations. | Formula details, thresholds, weights, and tuning data are private. |
| Connector coverage | Lists supported integration families at a high level. | Connector source, credentials, endpoint mappings, and deployment configs are private. |
| Alerting | Describes escalation channels conceptually. | Webhook formats, notification templates, routing rules, and secrets are private. |
| Reporting | Shows the shape of evidence useful to auditors and operators. | Report generation code, signatures, and customer-specific outputs are private. |

## Public Decision Categories

BridgeGuard public demos use broad decision categories:

- `allow`: activity appears consistent with expected bridge behavior.
- `review`: activity should be inspected before operational escalation.
- `block`: activity matches one or more high-risk defensive indicators.

The private implementation may use additional internal states, scoring dimensions, and calibration data.
