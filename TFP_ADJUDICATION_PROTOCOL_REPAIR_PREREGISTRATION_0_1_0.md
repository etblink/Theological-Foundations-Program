# TFP Adjudication Protocol 0.1.1 — Repair Preregistration

**Date:** 2026-10-05  
**Branch:** `repair/tfp-adjudication-protocol-0.1.1`  
**Base:** `74c737c03ccf149efaf371402add7e623c963e22`  
**Target:** `TFP_ADJUDICATION_PROTOCOL_0_1_0.md`  
**Audit:** `TFP_ADJUDICATION_PROTOCOL_INDEPENDENT_AUDIT_0_1_0.md`  
**Audit disposition:** `REPAIR_REQUIRED`

## 1. Repair objective

Produce `TFP_ADJUDICATION_PROTOCOL_0_1_1.md` that repairs the accepted external-audit findings without beginning a theological study or changing any theological adjudication.

## 2. Frozen repair matrix

### R1 — acceptance authority / audit independence
Repair by:
- distinguishing procedural gate completion from canonical truth-bearing acceptance;
- requiring human-owner acceptance for every canonical theological adjudication;
- requiring a separate acceptance record;
- making independent audit mandatory before canonical theological adjudication;
- prohibiting lane authors and synthesis authors from serving as sole independent auditor.

### R2 — evidence → adjudication → truth bridge
Repair by:
- defining proposition-level dispositions;
- defining study-level outcomes;
- requiring scope tags;
- adding non-numeric priority rules for combining evidence;
- defining `BEST_SUPPORTED_WITHIN_SCOPE`, `TRUTH_WARRANTED_WITHIN_SCOPE`, and `CLOSEST_TO_TRUTH_WITHIN_SCOPE`;
- preventing discriminator counting.

### R3 — miracle / revelation
Repair by:
- symmetric no-naturalism/no-supernaturalism assumptions;
- explicit background-assumption register;
- separating anomaly, causal class, particular cause, and theological consequence;
- dedicated revelation sequence.

### R4 — evidence burdens
Repair by:
- type-specific minimum sufficiency conditions;
- explicit rules for partial support, support, and non-establishment;
- decomposing doctrinal/revelation truth claims into evidentially tractable subclaims.

### R5 — claim typing
Repair by:
- adding normative, metaphysical, psychological/social explanatory, revelation, and authority categories;
- freezing claim types before evidence acquisition;
- logging post-freeze retyping;
- requiring independent review of consequential retyping;
- defining faith commitments as non-public warrant unless translated into adjudicable premises.

### R6 — philosophical / non-historical reasoning
Repair by:
- adding premise-warrant, validity, defeater, modal/coherence, theoretical-virtue, rival-framework, and sensitivity checks;
- adding normative and doctrinal-logical lanes where relevant.

### R7 — candidate universe
Repair by:
- one symmetric admission standard;
- independent candidate elicitation;
- independent review of exclusions;
- removing `NONE_ADEQUATE` and `UNDERDETERMINED` from candidate classes;
- defining post-freeze candidate addition.

### R8 — discriminators
Repair by:
- freezing discriminators before evidence acquisition;
- logging post-evidence additions;
- defining background-relative assumptions;
- forbidding unweighted tallying;
- typing non-discrimination / underdetermination.

### R9 — source hierarchy
Repair by:
- replacing lexical source rankings with defeasible source-quality dimensions;
- stating earlier ≠ automatically better;
- treating early and late sources symmetrically for reliability/dependence;
- allowing later preservation of earlier material;
- defining independence;
- handling mixed questions claim-by-claim.

### R10 — lane governance
Repair by:
- defining lane creation and freeze;
- replacing "accepted evidence" with non-governance terminology;
- adding a background-assumption register;
- specifying cumulative cross-lane synthesis.

### R11 — evidence acquisition / link decomposition
Repair by:
- adding an explicit evidence-acquisition phase;
- requiring search/source coverage, inclusion/exclusion rules, provenance, inaccessible sources, and negative searches;
- requiring node/arrow link decomposition for multi-step arguments.

### R12 — origins/development/truth / continuity
Repair by:
- defining C0–C7 as relation types, not a strict linear ladder;
- adding branching, convergence, loss, recovery, and discontinuity;
- symmetric burdens for continuity and discontinuity;
- stating when historical development bears on truth because the claim's warrant depends on continuity/origin.

### R13 — governing-document alignment
Repair by:
- explicit precedence;
- explicit G0–G6 ↔ protocol-phase mapping;
- full G0 preregistration contents;
- explicit relationship between Protocol and Method Seed;
- explicit satisfaction of STATE methodology flags.

### R14 — audit mechanics
Repair by:
- frozen audit criteria;
- mandatory independence for canonical theological adjudications;
- auditor-disagreement rule;
- repair/re-audit rule;
- minimum blinding where bias-relevant;
- limitations carried into canonical record;
- mandatory checks for typing drift, discriminator timing, lane leakage, premise warrant, and shallow heuristics.

### R15 — uncertainty
Repair by:
- fixed-format uncertainty statement;
- confidence separated from scope;
- named residual alternatives;
- background assumptions;
- result-flip conditions;
- underdetermination subtypes.

### R16 — stop/reopen
Repair by:
- mandatory `reopen_if`;
- coverage-based stop test;
- G6 status mapping;
- new-argument/defeater reopen paths for philosophical results.

### R17 — anti-heuristic
Repair by:
- adding established-tradition and fewest-assumptions heuristics;
- making anti-heuristic audit mandatory now, not eventually.

## 3. Explicit non-goals

This repair will not:
- begin the resurrection study;
- qualify itself;
- merge the repair branch;
- change EMT dispositions;
- reopen ISR;
- create a new theological truth conclusion;
- add optional methodological features unless directly useful to a required repair.

## 4. Re-audit gate

After repair:
- freeze a focused re-audit prompt limited to R1–R15 plus regression checks on R16–R17;
- require an auditor who did not author the repair;
- prefer an auditor who has not seen the first-pass reasoning;
- do not merge or qualify until external re-audit returns `PASS` or `PASS_WITH_LIMITATIONS` and the human owner explicitly accepts qualification.

## 5. Repair-state invariant

```text
PROTOCOL_0_1_1 = CANDIDATE__REPAIR_PENDING_REAUDIT
SECOND_STRESS_TEST = NOT_AUTHORIZED
MAJOR_DOCTRINAL_COMPARISON = HELD
```
