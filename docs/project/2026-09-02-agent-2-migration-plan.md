---
summary: "No-apply migration plan from the current adoption-steward schema-1 repository to the candidate agent/2 pilot contract."
read_when:
  - "Reviewing the first standing-agent pilot or the adoption-steward manifest and placement."
  - "Planning—but not applying—the adoption-steward migration."
type: "migration-plan"
status: "owner_decisions_and_gate_a_acceptance_pending"
---

# Adoption Steward `agent/2` migration plan — no apply

## Status and authority

This artifact is an inspect-and-plan result only. Its machine-readable companion sets `apply: false`. It does not appoint the agent, select the stable UUID, approve a release, issue a run permit, migrate the repository, change the fleet default, activate a runtime, or authorize effects. Those actions remain with their named owners and Gate A/Stage B transition records.

## Observed current state

At source revision `dc354723482f0470ad287d1de3e067a72cd99a85`:

- `agent.json` uses `ai-society.agent/1`;
- the repository is a standalone society-level agent repository;
- the manifest selects `ec-full`, declares `read` and `bash`, and contains broad advisory read territory;
- the README still says home follows Engineering Core product affinity and separately describes a null profile;
- repository policy correctly says the repository does not itself appoint an organizational role and that writes require external owner authority.

The README/manifest disagreement and product-affinity placement claim are current inconsistencies, not accepted authority. Current source is preserved until an explicit Stage B apply.

## Ratified target preserved by this plan

- `agent-adoption-steward` remains society-level at `~/ai-society/agents/agent-adoption-steward`;
- home follows accountable society appointment, not Engineering Core product affinity, read territory, profile provider, or runtime host;
- the agent receives one owner-approved stable UUID and one accountable appointment reference;
- resources use provider-qualified exact revisions;
- the base Engineering Core profile is `engineering-core/ec-adoption-steward`, not `ec-full`;
- profile publication is a complete five-member tree: dependency governance, documentation, security/privacy, testing, and validation;
- additional target-lane resources are exact and task-scoped, never inherited ambiently;
- the first high-assurance pilot is fresh, no-memory, no-transcript, no-compaction, no-ambient, and has `read` as its only tool ceiling;
- Pi observation and ASC process/effect custody remain separate from the agent repository;
- the generated persona projection is identity-bound to the authored persona sources and is not appointment or authorization.

## Owner decisions still required

Source inspection cannot select these facts:

1. the stable `agent_id` UUID;
2. the accountable society appointment and owner reference;
3. the exact accepted release identity;
4. the exact Stage B pilot task and task-scoped target-lane additions;
5. the exact machine and workspace;
6. the short validity interval;
7. the accepted governance and Agent Kernel contract revisions.

The conservative default is null/absent. No placeholder may be promoted into a live manifest or permit.

## Migration invariants

1. Migration is `inspect -> render to scratch -> compare -> review -> explicit apply`.
2. Schema-1 remains readable throughout the compatibility window.
3. No broad Copier refresh may overwrite agent-owned persona, diary, learning, decision, policy, or activity content.
4. Every authored persona byte and every agent-owned path must be compared before apply.
5. Provider import does not transfer provider ownership.
6. A release digest does not authorize a run, and a repository path does not establish appointment.
7. `read` is a Pi tool ceiling, not a claim of confidentiality or OS confinement.
8. A pre-provider attestation is not a pre-effect guarantee; ASC separately gates effects.
9. No migration apply or standing-agent activation occurs in Gate A.

## Stage B apply sequence

After Gate A-Pilot closure and an explicit transition record:

1. freeze the accepted owner revisions and appointment facts;
2. capture the complete schema-1 manifest and agent-owned file digests;
3. render the `agent/2` candidate into a scratch directory from accepted L0 and provider contracts;
4. materialize exact Prompt Vault/provider resources without ambient inheritance;
5. compile the persona projection from the canonical authored sources;
6. compare candidate and current agent-owned bytes and reject any unexplained difference;
7. run schema, canonicalization, ownership, complete-tree, invocation-policy, no-ambient, and rollback checks;
8. present the exact diff for owner review;
9. apply once through the authorized migration action;
10. retain the schema-1 source or an exact rollback artifact until the pilot comparison is accepted.

## Failure semantics

- Missing UUID, appointment, release, permit, machine/workspace, validity, or accepted upstream revision: `blocked_before_render_or_apply`.
- Candidate widens tools, hooks, credentials, effects, resources, target scope, or time: `reject_widening`.
- Persona or agent-owned bytes change without an accepted migration reason: `reject_content_overwrite`.
- Complete profile tree or invocation policy cannot be reproduced: `unproven_materialization`.
- Parent/child Git ownership overlaps: `reject_ownership_overlap`.
- Runtime cannot prove no ambient inheritance: migration may remain inspectable, but the live pilot is not eligible.

These are plan-local outcomes, not global lifecycle states.

## Compatibility and rollback

Compatibility retains schema-1 readers, the current repository, current Phase-2 paths, and the existing inactive/non-strict default. Rollback disables the non-default strict pilot feature, restores the exact prior manifest/projection bytes, and leaves live activation off. It never rewrites diary, learning, decision, policy, or activity history.

## Acceptance scenarios

The owner may accept this plan when it can verify that:

- the target home follows society appointment;
- all unresolved owner facts are explicit and null until selected;
- `ec-adoption-steward` is exact, complete, and narrower than `ec-full`;
- task-lane additions cannot become ambient profile membership;
- only `read` is in the first pilot tool ceiling;
- persona generation and every resource input are identity-bound;
- migration is reviewable and reversible;
- no apply, activation, or Stage B work is implied by plan acceptance.

## Reversal triggers

Reopen the plan if an accepted owner contract changes `agent/2`, the society appointment places the steward elsewhere, the exact role requires a different least-privilege profile, Pi cannot enforce the no-ambient envelope, or migration cannot preserve agent-owned content. Convenience, the current README wording, or a desire to use `ec-full` is not sufficient evidence for reversal.
