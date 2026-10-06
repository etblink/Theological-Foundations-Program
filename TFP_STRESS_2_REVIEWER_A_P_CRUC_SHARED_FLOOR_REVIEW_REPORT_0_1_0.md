All nine identities match. I'll read the register first, which holds all 11 candidate definitions.

The Q1 control largely addresses P-CRUC failure, though there's a possible label gap I'll confirm against the coverage map. Next up: coverage map, node-rival packet, freeze 0.1.2, S3 amendment, and my own recorded S3 report.

The freeze records the node-rival packet blob. I'll compare that against the verified blob, then extract the P-CRUC and D0 entries from the large coverage map.

The coverage map still routes P-CRUC as COMPARATIVE_ROUTE through D0 for all 11 candidates. I'll look at its `P_CRUC_shared_floor_review` block and D0 definition.

I'll confirm the recorded copy of my S3 report matches what I issued, by checking its key lines.

# TFP-STRESS-2: Reviewer A P-CRUC Shared-Floor Review

## 1. SESSION / SOURCE IDENTITY

- **Provider and model:** Anthropic, `claude-sonnet-5-5`.
- **Session:** `session_012EWsCBUVctdyhhk3v5ZxuF`. This is the same Reviewer A lineage.
- **Reviewer B:** I have not seen Reviewer B's report or reasoning. The coverage map's `reviewer` block names Reviewer B's lineage ID, and I saw that identifier only.
- **Pinned identities:** all nine match.
  - Candidate register 0.1.6: `1a30cfd1…`
  - Q1 control 0.1.4: `0a47cb27…`
  - Coverage map 0.1.5: `442b4518…`
  - Node-rival packet 0.1.1: `3dfe39bc…`
  - Admission freeze 0.1.2: `d600ec44…`
  - S3 amendment: `e36a61d5…`
  - My S3 report as recorded: `42a00898…`
  - Protocol 0.1.7 and Governance 0.1.5, both at `b9854f85…`
- **Not opened:** the S2 amendment (read in my previous turn), external literature, the web, and later artifact versions.

## 2. DISPOSITION

**`P_CRUC_SHARED_FLOOR_APPROVED_WITH_LIMITATIONS`**

- The A6 definition is satisfied. P-CRUC may be classified `NONCOMPARATIVE_SHARED_FLOOR` against the exact 11-candidate universe.
- The approval carries **conditions precedent** (section 9). They must be recorded in the freeze amendment before freeze identities are fixed.
- I specify the exact text for each condition so the classification itself needs no further review.

## 3. A6 NECESSITY / IDENTICAL-TRUTH-CONDITIONS CHECK

**Necessary for every admitted candidate: `SATISFIED`.**
- I read each of the 11 cores, not just the proposition lists.
- R-TRANS, V, H-IND, H-SOC, H-SEED-SPREAD, L, F and the three C-HET units each say "Jesus was crucified…". Their `P-DEATH` is defined "in connection with the outcome-material crucifixion event attributed to Jesus", so `P-DEATH` itself presupposes `P-CRUC`.
- S1 states `P-CRUC` explicitly ("crucified but survived").
- The operational test is met: without it each candidate would cease to be that candidate and lose a truth claim the study needs.

**Materially the same truth conditions: `SATISFIED`.**
- There is one shared text: "Jesus himself underwent the outcome-material Roman crucifixion event attributed to him."
- It appears identically across all 11. The candidates differ on what followed, not on this event or its subject.
- Minor note: "outcome-material" is the same phrase used in the `P-DEATH` definition and is never separately defined. It is identical across candidates, so this is not a defect.

## 4. CONDITIONS (a)-(g)

| Condition | Status | Notes |
|---|---|---|
| (a) identical necessity | **CLOSED** | All 11 verified from the cores. |
| (b) amendment control | **CLOSED** | S2 and S3 amendments are `APPROVED_FOR_USE__PRE_EVIDENCE` with C4 class, direction classification and ledger references. The escape model is recorded in the S3 amendment, and freeze 0.1.2 supersedes 0.1.1. Pointer note: the S2 amendment still says P-CRUC "remains non-shared because S3 still denies it". It is a frozen historical record, superseded by the S3 amendment and freeze 0.1.2, and should carry a pointer to them. |
| (c) serious node rivals preserved | **PARTIAL** | Direct route and sufficiency record are required, and condition-11 control is present. The packet is thin as a steelman. See the notes below. |
| (d) P-DEATH non-shared | **CLOSED** | S1 denies it. The register classifies it `NOT_SHARED_FLOOR`, and the Q1 control's `denied_by` lists S1 only. |
| (e) frozen candidate set | **PARTIAL** | The coverage map's review block says the classification is "frozen against exact 11-candidate set". But the node family's `reopen_if` allows a new full candidate that denies P-CRUC. No rule says that admission reopens this classification. |
| (f) Q1 failure handling | **PARTIAL** | Rows 1 and 2 cover P-CRUC as an affirmative R conjunct. Row 3 and the `shared_floor` list name only P-HIST-JESUS and P-EARLY-PROCLAMATION-EXISTENCE (see below). |
| (g) revised-candidate fallback | **PARTIAL** | The fallback is preserved in the register, the packet and the amendment, but triggered only "if outcome-material". The trigger is not tied to P-CRUC outcomes. |

**(c) notes**
- The packet's variants carry short formulations only. They omit the rival's native argument forms that I and the S2 amendment required preserving: no disciple-eyewitness, misidentification, and doubt/assumption.
- It has no expected or weakening evidence per variant.
- It has no slot for an equal-strength review. The affirmative side has expected and weakening evidence in the coverage map, so the rival's expectations must be registered before exposure, or the P-CRUC test is asymmetric.
- Under shared floor this test is the **only** place the non-crucifixion family is ever tested, so its quality matters more.

**(f) note.** Under the current table, a below-SUPPORTED P-CRUC with tied rivals can produce `UNDERDETERMINED` (row 6). The same shortfall in P-HIST-JESUS or P-EARLY-PROCLAMATION-EXISTENCE produces `R_EVENT_NOT_WARRANTED` (row 3). The inconsistency affects the plain-language label, not eligibility.

## 5. SHARED-FLOOR OUTCOME MAP

The Protocol's A12 shared-floor map applies unchanged. I checked each of your four non-implications.

- **Weak P-CRUC evidence is ignored:** No.
  - SUPPORTED permits no ranking effect and may satisfy the shared truth-warrant condition.
  - PARTIALLY_SUPPORTED, PLAUSIBLE_BUT_UNATTESTED, NOT_ESTABLISHED, UNDERDETERMINED or proposition-level INSUFFICIENT_SIGNAL leaves ranking unaffected and blocks TRUTH_WARRANTED for all dependent candidates.
  - Q1 rows 4 and 5 require SUPPORTED.
- **Node rivals disappear:** No. They are tested directly at P-CRUC, with condition-11 control.
- **A contradicted P-CRUC permits a winner:** No.
  - CONTRADICTED makes every dependent candidate INADEQUATE_BY_EVIDENCE, so N3 gives NONE_ADEQUATE under adequate coverage.
  - Q1 row 2 reports `R_EVENT_EVIDENCE_AGAINST`.
- **Ranking converted into a truth verdict below SUPPORTED:** No, with one reporting condition. A relative label such as BEST_SUPPORTED among the 11 is "conditional on a shared-floor P-CRUC of [disposition]" (condition 5 in section 9).

**One back-door hazard found.**
- `P-DEATH` embeds `P-CRUC`, and the lane chain rule says a chain "cannot exceed its weakest necessary link".
- If `P-DEATH` inherited a weak `P-CRUC`, a NOT_ESTABLISHED P-CRUC would make `P-DEATH` ranking-blocking for the ten candidates that require it.
- S1 denies `P-DEATH`, so a P-CRUC shortfall could leave S1 the only ranking-eligible candidate.
- That is a shared-floor proposition selecting a candidate, which the shared floor must never do.
- Condition 1 in section 9 closes it.

## 6. Q1 / REVISED-CANDIDATE CONSEQUENCE

- **A. SUPPORTED P-CRUC: YES.** Ordinary candidate comparison proceeds, subject to every other control.
- **B. Below SUPPORTED, not against: YES** (with the condition-2 label fix).
  - Relative ranking proceeds under the shared-floor map.
  - R_EVENT truth warrant stays blocked (rows 4 and 5 need SUPPORTED, and TRUTH_WARRANTED condition 4 blocks it).
  - Row 3 should also name P-CRUC, so the label is consistently `NOT_WARRANTED` and not `UNDERDETERMINED`.
- **C. EVIDENCE_AGAINST P-CRUC: YES.** Q1 row 2 gives `R_EVENT_EVIDENCE_AGAINST`, and truth warrant is blocked. The node rival stays live, and shared-floor MATERIAL_DEFEATER status applies.
- **D. CONTRADICTED P-CRUC: YES.** All 11 candidates become INADEQUATE_BY_EVIDENCE. The study must not manufacture a winner from the frozen set.
- **E. Revised candidate: YES.** The study routes to `PROPOSED_REVISED_CANDIDATE_REQUIRED_WITHIN_SCOPE` and does not treat the node rival as a full candidate. The trigger should be explicit for P-CRUC outcomes (condition 5).

## 7. COVERAGE-MODE DECISION

**`NONCOMPARATIVE_SHARED_FLOOR`**

- `D0-CRUCIFIXION-ATTRIBUTION` remains a **node-rival evidential discriminator and sufficiency control** on P-CRUC.
- It is **not** a candidate-selecting comparative route. No candidate pair differs on P-CRUC any more, so D0 compares the affirmative claim to a node rival, not two candidates.
- It must not feed N2 Steps 2–3. In particular, it must not use the UNMAKEABLE-blocks-dominance rule, which would otherwise let a P-CRUC evidence problem block ranking, contradicting shared-floor design. Any D0 infeasibility is handled only through Q1 row 1.
- The coverage map still lists all 11 P-CRUC entries as `COMPARATIVE_ROUTE` with `direct_route: null`. That contradicts this classification and must change (condition 3).

## 8. NEW-DEFECT CHECK

- **Asymmetric reduction of the affirmative crucifixion burden:** none for R_EVENT. The Q1 table still demands SUPPORTED `P-CRUC`. The shared-floor design reduces only P-CRUC's effect on ranking among crucifixion-affirming candidates, which applies equally to all 11 and is bounded by the truth-warrant block and the conditional labelling.
- **Non-crucifixion rivals structurally erased:** no. The family is a live node rival with a direct route. Its founding mechanism is carried by the revised-candidate fallback.
- **Node-level evidence prevented from defeating P-CRUC:** no. The sufficiency record tests the rival directly, and EVIDENCE_AGAINST or CONTRADICTED remain reachable.
- **A12 vs Q1 contradiction:** the row-3 label gap (condition 2).
- **P-DEATH accidentally promoted:** no promotion. The inheritance hazard in section 5 is the related defect (condition 1).
- **Candidate-set circularity:** limited. The set was shaped by fidelity reviews and the classification follows from it. Condition 5 blocks silent reopening, and the node rival's retention plus condition-11 control prevents the removal from acting as defeat.
- **Suppression of REVISED_CANDIDATE_REQUIRED:** possible only through the discretionary trigger (condition 5).
- **Stale text:** the register's `shared_floor_conditions` for P-HIST-JESUS still says `P_CRUC_is_not_shared_floor: true`.

## 9. REQUIRED REPAIR

These are conditions precedent to recording the freeze. The text below can be applied verbatim.

1. **No inheritance of shared-floor shortfalls.** Add to the Q1 control and the coverage map: "Shared-floor propositions (`P-HIST-JESUS`, `P-EARLY-PROCLAMATION-EXISTENCE`, `P-CRUC`) are evaluated on their own sufficiency records. Every candidate-specific proposition, including `P-DEATH`, `P-S1-NONDEATH` and all `P-R-*` propositions, is evaluated conditional on the shared-floor propositions being true. A shared-floor shortfall is carried only by the shared-floor proposition and may not be inherited by, double-counted in, or used to lower any candidate-specific disposition, ranking-eligibility status or direction result. `P-DEATH` answers: given that Jesus underwent the crucifixion event, did he enter the death state as defined? At chain level the Q1 answer table alone applies the weakest-link rule."
2. **Q1 table.** Add P-CRUC to `q1_chain_prerequisites.shared_floor` (keeping it among the affirmative R conjuncts), and name it in row 3.
3. **Coverage map.**
   - Replace the 11 P-CRUC `COMPARATIVE_ROUTE` entries with one `NONCOMPARATIVE_SHARED_FLOOR` entry covering all 11.
   - Populate `direct_route` with the D0 node-rival route plus the sufficiency record.
   - Record D0 as a node-rival evidential and sufficiency control, excluded from N2 and from dominance-blocking.
4. **Node-rival packet.** Before the Wave-1 packet freeze, add:
   - per-variant expected and weakening evidence, registered before exposure;
   - the rival's native argument forms, as FORMULATION_ONLY: resemblance/misidentification, witness confusion and doubt/assumption, no disciple-eyewitness;
   - an equal-strength review slot for Reviewer B.
   - Loke's counter-arguments stay evidence-level and are not pre-applied.
5. **Fallback trigger and reporting rule.**
   - If P-CRUC is EVIDENCE_AGAINST or CONTRADICTED at node level, or node-rival evidence otherwise makes a no-crucifixion-plus-founding-mechanism model outcome-material, record `PROPOSED_REVISED_CANDIDATE_REQUIRED_WITHIN_SCOPE` alongside the base outcome.
   - Report any relative label among the 11 with the qualifier "conditional on a shared-floor P-CRUC of [disposition]".
   - Add: "This classification is frozen against the exact 11-candidate universe. Admission of any additional full candidate before G0 (including via a `reopen_if`) is a C4 amendment that reopens it."
6. **Mechanical.**
   - Update the register's `shared_floor_conditions` and the freeze record's P-CRUC block.
   - Add a pointer in the S2 amendment to the S3 amendment and freeze 0.1.2.
   - Supersede freeze 0.1.2 (as 0.1.3) when these are recorded.

## 10. FREEZE DECISION

> May P-CRUC now be frozen as NONCOMPARATIVE_SHARED_FLOOR against the exact 11-candidate G0 universe while preserving the full noncrucifixion node-rival family, its direct evidence/sufficiency route, TRUTH_WARRANTED condition 11, and the revised-candidate fallback?

**Yes, conditional on the repairs in section 9 being recorded in the same freeze amendment.**

- The A6 definition is met.
- No further review of the classification is needed if the specified text is applied.
- Reviewer B retains its later equal-strength and coverage review of the node-rival packet.
- This review assigns no historical disposition to P-CRUC, did not research whether Jesus was crucified, and does not authorize G0 or G1.

**STOP.**