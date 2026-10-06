I'll fetch the branch and read the named prompt first. It should set the boundaries for what else I may open.

The prompt names six pinned sources. I'll verify the four branch blobs, then re-check the Protocol and Governance blobs, which I already verified earlier in this session.

All six pinned identities match. I'll read the four study artifacts now.

I'll open just the C-HET module map, since I need its P-CHET-* ID definitions to assess subsumption, while keeping to the six permitted sources.

# TFP-STRESS-2 — Reviewer A Final Candidate / Background Admission Review (B4/A8)

## 1. SESSION / SOURCE IDENTITY

- **Provider and model:** Anthropic, `claude-sonnet-5-5`.
- **Session:** `session_012EWsCBUVctdyhhk3v5ZxuF`, the same session as the prior Reviewer A blind elicitation and the Protocol 0.1.7 qualification audit.
- **Reviewer B's report or reasoning:** I have not seen it. The branch file listing showed its filenames, and I opened none of those files.
- **Pinned identities:** all six match.

| Source | Blob |
|---|---|
| Preregistration 0.1.2 | `5c94f11a…` |
| Candidate register | `c993f987…` |
| Background register | `ff98e574…` |
| Q1 event control | `f2d71f6d…` |
| Protocol 0.1.7 (commit `b9854f85…`) | `0d9406d9…` |
| Governance 0.1.5 (commit `b9854f85…`) | `02338ce3…` |

- **One extra read, disclosed:** I also read `TFP_STRESS_2_C_HET_MODULE_MAP_0_1_0.yaml`. The prompt allows this where needed to understand an ID named in the register. I needed it to judge whether `P-CHET-*` is subsumed by H+L.
- **Not opened:** the coverage map, source plan, ledger, role architecture, Reviewer B artifacts, my own blind report, and any web or literature source.
- **Anchoring note:** I authored the blind elicitation that fed this register. This review is therefore partly self-referential on the question "did anything disappear". The program lead's artifact is the check on that.

## 2. DISPOSITION

**`B4_A8_REPAIR_REQUIRED`**

- The candidate universe is broadly right. No major serious class from my blind elicitation disappeared without a stated reason, and the exclusions mostly stand.
- The register is not yet bounded enough to freeze. The problems are structural, not about who is in the field:
  - **Overlap:** candidates are defined through one causal-role ladder (PRIMARY or NECESSARY_CONTRIBUTING) that lets several candidates be true at once.
  - **S2 specification:** S2 fails B1.3 as written.
  - **R split:** the R split is likely to produce false underdetermination and an asymmetric truth-warrant burden.
  - **Backgrounds:** half of the background register is evidence propositions presented as backgrounds.
- The repairs are targeted, and a narrow re-review should suffice.

## 3. CANDIDATE ADMISSION TABLE

B1 criteria are (1) relevant, (2) materially distinct, (3) specified enough to generate truth-relevant consequences, (4) not subsumed, (5) traceably formulable. ✓ = pass, ⚠ = passes only if the repair named in the right-hand column is applied.

| ID | 1 | 2 | 3 | 4 | 5 | Disposition |
|---|---|---|---|---|---|---|
| R-PHYS | ✓ | ✓ | ✓ | ⚠ | ✓ | ADMIT with RR-2 |
| R-TRANS | ✓ | ⚠ | ⚠ | ⚠ | ✓ | ADMIT with RR-2 and RR-8 |
| V | ✓ | ✓ | ✓ | ✓ | ✓ | **ADMIT**, with notes below |
| H-IND | ✓ | ⚠ | ⚠ | ⚠ | ✓ | ADMIT with RR-1 |
| H-SOC | ✓ | ⚠ | ⚠ | ⚠ | ✓ | ADMIT with RR-1 |
| L | ✓ | ⚠ | ✓ | ⚠ | ✓ | ADMIT with RR-1 and RR-4 |
| S1 | ✓ | ✓ | ⚠ | ✓ | ✓ | ADMIT with RR-3 |
| S2 | ✓ | ✓ | ✗ | ⚠ | ✓ | **Demote to node-level rival unless RR-3 is applied** |
| S3 | ✓ | ⚠ | ⚠ | ⚠ | ✓ | ADMIT with RR-3 |
| F | ✓ | ⚠ | ✓ | ⚠ | ✓ | ADMIT with RR-4 |
| C-HET-IND | ✓ | ✓ | ✓ | ⚠ | ✓ | ADMIT with RR-1 |
| C-HET-SOC | ✓ | ✓ | ✓ | ⚠ | ✓ | ADMIT with RR-1 |

**Notes**
- **V:**
  - It is distinct, and "cause unresolved" is acceptable because Q2 is deferred.
  - Its distinctness from R-TRANS rests on EMB-1, which is a metaphysical criterion with thin evidential routes. That is a feasibility issue for Reviewer C, not an admission defect.
  - The non-theistic survival variant stays conditional on BGD-1.
- **S2 (fails B1.3):**
  - Its core says only that "a separately specified later belief/encounter process" generated the proclamation.
  - That leaves the origin mechanism unspecified, which makes S2 "substitution × any origin": an open composite, which X-FREEFORM-COMPOSITE bars.
- **S1 and S3:** both require encounter with a surviving Jesus.
- **S3:**
  - It says "post-rescue encounter or knowledge process" (a disjunction).
  - It also omits `P-CRUC`, so it never says whether Jesus was crucified.

## 4. CANDIDATE OVERLAP / SUBSUMPTION

**R-PHYS vs R-TRANS**
- R-TRANS is satisfied "without requiring material continuity". If "transformed" is not a positive requirement, every R-PHYS world is an R-TRANS world.
- R-TRANS is then the generic embodied-event candidate and R-PHYS is a stricter special case.
- The "no borrowing" rule then bars R-TRANS from using evidence that logically bears on it, which is incoherent for nested hypotheses.
- **Defect:** the relation (mutually exclusive or nested) is not stated.
- **Second defect, which would bias against an affirmative answer:**
  - Truth-warrant requires every necessary proposition of the attached candidate to be SUPPORTED.
  - Each R submodel's distinctive proposition (continuity or transformation) is hard to establish.
  - R_EVENT's own conjuncts could all be SUPPORTED while neither submodel is truth-warrantable. The Q1 table would then yield `NOT_TRUTH_WARRANTED` for a proposition that is in fact warranted.
- **Sibling competition:**
  - N3 row 9 requires the winner to dominate every other ranking-eligible candidate. R-PHYS and R-TRANS could both beat all non-R candidates yet be unseparable.
  - That produces `UNDERDETERMINED` for Q1 purely from the submodel split.

**R-TRANS vs V**
- The boundary is formally clean: EMB-1 to EMB-3 partition real-referent worlds, and V is "fails EMB-1 or EMB-2".
- The criteria text for EMB-2 reads "the postmortem body **is attributed** determinate spatiotemporal location…". That mixes a source attribution with an ontological criterion, so EMB-2 can be satisfied by a source's claim.
- **Defect:** this needs to be ontological ("has…").
- **Uncovered case:** if EMB-3 fails, you have a real referent that is neither R nor V (see `X-REAL-REFERENT-NONIDENTITY` in section 5).

**V vs H:** distinct on `P-V-REAL-REFERENT` vs `P-H*-NONVERIDICAL`. No overlap.

**H-IND vs H-SOC**
- Neither forbids the other mechanism being NECESSARY_CONTRIBUTING, so both can be satisfied by an individual-seed-then-social-spread world.
- H-SOC reads "experience-**report** formation". If that means reports formed without experiences, H-SOC collapses into L or F.
- **Defect:** H-SOC must require genuine non-veridical experiences, not only reports.

**H vs L**
- L requires experience to be "secondary or non-primary".
- Under the ladder, NECESSARY_CONTRIBUTING is also non-primary.
- A world with NC experience and PRIMARY interpretation satisfies both H and L.
- **Defect:** L's `P-L-EXPERIENCE-NONPRIMARY` is not tied to the ladder.

**S1 / S2 / S3**
- The three are distinct on necessary propositions (natural survival; substitution; nonordinary rescue).
- S1 and S3 share every Q1-relevant consequence. They differ only by causal class, which is a Q2-type dimension.
- R and V, by contrast, are not split by cause. This is an asymmetry in granularity.
- The traditional Islamic formulation (substituted victim plus divine raising, with the Christian proclamation arising by error) needs `P-S2-NOT-CRUCIFIED` **and** `P-S3-RESCUE`. Neither unit can state it alone, so the S units can only represent it by trading propositions.
- A frozen, closed definition of what counts as "died" (versus "apparently died and survived") is missing. Without it the S1 / R-PHYS boundary is manipulable.

**F vs L / H / C-HET**
- F's boundary with L is the intent to deceive, and with H and C-HET is the stratum and whether sincere experience is also necessary.
- C-HET forbids `FABRICATION`, but `FABRICATION` is undefined. It could cover either deliberate invention of later narrative (which should be M-NARR) or only founding-stratum deception.
- L and H do not forbid fabrication at all.

**C-HET vs H+L**
- The module map says "H alone treats the experiential process as sufficient". The register does not say this of H: it allows NC.
- With H-IND's ladder value NC, C-HET-IND is a special case of H-IND.
- **Defect:** the register and module map conflict.
- The module map itself is well bounded: closed module list, forbidden modules, no optional modules, and no unlisted interactions.
- Both C-HET variants forbid the other experience module. The seed-then-spread pattern (individual vision, social amplification) therefore has no home: it is excluded from both H units as non-exclusive and from both C-HET variants as forbidden. That is arguably the most prominent naturalistic mechanism family.

## 5. EXCLUSION REVIEW

| Exclusion | Decision | Reason |
|---|---|---|
| X-NONHISTORICITY-AS-FULL-CANDIDATE | **RETAIN_AS_NODE_OR_RIVAL_ONLY** | Legitimate scope control, not artificial narrowing. See below and section 6. |
| X-Q2-DIVINE-AGENT | **EXCLUDE_OUT_OF_SCOPE** | Defer. Q2 needs its own candidates, backgrounds and discriminators, as I recommended blind. Condition: S3's "nonordinary" cause and BGD-2's theistic variant must not smuggle Q2 attribution into Q1. |
| X-FREEFORM-COMPOSITE | **EXCLUDE_SUBSTANTIVE** | Violates candidate freeze (B5). C-HET already supplies the frozen, bounded composite. |
| X-BODY-DISPOSITION-ONLY | **RETAIN_AS_NODE_OR_RIVAL_ONLY** | Not a causal origin explanation. It stays as proposition-level rivals on tomb and body claims. Confirm the coverage map keeps those rivals live. |
| X-MIXED-DECEPTION-SINCERITY-COMPOSITE | **EXCLUDE_SUBSTANTIVE**, with conditions | See below. |
| X-ARBITRARY-SPECULATIVE-MODELS | **EXCLUDE_SUBSTANTIVE** | Fails the SERIOUS_RIVAL rule. This is the right test, not popularity. |
| **New:** X-REAL-REFERENT-NONIDENTITY | **RETAIN_AS_NODE_OR_RIVAL_ONLY** | A real referent that fails EMB-3 (misidentified living person, impersonating agent). It is covered by neither R nor V. Keep it as a rival on `P-V-IDENTITY-JESUS` and the EMB-3 test rather than as a candidate. It is not on the register's list. |

**Nonhistoricity.** I judge it legitimate scope control, for four reasons:
1. Q1 presupposes the subject, and the preregistration expressly excludes a global historicity study.
2. The rival is not suppressed. The shared-floor map defeats every candidate if `P-HIST-JESUS` is CONTRADICTED, and blocks truth-warrant if it is below SUPPORTED.
3. A full nonhistoricity candidate would answer a different question and need an evidence domain far outside the event window.
4. It has no necessary propositions about the post-crucifixion event, so event discriminators could not compare it.

**X-MIXED.** Excluding it is a defensible boundary, not a meaningful universe hole, on these grounds:
- The serious scholarly hybrid is sincere experience plus later legendary embellishment, which C-HET covers with later embellishment in M-NARR.
- Pure deception is covered by F.
- I know of no determinate, independently formulated model in which founding-stratum deliberate fabrication and necessary sincere experience co-occur.
- It therefore likely fails SERIOUS_RIVAL, which makes this an `EXCLUDE_SUBSTANTIVE` outcome rather than a pragmatic deferral.

The register's stated reason ("risk of post-hoc flexibility") is a convenience reason, not a SERIOUS_RIVAL finding. That matters because TRUTH_WARRANTED condition 11 requires every serious rival to be compared or shown inadequate. An unadmitted serious rival would either permanently block TRUTH_WARRANTED or be dismissed without a packet. The following are required:
- Record the SERIOUS_RIVAL-failure grounds as the B4 determination.
- Define `FABRICATION`.
- Add the exclusivity rules in RR-1.
- State that the REVISED_CANDIDATE_REQUIRED route remains available.

## 6. P-HIST-JESUS SHARED-FLOOR DECISION

**Yes.** After the nonhistoricity exclusion freezes, `P-HIST-JESUS` may be SHARED_FLOOR, on these conditions:

- **(a)** All 12 candidates list it with the identical text (verified from the register's shared definition).
- **(b)** The exclusion is recorded with its reason and is C4-controlled.
- **(c)** It keeps a direct evidence route and a steelman-quality formulation of the nonhistoricity rival, even though NONCOMPARATIVE_SHARED_FLOOR does not itself require a route. Truth-warrant needs SUPPORTED, so a sufficiency record is required anyway.
- **(d)** `P-CRUC` is **not** shared floor, because S2 denies it and S3's position is unstated.
- **(e)** The classification stays frozen against this candidate set.
- **(f)** The Q1 answer table must say how a shared-floor `P-HIST-JESUS` that is EVIDENCE_AGAINST or CONTRADICTED is reported. Q1's four conjuncts omit it, so a "relatively supported" answer could otherwise coexist with a failed node in the chain.

**Related defect.** `P-EARLY-PROCLAMATION-EXISTENCE` is labelled PROVISIONAL_SHARED_FLOOR, but S1, S2 and S3 omit it from their necessary lists. That fails the shared-floor condition as written. Either add it to the S units or reclassify it.

## 7. BACKGROUND ADMISSION TABLE

The test applied is whether the item is a framework (a background) or a disguised evidence proposition: a claim the study's own lanes must adjudicate with dispositions. The protocol's own rule is that empirical uncertainty is propagated through confidence and sensitivity (A14). It should not be turned into FRAMEWORK_DEPENDENCE, which the Protocol reserves for genuine framework flips.

| BGD | Decision | Reason and flags |
|---|---|---|
| BGD-1 ontology | **ADMIT** | Genuine worldview framework. Fix the typo `NONTHETIC` and the placeholder condition "if seriously formulated": it needs formulation criteria stated before freeze. |
| BGD-2 prior/likelihood | **ADMIT_CONDITIONALLY** | The theistic-likelihood variant must be restricted to anomalous postmortem events in general. It must not use Jesus-specific claims, which are out of scope. Flag to C: possible redundancy with BGD-1 and BGD-10. |
| BGD-3 historiographical method | **ADMIT_CONDITIONALLY** | Methods are real backgrounds, but the variants are not mutually exclusive, and the "eyewitness-oriented" variant carries a contested empirical premise about source authorship. Each variant must state its weighting rule on named inferences. Empirical premises must become evidence propositions so retirement follows a disposition, not a judgment. |
| BGD-4 dating/dependence | **MOVE_TO_EVIDENCE_PROPOSITION** | Dating ranges, authorship and dependence are source-critical facts to be dispositioned in the textual lane, with sensitivity propagated through confidence. Flag to C: only genuine paradigm-level choices might remain, if any. |
| BGD-5 experiential capacity | **MOVE_TO_EVIDENCE_PROPOSITION** | Its two variants are rival answers to `P-HIND-/P-HSOC-MECHANISM-SUFFICIENT`, which are already necessary propositions. A background version double-counts them. A re-scoped "transfer standard for modern psychological findings" could remain as a methodological background. |
| BGD-6 crucifixion/burial | **MOVE_TO_EVIDENCE_PROPOSITION** | Its variants are answers to `P-DEATH`, `P-S1-NONDEATH` and `P-RPHYS-CONTINUITY`, the very propositions it lists. |
| BGD-7 Second Temple concepts | **MOVE_TO_EVIDENCE_PROPOSITION** | Concept availability and content are textual and historical propositions (`P-EARLY-PROCLAMATION-CONTENT`). |
| BGD-8 Pauline body reading | **MOVE_TO_EVIDENCE_PROPOSITION** | The register itself says it affects only what a source claims. Competing readings are handled in the interpretive sufficiency template ("serious rival readings"). |
| BGD-9 testimony epistemology | **ADMIT_CONDITIONALLY** | A genuine philosophical background. The variant `OTHER_SERIOUS_TESTIMONY_MODEL` is an unnamed placeholder and must be named or removed. The proposition ID `H_MECHANISM` is undefined in the candidate register. |
| BGD-10 reference class | **ADMIT_CONDITIONALLY** | Reference-class choice is a real framework issue. Frequencies within a class are evidence propositions. `ANOMALOUS_POSTMORTEM_CLAIM_REFERENCE_CLASS` is ontology-laden, which interacts with BGD-1. |

**Candidate omission to raise.** The Q1 control's EMB-1 (bodily subjecthood) and EMB-3 (personal identity) depend on a metaphysics of embodiment and identity (constitution, dualist, psychological-continuity, animalist, replica accounts). No background carries this, so the study's own criteria act as a silent default. I recommend adding it as a background or an explicit dimension of BGD-1.

**Flags to Reviewer C, not decided here**
- The required initial interaction sets cite BGD-4, 5, 7 and 8, which move.
- BGD-1, 2, 9 and 10 overlap heavily as inputs to one prior-and-likelihood inference.
- The split/merge for BGD-3 variants is outstanding.

## 8. SYMMETRY ATTACK RESULTS

| Attack | Result |
|---|---|
| Define a candidate more weakly than rivals | **Partly succeeds.** S2 fails B1.3, and H and L are thinner than C-HET (which carries body and narrative propositions). Every unit needs a packet-stated body-disposition expectation, so that silence is justified, not free. |
| R umbrella survives submodel failure | **Blocked** for ranking: umbrellas are non-status-bearing. **Residual:** nesting and the sibling-competition and truth-warrant issues in RR-2. |
| S submodels trade propositions | **Partly succeeds** (Islamic native formulation; S1 and S3 share encounter evidence; the P-DEATH definition). The evidence-binding rule helps. |
| C-HET becomes a catch-all | **Blocked** by the closed module map, forbidden modules and no optional modules. **Residual:** the register and map conflict on H; the seed-then-spread gap. |
| Confessional candidate enters on tradition alone | **Blocked.** R is written in neutral Q1 terms, with no authority commitments. The packet must still supply proponent-recognizable expected evidence (not a diluted R). |
| Naturalistic default without mechanism burden | **Mostly blocked** by `P-*-MECHANISM-SUFFICIENT` and "independently warranted" wording. Closed mechanism lists per H unit are needed before G1. |
| Exclude a serious minority model because it is unpopular | **Blocked.** Nonhistoricity is handled at node level for structural reasons. X-MIXED is re-grounded on SERIOUS_RIVAL. S units and V are admitted. |
| Admit arbitrary speculation for completeness | **Blocked** by the X-ARBITRARY rule. |

**Cross-reviewer flag (outside my remit)**
- The Q1 answer table lets any UNDERDETERMINED base outcome pre-empt every later row (row 2).
- The negative side has many sibling units (H-IND, H-SOC, L, F, C-HET-IND, C-HET-SOC, S1–S3, V). Their inseparability can produce `UNDERDETERMINED` even where every R submodel is defeated by evidence.
- That would give a Q1 answer of "undetermined" instead of "evidence against". Reviewers B and C should consider whether this is the intended mapping.

## 9. REQUIRED REPAIRS

- **RR-1 (candidate partition and mechanism closure).** Add a frozen causal-profile table giving each unit's allowed ladder values for every mechanism module (individual experience, social experience, interpretive, fabrication, narrative). It must make H-IND, H-SOC, L, F and C-HET non-overlapping and reconcile the register with the module map. It must also:
  - give the seed-then-spread pattern an explicit home or an explicit exclusion with reasons;
  - require H-SOC to include genuine experiences and not only reports;
  - freeze a closed mechanism list per H unit.
- **RR-2 (R split).** State the R-PHYS / R-TRANS relation (mutually exclusive or nested), define "transformed" or make R-TRANS the generic R candidate, add a sibling non-rivalry rule for N3 dominance, and ensure truth-warrant can attach to the Q1-positive candidate. Prefer redefining R-TRANS as the generic embodied candidate, which needs no new unit.
- **RR-3 (S family).** For S2, either freeze a closed origin mechanism or demote it to a node-level rival. For S3, remove the "or" disjunction and state its position on `P-CRUC`. Make S2 and S3 able to state the Islamic native formulation without borrowing propositions. Freeze an operational definition of P-DEATH. Add `P-EARLY-PROCLAMATION-EXISTENCE` to S1–S3 or reclassify it. State S3's falsifiability, meaning what death evidence it accepts.
- **RR-4 (F boundary).** Define `FABRICATION`. Decide whether later deliberate narrative invention is M-NARR or F, and set the F / L boundary by stratum and by actor knowledge. Add the SERIOUS_RIVAL grounds for the X-MIXED exclusion.
- **RR-5 (exclusion register).** Add `X-REAL-REFERENT-NONIDENTITY`. For every exclusion, record substantive versus out-of-scope and the independent reviewer disposition (B4).
- **RR-6 (shared floor).** Apply conditions (a)–(f) from section 6.
- **RR-7 (backgrounds).** Re-file BGD-4, 5, 6, 7 and 8 as evidence propositions; resolve the BGD-1, 2, 3, 9 and 10 conditions; fix the typos and placeholders; decide whether to add the embodiment/identity background.
- **RR-8 (EMB-2 wording; for Reviewer B and the program lead).** Replace "is attributed" with an ontological formulation.

## 10. FINAL B4/A8 DECISION

**`B4_A8_REPAIR_REQUIRED`**

> Is the repaired candidate/background admission set sufficiently complete, symmetric, and bounded to freeze candidate admissions/exclusions and proceed to steelman-packet construction, without beginning G1 evidence acquisition?

**Not yet.**

- **Stable now:**
  - Admission of V.
  - Admission of R, H-IND, H-SOC, L, S1, S3, F and C-HET as formulated, subject to the RR items above (the repairs should not change who is in the field).
  - The decisions on X-Q2, X-FREEFORM, X-BODY, X-ARBITRARY and nonhistoricity (with conditions).
- **Not yet freezable:** S2, the R submodel structure, the H, L, F and C-HET partition, and the background register.
- **Next step:** apply RR-1 to RR-8 and return the artifacts for a narrow re-review. Blind elicitation need not be repeated.
- **Out of scope here:** this review does not authorize G0 or G1, and it makes no judgment on whether the resurrection occurred.

**STOP.**