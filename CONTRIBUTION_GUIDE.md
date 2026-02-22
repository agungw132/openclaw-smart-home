# CONTRIBUTION_GUIDE.md — smart-home

Project objective:
Build a Kubernetes-based smart-home data platform to ingest IoT data and provide notebook, basic dashboard, and time-series database services.

## Specialist ownership and deliverables

- `agent-supervisor`
  - Owns: project coordination, cross-agent integration, status/risk reporting.
  - Delivers: execution plan, consolidated updates, blocker escalation.

- `agent-product-owner`
  - Owns: `product/requirements/`, scope and acceptance criteria.
  - Delivers: PRD/backlog, prioritized milestones, success metrics.

- `agent-solution-architect`
  - Owns: `architecture/`, `docs/adr/`.
  - Delivers: architecture baseline, ADRs, domain boundaries, phased rollout design.

- `agent-devops-platform`
  - Owns: `infra/iac/`, `infra/orchestration/`.
  - Delivers: Terraform/Terragrunt/Helm manifests, environment configs, deploy runbooks.

- `agent-data-engineer`
  - Owns: `data/contracts/`, `data/schemas/`, `data/catalog/`, `pipelines/*`.
  - Delivers: ingestion/transformation/serving pipelines, schema contracts, data catalog entries.

- `agent-qa-engineer`
  - Owns: `quality/tests/`, validation strategy in `quality/monitoring/`.
  - Delivers: test plans, test artifacts, data quality and integration validation gates.

- `agent-security-appsec`
  - Owns: `security/access-control/`, `security/privacy/`.
  - Delivers: threat/risk review, RBAC/policy baseline, secrets/data-protection controls.

- `agent-sre-platform`
  - Owns: `operations/sre/`, SLO and alerting docs in `quality/monitoring/`.
  - Delivers: reliability runbooks, SLOs/alerts, incident/rollback playbooks.

- `agent-release-manager`
  - Owns: release checklist and rollout governance across docs/runbooks.
  - Delivers: release gates, cutover plan, go/no-go checklist.

## Contribution rules
- Work only inside this project folder.
- Append every material action to `changelog.md`.
- If task scope is unclear or outside ownership, escalate to supervisor before acting.
