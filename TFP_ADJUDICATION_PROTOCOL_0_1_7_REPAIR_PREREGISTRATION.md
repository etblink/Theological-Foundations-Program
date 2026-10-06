# TFP Adjudication Protocol 0.1.7 — Bounded Exit-Gate Repair Preregistration

**Date:** 2026-10-05  
**Authorization:** `TFP_PROGRAM_REANCHORING_ACCEPTANCE_0_1_0.md`  
**Source protocol:** `TFP_ADJUDICATION_PROTOCOL_0_1_6.md`  
**Source audit:** `TFP_ADJUDICATION_PROTOCOL_0_1_6_STRICT_QUALIFICATION_REAUDIT_REPORT.md`  
**Repair posture:** one bounded repair cycle; no speculative expansion

## 1. Objective

Produce candidate Protocol 0.1.7 by repairing the five accepted MAJOR defects from the 0.1.6 strict audit and only directly interacting MINOR defects needed for qualification validity, outcome determinacy, or cold-start executability.

The protocol exists to serve substantive theological truth research. This repair is an exit-gate repair, not a new methodological research program.

## 2. MAJOR repair scope

### R1 — exhaustive base outcome partition

Repair by:
- turning candidate structural/evidential statuses into a true non-overlapping partition;
- defining exact base-outcome precedence;
- explicitly covering:
  - 0 adequate;
  - 1 adequate;
  - 2+ adequate / 0 ranking-eligible;
  - 2+ adequate / 1 ranking-eligible;
  - 2+ ranking-eligible / no dominance;
  - robust dominance;
- defining when INSUFFICIENT_SIGNAL fires, including prerequisite-4/coverage failure;
- adding a compact decision table.

### R2 — evidence/disposition to discriminator direction

Repair by:
- requiring each CRITICAL/MATERIAL discriminator to preregister a `DIRECTION_RULE`;
- mapping specified evidence/proposition dispositions to `FAVORS_A`, `FAVORS_B`, `NEUTRAL_OR_NONDISCRIMINATING`, or `UNMAKEABLE`;
- prohibiting post-evidence invention of directional criteria;
- assigning an independent post-evidence `DIRECTION_RESULT_REVIEWER`.

### R3 — post-evidence confirmatory ceiling

Repair by eliminating the contradictory cross-candidate “adverse to B but favorable to A” ceiling.

For any post-evidence amendment with a favorable or mixed effect:
- candidate-level corrections and adverse consequences are preserved;
- no candidate may receive a stronger confirmatory comparative outcome because of that amendment;
- if the amendment changes the relative ranking/dominance surface, the current confirmatory comparison ends with `UNDERDETERMINED_WITHIN_SCOPE: POST_EVIDENCE_DIRECTIONAL_CONTAMINATION`;
- positive comparative use requires a new preregistered confirmatory cycle or genuinely held-out evidence.

This is intentionally simpler than inventing a cross-candidate favorability metric.

### R4 — qualification STATE transition

Repair by:
- replacing ambiguous qualification-transition “Q1/Q2” labels with `QT1` / `QT2`;
- expanding the QT1 whitelist to include all fields required to keep STATE internally consistent;
- defining the operative Governance reference after ratification as the exact immutable governed-bundle path/blob;
- allowing candidate-governance/candidate-protocol bookkeeping to be cleared or marked qualified;
- forbidding all research-truth, adjudication, negative-knowledge, and reopen-condition changes during QT1/QT2.

### R5 — qualification role-control completeness

Repair by:
- requiring the next role-control record to conform exactly to Governance, STATE, and the protocol template;
- including candidate protocol/Governance authors, human-owner authorship/reviewer status, source-manifest preparer, operative-Governance baseline, actor lineages, strict-audit count, and per-audit ASSIGNED status;
- treating the launch-time role-control blob as immutable; audit completion is evidenced by the audit report, not by mutating the frozen role-control blob.

## 3. Directly interacting MINOR repairs

Repair only these directly coupled items:

- M1: add existential/practical sufficiency template;
- M2: define evidence exposure and require ledger-completeness attestation;
- M3/M4: audit disagreement is material only when canonical consequence differs; reconciliation author must be disjoint;
- M6: assign background granularity/interaction reviewer;
- M7: define CLOSEST adjudicator/background behavior and allowed base outcome;
- M8: align adverse-source-probe infeasibility with coverage labels;
- M9: freeze SHARED_FLOOR/CANDIDATE_SPECIFIC reference set at G0;
- M10: re-run adequacy/eligibility as well as dominance under each required background;
- M11: make MODERATE/LOW confidence thresholds mutually exclusive;
- M12: remove Q2 transition-name collision by QT1/QT2;
- M13: frozen role-control launch blob does not mutate after audit;
- M14: add only the minimum schemas needed for the repaired direction/amendment/qualification surfaces.

Items not necessary to these surfaces may remain explicit limitations or later maintenance work rather than expanding Protocol 0.1.7.

## 4. Anti-drift constraints

During this repair:

- do not create a new scoring system;
- do not add generalized machinery unrelated to R1–R5;
- do not widen the program scope;
- do not authorize TFP-STRESS-2;
- prefer deleting ambiguity to adding procedural layers;
- preserve `UNDERDETERMINED`, `INSUFFICIENT_SIGNAL`, and `PASS_WITH_LIMITATIONS` as legitimate outcomes.

## 5. Exit gate

After repair:
1. freeze one new immutable governed bundle;
2. create a complete role-control record after fresh auditor assignment;
3. run one fresh strict qualification audit.

If that audit returns `PASS` or `PASS_WITH_LIMITATIONS` with no repair-triggering defect cluster under the protocol's own semantics, proceed to human-owner qualification instead of another perfection loop.

```text
PROTOCOL_0_1_7 = CANDIDATE__BOUNDED_EXIT_GATE_REPAIR
QUALIFIED_PROTOCOL = NONE
TFP_STRESS_2 = NOT_AUTHORIZED
```
