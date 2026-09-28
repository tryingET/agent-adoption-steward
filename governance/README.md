---
summary: "Work authority for agent-adoption-steward: the Agent Kernel DB; the checked-in work-items projection is retired."
read_when:
  - "Routing active or deferred work for this repo"
  - "Considering a checked-in work-items file"
---

# Governance — agent-adoption-steward

Deferred and active work for this repo lives in the **Agent Kernel DB** (`ak task ...`).
The AK DB is the sole work authority; no checked-in work-items projection exists or should be reintroduced.

The retired `governance/work-items.json` projection carried no task items (empty
`milestones`); nothing was lost at retirement.

## Optional explicit task-scope snapshots

When a task needs explicit scope:

- author/update the scope in AK via `ak task scope show|set|update ...`
- keep repo-side copies under `governance/task-scopes/AK-<TASK-ID>.snapshot.json` as frozen exports
- refresh a checked-in snapshot with `mkdir -p governance/task-scopes && ak task scope export <TASK-ID> > governance/task-scopes/AK-<TASK-ID>.snapshot.json`
- verify checked-in snapshots with `./scripts/check-task-scope-snapshots.sh` before commit or in CI

## Non-negotiable

- Do not leave deferred work as ad-hoc TODO comments or scattered markdown notes.
- Do not reintroduce a checked-in `governance/work-items.json` projection; the AK DB is authoritative.
- Do not hand-author `governance/task-scopes/AK-*.snapshot.json` as if it were the live task-scope source of truth.
