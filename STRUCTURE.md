# STRUCTURE.md — smart-home

Domain: `data-platform`

Enforced top-level structure (copied from template):
- `architecture/`
- `artifacts/`
- `data/`
  - `catalog/`
  - `contracts/`
  - `schemas/`
- `docs/`
  - `adr/`
  - `runbooks/`
- `infra/`
  - `iac/`
  - `orchestration/`
- `operations/`
  - `sre/`
- `pipelines/`
  - `ingestion/`
  - `transformation/`
  - `serving/`
- `product/`
  - `requirements/`
- `quality/`
  - `monitoring/`
  - `tests/`
- `security/`
  - `access-control/`
  - `privacy/`

Rules:
- Top-level directory changes require supervisor approval and changelog entry.
- All contributions must follow `CONTRIBUTION_GUIDE.md` ownership.
