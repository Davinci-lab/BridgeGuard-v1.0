# Demo Scenarios

These scenarios are intentionally descriptive and defensive. They do not include exploit payloads, production rules, live endpoints, or instructions for attacking a bridge.

| Scenario | Defensive Signal | Expected Operator Outcome |
| --- | --- | --- |
| Validator quorum anomaly | A bridge action appears to be approved by an unusual validator pattern. | Escalate for manual review before accepting the event as trusted. |
| Message replay pattern | A message resembles a previously processed transfer intent. | Block or quarantine the event until replay status is resolved. |
| Liquidity drain velocity | Outbound value accelerates beyond the normal profile for a monitored route. | Trigger risk review and require additional approval. |
| Contract upgrade drift | Runtime behavior changes after an upgrade-related event. | Verify governance, deployment provenance, and expected invariants. |
| Connector health degradation | A data source becomes stale or inconsistent with peer sources. | Degrade confidence and route decisions through a safer review path. |

## Safe Demonstration Rules

- Use synthetic or public historical data only.
- Remove addresses, customer identifiers, credentials, and infrastructure metadata.
- Avoid publishing thresholds or formulas that reproduce private detections.
- Keep examples focused on operator interpretation and defensive response.
