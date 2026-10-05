# TFP Adjudication Protocol 0.1.3

**Project:** Theological Foundations Program  
**Status:** `CANDIDATE__REPAIR_PENDING_REAUDIT`  
**Date:** 2026-10-05  
**Supersedes operational use of:** no prior protocol unless and until this version is independently re-audited and explicitly qualified  
**Governance:** `GOVERNANCE.md`  
**Canonical state:** `STATE.yaml`  
**Program charter:** `TFP_PROGRAM_CHARTER_0_1_1.md`  
**Method seed:** `TFP_METHOD_SEED_0_1_0.md`

---

## 0. Authority, roles, and qualification boundary

Precedence is:

1. Program Charter — ultimate purpose;
2. Governance — authority and operating rules;
3. `STATE.yaml` — current authorization/state;
4. accepted bounded adjudication records — their exact conclusions;
5. independently qualified adjudication protocol named in STATE — study procedure;
6. Method Seed — methodological rationale not superseded above;
7. frozen research artifacts — historical evidence/reasoning;
8. README — orientation only.

Role definitions come from Governance 0.1.2:

- **human owner:** authorizes every bounded truth-adjudication study at G0, accepts canonical theological adjudications at G5, and qualifies protocols after required audit;
- **program lead:** orchestrates already-authorized work but cannot self-authorize a truth study, override failed audit, or substitute for human acceptance;
- **independent reviewer:** did not author/co-author the item or make the outcome-determinative decision being reviewed;
- **strict independent auditor:** did not author/co-author the G0 preregistration, candidate packets, outcome-determinative lanes, comparative synthesis, or repair under audit, and made no outcome-material reviewer determination in the same study/qualification cycle.

The strict auditor MUST be disjoint from all reviewers who made outcome-material determinations, including candidate/background exclusions, amendment classification, coverage-completeness review, and lane-amendment materiality review.

A protocol-qualification audit uses the same strict-independence standard.

Procedural separation between AI sessions/models is not guaranteed independence of training priors. Model/session provenance must be recorded.

### Protocol qualification act

A protocol version becomes operative only when all occur:

1. independent protocol audit returns `PASS` or `PASS_WITH_LIMITATIONS`;
2. no unresolved BLOCKING or MAJOR defect remains;
3. the human owner creates a versioned protocol-qualification acceptance record;
4. `STATE.yaml` names that exact protocol as `qualified_protocol` and carries any audit limitations.

Protocol qualification does **not** authorize a theological stress test.

---

## 1. Governing principles

TFP seeks which theological claims/frameworks, if any, are true or closest to truth as warranted by evidence and argument.

Core separations:

```text
EVIDENCE ≠ SYNTHESIS
SYNTHESIS ≠ ADJUDICATION
ADJUDICATION ≠ AUTHORIZATION
CANDIDATE ≠ CANONICAL
AUDIT PASS ≠ HUMAN ACCEPTANCE
LOCAL RESULT ≠ GLOBAL THEOLOGICAL VERDICT
```

A study must distinguish:

- origins;
- development;
- meaning;
- truth.

A natural origin does not imply falsity. Ancient origin does not imply truth. Later development is neither corruption nor maturation by default.

---

## 2. Gate map

| Governance gate | Protocol phases |
|---|---|
| **G0 Question authorization** | A–D: charter, roles/backgrounds, candidates/steelman, typing/link map, source plan, discriminators, adequacy, lanes, stop/reopen, audit criteria |
| **G1 Evidence acquisition** | E: frozen-plan search, provenance, coverage, negative/inaccessible evidence, plausibility/attestation record |
| **G2 Lane synthesis** | F–M: proposition dispositions, type-specific sufficiency, philosophical machinery, miracle/revelation/prophecy, source quality, lane freeze, proposition consolidation, continuity |
| **G3 Comparative adjudication** | N–N3: candidate adequacy, inferential bridge, provisional study outcome |
| **G4 Adversarial audit** | O: independent audit with defined severity/outcomes and cold-start test |
| **G5 Canonical acceptance** | P: human-owner acceptance and canonical STATE transition |
| **G6 Hold/close/reopen** | Q: uncertainty, limitations, stop status, negative knowledge, `reopen_if` |

Anti-heuristic and cold-start checks are mandatory G4 checks, not freestanding optional phases.

---

# G0 — QUESTION AUTHORIZATION

## 3. Phase A — Truth-question charter

Before viewing outcome-relevant evidence, freeze:

### A1. Exact truth question
Use an adjudicable proposition/comparison.

### A2. Scope
State:
- time period;
- source corpus;
- domain/tradition boundaries in generic terms;
- geography/languages where relevant;
- explicit exclusions;
- limits on downstream inference.

For the independent candidate-elicitation pass, provide this generic scope without disclosing the initial candidate list unless candidate identity is logically necessary to the question.

### A3. Role matrix
Name:
- human owner;
- program lead;
- candidate constructors;
- lane authors;
- each independent reviewer and the exact reviewer determination assigned;
- intended strict independent auditor(s), if known;
- any human-owner dual-role exception.

Outcome-material reviewers and the strict auditor MUST be disjoint.

The human owner must explicitly authorize the study at G0.

If the human owner materially authors the preregistration, a candidate packet, an outcome-determinative lane, the synthesis, or the protocol being qualified, apply the Governance dual-role rule.

### A4. Claim types and trigger tags
Type every material subclaim using one or more:

- textual;
- historical;
- archaeological/material;
- linguistic;
- interpretive;
- philosophical;
- metaphysical;
- doctrinal;
- empirical;
- experiential/testimonial;
- psychological/sociological explanatory;
- normative/moral;
- revelation;
- authority/canon;
- faith commitment;
- miracle/anomalous-event;
- prophecy.

`miracle/anomalous-event` and `prophecy` are trigger tags that normally coexist with historical/textual/philosophical types.

Any claim tagged miracle/anomalous-event, revelation, or prophecy MUST invoke Phase I. Whether a prophecy is ultimately argued to require supernatural foreknowledge is itself an adjudicated step, not a trigger-selection decision.

### A5. Dependency / link map
Decompose nodes and arrows.
Classify each as:
- necessary;
- supporting/non-necessary;
- alternative path.

Nodes **and arrows** receive dispositions where truth-critical.

### A6. Necessary truth-bearing propositions
Freeze each candidate's necessary propositions before evidence acquisition.

### A7. Candidate universe
Freeze admitted candidates and exclusions under Phase B.

### A8. Live background registers

A **SERIOUS_LIVE_BACKGROUND** is a background framework that:

1. is coherent enough to generate determinate inferential consequences;
2. is materially relevant to at least one truth-critical proposition, discriminator, admissibility judgment, or causal inference;
3. has either material representation in serious scholarship/tradition OR an independently formulated argument sufficient to make it a live rational alternative;
4. has not been canonically rejected within an applicable scope;
5. is not contradicted by frozen logical or evidential facts already common to every admitted candidate.

Background admission is symmetric: confessional, skeptical, naturalistic, supernaturalist, metaphysical, historiographic, linguistic, and methodological backgrounds face the same relevance/specification burden.

Before evidence acquisition:

- the program lead constructs an initial background register;
- an independent reviewer performs a background-elicitation pass given the truth question/scope without the initial register where feasible;
- every outcome-material exclusion receives an independent reviewer disposition;
- a different independent reviewer, or the same reviewer only if they made no inclusion/exclusion determination, verifies the frozen register is sufficiently complete for the scope.

For each admitted background, state:
- propositions;
- warrant;
- serious rivals;
- exact inference(s) it changes;
- evidence/argument that would defeat or retire it.

Definitions:

- **BACKGROUND_FLIP:** changing from one admitted live background to another changes the proposed study-level outcome label, candidate dominance, or eligibility for `TRUTH_WARRANTED`.
- **MATERIAL_BACKGROUND_SENSITIVITY:** a necessary proposition, CRITICAL discriminator, or MATERIAL truth-critical comparison changes disposition/direction enough to weaken a condition required by the proposed outcome, even if the headline ranking does not reverse.
- **ROBUST_ACROSS_LIVE_BACKGROUNDS:** no BACKGROUND_FLIP and no unresolved MATERIAL_BACKGROUND_SENSITIVITY defeats a required condition of the proposed outcome.

No naturalism, supernaturalism, confessional authority, or skepticism may be silently installed.

### A9. Source/evidence acquisition plan
Freeze:
- repositories/corpora/databases;
- source strata;
- date/language limits;
- inclusion/exclusion rules;
- search terms or source-selection rules;
- primary/secondary source plan;
- inaccessible-source handling.

### A10. Required lanes
Preregister every lane required for the question and its competence boundary.

### A11. Preregistered discriminators and priority
For each discriminator state:
- candidates compared;
- prediction/argument;
- relevant background;
- priority: `CRITICAL`, `MATERIAL`, or `CONTEXTUAL`;
- why that priority follows from the candidate's necessary propositions.

Priority meanings:

- **CRITICAL:** bears directly on a necessary truth-bearing proposition or candidate adequacy. An unresolved CRITICAL discriminator favoring B blocks A from dominating B.
- **MATERIAL:** changes relative warrant in a truth-relevant way but is not by itself candidate-fatal. MATERIAL discriminators may break a CRITICAL tie only when their direction is non-conflicting or contrary MATERIAL evidence is explicitly resolved.
- **CONTEXTUAL:** helps interpret plausibility/context but cannot establish dominance, truth-warrant, or defeat a candidate by itself.

For every CRITICAL or MATERIAL discriminator, preregister its directional result vocabulary:
- `FAVORS_A`;
- `FAVORS_B`;
- `NEUTRAL_OR_NONDISCRIMINATING`;
- `UNMAKEABLE`.

A **TRUTH_CRITICAL_COMPARISON** is:
- any CRITICAL discriminator; or
- a MATERIAL discriminator preregistered as bearing on a necessary truth-bearing proposition or as the specified tie-breaker when CRITICAL evidence is non-discriminating.

A truth-critical comparison is **MAKEABLE** only when evidence coverage is adequate enough to assign one frozen directional result. An unmakeable truth-critical comparison is never silently omitted.

"MATERIAL comparisons are directionally consistent in favor of A" means at least one is `FAVORS_A` and none is `FAVORS_B`. Conflicting MATERIAL directions produce `MIXED_TRADEOFF` unless one is independently defeated or shown dependent/redundant.

### A12. Minimum candidate adequacy gate
Before comparison, every candidate must satisfy all:

1. sufficiently specified to generate truth-relevant consequences;
2. internally non-contradictory or has a defensible resolution;
3. no necessary proposition already canonically contradicted within applicable scope;
4. enough evidence coverage exists to evaluate its truth-critical propositions;
5. the candidate is represented in a steelman packet.

Candidates failing this gate cannot receive `BEST_SUPPORTED`, `CLOSEST_TO_TRUTH`, or `TRUTH_WARRANTED`.

If all fail, use `NONE_ADEQUATE_WITHIN_SCOPE` only after adequate evidence coverage; otherwise use `INSUFFICIENT_SIGNAL`.

### A13. Expected / weakening evidence
For each candidate state:
- expected evidence;
- compatible but non-discriminating evidence;
- weakening evidence;
- contradiction conditions where possible.

### A14. Stop / reopen conditions
Preregister:
- coverage target;
- underdetermination condition;
- insufficient-signal condition;
- `reopen_if`.

### A15. Audit criteria
Freeze standard G4 criteria plus question-specific risks.

### A16. Shared proposition map
For any proposed `CLOSEST_TO_TRUTH` comparison, freeze before evidence acquisition:
- shared truth-bearing propositions;
- mapping rules across candidates;
- distortion risks;
- minimum dimensionality required by Phase N3.

If no defensible shared map exists, `CLOSEST_TO_TRUTH` is unavailable.

### A17. Protocol version and evidence-exposure ledger
Freeze:
- exact protocol version/commit governing the study;
- the timestamp/version at which each G0 artifact freezes;
- the first exposure to outcome-relevant evidence for each amendment surface.

A study stays under its frozen protocol version unless the human owner authorizes a migration plan. If a protocol migration after evidence exposure could change an outcome, treat it as `POST_EVIDENCE_OUTCOME_MATERIAL`.

---

## 4. Phase B — Candidate universe and steelman procedure

### B1. Symmetric admission rule
Admit a candidate only if it is:
1. relevant;
2. materially distinct;
3. specified enough to generate consequences;
4. not subsumed by another candidate;
5. traceably formulated.

This applies equally to traditional, skeptical, minority, hybrid, revised, and newly generated candidates.

### B2. Independent elicitation
Conduct at least one candidate-elicitation pass by an independent reviewer given the truth question and scope **without the initial candidate list where feasible**.

"Major candidate class" means any candidate family represented by:
- a material scholarly/traditional literature; or
- an independently generated model that differs on a necessary truth-bearing proposition.

### B3. Steelman packet
Every admitted candidate gets a frozen packet containing:
- candidate-native/primary formulation;
- strongest serious proponent source(s);
- core truth propositions;
- authority commitments;
- internal success conditions;
- expected evidence;
- strongest recognized objections;
- common caricatures explicitly rejected.

Where candidate distortion by rival knowledge is plausible:
- construct packets independently from one another where feasible;
- use tradition-native or proponent-informed sources;
- freeze each packet before comparative exposure;
- record any unavoidable contamination.

An independent reviewer performs an **equal-strength check**: packets must be comparable in specificity, source quality, objection coverage, and charitable formulation. If one packet is materially weaker, comparison pauses for repair.

Where feasible, obtain a tradition-native or proponent-informed review of the packet. If unavailable, document that absence.

One candidate may not be defined solely through an opponent's critique.

### B4. Exclusion review
Every exclusion states:
- candidate;
- reason/evidence;
- substantive vs out-of-scope;
- independent reviewer disposition if outcome-material.

### B5. Late or post-evidence candidate
A candidate discovered or constructed after outcome-relevant evidence exposure is labeled:
- `LATE_CANDIDATE`, and
- if constructed using exposed evidence, `POST_EVIDENCE_CONSTRUCTED_CANDIDATE`.

A post-evidence constructed candidate may be explored, but cannot win the same confirmatory adjudication merely by fitting exposed evidence. Canonical comparison requires a fresh preregistered follow-up or a held-out discriminator set frozen before candidate construction.

### B6. Meta-outcomes
`NONE_ADEQUATE`, `UNDERDETERMINED`, and `INSUFFICIENT_SIGNAL` are outcomes, not candidate frameworks.

### B7. Alternative-hypothesis sources
Heterodox sources may generate candidates/predictions but do not fill evidential gaps by authority.

Use:
```text
alternative model
→ explicit prediction
→ independent test
→ preserve success/failure
```

---

## 5. Phase C — Typing and amendment control

### C1. Typing freeze
Initial typing freezes at G0.

### C2. Multi-type rule
Each type-specific component receives its own disposition.
Overall claim strength cannot exceed the weakest **necessary** component.

### C3. Faith commitment
A faith commitment may be recorded as `CONFESSIONAL_COMMITMENT`, but is not public evidence by itself.

### C4. Amendment classes

**Every frozen G0 element in A1–A17** and every downstream frozen artifact is amendment-controlled. This includes:
- exact question and scope;
- role matrix;
- claim typing;
- node/arrow structure;
- necessary propositions;
- candidate set/exclusions;
- background register;
- source/search plan and inclusion/exclusion criteria;
- required lanes;
- discriminators and priority;
- adequacy gate;
- expected/weakening/contradiction evidence;
- coverage/stop/reopen conditions;
- audit criteria;
- shared proposition map;
- protocol version;
- frozen lane findings.

Every amendment must cite the A17 evidence-exposure ledger and be classified:

#### `PRE_EVIDENCE_AMENDMENT`
Made before relevant outcome evidence exposure.
Requires rationale; outcome-material changes require independent review.

#### `POST_EVIDENCE_NONMATERIAL`
After evidence exposure but clerical/non-outcome-determinative.
Requires independent reviewer confirmation.

#### `POST_EVIDENCE_ADVERSE_MATERIAL`
New evidence/error correction that can only leave the current result unchanged or make a candidate/outcome less favorable.
It MUST be incorporated into the current confirmatory study after re-analysis/re-freeze, because suppressing adverse information would bias the result.

#### `POST_EVIDENCE_FAVORABLE_OR_MIXED_MATERIAL`
Could improve a candidate/outcome, relax a burden, shrink the search universe, alter necessary propositions favorably, or has mixed directional effects.
It is exploratory for the current confirmatory study.
It may correct the descriptive record, but any favorable canonical consequence requires a fresh preregistered follow-up or held-out confirmation.

If a change contains both adverse and favorable effects, apply the stricter favorable/mixed rule to any claimed improvement while still incorporating the adverse effect immediately.

Retyping, role changes, scope changes, search-plan changes, and lane corrections all use this same classification.

---

## 6. Phase D — Link decomposition

For every truth-critical chain record:

- node;
- arrow;
- necessary/supporting status;
- evidence;
- alternatives;
- disposition;
- confidence;
- dependence.

A failed arrow breaks only claims that depend on it.

Long chains do not inherit truth from attractive endpoints.

---

# G1 — EVIDENCE ACQUISITION

## 7. Phase E — Evidence acquisition

The A9 acquisition plan is frozen at G0.

### E1. Provenance record
As relevant:
- source/manuscript identity;
- edition/translation;
- date and uncertainty;
- authorship;
- genre;
- dependence;
- archaeological context;
- custody;
- analytical method;
- publication status;
- quotation context;
- philosophical argument source.

### E2. Negative/inaccessible evidence
Record:
- failed searches;
- expected-but-absent evidence where absence is probative;
- inaccessible sources;
- missing data.

### E3. Coverage states

#### `COVERAGE_COMPLETE_FOR_FROZEN_SCOPE`
All preregistered source strata searched; all identified outcome-material sources obtained/evaluated.

#### `COVERAGE_MATERIALLY_COMPLETE_WITH_LISTED_GAPS`
All truth-critical strata and known outcome-material sources addressed; remaining missing sources are listed, and an independent reviewer judges no listed gap likely to change a truth-critical disposition.

#### `COVERAGE_INCOMPLETE`
A truth-critical source stratum/material source remains unsearched, unavailable without adequate substitute, or potentially outcome-changing.

Only the first two can support canonical comparative adjudication.

### E4. Plausibility / attestation record
For historical-development claims record separately, where applicable:

- physically possible;
- culturally plausible;
- archaeologically evidenced;
- textually attested;
- historically inferred;
- independently replicated;
- contradicted.

These are descriptors, not a score or mandatory sequence.

"Could have happened" is not "did happen."

### E5. Source proximity / later evidence
For questions about earlier periods:
- later sources may illuminate;
- later sources may preserve earlier material;
- later sources may reinterpret;
- later sources may invent.

Later material may not be projected backward without a transmission/preservation argument.

### E6. Evidence convergence
Record evidence classes and dependencies.
Convergence is stronger when genuinely independent evidence classes bear on the same truth-critical proposition.
Repeated dependent sources count as one evidential stream for convergence purposes.

---

# G2 — LANE SYNTHESIS

## 8. Phase F — Proposition dispositions

Every disposition is `WITHIN_SCOPE`.

### Defeater classes
These are epistemic, not audit-severity labels:

- **TRUTH_CRITICAL_DEFEATER:** directly undermines a necessary truth-bearing proposition, CRITICAL discriminator, or a required condition for the proposed outcome. If undefeated, it blocks `SUPPORTED` for the affected necessary proposition and blocks `TRUTH_WARRANTED`.
- **MATERIAL_DEFEATER:** materially lowers warrant or favors a serious rival but is not by itself candidate-fatal. It must be resolved or carried into a weaker/underdetermined disposition.

### `SUPPORTED_WITHIN_SCOPE`
Requires:
- applicable type-specific mandatory elements all `MET` or justified `NOT_APPLICABLE`;
- coverage complete/materially complete;
- serious alternatives tested;
- no undefeated TRUTH_CRITICAL_DEFEATER or MATERIAL_DEFEATER;
- a `SUFFICIENCY_RECORD` listing evidence and rationale for each mandatory element.

This remains disciplined expert judgment, not a mechanical numerical threshold.

### `PARTIALLY_SUPPORTED_WITHIN_SCOPE`
Positive evidence materially supports the proposition, but one or more necessary evidentiary requirements remain unresolved.

This label is valid even for a simple proposition; "component" may mean evidentiary requirement rather than logical subclaim.

### `PLAUSIBLE_BUT_UNATTESTED_WITHIN_SCOPE`
Coherent/possible, but required occurrence/instantiation evidence is absent.

### `NOT_ESTABLISHED_WITHIN_SCOPE`
Minimum support burden not met and evidence does not materially favor the negation/rival.

### `EVIDENCE_AGAINST_WITHIN_SCOPE`
Material evidence is less expected if the proposition is true than under a serious rival/negation, or a major undefeated defeater exists.

### `CONTRADICTED_WITHIN_SCOPE`
A necessary component conflicts with high-quality evidence/valid argument and no repair consistent with frozen formulation remains.

### `UNDERDETERMINED_WITHIN_SCOPE`
Adequate coverage exists but competing conclusions remain live.

Subtype:
- `EVIDENTIAL_EQUIVALENCE`;
- `FRAMEWORK_DEPENDENCE`;
- `PHILOSOPHICAL_EQUIVALENCE`;
- `MIXED_TRADEOFF`.

Use `FRAMEWORK_DEPENDENCE` when a BACKGROUND_FLIP occurs or when unresolved MATERIAL_BACKGROUND_SENSITIVITY defeats a required condition of the proposed study-level outcome.

### `INSUFFICIENT_SIGNAL_WITHIN_SCOPE`
Evidence quality/coverage is inadequate.

Subtype(s) may co-occur:
- `MISSING_CRITICAL_EVIDENCE`;
- `PROVENANCE_FAILURE`;
- `SOURCE_ACCESS_FAILURE`.

A non-operationalized question fails G0 and is not an insufficient-signal subtype.

No disposition is a vote.

---

## 9. Phase G — Type-specific sufficiency templates

For `SUPPORTED_WITHIN_SCOPE`, create a `SUFFICIENCY_RECORD` marking each applicable mandatory item `MET` / `NOT_MET` / justified `NOT_APPLICABLE`.

### Textual
Mandatory:
- adequate textual base;
- material variants assessed;
- grammar/syntax/genre/context;
- serious rival readings;
- no silent projection of later doctrine.

### Historical
Mandatory:
- provenance/dating/genre/interests;
- dependence/independence;
- contextual plausibility;
- expected and materially absent evidence;
- serious alternatives;
- reliability assessed question-specifically.

### Archaeological/material
Mandatory:
- context/provenance;
- dating;
- method;
- controls/comparators;
- alternative functions;
- custody issues addressed.

### Linguistic
Mandatory:
- relevant-period corpus;
- semantic range;
- syntax/context;
- diachronic change;
- comparanda where relevant.

### Interpretive
Mandatory:
- secure source base;
- local/broader context;
- explanatory coverage;
- serious rival readings;
- non-circularity;
- original meaning separated from reception.

### Philosophical
Mandatory:
- explicit argument form;
- validity/inductive-abductive strength;
- premise warrant;
- hidden assumptions;
- major defeaters;
- serious rival arguments;
- sensitivity.

### Metaphysical
Mandatory:
- ontology/modal commitments;
- coherence;
- warrant for central commitments;
- rival ontologies;
- defeaters/counterexamples;
- distinction among conceivability, possibility, necessity, actuality.

### Doctrinal
Mandatory:
- exact doctrine;
- internal implications;
- source/authority derivation;
- historical development where relevant.

Doctrinal sources establish what a system teaches, not truth. A doctrinal truth verdict inherits support from its truth-bearing premises.

### Empirical
Mandatory:
- operationalization;
- appropriate method/data;
- robustness/replication proportionate to claim;
- alternative mechanisms;
- uncertainty.

### Experiential/testimonial
Mandatory:
- authenticity;
- access/opportunity;
- reliability factors;
- independence;
- transmission distortion;
- rival psychological/social explanations;
- corroboration expectations compared symmetrically across live rival explanations.

Sincerity alone is not external truth.

### Psychological/sociological explanatory
Mandatory:
- construct validity;
- relevant population/sample;
- causal/mechanistic warrant proportionate to claim;
- rival mechanisms;
- no genetic-fallacy inference.

### Normative/moral
Mandatory:
- exact normative claim;
- metaethical background;
- argument;
- consistency/counterexamples;
- rival normative accounts;
- descriptive origin separated from normative warrant.

### Revelation
Use Phase I plus relevant historical/philosophical/authority requirements.

### Miracle/anomalous-event trigger
This tag does not replace claim typing. `SUPPORTED` requires every applicable historical/textual/testimonial/philosophical sufficiency element **and** completion of the Phase I miracle sequence.

### Prophecy trigger
This tag does not replace claim typing. `SUPPORTED` requires every applicable textual/historical/linguistic/philosophical sufficiency element **and** completion of the Phase I prophecy sequence.

### Authority/canon
Mandatory:
- exact authority claim;
- historical basis;
- transmission/canonicalization evidence;
- non-circular warrant;
- rival authority claims;
- scope.

### Faith commitment
Cannot by itself receive public `SUPPORTED_WITHIN_SCOPE`.

### Premise-warrant categories
For philosophical/metaphysical/normative work, classify premise warrant as:
- logical/analytic;
- empirical;
- historical;
- testimonial;
- phenomenological;
- introspective/intuitional;
- normative;
- theoretical/explanatory;
- confessional.

Intuition is defeasible philosophical evidence, not self-authenticating public warrant. If a truth-critical premise depends on disputed intuition, test rival-framework sensitivity.

---

## 10. Phase H — Philosophical / metaphysical / normative machinery

Record:

1. proposition;
2. argument form;
3. premise list;
4. premise-warrant category/source;
5. inferential validity/strength;
6. hidden assumptions;
7. defeaters;
8. rival frameworks;
9. defeasible theoretical virtues:
   - coherence;
   - scope;
   - depth;
   - parsimony;
   - unification;
   - fit with other warranted beliefs;
10. sensitivity / flip conditions.

Parsimony and fewest assumptions are never automatic winners.

---

## 11. Phase I — Miracle, revelation, and prophecy

### I1. Symmetric starting rule
Do not assume:
- naturalism;
- supernaturalism;
- sincere testimony suffices;
- miracles are impossible;
- unspecified supernatural cause wins because natural alternatives are incomplete;
- unspecified natural/ordinary/unknown cause wins because a supernatural identification is incomplete.

### I2. Trigger
Phase I is mandatory whenever a truth-critical subclaim is tagged:
- miracle/anomalous-event;
- revelation;
- prophecy.

A miracle or prophecy claim also retains its historical/textual/philosophical types; the trigger tag cannot be omitted or relabeled to bypass Phase I. Whether prophecy requires supernatural foreknowledge is adjudicated inside I7.

### I3. Miracle/anomalous-event sequence
Evaluate separately:

1. report made;
2. transmission reliability;
3. historical core;
4. degree of anomaly relative to each explicit live causal framework;
5. specified causal classes;
6. metaphysical admissibility;
7. particular cause/agent identification;
8. theological consequence.

Catch-all classes:
- `UNKNOWN` and `UNSPECIFIED_SUPERNATURAL_CAUSE` are residual statuses, not explanatory winners;
- `FRAUD_OR_ERROR`, `ORDINARY_NATURAL`, `RARE_NATURAL`, and any proposed supernatural causal class must be specified enough to generate truth-relevant expectations before they can defeat a specified rival.

### I4. Background robustness
Use the A8 independently reviewed SERIOUS_LIVE_BACKGROUND register.
Run every truth-critical causal/theological inference under each live register not independently rejected by applicable canonical adjudication.

If a BACKGROUND_FLIP occurs:
- `TRUTH_WARRANTED` is prohibited;
- report conditional results;
- use `UNDERDETERMINED_WITHIN_SCOPE: FRAMEWORK_DEPENDENCE`.

If MATERIAL_BACKGROUND_SENSITIVITY defeats any required condition for the proposed outcome, that stronger outcome is prohibited even if the headline ranking does not reverse.

Sensitivity-testing alone does not satisfy ROBUST_ACROSS_LIVE_BACKGROUNDS.

### I5. Priors
If a probabilistic prior is used:
- state basis;
- apply symmetrically;
- sensitivity-test.

If no defensible prior exists, do not hide one in "ordinary" or "extraordinary."

### I6. Revelation sequence
Evaluate separately:

1. revelation claim made;
2. claimant sincerity/experience;
3. transmission;
4. philosophical possibility;
5. evidence that revelation rather than ordinary cognition/explanation occurred;
6. source identification;
7. warrant for source authority/truthfulness;
8. preservation;
9. doctrinal consequence.

Competing revelation claims face the same sequence.

No claim self-authenticates by circular appeal unless a separate self-authentication argument is explicitly formulated and audited.

### I7. Prophecy
Separate:
- text/authorship/date;
- prediction specificity before event;
- transmission/editing;
- event occurrence;
- fit vs flexible reinterpretation;
- chance/base-rate considerations where applicable;
- ordinary information routes;
- supernatural foreknowledge claim;
- source identification;
- theological consequence.

---

## 12. Phase J — Source quality

No universal lexical hierarchy.

Evaluate:
- proximity;
- reliability;
- genre;
- access;
- independence;
- transmission;
- bias/interests;
- preservation;
- corroboration;
- provenance.

Rules:

1. earlier ≠ automatically better;
2. later ≠ automatically worse;
3. later source may preserve earlier material;
4. early source may be unreliable;
5. independence requires no material common source/informant/institutional bottleneck relevant to convergence;
6. degrees of dependence are recorded;
7. mixed questions use claim-specific source evaluation.

---

## 13. Phase K — Lane freeze and amendment gate

### K1. Lane construction
Lanes are by claim competence, not favored candidate.

### K2. Required lanes
Use the A10 frozen list.
A later required lane is an amendment under C4.

### K3. Background register
Every lane receives the frozen A8 register and cites any background dependency at the exact inferential point.

### K4. Lane freeze
A lane freezes only when:
- scope complete;
- coverage state recorded;
- proposition/arrow dispositions issued;
- sufficiency records attached where supported;
- unresolved conflicts listed;
- exact artifact/version fixed.

### K5. Lane amendment
Lane amendments use C4 and the A17 exposure ledger.

- `POST_EVIDENCE_NONMATERIAL`: may be incorporated after independent confirmation.
- `POST_EVIDENCE_ADVERSE_MATERIAL`: MUST be incorporated after re-analysis/re-freeze and any dependent synthesis must rerun.
- `POST_EVIDENCE_FAVORABLE_OR_MIXED_MATERIAL`: re-analysis/re-freeze is required for an accurate descriptive record, but any favorable canonical consequence is exploratory until fresh preregistration/held-out confirmation.

Every material amendment:
- invalidates the prior frozen finding for synthesis;
- records direction of effect;
- identifies dependent artifacts;
- triggers re-synthesis where the amended finding can worsen/alter the current result;
- is explicitly inspected at G4.

Thus genuine error correction is never suppressed, but post-evidence favorable correction cannot silently improve the same confirmatory adjudication.

### K6. Circular dependency
If Lane A requires Lane B's conclusion while Lane B requires Lane A's conclusion:
- extract the shared premise into a separate background/precondition analysis; or
- mark the dependency unresolved.

An unresolved outcome-determinative cycle yields `UNDERDETERMINED_WITHIN_SCOPE: DEPENDENCY_CYCLE` at G2/G3. `INVALID_COMPARISON` is reserved for the G4 audit outcome.

---

## 14. Phase L — Proposition consolidation across lanes

For every truth-critical proposition build a `PROPOSITION_EVIDENCE_MATRIX` listing:
- lanes;
- claim facet addressed;
- direct vs indirect support;
- independence/dependence;
- disposition;
- discriminator priority;
- defeaters.

Definitions:
- **direct evidence:** bears on the truth/falsity of the proposition without requiring a separate disputed truth-bearing bridge;
- **indirect evidence:** bears through one or more additional inferential bridges;
- **sufficiently strong conflict:** independent direct evidence on both sides reaches at least PARTIALLY_SUPPORTED or one side presents an unresolved TRUTH_CRITICAL_DEFEATER.

### L1. Distinct necessary facets
If lanes address different necessary facets, the proposition cannot exceed the weakest necessary facet.

### L2. Independent convergence on the same facet
Independent partial supports may jointly yield `SUPPORTED` only if:
- together they satisfy all preregistered mandatory sufficiency elements;
- each stream adds non-duplicative truth-relevant information;
- dependency analysis confirms they are not repetitions of one bottleneck;
- no undefeated TRUTH_CRITICAL_DEFEATER or MATERIAL_DEFEATER remains.

Mere repetition never promotes a disposition.

### L3. Cross-lane conflict
Resolve in order:

1. check whether lanes address different propositions/facets;
2. check source/evidence dependence;
3. direct claim-specific evidence outranks merely contextual compatibility for that proposition;
4. a valid defeater can override otherwise positive support;
5. if two independent, direct, sufficiently strong lanes remain in material conflict with no principled priority, use `UNDERDETERMINED_WITHIN_SCOPE: MIXED_TRADEOFF`.

No vote-counting.

### L4. Chain attenuation
Every necessary node **and arrow** in a multi-step chain receives disposition/confidence.

The chain disposition cannot exceed its weakest necessary link.

A proposition/arrow may be `SUPPORTED` yet have `LOW` confidence only when the sufficiency elements are met but material uncertainty remains about robustness/generalization. Such a LOW-confidence necessary link blocks `TRUTH_WARRANTED` unless an independent reviewer confirms that the uncertainty cannot defeat any required truth-warrant condition.

When two or more necessary links are `MODERATE` confidence and their uncertainties are at least partly independent, create a `CUMULATIVE_FRAGILITY_REVIEW` stating whether their joint uncertainty could plausibly produce a BACKGROUND_FLIP, disposition downgrade, or chain failure.

If yes or unresolved, `TRUTH_WARRANTED` is blocked.
No numerical multiplication is required.

### L5. Evidence convergence record
For each promoted disposition state:
- what survived from prior/lower-level evidence;
- what changed in meaning/function;
- which independent evidence classes converge;
- which apparent convergences share a dependency.

---

## 15. Phase M — Continuity Framework C0–C7

C0–C7 are relation types, not a mandatory ladder:

- **C0 recurrence:** similar motif/idea/form/practice occurs in more than one context.
- **C1 form/material continuity:** related artifact/form/symbol/textual formula can be chronologically traced.
- **C2 carrier continuity:** contact, population, institution, text, apprenticeship, trade, or another plausible carrier is evidenced.
- **C3 practice continuity:** comparable ritual/institutional/practical use persists.
- **C4 semantic continuity:** demonstrably comparable conceptual work persists.
- **C5 named textual continuity:** texts explicitly name the concept/deity/doctrine/proposition/relation.
- **C6 genealogical continuity:** evidence favors historical derivation over mere resemblance or independent reinvention.
- **C7 doctrinal continuity:** a later doctrine preserves, intentionally develops, or explicitly recovers an earlier truth-relevant proposition with more than thematic resemblance.

Possible patterns:
- branching;
- convergence;
- loss;
- recovery;
- refunctionalization;
- parallel construction;
- discontinuity.

### No-jump rule
A C6/C7 claim cannot be inferred from C0/C1 resemblance alone.
The study must separately establish the carrier, semantic, textual, or other relations actually required by that genealogy.

### Independent-reinvention null
Whenever common environmental, psychological, social, philosophical, or institutional conditions could plausibly generate the same form/concept more than once:
- specify independent reinvention as a rival explanation;
- state discriminators between reinvention and transmission;
- do not infer transmission from resemblance alone;
- preserve the null result whether favored or not.

### Symmetry
Continuity and discontinuity/corruption claims face **comparable** evidential burdens.

### Truth relevance
Development bears directly on truth when warrant depends on:
- original authorship;
- faithful transmission;
- revelation continuity;
- succession;
- original meaning;
- another historically contingent authority premise.

Continuity itself never proves truth.

---

# G3 — COMPARATIVE ADJUDICATION

## 16. Phase N — Candidate adequacy and background robustness

Before relative comparison:

1. apply A12 adequacy gate;
2. apply necessary-proposition map;
3. apply background-robustness test;
4. record unmakeable truth-critical comparisons rather than dropping them.

An unmakeable TRUTH_CRITICAL_COMPARISON normally produces `UNDERDETERMINED_WITHIN_SCOPE` or `INSUFFICIENT_SIGNAL_WITHIN_SCOPE`, not silent omission.

---

## 17. Phase N2 — Inferential bridge

Use this defeater-first order:

1. necessary proposition `CONTRADICTED` → candidate inadequate;
2. necessary proposition `EVIDENCE_AGAINST` → MATERIAL_DEFEATER requiring resolution;
3. necessary proposition `INSUFFICIENT_SIGNAL` → no truth adjudication;
4. necessary proposition `NOT_ESTABLISHED` → no truth-warrant;
5. necessary proposition `PARTIALLY_SUPPORTED` → relative comparison possible, truth-warrant normally blocked;
6. independent direct CRITICAL discriminators outrank MATERIAL and CONTEXTUAL evidence;
7. MATERIAL discriminators may decide relative support only when CRITICAL comparisons are tied/non-discriminating and unresolved MATERIAL evidence does not point materially in opposite directions;
8. CONTEXTUAL evidence may shape interpretation but cannot establish dominance or truth-warrant by itself;
9. internal coherence never substitutes for external warrant;
10. outcome must be ROBUST_ACROSS_LIVE_BACKGROUNDS or else the strongest background-sensitive outcome permitted is `FRAMEWORK_DEPENDENCE`.

### Candidate dominance
A dominates B only if:
- both pass adequacy;
- no makeable CRITICAL comparison favors B over A without resolution;
- A is at least as well warranted as B on every makeable CRITICAL comparison;
- at least one of the following holds:
  1. a CRITICAL comparison favors A and no unresolved MATERIAL comparison favors B strongly enough to create a MIXED_TRADEOFF; or
  2. all CRITICAL comparisons are tied/non-discriminating and the MATERIAL comparisons are directionally consistent in favor of A, with no unresolved MATERIAL comparison favoring B;
- CONTEXTUAL evidence is not used as the sole basis of dominance.

If CRITICAL evidence is tied and MATERIAL evidence conflicts materially, or if an outcome-relevant TRUTH_CRITICAL_COMPARISON is unmakeable, use `UNDERDETERMINED_WITHIN_SCOPE: MIXED_TRADEOFF` or `INSUFFICIENT_SIGNAL_WITHIN_SCOPE` as appropriate.

---

## 18. Phase N3 — Provisional study outcomes

At G3 every outcome is prefixed `PROPOSED_`.
The prefix is removed only after G4 PASS/PASS_WITH_LIMITATIONS and G5 human acceptance.

### `PROPOSED_CANDIDATE_A_BEST_SUPPORTED_WITHIN_SCOPE`
Relative evidential ranking only.

Requires:
- A and relevant rivals pass adequacy;
- A dominates every serious rival on makeable truth-critical comparisons;
- no unresolved CRITICAL comparison is simply omitted.

May be used when necessary truth-bearing propositions remain only partially supported/not established.

It does **not** assert approximate truth.

### `PROPOSED_CANDIDATE_A_TRUTH_WARRANTED_WITHIN_SCOPE`
Requires all:

1. exact truth proposition explicit;
2. candidate-universe gate passed;
3. all necessary truth-bearing propositions `SUPPORTED`;
4. all necessary sufficiency records complete;
5. no undefeated TRUTH_CRITICAL_DEFEATER or MATERIAL_DEFEATER;
6. adequate coverage;
7. ROBUST_ACROSS_LIVE_BACKGROUNDS across all admitted SERIOUS_LIVE_BACKGROUND registers, or rival backgrounds independently rejected by applicable canonical adjudication;
8. no necessary LOW-confidence link capable of materially flipping result;
9. serious rivals compared equally;
10. external warrant, not mere coherence/priority/consensus;
11. G4 independent audit PASS/PASS_WITH_LIMITATIONS;
12. G5 human acceptance.

Before G4/G5 it remains `PROPOSED_` and conditions 11–12 are pending gates, not assumed facts.

### `PROPOSED_CANDIDATE_A_CLOSEST_TO_TRUTH_WITHIN_SCOPE`
This is a truth-likeness claim and is stricter than `BEST_SUPPORTED`.

Use only when:

- no candidate is truth-warranted;
- the A16 shared proposition map contains at least **two independent truth-bearing dimensions**; for a genuinely one-dimensional/single-proposition question this label is unavailable;
- candidates differ on directionally comparable truth-bearing propositions;
- A is not contradicted on any CRITICAL shared proposition;
- for every serious rival B, A is better warranted on at least two independent shared truth-bearing dimensions OR on one CRITICAL dimension plus one independent MATERIAL dimension;
- no unresolved CRITICAL dimension favors B;
- no unresolved MATERIAL conflict makes the truth-likeness ordering non-monotonic;
- residual unsupported propositions are explicit.

If candidates cannot be mapped into a shared proposition space without distortion, use `BEST_SUPPORTED` or `UNDERDETERMINED` instead.

### `PROPOSED_REVISED_CANDIDATE_REQUIRED_WITHIN_SCOPE`
Supported components survive but no admitted candidate combines them.
Triggers a new preregistered candidate cycle; does not create a winner.

### `PROPOSED_NONE_ADEQUATE_WITHIN_SCOPE`
Use under adequate coverage when every admitted candidate either:
- fails the A12 adequacy gate; or
- later becomes inadequate because a necessary proposition is `CONTRADICTED_WITHIN_SCOPE` or an undefeated TRUTH_CRITICAL_DEFEATER defeats a required candidate condition.

If coverage is inadequate, use `PROPOSED_INSUFFICIENT_SIGNAL_WITHIN_SCOPE` instead.

### `PROPOSED_UNDERDETERMINED_WITHIN_SCOPE`
Two or more adequate candidates remain and no warranted preference exists.
Record subtype.

### `PROPOSED_INSUFFICIENT_SIGNAL_WITHIN_SCOPE`
Coverage/quality insufficient.
Record subtype(s).

### Single-proposition questions
For "Did X occur?" or "Is P true?", define candidates minimally as `P` and material rivals/negation where appropriate, without manufacturing false dichotomies.

---

# G4 — ADVERSARIAL AUDIT

## 19. Phase O — Audit severity and outcomes

### Severity
- **BLOCKING:** governance/authority failure or core inferential defect that makes qualification/adjudication unsafe or invalid.
- **MAJOR:** methodological defect that could materially change outcome/reproducibility; qualification/adjudication is blocked until repaired.
- **MINOR:** real defect not expected by itself to change the bounded outcome; repair or explicit limitation required.
- **NOTE:** observation/non-defect.

### Audit outcomes

#### `PASS`
All mandatory audit checks pass.
No unresolved BLOCKING/MAJOR/MINOR defect.
No qualification-relevant unresolved limitation.
NOTEs may remain.

#### `PASS_WITH_LIMITATIONS`
No unresolved BLOCKING/MAJOR defect.
May contain:
- irreducible/non-defect `LIMITATION` findings; and/or
- one or more `FAIL_MINOR` findings only when each is explicitly demonstrated non-outcome-determinative, bounded, and carried forward as a downstream constraint.

Every carried item is copied into G5/STATE.

#### `REPAIR_REQUIRED`
At least one BLOCKING or MAJOR defect exists, or a cluster of MINOR defects collectively threatens reproducibility/outcome integrity.

#### `INVALID_COMPARISON`
A defect in question/candidate/background/evidence design invalidates comparison such that local repair after G3 is insufficient and restart from an earlier gate is required.

#### `INSUFFICIENT_SIGNAL`
Auditor lacks required frozen artifacts/evidence/access to evaluate method/result. This is not a merit verdict.

### O1. Mandatory strict independence
Any proposed canonical theological adjudication, truth-warrant, closest-to-truth outcome, program-level truth-bearing result, **or protocol qualification** requires a strict independent auditor.

The strict auditor may not have authored/co-authored:
- G0 preregistration;
- candidate packet;
- outcome-determinative lane;
- synthesis;
- repair/protocol version being audited.

The strict auditor also may not have made any outcome-material reviewer determination in the same cycle, including:
- candidate or background inclusion/exclusion review;
- amendment classification;
- coverage-completeness review;
- lane-amendment materiality review;
- any other reviewer determination that can change an outcome.

The role matrix must demonstrate disjointness before audit launch.

### O2. Per-topic audit tests
Each mandatory topic receives exactly one:
- `PASS`;
- `FAIL_BLOCKING`;
- `FAIL_MAJOR`;
- `FAIL_MINOR`;
- `LIMITATION`;
- `NOT_APPLICABLE_WITH_REASON`.

`FAIL_MINOR` is a real defect that is non-outcome-determinative by itself. It must be repaired before `PASS`, or explicitly bounded/carried under `PASS_WITH_LIMITATIONS`.

`LIMITATION` is an irreducible or scope-bound constraint rather than a correctable defect.

Mandatory topics:
1. governance/role compliance;
2. candidate completeness/exclusions;
3. steelman integrity;
4. claim-typing drift;
5. necessary-proposition/amendment timing;
6. discriminator timing/priority changes;
7. search/source-plan adherence;
8. source-selection bias;
9. lane leakage/dependency/circularity;
10. proposition consolidation;
11. background-register robustness;
12. premise warrant;
13. equal-standard application;
14. shallow-heuristic reproduction;
15. outcome scope/label correctness;
16. uncertainty completeness;
17. cold-start reproducibility.

A `FAIL_BLOCKING` or `FAIL_MAJOR` forces `REPAIR_REQUIRED` or `INVALID_COMPARISON`.
A cluster of `FAIL_MINOR` findings that collectively threatens reproducibility/outcome integrity also forces `REPAIR_REQUIRED`.

Audit-outcome namespace rule:
- proposition-level: `INSUFFICIENT_SIGNAL_WITHIN_SCOPE`;
- study-level: `PROPOSED_INSUFFICIENT_SIGNAL_WITHIN_SCOPE`;
- audit-level: record `AUDIT_INSUFFICIENT_SIGNAL` (display label may remain `INSUFFICIENT_SIGNAL`).

`INVALID_COMPARISON` is reserved for G4 audit disposition.

### O3. Blinding
Use blinding where it reduces a real bias without removing necessary context.
At minimum, the auditor is not given any human preference as authority and receives frozen artifacts.

### O4. Auditor disagreement
If multiple auditors disagree materially:
- status `DISPUTED_AUDIT`;
- no G5 acceptance;
- obtain a frozen reconciliation response or another independent audit.

### O5. Program-lead disagreement with a single auditor
The program lead may publish a response but cannot override a required audit failure.

Options:
- accept and repair;
- request a new strict independent audit against the same frozen criteria;
- ask the human owner to amend Governance/Protocol explicitly for future work.

No failed required audit may be bypassed by state update.

### O6. Repair/re-audit
After `REPAIR_REQUIRED`:
- preserve original audit;
- freeze repair matrix before editing;
- version repair;
- strict independent re-audit;
- repair author cannot self-certify.

### O7. PASS_WITH_LIMITATIONS
Every limitation is copied into:
- acceptance record;
- canonical STATE entry;
- downstream-use constraints.

### O8. Cold-start performer and pass rule
The strict independent auditor performs the formal cold-start reproducibility check at G4.
Program lead may preflight earlier but cannot certify it.

Cold-start test: using only the governed frozen source set, determine whether an unfamiliar competent researcher can recover:
- authorization and role boundaries;
- candidates/exclusions and steelman packets;
- backgrounds;
- typing/link map;
- acquisition plan/coverage;
- amendment history/exposure ledger;
- lane findings and proposition consolidation;
- discriminator priority/dominance;
- provisional outcome meaning;
- audit requirements;
- human acceptance/state transition;
- stop/reopen conditions.

If any **outcome-determinative** step requires undocumented project lore, topic 17 is `FAIL_MAJOR`.
If only non-outcome procedural detail is missing, use `FAIL_MINOR`.

### O9. Protocol-qualification audit topics
A protocol-qualification audit uses the same severity/outcome semantics and MUST test:
1. authority/governance consistency;
2. role/strict-independence rules;
3. candidate/background symmetry;
4. evidence-acquisition/provenance/coverage;
5. claim typing and sufficiency;
6. amendment/change control;
7. lane/proposition consolidation;
8. comparative outcome/inferential bridge;
9. miracle/revelation/prophecy handling;
10. philosophy/source/continuity handling;
11. audit semantics themselves;
12. STATE/schema/legacy alignment;
13. uncertainty/stop/reopen;
14. cold-start reproducibility;
15. regression/internal consistency.

A protocol audit may add frozen question-specific checks before launch but may not weaken this minimum set.

---

# G5 — HUMAN ACCEPTANCE

## 20. Phase P — Canonical acceptance

Only the human owner can accept a canonical theological adjudication.

The human owner cannot substitute for the strict audit.

If the human owner materially authored the preregistration, candidate packet, outcome-determinative lane, synthesis, or protocol being qualified, apply the Governance dual-role exception.

### P1. Acceptance record
Must cite:
- study ID/version;
- exact scope;
- proposed outcome;
- synthesis;
- audit;
- limitations;
- uncertainty statement;
- negative knowledge;
- `reopen_if`;
- explicit human-owner acceptance.

### P2. Outcome promotion
After valid G4/G5:
- `PROPOSED_CANDIDATE_A_BEST_SUPPORTED_WITHIN_SCOPE` → `CANDIDATE_A_BEST_SUPPORTED_WITHIN_SCOPE`;
- similarly for other accepted outcomes.

No prefix removal occurs earlier.

### P3. Canonical STATE adjudication schema
Every canonical adjudication entry MUST contain:

```yaml
- id:
  question:
  outcome:
  scope:
  protocol_version:
  accepted_at:
  synthesis_artifact:
  audit_artifact:
  human_acceptance_artifact:
  confidence:
  evidence_coverage:
  background_assumptions:
  residual_alternatives:
  limitations:
  negative_knowledge:
  reopen_if:
```

After the human owner creates the acceptance record, the program lead or another already-authorized research agent performs the **mechanical** STATE update and cites the acceptance artifact. That edit records acceptance; it does not create it.

### P4. Legacy-state rule
Pre-protocol research dispositions, including EMT Stage-1 dispositions, are tagged `legacy_research_disposition` and are **not** canonical theological adjudications under this protocol unless re-adjudicated through G0–G5.

### P5. Program-level truth commitments
Statements such as "Christianity is true" require:
- explicit human authorization;
- multiple appropriately scoped bounded adjudications;
- program-level synthesis;
- strict independent audit;
- separate human acceptance.

One study cannot silently generate them.

---

# G6 — UNCERTAINTY / STOP / REOPEN

## 21. Phase Q — Mandatory uncertainty statement

Record:

1. exact scope;
2. confidence:
   - `HIGH`: result is ROBUST_ACROSS_LIVE_BACKGROUNDS and no known material gap plausibly defeats a required condition;
   - `MODERATE`: result is favored but one or more material uncertainties remain that could weaken, though not currently reverse, the study-level outcome;
   - `LOW`: result is tentative and one or more live uncertainties could plausibly reverse/downgrade it;

For proposition/node/arrow confidence, apply the same meanings relative to that local disposition: HIGH = robust; MODERATE = material uncertainty could weaken but not presently reverse the disposition; LOW = live uncertainty could plausibly downgrade/reverse the disposition.
3. coverage state;
4. residual alternatives;
5. background assumptions;
6. known weaknesses;
7. missing/inaccessible evidence;
8. flip/weaken conditions;
9. underdetermination subtype where applicable;
10. audit limitations.

Confidence and scope are separate.

### Carried protocol limitations
Even after qualification, explicitly remember:
- `SUPPORTED_WITHIN_SCOPE` includes disciplined expert judgment;
- metaphysical/revelation questions may often remain underdetermined;
- AI-session/model independence is procedural, not guaranteed independence of priors.

---

## 22. Phase Q2 — Stop and reopen

A study may stop when:
- frozen coverage target is complete/materially complete;
- truth-critical sources are addressed or listed;
- remaining accessible material is predominantly dependent/repetitive or not expected to change a truth-critical proposition;
- remaining gaps and possible effect are stated.

Low expected information gain is a valid stop reason **only after** this coverage record exists or when further truth-critical evidence is unavailable.

Every stop maps to:
- `CLOSED`;
- `HELD`;
- `SUPERSEDED`;
- `REOPENED`.

Every CLOSED/HELD study MUST define `reopen_if`, including where relevant:
- new evidence/source;
- changed dating/provenance;
- replication;
- new philosophical argument;
- new defeater;
- changed premise warrant;
- credible audit challenge;
- material candidate expansion.

---

## 23. Anti-heuristic safeguard

The audit MUST test whether the result can be reproduced mechanically by any slogan such as:

- always earliest source;
- always consensus;
- always distrust later doctrine;
- always trust established tradition;
- always simplest/fewest assumptions;
- always naturalistic;
- always supernatural;
- always reject miracle testimony;
- always accept sincere testimony;
- always development = corruption;
- always development = maturation;
- always independent invention;
- always transmission.

The test is **not** whether a headline outcome happens to match a slogan.

For each candidate and every CRITICAL/MATERIAL disposition, ask whether the same disposition could have been produced by applying one slogan **without integrating the actual evidence**.

If a single heuristic mechanically reproduces the material disposition pattern without evidence integration, audit topic 14 is `FAIL_MAJOR` unless that rule was independently justified for the exact question.
If only a contextual/non-outcome pattern is affected, use `FAIL_MINOR`.

---

## 24. Current qualification state

```text
PROTOCOL_VERSION = 0.1.3
STATUS = CANDIDATE__REPAIR_PENDING_REAUDIT
SELF_QUALIFICATION = PROHIBITED
TFP_STRESS_2 = NOT_AUTHORIZED
MAJOR_DOCTRINAL_COMPARISON = HELD
NEXT = FOCUSED_INDEPENDENT_REAUDIT
```

## 25. Governing principle

> A theological conclusion may travel only as far as its typed evidence, explicit dependencies, background robustness, proposition consolidation, adversarial audit, and human acceptance can carry it.
