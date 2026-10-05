# Theological Foundations Program — Governance

**Version:** 0.1.1  
**Status:** active governance  
**Date:** 2026-10-05  
**Governing charter:** `TFP_PROGRAM_CHARTER_0_1_1.md`

## 1. Purpose

This file governs how the Theological Foundations Program (TFP) changes state, conducts research, accepts conclusions, preserves negative knowledge, and authorizes future work.

TFP's ultimate aim is truth adjudication:

> Determine which theological claims or frameworks, if any, are true—or closest to the truth the evidence and arguments permit us to identify.

Governance exists to prevent that aim from being corrupted by drift, selective evidence, premature synthesis, authority confusion, or silent rewriting of prior results.

## 2. Authority model

Different artifacts answer different questions.

### Program purpose
`TFP_PROGRAM_CHARTER_0_1_1.md`

Defines:
- ultimate aim;
- epistemic posture;
- claim-type boundaries;
- program-level scope.

### Durable operating rules
`GOVERNANCE.md`

Defines:
- how research is authorized;
- how state changes;
- how adjudications are accepted;
- how negative knowledge and reopening work;
- how conflicts among artifacts are resolved.

### Canonical current state
`STATE.yaml`

This is the **sole canonical mutable project-state file**.

It answers:
- what is active now;
- what is held or closed;
- what is authorized;
- what the next action is;
- what canonical conclusions currently exist;
- what reopen conditions are live.

### Qualified adjudication protocol
The protocol identified by STATE.yaml is the operational procedure for authorized studies once independently qualified.

The protocol is subordinate to Charter, Governance, and canonical STATE. A candidate or repair protocol does not become operative merely by existing in the repository.

### Provisional method
TFP_METHOD_SEED_0_1_0.md contains the current methodological source and rationale.

It is not immutable and is not itself authority to change canonical conclusions.

### Frozen research artifacts

Preregistrations, audits, source reviews, syntheses, and decision records preserve evidence and reasoning at a point in time.

They are historical evidence, not competing current-state authorities.

### README

The README is orientation only.

If README prose conflicts with `STATE.yaml`, the state file governs current status.

### Git history

Git preserves provenance and history.

Historical commits do not override current canonical state merely because they are older or more detailed.

## 3. Roles and independence

### Human owner
The **human owner** is the person with final program authority.

Only the human owner may:
- authorize a new bounded truth-adjudication study at G0;
- accept a canonical theological adjudication at G5;
- qualify a new adjudication protocol after the required independent audit;
- change governance where authority boundaries are affected.

### Program lead
The **program lead** is the designated research-orchestration role named in STATE.yaml or the study charter.

The program lead may:
- prepare preregistrations;
- coordinate evidence lanes;
- record procedural gate completion;
- propose repairs;
- update state within already-authorized scope.

The program lead may not:
- authorize their own new truth-adjudication study;
- substitute for the human owner's G5 acceptance;
- override a failed required independent audit.

### Independent reviewer
An **independent reviewer** for a specific decision:
- did not author or co-author the artifact/change being reviewed;
- did not make the outcome-determinative decision under review;
- has not been assigned a conflicting role in the same gate;
- receives the frozen material necessary for review.

Procedural independence between AI sessions or models does not guarantee independence of training priors. Model/session provenance must therefore be recorded when AI reviewers are used.

### Strict independent auditor
A **strict independent auditor** may not have authored or co-authored:
- the G0 preregistration;
- any candidate steelman packet;
- any outcome-determinative lane;
- the comparative synthesis;
- the repair under audit.

The auditor may inspect frozen source material but may not edit the study while auditing.

### Human-owner dual-role exception
The human owner may contribute evidence or discussion. If the human owner also materially authors the comparative synthesis, that dual role must be preregistered or recorded as an exception before G4, and canonical acceptance requires at least two strict independent audits or another independence safeguard explicitly accepted in the study charter.

### Role freeze
Every G0 charter must name:
- human owner;
- program lead;
- candidate constructors;
- lane authors;
- independent reviewers;
- intended strict independent auditor(s), if known;
- any approved dual-role exception.

## 4. Core governance separations

TFP adopts the following non-equivalences:

```text
EVIDENCE ≠ SYNTHESIS
SYNTHESIS ≠ ADJUDICATION
ADJUDICATION ≠ AUTHORIZATION

CANDIDATE ≠ CANONICAL
OBSERVATION ≠ ACCEPTANCE
AUDITOR_PASS ≠ PROGRAM_ACCEPTANCE

HISTORICAL_RESULT ≠ GLOBAL_THEOLOGICAL_VERDICT
LOCAL_RESULT ≠ WHOLE-FRAMEWORK_TRUTH
HOLD ≠ FORGOTTEN
FAILURE ≠ DELETION
```

No transition across these boundaries is implicit.

## 5. Research lifecycle

A bounded TFP investigation should normally pass through:

### G0 — Question authorization
Freeze:
- exact question;
- scope;
- claim types;
- candidate universe or candidate-selection rule;
- major alternatives;
- expected evidence;
- potential falsifiers or weakening evidence;
- stop conditions.

### G1 — Evidence acquisition
Collect source material without allowing provisional synthesis to redefine the question.

Where practical:
- separate evidence collection from interpretation;
- preserve source provenance;
- distinguish primary from secondary sources;
- record inaccessible or missing evidence.

### G2 — Lane synthesis
Analyze evidence within its proper claim type.

Examples:
- textual;
- historical;
- archaeological;
- philosophical;
- doctrinal;
- experiential.

One lane may inform another but may not silently substitute for it.

### G3 — Comparative adjudication
Compare serious candidates under equal standards.

Required:
- strongest recognizable form of each candidate;
- explicit discriminators;
- alternative explanations;
- uncertainty;
- negative evidence.

### G4 — Adversarial audit
Attempt to overturn the provisional result.

Where useful:
- independent auditor;
- blind or label-reduced evaluation;
- held-out evidence;
- red-team reconstruction;
- strongest rival interpretation.

### G5 — Canonical acceptance
Only an explicit acceptance step may change canonical adjudication state.

A successful audit alone does not change program truth commitments.

### G6 — Hold / close / reopen
Every completed lane must state:
- closed;
- held;
- superseded;
- or reopened.

Held or closed work should have explicit `reopen_if` conditions where practical.

## 6. Claim typing

Before adjudication, claims should be typed where possible as:

- textual;
- historical;
- archaeological/material;
- linguistic;
- interpretive;
- philosophical;
- doctrinal;
- empirical;
- experiential/practical;
- faith commitment.

A claim may span types.

The evidence burden must match the type of claim.

## 7. Equal-standard principle

Comparable rival claims must face comparable burdens.

TFP must not privilege a position because it is:

- traditional;
- skeptical;
- confessional;
- secular;
- majority;
- minority;
- ancient;
- modern;
- institutionally authoritative;
- emotionally attractive.

A method that defeats one candidate must be checked for symmetrical consequences against rivals where applicable.

## 8. Candidate-universe rule

TFP must not declare a winner from an artificially narrow field.

Before comparative closure, ask:

1. Are the serious candidate classes represented?
2. Did one framework define all rivals in its own vocabulary?
3. Is a hybrid or revised synthesis a legitimate candidate?
4. Is `NONE_ADEQUATE` or `UNDERDETERMINED` still live?

Candidate completeness is a gate, not an afterthought.

## 9. Independent construction and contamination control

Where a candidate can be distorted by knowledge of its rivals:

- build or source its strongest form independently;
- freeze it before comparative exposure;
- use tradition-native sources and informed advocates;
- preserve an independence interval where useful.

TFP should not manufacture convergence and later treat that convergence as discovery.

## 10. Preregistration

Complex studies should preregister enough structure to reveal later drift.

A preregistration should preserve:
- the original hypothesis or truth question;
- dependency structure;
- candidate set;
- evidential expectations;
- weakening conditions;
- alternatives;
- disposition vocabulary.

Derived hypotheses may be created later but may not silently replace the original.

## 11. Evidence provenance

For consequential claims, record enough provenance to reconstruct the evidential path.

Depending on domain this may include:
- manuscript/source identity;
- edition or translation;
- archaeological context;
- chain of custody;
- publication details;
- dating assumptions;
- analytical method;
- quotation context;
- philosophical premises.

Evidence with weak provenance may remain informative but must be marked accordingly.

## 12. Observation-first rule

When reviewing a source, first record what the source actually contains before reconciling it with current TFP conclusions.

Disagreement with canonical state is a finding.

It must not be silently harmonized away.

## 13. Negative knowledge

Negative results are first-class project assets.

Preserve:
- failed arguments;
- unsupported genealogies;
- chronology conflicts;
- disconfirmed predictions;
- unsuccessful candidate explanations;
- missing evidence;
- methodological failures.

Where useful, canonical negative knowledge should record:

```text
claim
status
reason
scope
reopen_if
```

A later successor should not need to rediscover why an attractive path was rejected.

## 14. Reopening rule

Closed or held work may reopen only for a stated reason such as:

- materially new evidence;
- changed dating/source attribution;
- successful independent replication;
- a credible audit exposing an error;
- a newly relevant downstream question.

Mere renewed interest is not automatically sufficient.

## 15. One authoritative next action

TFP may maintain a large research queue, but `STATE.yaml` should identify one authoritative next action unless a deliberately parallel bounded stage is authorized.

This prevents locally interesting work from becoming the program's accidental center of gravity.

## 16. Stop rule

Research is not required to continue indefinitely.

A lane should stop or hold when:

- its authorized question is answered within scope;
- the frozen coverage plan is complete or materially complete and further accessible evidence is unlikely to change a truth-critical disposition;
- the next useful step depends on unavailable evidence;
- expected information gain becomes low **after** an auditable coverage record exists, or further truth-critical evidence is unavailable;
- another program gate has higher value.

Low expected information gain alone is not a substitute for documenting source/evidence coverage.

`UNDERDETERMINED` and `INSUFFICIENT_SIGNAL` are legitimate results.

## 17. No opaque global score

TFP should not compress heterogeneous evidence into a single unexplained truth score.

A candidate may:
- fit early texts well;
- fit later doctrine poorly;
- have strong historical continuity;
- remain philosophically weak;
- or vice versa.

Typed dispositions are preferred to false numerical precision.

## 18. Continuity control

Historical or doctrinal continuity should use the candidate **Continuity Framework (C0–C7)**:

- C0 recurrence;
- C1 material continuity;
- C2 carrier continuity;
- C3 ritual/practice continuity;
- C4 semantic continuity;
- C5 named textual continuity;
- C6 genealogical continuity;
- C7 doctrinal continuity.

These are relation types, not a mandatory universal linear sequence. Branching, convergence, loss, recovery, refunctionalization and independent construction are permitted.

However, no study may jump from mere resemblance/recurrence to genealogy or doctrinal continuity without separately establishing the relations actually required by that claim.

## 19. Origins / development / truth separation

Always distinguish:

- how a belief arose;
- how it developed;
- what it meant;
- whether it is true.

A natural historical origin does not by itself falsify a theological claim.

A theological claim being true does not make every historical account of its development correct.

## 20. Blindness and independent audit

Where practical, TFP should use controlled independence.

Possible forms include:
- anonymized interpretations;
- tradition labels withheld during semantic evaluation;
- independent candidate reconstruction;
- held-out source packets;
- auditor review before seeing the provisional verdict.

Blindness is a tool, not a ritual requirement.

It should be used where it reduces a real bias.

## 21. Human and program authority

Research agents may execute work autonomously within explicitly authorized scope.

They may:
- collect evidence;
- create frozen research artifacts;
- propose dispositions;
- update `STATE.yaml` to reflect already-authorized work and completed gates.

They may not silently:
- redefine TFP's governing aim;
- authorize a new major theological program;
- promote a local result into a global truth commitment;
- erase negative knowledge;
- reopen held work without satisfying a reopen condition or receiving authorization.

The human owner retains final authority over:
- program purpose;
- authorization of bounded truth-adjudication studies;
- major scope changes;
- acceptance of canonical theological adjudications;
- acceptance of consequential program-level truth commitments;
- qualification of adjudication protocols after required independent audit;
- changes to governance itself when those changes alter authority boundaries.

## 22. Conflict resolution

If artifacts disagree:

1. Charter governs ultimate purpose.
2. Governance governs operating rules.
3. `STATE.yaml` governs current operational status.
4. Accepted adjudication records govern their bounded conclusions.
5. The independently qualified adjudication protocol named by STATE governs study procedure.
6. The Method Seed supplies methodological rationale where not superseded by higher authority.
7. Frozen research artifacts preserve historical evidence/reasoning.
8. README and prose summaries are orientation only.

A conflict should be repaired explicitly, not silently harmonized.

## 23. Succession requirement

A competent unfamiliar successor should be able to recover:

- what TFP is trying to determine;
- what method currently governs;
- what is active;
- what is held;
- what has been rejected;
- what the next action is;
- what evidence would reopen closed work.

If this requires reconstructing state from dozens of prose files, governance has failed.

## 24. Current governance state

```text
GOVERNANCE_VERSION = 0.1.1
CANONICAL_MUTABLE_STATE = STATE.yaml
PROGRAM_CHARTER = TFP_PROGRAM_CHARTER_0_1_1.md
CURRENT_METHOD = TFP_METHOD_SEED_0_1_0.md
QUALIFIED_PROTOCOL = STATE_CONTROLLED
GLOBAL_TRUTH_ADJUDICATION = NOT_YET_REACHED
```

## 25. Governing maxim

> Preserve the difference between what was observed, what was inferred, what was accepted, and what the program is authorized to conclude.
