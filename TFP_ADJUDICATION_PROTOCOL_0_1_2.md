# TFP Adjudication Protocol 0.1.2

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

Role definitions come from Governance 0.1.1:

- **human owner:** authorizes every bounded truth-adjudication study at G0, accepts canonical theological adjudications at G5, and qualifies protocols after required audit;
- **program lead:** orchestrates already-authorized work but cannot self-authorize a truth study, override failed audit, or substitute for human acceptance;
- **independent reviewer:** did not author/co-author the item or make the outcome-determinative decision being reviewed;
- **strict independent auditor:** did not author/co-author the G0 preregistration, candidate packets, outcome-determinative lanes, comparative synthesis, or repair under audit.

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
| **G2 Lane synthesis** | F–L: proposition dispositions, type-specific sufficiency, philosophical machinery, miracle/revelation/prophecy, source quality, lane freeze, proposition consolidation, continuity |
| **G3 Comparative adjudication** | M–N: candidate adequacy, inferential bridge, provisional study outcome |
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
- traditions/candidates in view;
- geography/languages where relevant;
- explicit exclusions;
- limits on downstream inference.

### A3. Role matrix
Name:
- human owner;
- program lead;
- candidate constructors;
- lane authors;
- independent reviewers;
- intended strict independent auditor(s), if known;
- any human-owner dual-role exception.

The human owner must explicitly authorize the study at G0.

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

Any claim tagged miracle/anomalous-event, revelation, or supernatural prophecy MUST invoke Phase I.

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
Enumerate every serious live background that could materially change admissibility or inference, including relevant:
- metaphysical;
- epistemological;
- historiographic;
- linguistic;
- confessional/anti-confessional;
- methodological assumptions.

For each background:
- state propositions;
- warrant;
- serious rival background(s);
- what inference would change if it changed.

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
Any post-freeze change to:
- candidate set;
- claim type;
- necessary-proposition status;
- background register;
- source/search plan;
- inclusion/exclusion rule;
- required lanes;
- discriminator;
- discriminator priority;
- adequacy gate;
- frozen lane finding

must be versioned and classified:

#### `PRE_EVIDENCE_AMENDMENT`
Made before any relevant outcome evidence is viewed.
Requires rationale; independent review if outcome-determinative.

#### `POST_EVIDENCE_NONMATERIAL`
After evidence exposure but demonstrably clerical/non-outcome-determinative.
Requires independent reviewer confirmation.

#### `POST_EVIDENCE_OUTCOME_MATERIAL`
Could improve/worsen a candidate, alter burden, change search universe, change necessary propositions, or affect synthesis.

It is exploratory for the current confirmatory study.
It cannot be used to improve a canonical result in that same study.
Canonical use requires a fresh preregistered follow-up or held-out confirmation.

Retyping may not raise or lower any candidate's burden after contrary/favorable evidence appears without this rule.

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

### `SUPPORTED_WITHIN_SCOPE`
Requires:
- applicable type-specific mandatory elements all `MET` or justified `NOT_APPLICABLE`;
- coverage complete/materially complete;
- serious alternatives tested;
- no undefeated CRITICAL/MAJOR defeater;
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

Use `FRAMEWORK_DEPENDENCE` specifically when outcome changes under serious live rival background registers.

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
- supernatural prophecy.

A miracle claim also retains its historical/textual/philosophical types; the tag cannot be omitted to bypass Phase I.

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
- `UNKNOWN` is a residual status, not an explanatory winner;
- `FRAUD_OR_ERROR`, `ORDINARY_NATURAL`, and `RARE_NATURAL` must be specified enough to generate evidence expectations before they can defeat a specified rival.

### I4. Background robustness
At G0 enumerate serious live rival background registers.
Run every truth-critical causal/theological inference under each live register not independently rejected by applicable canonical adjudication.

If the study-level result flips under a serious live rival background:
- `TRUTH_WARRANTED` is prohibited;
- report conditional results;
- use `UNDERDETERMINED_WITHIN_SCOPE: FRAMEWORK_DEPENDENCE`.

Sensitivity-testing alone does not satisfy robustness.

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
Any material change after freeze is `POST_EVIDENCE_OUTCOME_MATERIAL` unless an independent reviewer documents why it is nonmaterial.

A material amendment:
- invalidates the old frozen finding for synthesis;
- requires re-analysis/re-freeze;
- requires any dependent comparative synthesis to rerun;
- is explicitly inspected at G4.

### K6. Circular dependency
If Lane A requires Lane B's conclusion while Lane B requires Lane A's conclusion:
- extract the shared premise into a separate background/precondition analysis; or
- mark the dependency unresolved.

An unresolved outcome-determinative cycle yields `UNDERDETERMINED` or `INVALID_COMPARISON` as appropriate.

---

## 14. Phase L — Proposition consolidation across lanes

For every truth-critical proposition build a `PROPOSITION_EVIDENCE_MATRIX` listing:
- lanes;
- claim facet addressed;
- direct vs indirect support;
- independence/dependence;
- disposition;
- priority/defeaters.

### L1. Distinct necessary facets
If lanes address different necessary facets, the proposition cannot exceed the weakest necessary facet.

### L2. Independent convergence on the same facet
Independent partial supports may jointly yield `SUPPORTED` only if:
- together they satisfy all preregistered mandatory sufficiency elements;
- each stream adds non-duplicative truth-relevant information;
- dependency analysis confirms they are not repetitions of one bottleneck;
- no undefeated CRITICAL/MAJOR defeater remains.

Mere repetition never promotes a disposition.

### L3. Cross-lane conflict
Resolve in order:

1. check whether lanes address different propositions/facets;
2. check source/evidence dependence;
3. direct claim-specific evidence outranks merely contextual compatibility for that proposition;
4. a valid defeater can override otherwise positive support;
5. if two independent, direct, sufficiently strong lanes remain in material conflict with no principled priority, use `UNDERDETERMINED: MIXED_TRADEOFF`.

No vote-counting.

### L4. Chain attenuation
Every necessary node **and arrow** in a multi-step chain receives disposition/confidence.

The chain disposition cannot exceed its weakest necessary link.

If any necessary link has `LOW` confidence, a study-level `TRUTH_WARRANTED` outcome requires explicit justification that the low confidence cannot materially flip the conclusion; otherwise truth-warrant is blocked.

Multiple supported-but-uncertain links require a cumulative-fragility note. No numerical multiplication is required.

### L5. Evidence convergence record
For each promoted disposition state:
- what survived from prior/lower-level evidence;
- what changed in meaning/function;
- which independent evidence classes converge;
- which apparent convergences share a dependency.

---

## 15. Phase M — Continuity Framework C0–C7

C0–C7 are relation types, not a mandatory ladder:

- C0 recurrence;
- C1 form/material continuity;
- C2 carrier continuity;
- C3 practice continuity;
- C4 semantic continuity;
- C5 named textual continuity;
- C6 genealogical continuity;
- C7 doctrinal continuity.

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

### Symmetry
Continuity and discontinuity/corruption claims face evidential burdens.

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

An unmakeable CRITICAL comparison normally produces `UNDERDETERMINED` or `INSUFFICIENT_SIGNAL`, not silent omission.

---

## 17. Phase N2 — Inferential bridge

Use this defeater-first order:

1. necessary proposition `CONTRADICTED` → candidate inadequate;
2. necessary proposition `EVIDENCE_AGAINST` → major live defeater requiring resolution;
3. necessary proposition `INSUFFICIENT_SIGNAL` → no truth adjudication;
4. necessary proposition `NOT_ESTABLISHED` → no truth-warrant;
5. necessary proposition `PARTIALLY_SUPPORTED` → relative comparison possible, truth-warrant normally blocked;
6. independent direct CRITICAL discriminators outrank generic compatibility;
7. internal coherence never substitutes for external warrant;
8. outcome must be robust across serious live rival background registers or else `FRAMEWORK_DEPENDENCE`.

### Candidate dominance
A dominates B only if:
- both pass adequacy;
- no CRITICAL comparison materially favors B over A without resolution;
- A is at least as well warranted on every makeable truth-critical comparison;
- at least one truth-critical comparison materially favors A.

If irreducible tradeoffs remain, use `UNDERDETERMINED: MIXED_TRADEOFF`.

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
5. no undefeated CRITICAL/MAJOR defeater;
6. adequate coverage;
7. background robustness across all serious live rival registers, or rival backgrounds independently rejected by applicable canonical adjudication;
8. no necessary LOW-confidence link capable of materially flipping result;
9. serious rivals compared equally;
10. external warrant, not mere coherence/priority/consensus;
11. G4 independent audit PASS/PASS_WITH_LIMITATIONS;
12. G5 human acceptance.

Before G4/G5 it remains `PROPOSED_` and conditions 11–12 are pending gates, not assumed facts.

### `PROPOSED_CANDIDATE_A_CLOSEST_TO_TRUTH_WITHIN_SCOPE`
Use only when:

- no candidate is truth-warranted;
- a **shared proposition map** was frozen at G0 for the candidates;
- candidates differ on directionally comparable truth-bearing propositions;
- A is not contradicted on any CRITICAL shared proposition;
- for every serious rival B, at least one CRITICAL shared proposition is better warranted for A than B and none is better warranted for B than A without resolution;
- residual unsupported propositions are explicit.

If candidates cannot be mapped into a shared proposition space without distortion, this label is unavailable; use `BEST_SUPPORTED` or `UNDERDETERMINED`.

### `PROPOSED_REVISED_CANDIDATE_REQUIRED_WITHIN_SCOPE`
Supported components survive but no admitted candidate combines them.
Triggers a new preregistered candidate cycle; does not create a winner.

### `PROPOSED_NONE_ADEQUATE_WITHIN_SCOPE`
All admitted candidates fail A12 under adequate coverage.

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
No unresolved BLOCKING/MAJOR defect.
No qualification-relevant unresolved limitation.
Any MINOR is demonstrably non-outcome-determinative and recorded.

#### `PASS_WITH_LIMITATIONS`
No unresolved BLOCKING/MAJOR defect.
One or more irreducible/non-defect limitations constrain downstream use and are explicitly carried into G5/STATE.

#### `REPAIR_REQUIRED`
At least one BLOCKING or MAJOR defect exists, or a cluster of MINOR defects collectively threatens reproducibility/outcome integrity.

#### `INVALID_COMPARISON`
A defect in question/candidate/background/evidence design invalidates comparison such that local repair after G3 is insufficient and restart from an earlier gate is required.

#### `INSUFFICIENT_SIGNAL`
Auditor lacks required frozen artifacts/evidence/access to evaluate method/result. This is not a merit verdict.

### O1. Mandatory strict independence
Any proposed canonical theological adjudication, truth-warrant, closest-to-truth outcome, or program-level truth-bearing result requires a strict independent auditor.

The strict auditor may not have authored/co-authored:
- G0 preregistration;
- candidate packet;
- outcome-determinative lane;
- synthesis;
- repair being audited.

### O2. Per-topic audit tests
Each mandatory topic receives exactly one:
- `PASS`;
- `FAIL_BLOCKING`;
- `FAIL_MAJOR`;
- `LIMITATION`;
- `NOT_APPLICABLE_WITH_REASON`.

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

### O8. Cold-start performer
The strict independent auditor performs the formal cold-start reproducibility check at G4.
Program lead may preflight earlier but cannot certify it.

---

# G5 — HUMAN ACCEPTANCE

## 20. Phase P — Canonical acceptance

Only the human owner can accept a canonical theological adjudication.

The human owner cannot substitute for the strict audit.

If the human owner materially authored the synthesis, apply the Governance dual-role exception.

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
   - `HIGH`: result is robust across serious live rivals/backgrounds and no known material gap plausibly flips it;
   - `MODERATE`: result is favored but one or more material uncertainties remain that could weaken, though not currently reverse, it;
   - `LOW`: result is tentative and one or more live uncertainties could plausibly reverse it;
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

If yes, the method fails unless that rule was independently justified for the exact question.

---

## 24. Current qualification state

```text
PROTOCOL_VERSION = 0.1.2
STATUS = CANDIDATE__REPAIR_PENDING_REAUDIT
SELF_QUALIFICATION = PROHIBITED
TFP_STRESS_2 = NOT_AUTHORIZED
MAJOR_DOCTRINAL_COMPARISON = HELD
NEXT = FOCUSED_INDEPENDENT_REAUDIT
```

## 25. Governing principle

> A theological conclusion may travel only as far as its typed evidence, explicit dependencies, background robustness, proposition consolidation, adversarial audit, and human acceptance can carry it.
