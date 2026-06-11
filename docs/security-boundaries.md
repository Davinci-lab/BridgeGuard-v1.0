# Security Boundaries

## Public Safety Boundary

The public showcase must remain safe for open distribution. It may describe what BridgeGuard detects and why the detection matters, but it must not disclose enough detail to clone the product, bypass detections, or target a bridge.

## Redaction Checklist

Before publishing any update, verify that it contains none of the following:

- source code for backend, frontend, workers, connectors, or rule engines;
- API keys, tokens, secrets, passwords, private keys, seed phrases, or certificates;
- RPC URLs, webhook URLs, SMTP settings, database URLs, internal hostnames, or IPs;
- customer names, pilot data, logs, screenshots, wallet addresses, or transaction IDs unless explicitly approved for public use;
- exact scoring formulas, private thresholds, calibration datasets, or proprietary policies;
- exploit payloads, attack scripts, or step-by-step offensive instructions.

## Repository Handling

If private material was ever committed to a public Git history, removing it in a later commit is not enough. The public branch history should be replaced with a sanitized history, and any exposed secrets should be rotated.
