# Operations Runbook

## 15-minute Triage Flow
1. Validate ingest path (MQTT -> Kafka -> storage).
2. Check broker/exporter health and consumer lag.
3. Verify data-write latency and backlog status.
4. Check replay/canary status.
5. Decide rollback vs forward-fix.

## Escalation Matrix
- Ingestion/transport issue: DevOps + SRE
- Data integrity issue: Data Engineer + QA
- Security controls: AppSec
- Release/no-go decision: Release Manager + Supervisor

## Mandatory Links for Rollouts
- Pre-check evidence
- Rollback plan
- Post-check evidence
