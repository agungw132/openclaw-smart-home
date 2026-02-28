# smart-home

## Project Overview
Data-platform project for smart-home telemetry ingestion, transport, storage, and operational visibility.

## Scope
- In scope: telemetry/data pipeline design and operations (MQTT/Kafka/TSDB flow), platform integration, monitoring.
- Out of scope: unrelated enterprise platform services.

## Architecture Snapshot
- Ingestion and event transport pipeline for smart-home data.
- Data persistence and observability integrated with platform tooling.
- Infrastructure and deployment managed through IaC workflow.

## Repository Structure
See:
- `STRUCTURE.md`
- `CONTRIBUTION_GUIDE.md`

## Ownership & Contribution
Primary collaborators include supervisor, solution architect, devops, data engineer, sre, appsec, qa, release manager.
Folder-level ownership: `CONTRIBUTION_GUIDE.md`.

## Environments & Deployment Flow
- Current focus: DEV rollout and stabilization
- Recommended promotion: plan -> approval -> apply -> verify

## Operations
- Project status and milestones: `changelog.md`
- Phase-2 runbook index: `docs/OPERATIONS_RUNBOOK.md`
- Keep rollout/rollback steps linked from operational docs.

## Security & Compliance
- Security baseline and controls: `docs/SECURITY_BASELINE.md`
- Follow secure secret handling and runtime injection policy.
- Apply baseline controls before promotion to higher environments.

## Quality & Validation
- Validation strategy and acceptance criteria: `docs/QUALITY_VALIDATION.md`
- Define and maintain end-to-end smoke tests for ingestion -> transport -> storage.
- Keep evidence and acceptance checks in project validation/test folders.

## Change Tracking
- `changelog.md` is the source of truth for updates, blockers, and next actions.
