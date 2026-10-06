# TFP-STRESS-2 — Reviewer A Final Candidate / Background Admission Review Prompt 0.1.0

You are being asked to continue as **REVIEWER_A** for the final pre-G0 candidate/background admission step of TFP-STRESS-2.

This is a design review only. It is not an evidence review, not a G4 audit, and not G0 authorization.

## 1. Exact session

Use only the same Reviewer A session:

`session_012EWsCBUVctdyhhk3v5ZxuF`

Provider/model expected:
- Anthropic
- `claude-sonnet-5-5`

At the top of your response confirm:
- provider/model/session;
- that this is the same session;
- whether you have seen Reviewer B's own report or reasoning.

You may have seen the program lead's current repaired artifacts. That is expected for this final admission review.

If this is not the exact session above, return `INVALID_REVIEW` and STOP.

## 2. Exact permitted sources

Repository:

`https://github.com/etblink/Theological-Foundations-Program`

Branch:

`research/tfp-stress-2-resurrection-g0`

Read only:

1. `TFP_STRESS_2_RESURRECTION_G0_PREREGISTRATION_0_1_2.md`
   - blob: `5c94f11a9a6b76c11b0ed09458cf7cc9938fbfb3`
2. `TFP_STRESS_2_CANDIDATE_REGISTER_0_1_0.yaml`
   - blob: `c993f987f7b58cb7d170ce1f2858b5beb9f4f7aa`
3. `TFP_STRESS_2_BACKGROUND_REGISTER_0_1_0.yaml`
   - blob: `ff98e574f9b2cd81c1cfb851dc13d85ac75e83e4`
4. `TFP_STRESS_2_Q1_EVENT_CONTROL_0_1_0.yaml`
   - blob: `f2d71f6d76c02b19d8d1cc506aabf8ff5e55a283`
5. Qualified Protocol 0.1.7:
   - commit: `b9854f8521193c44e3ed50f5a8b1672572674ec5`
   - path: `TFP_ADJUDICATION_PROTOCOL_0_1_7.md`
   - blob: `0d9406d9ea62ec35ce6424b60ef03ced5dbd332a`
6. Governance 0.1.5:
   - same commit
   - path: `GOVERNANCE.md`
   - blob: `02338ce337de0a115d6942962ce360427080db8d`

Do **not** read:
- Reviewer B's report;
- Reviewer B repair record;
- coverage-map/source-plan/C-HET artifacts unless specifically needed to understand an ID already named in the candidate register;
- issues/PRs/chat logs;
- external literature;
- web search;
- later branch-tip versions of the permitted files.

If a pinned identity fails, return `INVALID_REVIEW` and STOP.

## 3. Your exact role

You are the independent final reviewer for:

- B1 candidate admission;
- B4 candidate exclusion;
- final confirmation that the candidate set is not artificially narrowed;
- A8 candidate/background inclusion-exclusion at the level of whether each background belongs in the live register.

You are **not** the Reviewer C granularity/interaction reviewer.

Do not decide:
- final background split/merge structure;
- background interaction matrix;
- discriminator tiers/direction rules;
- source-plan sufficiency;
- coverage-map certification;
- candidate truth;
- resurrection outcome.

## 4. Candidate review tasks

For every status-bearing candidate:

- R-PHYS
- R-TRANS
- V
- H-IND
- H-SOC
- L
- S1
- S2
- S3
- F
- C-HET-IND
- C-HET-SOC

determine whether it satisfies Protocol B1:

1. relevant;
2. materially distinct;
3. specified enough to generate truth-relevant consequences;
4. not subsumed by another candidate;
5. traceably formulable.

Specifically attack:

- R-PHYS vs R-TRANS overlap;
- R-TRANS vs V overlap;
- V vs H overlap;
- H-IND vs H-SOC overlap;
- H vs L overlap;
- S1/S2/S3 distinctness;
- F vs L/H/C-HET overlap;
- C-HET-IND/SOC vs H+L union/subsumption;
- whether any candidate is so weakly formulated that it should instead be excluded or retained only as a proposition-level rival;
- whether any major serious candidate class from your original blind elicitation disappeared without a valid reason.

## 5. Exclusion review

Review each proposed exclusion:

### X-NONHISTORICITY-AS-FULL-CANDIDATE
Proposed:
- exclude as full Q1 candidate;
- retain as node-level rival on P-HIST-JESUS/P-CRUC.

Decide whether this is legitimate scope control or artificial narrowing.

If legitimate, explicitly state whether P-HIST-JESUS may be treated as SHARED_FLOOR **after** this B4 exclusion freezes, assuming all admitted candidates require it under the same truth conditions.

### X-Q2-DIVINE-AGENT
Proposed:
- defer to a separate study.

### X-FREEFORM-COMPOSITE
Proposed:
- exclude.

### X-BODY-DISPOSITION-ONLY
Proposed:
- not a full causal candidate.

### X-MIXED-DECEPTION-SINCERITY-COMPOSITE
Proposed:
- do not admit in this cycle;
- route later need to REVISED_CANDIDATE_REQUIRED.

Pay special attention to this one. Determine whether excluding mixed deception+sincerity creates a meaningful candidate-universe hole or is a defensible anti-tailoring boundary.

### X-ARBITRARY-SPECULATIVE-MODELS
Proposed:
- exclude unless they satisfy the SERIOUS_RIVAL rule.

For every exclusion return:
- `ADMIT`
- `EXCLUDE_SUBSTANTIVE`
- `EXCLUDE_OUT_OF_SCOPE`
- `RETAIN_AS_NODE_OR_RIVAL_ONLY`
- `REPAIR_BEFORE_DECISION`

with reason.

## 6. Background admission review

Review BGD-1 through BGD-10 only for:

- coherence;
- material relevance;
- serious representation/independently defensible argument;
- whether it is already defeated by an independent constraint;
- whether it is a background rather than merely a disguised evidence proposition.

For each return:
- `ADMIT`
- `EXCLUDE`
- `ADMIT_CONDITIONALLY`
- `MOVE_TO_EVIDENCE_PROPOSITION`

Do not perform final split/merge or interaction testing; flag those to Reviewer C.

Pay special attention to BGD-3/4/5/6/7/8/10, which are partly empirical and therefore must not be kept alive after their defining empirical premises fail.

## 7. Outcome-material symmetry attacks

Try to:

- make a candidate easier to keep alive by defining it more weakly than rivals;
- let R umbrella benefits survive submodel failure;
- let S submodels trade propositions;
- let C-HET become a catch-all;
- let a confessional candidate enter on tradition alone;
- let a naturalistic candidate enter as the default ordinary explanation without independent formulation/mechanism burden;
- exclude a minority but serious model merely because it is unpopular;
- admit arbitrary speculation merely to claim completeness.

## 8. Required report structure

Use exactly:

1. **SESSION / SOURCE IDENTITY**
2. **DISPOSITION**
3. **CANDIDATE ADMISSION TABLE**
4. **CANDIDATE OVERLAP / SUBSUMPTION**
5. **EXCLUSION REVIEW**
6. **P-HIST-JESUS SHARED-FLOOR DECISION**
7. **BACKGROUND ADMISSION TABLE**
8. **SYMMETRY ATTACK RESULTS**
9. **REQUIRED REPAIRS**
10. **FINAL B4/A8 DECISION**

Final disposition exactly one:

- `B4_A8_PASS`
- `B4_A8_PASS_WITH_REPAIRS`
- `B4_A8_REPAIR_REQUIRED`
- `INVALID_REVIEW`

The final decision must answer:

> Is the repaired candidate/background admission set sufficiently complete, symmetric, and bounded to freeze candidate admissions/exclusions and proceed to steelman-packet construction, without beginning G1 evidence acquisition?

Do not modify the repository.
Do not search evidence.
Do not authorize G0 or G1.
Do not judge whether the resurrection occurred.

**STOP.**
