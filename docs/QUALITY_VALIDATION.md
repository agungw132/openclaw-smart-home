# Quality & Validation

## Minimum Acceptance Criteria
- E2E smoke check passes: MQTT publish -> Kafka topic -> storage row.
- Replay/canary validation passes.
- Consumer lag and ingestion latency within threshold.
- Data integrity checks pass (idempotency/late arrival handling).

## Evidence Requirements
- CI artifacts or command output snippets
- Dashboard and alert evidence
- Changelog entry with next step or blocker
