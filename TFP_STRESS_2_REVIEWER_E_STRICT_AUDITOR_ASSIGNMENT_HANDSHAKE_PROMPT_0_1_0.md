# TFP-STRESS-2 — Prospective Reviewer E Strict-Auditor Assignment Handshake 0.1.0

You are being considered for assignment as **Reviewer E, the strict independent auditor** for a Theological Foundations Program study identified only as **TFP-STRESS-2**.

This is an **assignment-only handshake**. Do **not** inspect the repository, search for TFP-STRESS-2, request or infer the study outcome, read prior audit/repair material, or perform any substantive audit yet.

Your only task is to establish whether your present actor lineage is procedurally disjoint enough to receive the later frozen audit packet.

## Required declaration

State, as exactly as your interface makes possible:

1. provider;
2. model;
3. session/conversation identifier, or `NOT_EXPOSED_BY_PROVIDER`;
4. whether this is a fresh conversation/context for this assignment;
5. whether this conversation is a continuation, fork, subagent, shared-context descendant, or other inherited-context continuation of any prior TFP conversation;
6. whether you have already read or been shown substantive TFP-STRESS-2 evidence, candidate results, G2/G3 synthesis, audit findings, repair reasoning, or outcome information in this conversation;
7. whether you have previously served in an outcome-material role for TFP-STRESS-2 in this or any continued/shared-context lineage;
8. whether visible persistent memory or other carried context contains substantive TFP-STRESS-2 audit/repair/outcome reasoning;
9. whether you are the same actor lineage as, or a continuation/fork/shared-context descendant of, the Program Lead or any prior Reviewer A, B, C, or D for TFP-STRESS-2.

## Decision rule

Return exactly one assignment status:

- `PROCEDURALLY_DISJOINT_FOR_ASSIGNMENT`
- `NOT_PROCEDURALLY_DISJOINT`
- `CANNOT_ESTABLISH_DISJOINTNESS`

Use `PROCEDURALLY_DISJOINT_FOR_ASSIGNMENT` only if you can affirm that this is a fresh actor lineage for the proposed strict audit, with no substantive TFP-STRESS-2 outcome/audit/repair material already supplied in this conversation and no continuation/fork/shared-context descent from an outcome-material TFP-STRESS-2 role.

If you cannot establish that, return one of the other two statuses.

## Output format

Return only:

```text
PROVIDER:
MODEL:
SESSION_ID:
FRESH_CONTEXT:
CONTINUATION_OR_SHARED_CONTEXT:
PRIOR_TFP_STRESS_2_SUBSTANTIVE_EXPOSURE:
PRIOR_TFP_STRESS_2_OUTCOME_MATERIAL_ROLE:
VISIBLE_PERSISTENT_MEMORY_EXPOSURE:
RELATION_TO_PROGRAM_LEAD_OR_REVIEWERS_A_B_C_D:
ASSIGNMENT_STATUS:
```

Do not add substantive study analysis. Stop after the handshake.
