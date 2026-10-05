# TFP Adjudication Protocol 0.1.5

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

Role definitions come from candidate Governance 0.1.4, which must be ratified by the human owner as part of qualification if this package passes audit:

- **human owner:** authorizes every bounded truth-adjudication study at G0, accepts canonical theological adjudications at G5, and qualifies protocols after required audit;
- **program lead:** orchestrates already-authorized work but cannot self-authorize a truth study, override failed audit, or substitute for human acceptance;
- **independent reviewer:** did not author/co-author the item or make the outcome-determinative decision being reviewed;
- **strict independent auditor:** did not author/co-author the G0 preregistration, candidate packets, outcome-determinative lanes, comparative synthesis, or repair under audit, and made no outcome-material reviewer determination in the same study/qualification cycle.

The strict auditor MUST be disjoint from all reviewers who made outcome-material determinations, including candidate/background exclusions, amendment classification, coverage-completeness review, and lane-amendment materiality review.

A protocol-qualification audit uses the same strict-independence standard.

Procedural separation between AI sessions/models is not guaranteed independence of training priors. Model/session provenance must be recorded.

### Protocol qualification act

A protocol version becomes operative only when all occur:

1. a strict qualification audit is run against an **immutable qualification source manifest** that pins:
   - governed bundle commit SHA;
   - protocol blob SHA;
   - Governance blob SHA/version;
   - Charter blob SHA;
   - audited STATE snapshot blob SHA;
   - Method Seed blob SHA;
2. every required strict protocol audit returns `PASS` or `PASS_WITH_LIMITATIONS`;
3. no unresolved BLOCKING or MAJOR defect remains;
4. the external qualification role-control record is completed/frozen before substantive audit and cited by the audit;
5. every audit of that same frozen bundle is disclosed under O4;
6. the human owner creates a versioned qualification acceptance record that:
   - cites the immutable source manifest;
   - cites every required audit and disposition;
   - ratifies the exact candidate Governance blob/version;
   - states carried limitations;
7. canonical mutable `STATE.yaml` performs the **mechanical post-audit qualification transition** and records:
   - the audited STATE blob SHA;
   - the immutable governed bundle commit;
   - the post-qualification STATE commit.

The five audited blobs remain immutable historical evidence. The mechanical post-audit STATE transition does **not** alter or retroactively replace the audited STATE snapshot and therefore does not invalidate the audit.

Any substantive change to Charter, Governance, Method Seed, Protocol, or to the audited STATE content **before human qualification acceptance** invalidates the audit for qualification and requires a new immutable bundle/audit.

Static candidate-status text inside the frozen Protocol/Governance files is historical metadata for the audited bundle. Operative status after qualification is read only from canonical STATE.

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
- initial claim-typing reviewer;
- necessary-proposition/coverage-map reviewer;
- source-plan reviewer;
- adverse-source-probe / coverage-state reviewer;
- MAKEABLE certifier;
- background-register inclusion/exclusion reviewer(s);
- amendment-direction reviewer;
- ledger-integrity reviewer;
- fragility/LOW-confidence reviewer;
- all other independent reviewers and their exact decision scopes;
- intended strict independent auditor(s), if known;
- actor-lineage identifiers/provenance for AI roles;
- any human-owner dual-role exception.

The program lead and every outcome-material reviewer MUST be disjoint from the strict auditor.

The human owner must explicitly authorize the study at G0.

If the human owner materially authors the preregistration, candidate packet, outcome-determinative lane, synthesis, or makes an outcome-material reviewer determination, apply the Governance dual-role rule.

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

The final two are trigger tags that normally coexist with other claim types.

Definitions:

- **miracle/anomalous-event:** any truth-critical event claim for which at least one admitted candidate or serious live background attributes causal significance beyond ordinary causal expectations, or where the study asks whether such attribution is warranted.
- **prophecy:** any truth-critical claim that a statement predicts a later event in a way argued by any admitted candidate to exceed ordinary information, inference, coincidence, or retrospective fitting.

Any claim tagged miracle/anomalous-event, revelation, or prophecy MUST invoke Phase I.

Before G0 closes, an independent claim-typing reviewer checks:
- all truth-critical claims are typed;
- trigger tags cannot be avoided by a candidate-favoring description;
- comparable rival claims carry comparable type burdens.

Consequential initial typing is an outcome-material reviewer determination and bars that reviewer from serving as strict auditor.

### A5. Dependency / link map
Decompose nodes and arrows.
Classify each as:
- necessary;
- supporting/non-necessary;
- alternative path.

Nodes **and arrows** receive dispositions where truth-critical.

### A6. Necessary truth-bearing propositions and coverage map

Freeze each candidate's necessary truth-bearing propositions before evidence acquisition.

For each candidate, distinguish:
- necessary propositions;
- supporting but non-necessary propositions;
- merely contextual propositions.

An independent reviewer confirms:
- the classification follows the candidate's strongest frozen formulation;
- difficult/vulnerable claims are not demoted to reduce burden;
- comparable rivals face comparable necessity criteria.

Create a `NECESSARY_PROPOSITION_COVERAGE_MAP`.

For **every necessary proposition of every admitted candidate**, record exactly one coverage mode:

1. `COMPARATIVE_ROUTE`
   - one or more preregistered CRITICAL/MATERIAL comparisons bear on that proposition; or
2. `NONCOMPARATIVE_CANDIDATE_SPECIFIC`
   - pairwise comparison would distort the proposition; the direct evidence/argument route is specified; or
3. `NONCOMPARATIVE_SHARED_FLOOR`
   - the proposition is substantively the same necessary premise across all relevant candidates and therefore does not discriminate among them.

For every map entry record:
- candidate(s);
- proposition ID;
- route type;
- comparator/discriminator IDs where applicable;
- direct evidence/argument route where applicable;
- expected evidence;
- weakening/defeating evidence;
- lane(s);
- required coverage certification.

Independent certification of `NECESSARY_PROPOSITION_COVERAGE_COMPLETE` is required before G0 closes.

Ranking consequences:

- a candidate-specific noncomparative necessary proposition must be `SUPPORTED_WITHIN_SCOPE` for that candidate to receive `BEST_SUPPORTED` or `CLOSEST_TO_TRUTH`;
- a shared-floor necessary proposition may remain unresolved without changing relative ranking, but it blocks `TRUTH_WARRANTED` for every candidate that depends on it;
- comparative-route propositions enter the A11/N2 dominance procedure.

No candidate may enter comparative adjudication without a complete certified map.

These reviews are outcome-material; reviewer(s) cannot serve as strict auditor.

### A7. Candidate universe
Freeze admitted candidates and exclusions under Phase B.

### A8. Live background registers

A **SERIOUS_LIVE_BACKGROUND** is a background framework that:

1. is coherent enough to generate determinate inferential consequences;
2. is materially relevant to at least one truth-critical proposition, discriminator, admissibility judgment, or causal inference;
3. has material representation in serious scholarship/tradition OR an independently formulated argument sufficient to make it a live rational alternative;
4. has not been canonically rejected within an applicable scope;
5. is not contradicted by an independently established logical/evidential constraint that does **not** depend on which candidate happens to be admitted.

Background admission is symmetric across confessional, skeptical, naturalistic, supernaturalist, metaphysical, historiographic, linguistic, and methodological backgrounds.

### A8.1 Construction and review

Before evidence acquisition:

- the program lead constructs an initial register;
- an independent reviewer performs a background-elicitation pass from the truth question and generic scope **without the initial register where feasible**;
- if blind elicitation is infeasible, the reason MUST be documented;
- every proposed inclusion and exclusion is independently reviewed against A8(1)–(5);
- a frozen `BACKGROUND_REGISTER_REVIEW` lists admitted and excluded backgrounds with reasons.

The reviewer who made inclusion/exclusion decisions cannot be the strict auditor.

### A8.2 Granularity

Split a background into separate variants only when the variants differ on an assumption that can change a truth-critical inference or outcome.

Merge variants when their differences are irrelevant to every frozen truth-critical inference.

The register must state:
- dimensions;
- variants within each dimension;
- compatibility/incompatibility constraints;
- the inferential point affected by each difference.

### A8.3 Joint combinations

Create a `BACKGROUND_INTERACTION_MATRIX`.

For each pair or higher-order set of dimensions, mark whether assumptions jointly affect the same truth-critical inference.

- If they do not interact materially, one-at-a-time sensitivity is sufficient with rationale.
- If they do interact materially, every compatible joint combination that can change a required outcome condition must be tested.
- If the compatible combination set becomes too large to test responsibly, narrow the scope transparently or return `INSUFFICIENT_SIGNAL_WITHIN_SCOPE`; do not silently sample favorable combinations.

For each admitted background/combination, state:
- propositions;
- warrant;
- exact inference(s) affected;
- evidence/argument that would defeat or retire it.

Definitions:

- **BACKGROUND_FLIP:** moving between two admitted single backgrounds or tested joint combinations changes the proposed study-level outcome label, candidate dominance, or eligibility for `TRUTH_WARRANTED`.
- **MATERIAL_BACKGROUND_SENSITIVITY:** a necessary proposition or truth-critical comparison changes enough to weaken a required condition of the proposed outcome even when the headline label does not flip.
- **ROBUST_ACROSS_LIVE_BACKGROUNDS:** no tested live background or required joint combination creates a BACKGROUND_FLIP or unresolved MATERIAL_BACKGROUND_SENSITIVITY that defeats a required condition.

No naturalism, supernaturalism, confessional authority, or skepticism may be silently installed.

### A9. Source/evidence acquisition plan

Before evidence acquisition, draft a `SOURCE_PLAN` containing:

- repositories/corpora/databases;
- primary-source strata;
- secondary-source strata;
- candidate-native / tradition-native source strata where relevant;
- serious skeptical/critical/adverse source strata where relevant;
- neutral or cross-tradition scholarly strata where available;
- source strata needed to test each SERIOUS_LIVE_BACKGROUND;
- date/language limits;
- inclusion/exclusion rules;
- search terms or source-selection rules;
- inaccessible-source handling.

### A9.1 Independent source-plan control

Before freeze, an independent `SOURCE_PLAN_REVIEWER` receives the truth question, generic scope, admitted candidates, and background register.

The reviewer must:
1. independently elicit any missing source strata before seeing the draft plan where feasible;
2. test whether each candidate has access to its strongest native evidence;
3. test whether serious adverse/critical evidence is represented symmetrically;
4. test whether every live background has the evidence classes needed to challenge it;
5. identify foreseeable source-selection bottlenecks.

The plan freezes only after the reviewer issues `SOURCE_PLAN_PASS` or a versioned repair is completed.

Source-plan review is outcome-material and the reviewer cannot serve as strict auditor.

### A10. Required lanes
Preregister every lane required for the question and its competence boundary.

### A11. Preregistered discriminators and priority

For each discriminator state:
- candidate pair or candidate-vs-rival relation;
- necessary proposition(s) served;
- prediction/argument;
- relevant background;
- priority;
- symmetric rationale;
- directional result vocabulary;
- feasibility status;
- comparison-scoped coverage certification required to become MAKEABLE.

Priority is pair-relative and **mutually exclusive**:

- **CRITICAL:** if the discriminator's result can determine candidate adequacy **or** determine whether a necessary truth-bearing proposition is established/defeated for at least one member of the pair.
- **MATERIAL:** only if it changes relative warrant in a truth-relevant way **without** determining candidate adequacy and **without** determining the truth-status of a necessary proposition.
- **CONTEXTUAL:** if it informs interpretation/plausibility but does neither of the above.

If a discriminator satisfies the CRITICAL definition, it cannot be labeled MATERIAL.

An independent reviewer confirms:
- tier classification;
- pair symmetry;
- coverage-map linkage;
- feasibility.

### Feasibility

Before G0 closes, every CRITICAL discriminator receives:
- `FEASIBLE_WITHIN_SCOPE`; or
- `INFEASIBLE_WITHIN_SCOPE`.

A known-infeasible discriminator may remain CRITICAL only when the preregistration explicitly states that `INSUFFICIENT_SIGNAL_WITHIN_SCOPE` is the intended confirmatory consequence. Otherwise it must be reformulated or removed before evidence exposure.

For every CRITICAL or MATERIAL discriminator use:
- `FAVORS_A`;
- `FAVORS_B`;
- `NEUTRAL_OR_NONDISCRIMINATING`;
- `UNMAKEABLE`.

Definitions:

- **UNMAKEABLE:** the comparison cannot receive a directional result because comparison-scoped evidence coverage/access is inadequate or provenance fails.
- **NEUTRAL_OR_NONDISCRIMINATING:** comparison-scoped coverage is adequate and independently certified, but the evidence supplies no warranted direction.
- **MAKEABLE:** a designated independent `MAKEABLE_CERTIFIER` confirms comparison-scoped coverage is `COMPLETE` or `MATERIALLY_COMPLETE` and provenance is adequate to issue one of the first three directional results.

A **TRUTH_CRITICAL_COMPARISON** is any CRITICAL discriminator, plus a MATERIAL discriminator preregistered as a tie-breaker only after all relevant CRITICAL comparisons are MAKEABLE and neutral/non-discriminating.

Rules:
- any UNMAKEABLE CRITICAL comparison blocks dominance between affected live candidates;
- MATERIAL evidence cannot directly veto a resolved CRITICAL result;
- evidence that undermines a premise/evidence supporting a CRITICAL result is processed first as a proposition-level defeater; the CRITICAL result is then reissued or withdrawn;
- if all relevant CRITICAL comparisons are MAKEABLE and neutral, MATERIAL may decide dominance only when directions are non-conflicting;
- conflicting MATERIAL directions with neutral CRITICAL evidence yield `UNDERDETERMINED_WITHIN_SCOPE: MIXED_TRADEOFF` unless resolved by dependence/defeater analysis;
- CONTEXTUAL evidence never establishes dominance.

### A12. Candidate adequacy and ranking eligibility

Before comparison, every candidate must satisfy:

1. sufficiently specified to generate truth-relevant consequences;
2. internally non-contradictory or has a defensible resolution;
3. candidate-native steelman packet frozen;
4. enough evidence coverage exists to evaluate its necessary propositions;
5. `NECESSARY_PROPOSITION_COVERAGE_COMPLETE` is certified.

A candidate is **INADEQUATE_WITHIN_SCOPE** if:
- any necessary proposition is `CONTRADICTED_WITHIN_SCOPE`; or
- an undefeated `TRUTH_CRITICAL_DEFEATER` defeats a necessary proposition or required candidate condition.

A candidate is **ADEQUATE_BUT_RANKING_BLOCKED** if any candidate-specific necessary proposition is:
- `EVIDENCE_AGAINST_WITHIN_SCOPE`;
- `NOT_ESTABLISHED_WITHIN_SCOPE`;
- `INSUFFICIENT_SIGNAL_WITHIN_SCOPE`;
or carries an undefeated MATERIAL_DEFEATER.

A candidate-specific necessary proposition that is only `PARTIALLY_SUPPORTED_WITHIN_SCOPE` may remain RANKING_ELIGIBLE, but the partial-support limitation must be included in the comparison and blocks TRUTH_WARRANTED.

A `NONCOMPARATIVE_CANDIDATE_SPECIFIC` necessary proposition must be `SUPPORTED_WITHIN_SCOPE` before the candidate is RANKING_ELIGIBLE, because no pairwise discriminator exists to compensate for weakness in that candidate-specific obligation.

A `NONCOMPARATIVE_SHARED_FLOOR` unresolved premise does not choose among candidates but blocks TRUTH_WARRANTED for every dependent candidate.

Only candidates that are adequate and not ranking-blocked are **RANKING_ELIGIBLE**.

If no candidate is adequate under adequate coverage, use `NONE_ADEQUATE_WITHIN_SCOPE`.
If exactly one candidate is adequate, use `ONLY_ADEQUATE_CANDIDATE_WITHIN_SCOPE`.
If two or more candidates remain adequate but none is ranking-eligible, use `UNDERDETERMINED_WITHIN_SCOPE` or `INSUFFICIENT_SIGNAL_WITHIN_SCOPE` according to coverage.

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

At G0:

- freeze the exact qualified protocol identity governing the study;
- initialize an append-only `EVIDENCE_EXPOSURE_LEDGER`;
- record the freeze identity/time of every G0 artifact;
- name a ledger custodian and an independent ledger-integrity reviewer.

Each exposure entry records:
- monotonically increasing sequence number;
- repository commit/blob identity;
- time/order;
- actor/actor-lineage;
- artifact/source class;
- which amendment surfaces it could affect.

The custodian may append but may not rewrite prior entries.

When any amendment is classified, the independent ledger-integrity reviewer verifies:
- sequence continuity;
- commit history contains no unrecorded ledger rewrite;
- the relevant exposure precedes/follows the amendment as claimed.

The ledger-integrity reviewer is outcome-material and cannot serve as strict auditor.

A study remains under its frozen protocol version unless the human owner authorizes a migration plan. Outcome-material protocol migration after evidence exposure uses C4.

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

Every frozen G0 element in A1–A17 and every downstream frozen artifact is amendment-controlled.

Every amendment:
- cites the A17 ledger;
- identifies **every affected candidate and outcome condition**;
- receives independent direction-classification review before use.

Direction is relational:

For each affected candidate/outcome condition classify the amendment effect as:
- `ADVERSE`;
- `FAVORABLE`;
- `NEUTRAL`;
- `MIXED_OR_UNCLEAR`.

Then assign one amendment class:

#### `PRE_EVIDENCE_AMENDMENT`
Made before relevant outcome evidence exposure.
Requires rationale; outcome-material changes require independent review.

#### `POST_EVIDENCE_NONMATERIAL`
After exposure but clerical/non-outcome-determinative.
Requires independent confirmation.

#### `POST_EVIDENCE_ADVERSE_ONLY`
Every candidate/outcome effect is ADVERSE or NEUTRAL, and at least one is ADVERSE.
All adverse effects MUST enter the current confirmatory study after re-analysis/re-freeze.

#### `POST_EVIDENCE_FAVORABLE_OR_MIXED`
At least one candidate/outcome effect is FAVORABLE or MIXED_OR_UNCLEAR.
The descriptive correction is preserved, and every ADVERSE effect enters immediately.
No FAVORABLE consequence may improve the current confirmatory canonical result; favorable consequences remain exploratory until fresh preregistration or held-out confirmation.

Thus a defeater against B that improves A's relative standing is FAVORABLE_OR_MIXED: B's adverse consequence is incorporated, but A may not claim the post-evidence improvement as confirmatory support.

The independent direction reviewer and ledger-integrity reviewer cannot serve as strict auditor.

Retyping, role/scope/source-plan/background/discriminator/lane/protocol changes all use this rule.

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

### E3. Coverage states and adverse-source probe

Every coverage state has an explicit **coverage scope**:
- `STUDY`;
- `LANE:<id>`;
- `PROPOSITION:<id>`;
- `COMPARISON:<id>`.

Every state requires independent `COVERAGE_STATE_REVIEW`.

Before certifying `COMPLETE` or `MATERIALLY_COMPLETE`, an independent reviewer performs an **ADVERSE_SOURCE_PROBE** outside the original source-plan search paths where feasible.

The probe must:
- search at least one credible external/alternative index, bibliography, tradition-critical source stream, or citation trail not used to construct the plan;
- specifically look for evidence that would weaken the current source universe or expose omitted source classes;
- record queries/routes and results;
- add discovered outcome-material strata through the amendment rule.

Coverage labels:

#### `COVERAGE_COMPLETE_FOR_FROZEN_SCOPE`
All preregistered strata searched; all identified outcome-material sources evaluated; adverse-source probe found no omitted outcome-material source class.

#### `COVERAGE_MATERIALLY_COMPLETE_WITH_LISTED_GAPS`
Truth-critical strata addressed; gaps listed; adverse-source probe completed; reviewer judges no listed/discovered gap likely to change the scoped disposition/comparison.

#### `COVERAGE_INCOMPLETE`
A truth-critical stratum/source remains unsearched, inaccessible without adequate substitute, or potentially outcome-changing.

The reviewer certifies all states.

`MAKEABLE` comparison certification specifically requires a `COMPARISON:<id>` coverage review.

A self-declared/uncertified state is `COVERAGE_UNCERTIFIED` and cannot support canonical comparison.

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
- `MIXED_TRADEOFF`;
- `DEPENDENCY_CYCLE`.

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
- worldview/foundational, with neutral subtype recorded (for example tradition-confessional, secular-naturalistic, secular-nonnaturalistic, metaphysical-foundational, methodological-skeptical, or other).

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

Definitions:

- **revelation:** a truth-critical claim that information, command, proposition, experience, or disclosure originates from a divine/non-human transcendent source or from an agent claimed to possess such revelatory authority.
- **authority/canon dependent on revelation:** an authority/canon claim whose warrant materially depends on the truth, source, reliability, preservation, or authorized transmission of a revelation claim.

Phase I is mandatory whenever a truth-critical subclaim is tagged:
- miracle/anomalous-event;
- revelation;
- prophecy;
- authority/canon dependent on revelation.

The A4 definitions control miracle/prophecy tagging.

The trigger is candidate-symmetric: if any admitted candidate assigns such significance to the claim, the comparative study includes the trigger.

Relevant claims retain their historical/textual/philosophical/authority types; relabeling cannot bypass Phase I.

Initial trigger assignment passes the independent A4 typing review.

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

Every necessary node and arrow receives disposition/confidence.

The chain disposition cannot exceed its weakest necessary link.

A LOW-confidence necessary link **blocks `TRUTH_WARRANTED` in the current study**.
There is no reviewer waiver.

When two or more necessary links are MODERATE and their uncertainties are at least partly independent, create a `CUMULATIVE_FRAGILITY_REVIEW`.

A designated independent reviewer states whether joint uncertainty could plausibly:
- create a background flip;
- downgrade a truth-critical disposition;
- invalidate a necessary arrow;
- defeat candidate dominance.

If yes or unresolved, `TRUTH_WARRANTED` is blocked.

This reviewer is outcome-material and cannot serve as strict auditor.

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
- **C1 material continuity:** related artifact/form/symbol/textual formula can be chronologically traced.
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

## 16. Phase N — Candidate adequacy, discriminator completeness, and background robustness

Before relative comparison:

1. apply A12 adequacy/ranking-eligibility rules;
2. verify `NECESSARY_PROPOSITION_COVERAGE_COMPLETE` for **every admitted candidate**;
3. verify every RANKING_ELIGIBLE candidate's necessary propositions have frozen proposition dispositions;
4. apply background robustness including required joint combinations;
5. verify every relevant CRITICAL discriminator is either:
   - MAKEABLE; or
   - explicitly INFEASIBLE with the preregistered consequence.

An UNMAKEABLE CRITICAL comparison between otherwise RANKING_ELIGIBLE candidates blocks pairwise dominance.

Use:
- `INSUFFICIENT_SIGNAL_WITHIN_SCOPE` when unmakeable because evidence/coverage/provenance is inadequate;
- `UNDERDETERMINED_WITHIN_SCOPE` when adequate comparison coverage exists but evidence is neutral/non-discriminating.

---

## 17. Phase N2 — Inferential bridge

Apply proposition-level warrant before discriminator ranking:

1. necessary proposition `CONTRADICTED` → candidate INADEQUATE;
2. undefeated TRUTH_CRITICAL_DEFEATER of a necessary proposition/required condition → candidate INADEQUATE;
3. necessary proposition `EVIDENCE_AGAINST` → MATERIAL_DEFEATER and `ADEQUATE_BUT_RANKING_BLOCKED` until resolved;
4. candidate-specific necessary proposition `INSUFFICIENT_SIGNAL` → candidate is ADEQUATE_BUT_RANKING_BLOCKED; no ranking/truth adjudication dependent on it;
5. candidate-specific necessary proposition `NOT_ESTABLISHED` → candidate is ADEQUATE_BUT_RANKING_BLOCKED;
6. candidate-specific necessary proposition `PARTIALLY_SUPPORTED` → relative comparison may continue only when its A6 route is COMPARATIVE_ROUTE; truth-warrant remains blocked;
7. only after these proposition rules are applied, use A11 discriminator stages;
8. CONTEXTUAL evidence cannot establish dominance/truth-warrant;
9. internal coherence never substitutes for external warrant.

### Candidate dominance

Dominance is available only between RANKING_ELIGIBLE candidates with complete necessary-proposition coverage maps.

**Stage 1 — CRITICAL**
- UNMAKEABLE CRITICAL → dominance blocked.
- one or more FAVORS_A and none FAVORS_B → A passes Stage 1;
- one or more FAVORS_B and none FAVORS_A → B passes;
- opposing CRITICAL directions → `UNDERDETERMINED: MIXED_TRADEOFF` unless proposition-level dependence/defeater analysis resolves them;
- all CRITICAL neutral/non-discriminating → Stage 2.

**Stage 2 — MATERIAL**
Used only when Stage 1 is neutral.
- at least one MATERIAL comparison must favor the candidate;
- none may favor the rival;
- conflict → `UNDERDETERMINED: MIXED_TRADEOFF`;
- an UNMAKEABLE outcome-relevant MATERIAL tie-breaker blocks dominance when CRITICAL is neutral.

**Stage 3 — CONTEXTUAL**
May explain but never create/reverse dominance.

### Background-sensitive ranking

Run the dominance procedure under every required live background/joint combination.

Record separately:
- `RANKING_ROBUST`: the same candidate is BEST_SUPPORTED under every tested live background;
- `RANKING_FRAMEWORK_DEPENDENT`: ranking changes across backgrounds;
- `TRUTH_WARRANT_ROBUST`;
- `TRUTH_WARRANT_FRAMEWORK_DEPENDENT`: ranking is stable but eligibility for TRUTH_WARRANTED changes.

A truth-warrant eligibility-only background flip does **not** erase a robust BEST_SUPPORTED ranking.
It blocks only TRUTH_WARRANTED and must be reported as `TRUTH_WARRANT_FRAMEWORK_DEPENDENT`.

If ranking itself changes, use `UNDERDETERMINED_WITHIN_SCOPE: FRAMEWORK_DEPENDENCE`.

---

## 18. Phase N3 — Provisional study outcomes

At G3 every outcome is prefixed `PROPOSED_`.
The prefix is removed only after G4 audit and G5 human acceptance.

### `PROPOSED_CANDIDATE_A_BEST_SUPPORTED_WITHIN_SCOPE`

Requires:
- at least two RANKING_ELIGIBLE candidates;
- complete certified necessary-proposition coverage maps for all admitted candidates;
- frozen necessary-proposition dispositions for all RANKING_ELIGIBLE candidates;
- A dominates every other RANKING_ELIGIBLE candidate under the staged rule;
- no ranking-blocking MATERIAL_DEFEATER remains;
- ranking status is `RANKING_ROBUST` or the exact background dependence is reported.

This is relative evidential ranking, not approximate truth.

### `PROPOSED_CANDIDATE_A_ONLY_ADEQUATE_WITHIN_SCOPE`

Use when:
- coverage is adequate;
- A is the only ADEQUATE candidate;
- every other admitted candidate is INADEQUATE under A12/N2;
- A's own necessary propositions are not thereby promoted to SUPPORTED.

This means "only candidate not defeated by the adequacy gate," not "true" and not automatically "best supported."

### `PROPOSED_CANDIDATE_A_TRUTH_WARRANTED_WITHIN_SCOPE`

Requires all:

1. exact truth proposition explicit;
2. candidate universe gate passed;
3. complete certified necessary-proposition coverage map;
4. every necessary truth-bearing proposition `SUPPORTED`;
5. every sufficiency record complete;
6. no undefeated TRUTH_CRITICAL_DEFEATER or MATERIAL_DEFEATER;
7. adequate coverage including comparison/adverse-source controls;
8. `TRUTH_WARRANT_ROBUST` across all serious live backgrounds/joint combinations;
9. no LOW-confidence necessary link;
10. no unresolved cumulative-fragility review;
11. serious rivals compared equally;
12. external warrant, not mere coherence/priority/consensus;
13. G4 audit PASS/PASS_WITH_LIMITATIONS;
14. G5 human acceptance.

Before G4/G5 it remains PROPOSED.

### `PROPOSED_CANDIDATE_A_CLOSEST_TO_TRUTH_WITHIN_SCOPE`

Use only when:
- no candidate is truth-warranted;
- at least two RANKING_ELIGIBLE candidates remain;
- A16 shared proposition map contains at least two independent truth-bearing dimensions;
- complete necessary-proposition coverage maps exist;
- A is not contradicted on a CRITICAL shared proposition;
- A has the required comparative advantage on the shared dimensions;
- no unresolved CRITICAL/MATERIAL conflict defeats the ordering;
- residual unsupported propositions are explicit.

Unavailable for genuinely one-dimensional questions.

### `PROPOSED_REVISED_CANDIDATE_REQUIRED_WITHIN_SCOPE`
Supported components survive but no admitted candidate combines them. Triggers a new preregistered candidate cycle.

### `PROPOSED_NONE_ADEQUATE_WITHIN_SCOPE`
Use under adequate coverage when every admitted candidate is INADEQUATE.

### `PROPOSED_UNDERDETERMINED_WITHIN_SCOPE`
Two or more adequate/ranking-eligible candidates remain and no warranted preference exists.
Record subtype.

### `PROPOSED_INSUFFICIENT_SIGNAL_WITHIN_SCOPE`
Coverage/provenance is insufficient.
Record subtype(s).

### Single-proposition questions
For "Did X occur?" or "Is P true?", represent P and material rivals/negation where appropriate without manufacturing false dichotomies.

---

# G4 — ADVERSARIAL AUDIT

## 19. Phase O — Audit severity and outcomes

### Severity
- **BLOCKING:** governance/authority failure or core inferential defect that makes qualification/adjudication unsafe or invalid.
- **MAJOR:** methodological defect that could materially change outcome/reproducibility; qualification/adjudication is blocked until repaired.
- **MINOR:** real defect not expected by itself to change the bounded outcome; repair or explicit limitation required.
- **NOTE:** observation/non-defect.

### Audit terminology

- **decision surface:** one operational transition whose rules jointly determine a materially similar class of outcomes, e.g. candidate admission, evidence coverage, proposition disposition, dominance, canonical acceptance.
- **interacting MINOR defects:** MINOR findings whose combined operation can change the same gate, classification, or outcome even when none alone is expected to do so.
- **LIMITATION:** an irreducible scope/evidence/method constraint that cannot be removed without changing authorized scope, obtaining unavailable evidence/access, or replacing a deliberate methodological commitment, and that leaves no repairable outcome-determinative ambiguity.

### Audit outcomes

#### `PASS`
All mandatory checks pass; no unresolved BLOCKING/MAJOR/MINOR defect; NOTES may remain.

#### `PASS_WITH_LIMITATIONS`
No unresolved BLOCKING/MAJOR defect.
May carry irreducible LIMITATION findings and individually bounded non-outcome-determinative MINORs.

#### `REPAIR_REQUIRED`
Required when:
- any BLOCKING or MAJOR exists;
- three or more MINOR defects occur on the same decision surface; or
- two or more interacting MINORs could jointly change reproducibility/outcome integrity.

#### `INVALID_COMPARISON`
Study audit: comparison design invalid and must restart from an earlier gate.
Protocol audit: qualification bundle is internally inconsistent/incompletely frozen/mismatched so merits cannot be evaluated.

#### `INSUFFICIENT_SIGNAL`
Auditor lacks required frozen artifacts/evidence/access; not a merit verdict.

### Audit-set disclosure

Every G4/qualification record must identify **all known audits of the exact same frozen study/bundle**, including PASS and FAIL results.

No same-bundle audit may be silently discarded.

If same-bundle audits materially disagree:
- status = `DISPUTED_AUDIT`;
- G5/qualification is blocked;
- a versioned `AUDIT_RECONCILIATION_RECORD` must identify its author, each disputed finding, and whether disagreement is resolved;
- the reconciliation cannot delete or replace dissenting audits;
- if unresolved, obtain another strict audit or repair/re-audit the target.

A program lead may respond to an audit but cannot override a required failure.

### O1. Mandatory strict independence

Any canonical theological adjudication or protocol qualification requires a strict independent auditor.

For a study, use the G0 role matrix.

For protocol qualification, use the frozen external **qualification role-control record** named by STATE and the qualification source manifest. The role-control record is launch control, not one of the five governed methodological blobs, and must be completed after auditor assignment but before substantive audit begins.

The strict protocol auditor must be disjoint by actor lineage from:
- protocol author(s);
- candidate Governance amendment author(s);
- program lead for the repair cycle;
- every outcome-material qualification reviewer;
- source-manifest preparer if that person made any substantive qualification decision.

The role-control record must also identify:
- source-manifest preparer;
- human relaying operator, if any;
- strict auditor model/provider/session/actor-lineage after assignment;
- required strict-audit count.

The human operator may relay the frozen launch prompt/source manifest and returned audit report without collapsing independence, provided they do not transmit substantive prior audit reasoning or make reviewer decisions.

Before audit launch, the auditor must attest:
- actor/session/model provenance;
- no prohibited prior outcome-material reasoning is available;
- disjointness from the recorded author/reviewer lineages.

If the human owner materially authored or reviewed the candidate package, apply the Governance dual-role rule and required audit count.

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
The explicit MINOR-cluster thresholds in the audit-outcome definitions determine when MINORs force `REPAIR_REQUIRED`.

Audit-outcome namespace rule:
- proposition-level: `INSUFFICIENT_SIGNAL_WITHIN_SCOPE`;
- study-level: `PROPOSED_INSUFFICIENT_SIGNAL_WITHIN_SCOPE`;
- audit-level: record `AUDIT_INSUFFICIENT_SIGNAL` (display label may remain `INSUFFICIENT_SIGNAL`).

`INVALID_COMPARISON` is reserved for G4 audit disposition.

### O3. Blinding
Use blinding where it reduces a real bias without removing necessary context.
At minimum, the auditor is not given any human preference as authority and receives frozen artifacts.

### O4. Auditor disagreement

Material disagreement among audits of the same frozen target produces `DISPUTED_AUDIT` and invokes the Audit-set disclosure/reconciliation rule above.

### O5. Program-lead response

The program lead may publish a response but cannot override a required audit failure.

Options:
- accept and repair;
- obtain another strict audit against the same frozen criteria, while disclosing the full audit set;
- request an explicit future Governance/Protocol amendment.

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
- necessary-proposition coverage map;
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

A protocol-qualification audit uses the same topic-status vocabulary as O2 and the same severity/outcome semantics.

Mandatory topics:

1. authority/governance consistency;
2. role/strict-independence rules and actor-lineage provenance;
3. candidate/background symmetry;
4. evidence-acquisition/provenance/coverage;
5. claim typing and sufficiency;
6. amendment/change control and exposure ledger;
7. lane/proposition consolidation;
8. discriminator priority and inferential bridge;
9. miracle/revelation/prophecy handling;
10. philosophy/source/continuity handling;
11. audit semantics themselves;
12. STATE/schema/legacy alignment;
13. uncertainty/stop/reopen;
14. cold-start reproducibility;
15. immutable source identity and regression/internal consistency.

A protocol audit may add frozen checks before launch but may not weaken this set.

`INVALID_COMPARISON` in a protocol audit means the qualification bundle itself is not a valid stable target, not that a theological candidate comparison failed.

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
  lifecycle_status:  # ACTIVE | CLOSED | HELD | SUPERSEDED | REVIEW_REQUIRED | REOPENED
  authorization_artifact:
  role_matrix_artifact:
  evidence_exposure_ledger:
  accepted_at:
  synthesis_artifact:
  audit_artifacts: []
  audit_reconciliation_artifact:
  human_acceptance_artifact:
  confidence:
  evidence_coverage:
  background_assumptions:
  residual_alternatives:
  known_weaknesses:
  flip_or_weaken_conditions:
  underdetermination_subtype:
  limitations:
  negative_knowledge:
  reopen_if:
  superseded_by:
```

The G0 authorization, role matrix, and exposure ledger are canonical provenance links, not optional prose.

After the human owner creates the acceptance record, the program lead or another authorized agent performs the mechanical STATE update. The edit records acceptance; it does not create it.

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

### P6. Protocol-qualification STATE schema

The authoritative STATE field is `qualified_protocol`.

A qualified protocol record MUST contain:

```yaml
qualified_protocol:
  version:
  protocol_path:
  protocol_blob_sha:
  governed_bundle_commit:
  source_manifest:
  governance_version:
  governance_blob_sha:
  charter_blob_sha:
  method_seed_blob_sha:
  audited_state_blob_sha:
  audit_artifacts: []
  audit_dispositions: []
  audit_reconciliation_artifact:
  human_owner_acceptance_artifact:
  governance_ratification_artifact:
  post_qualification_state_commit:
  qualified_at:
  limitations: []
  status: "QUALIFIED"  # QUALIFIED | QUALIFICATION_CHALLENGED | DEQUALIFIED | SUPERSEDED
  reopen_if: []
  superseded_by:
```

If multiple strict audits are required, every audit/disposition appears in the arrays.

The post-qualification STATE commit is permitted by §0 because it is a mechanical state transition that cites—rather than mutates—the immutable audited bundle.

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

Even after qualification:

- `SUPPORTED_WITHIN_SCOPE` retains disciplined expert judgment **only inside the documented sufficiency/disposition steps**; this limitation does not excuse undefined dominance, source-selection, or background-selection rules.
- metaphysical/revelation questions may legitimately remain `UNDERDETERMINED_WITHIN_SCOPE: FRAMEWORK_DEPENDENCE` when serious live backgrounds or their required combinations genuinely change a truth-warrant condition;
- AI-session/model independence is procedural and cannot guarantee independent training priors. This does not excuse shared-context/actor-lineage collapse, which is governed separately.

---

## 22. Phase Q2 — Stop, reopen, supersede, and de-qualify

A study may stop when:
- certified coverage target is complete/materially complete;
- truth-critical sources are addressed/listed;
- remaining accessible material is predominantly dependent/repetitive or not expected to change a truth-critical proposition;
- remaining gaps and possible effect are stated.

Low expected information gain is valid only after this coverage record exists or further truth-critical evidence is unavailable.

Adjudication lifecycle states:
- `ACTIVE`;
- `CLOSED`;
- `HELD`;
- `SUPERSEDED`;
- `REVIEW_REQUIRED`;
- `REOPENED`.

Every CLOSED/HELD adjudication defines `reopen_if`.

### Protocol lifecycle

Protocol status:
- `QUALIFIED`;
- `QUALIFICATION_CHALLENGED`;
- `DEQUALIFIED`;
- `SUPERSEDED`.

If a credible later defect report identifies a possible BLOCKING/MAJOR methodological defect:

1. set `QUALIFICATION_CHALLENGED`;
2. pause new study authorization under it;
3. run independent impact audit;
4. accepted adjudications are not automatically erased;
5. mark an adjudication `REVIEW_REQUIRED` only if the defect could plausibly affect it;
6. human owner may restore QUALIFIED, qualify a repair, or set DEQUALIFIED.

A newer qualified protocol sets the older one SUPERSEDED for new work while preserving provenance.

---

## 23. Anti-heuristic safeguard

The G4 audit MUST produce a `HEURISTIC_MATRIX_AUDIT`.

Test at least:

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
- always transmission;
- always choose the weakest permitted disposition;
- always default to underdetermination when frameworks disagree;
- always prefer the candidate with more evidence items;
- always let any missing evidence block adjudication.

For each slogan and every candidate's CRITICAL/MATERIAL disposition pattern, record:
1. what the slogan alone would predict;
2. what the actual evidence-integrating procedure produced;
3. at least one material place where evidence integration, dependencies, defeaters, or typed burdens matter beyond the slogan.

A slogan matching the headline outcome is not itself a failure.

If one heuristic reproduces the material disposition matrix without evidence integration, topic 14 is `FAIL_MAJOR`.

An exemption claiming that a heuristic is actually justified for the exact question must be stated by the synthesis author and independently accepted or rejected by the strict auditor with reasons.

---

## 23A. Minimum artifact templates and cold-start definitions

These are minimum schemas; studies may add fields but may not omit required ones.

### SOURCE_PLAN

```yaml
study_id:
scope:
source_strata:
  - id:
    type:
    candidate_or_background_served:
    repositories_or_corpora:
    search_rules:
    inclusion_rules:
    exclusion_rules:
    languages_dates:
adverse_source_probe_plan:
inaccessible_source_rule:
reviewer:
freeze_identity:
```

### BACKGROUND_REGISTER_REVIEW

```yaml
study_id:
backgrounds:
  - id:
    propositions:
    admission_basis:
    truth_critical_relevance:
    variants:
    compatibility_constraints:
    status: ADMITTED | EXCLUDED
    reason:
elicitation_method:
blind_elicitation_feasible:
reviewer:
freeze_identity:
```

### BACKGROUND_INTERACTION_MATRIX

```yaml
dimensions:
pairs_or_higher_sets:
  - ids: []
    materially_interact: true|false
    rationale:
    compatible_combinations: []
    required_tests: []
reviewer:
freeze_identity:
```

### SUFFICIENCY_RECORD

```yaml
proposition_id:
claim_types: []
mandatory_elements:
  - element:
    status: MET | NOT_MET | NOT_APPLICABLE
    evidence:
    rationale:
defeaters: []
disposition:
confidence:
review_identity:
```

### PROPOSITION_EVIDENCE_MATRIX

```yaml
proposition_id:
necessary_for_candidates: []
lanes:
  - lane:
    facet:
    direct_or_indirect:
    independence:
    disposition:
    discriminator_links: []
    defeaters: []
consolidated_disposition:
rationale:
```

### EVIDENCE_EXPOSURE_LEDGER

```yaml
study_id:
custodian:
integrity_reviewer:
entries:
  - sequence:
    repository_commit:
    actor_lineage:
    source_or_artifact:
    exposure_class:
    amendment_surfaces: []
```

### Serious rival

A **SERIOUS_RIVAL** is a candidate/explanation/reading that:
- is coherent/specifiable;
- is materially relevant to a necessary proposition or outcome;
- has serious scholarly/traditional representation OR an independently defensible argument;
- is not already defeated by an applicable canonical adjudication.

The same rule applies regardless of confessional/skeptical orientation.

### MAKEABLE certifier

The designated independent `MAKEABLE_CERTIFIER` is the reviewer who issues the `COMPARISON:<id>` coverage certification required by A11.
That reviewer cannot serve as strict auditor.

## 24. Current qualification state

```text
PROTOCOL_VERSION = 0.1.5
STATUS = CANDIDATE__REPAIR_PENDING_REAUDIT
SELF_QUALIFICATION = PROHIBITED
TFP_STRESS_2 = NOT_AUTHORIZED
MAJOR_DOCTRINAL_COMPARISON = HELD
NEXT = STRICT_INDEPENDENT_QUALIFICATION_REAUDIT
```

## 25. Governing principle

> A theological conclusion may travel only as far as its typed evidence, explicit dependencies, background robustness, proposition consolidation, adversarial audit, and human acceptance can carry it.
