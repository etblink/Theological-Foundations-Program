# TFP Adjudication Protocol 0.1.2: Focused Independent Re-Audit Report

Audited text: `TFP_ADJUDICATION_PROTOCOL_0_1_2.md` on `repair/tfp-adjudication-protocol-0.1.2`, read after the Charter, Governance, STATE and Method Seed in the required order. I read no prior audit, repair-control artifact or README. STATE.yaml itself names prior audit files and lists the 0.1.1 re-audit's MAJOR categories. I treated that only as metadata and made no use of it. I modified no files. Severity uses the Protocol §19 definitions; I found no mismatch with the prompt.

## 1. DISPOSITION
**`REPAIR_REQUIRED`**: 0 BLOCKING, 4 MAJOR, 13 MINOR.

## 2. EXECUTIVE FINDING
Most of 0.1.2 is well built and works as a cold-start system. Four real defects remain.

- The independence rules still allow a reviewer to become the auditor of their own outcome-material approvals.
- Admission of background registers has no criteria and no review.
- The post-freeze amendment gate omits outcome-controlling frozen items and conflicts with the lane-amendment rule.
- Discriminator tiers and the dominance rule use terms that never connect.

Each MAJOR can change an outcome label or let a candidate's result improve quietly. Under §0 step 2, qualification cannot proceed while a MAJOR is unresolved. The MINORs are mostly vocabulary and consistency gaps with small fixes. I did not count them as a collective threat on their own, since the MAJORs already require repair.

## 3. ROLES / AUTHORITY / INDEPENDENCE
**What works:** The four role definitions agree between Governance §3 and Protocol §0. G0 role freeze (A3) is present. Qualification is a human-owner act and does not authorize a stress test (§0, §24). The owner dual-role exception is cited correctly in §20. Governance and Protocol agree on the §22 precedence list.

**MAJOR-1: Reviewer-to-auditor self-review is not prevented.**
- Governance §3 (lines 108–125) and Protocol §0/O1 exclude from the strict auditor only the authors of the G0 preregistration, packets, lanes, synthesis and repair.
- Independent reviewers make outcome-determinative calls at G0 and G1. These include candidate exclusions (B4), the E3 judgment that no listed gap is likely to change a truth-critical disposition, amendment classification (C4), and nonmateriality of lane changes (K5).
- Nothing bars the same person or session from being the named strict auditor (A3 lists them separately but does not require disjointness).
- That auditor would then audit their own approvals under topics 2, 5, 6 and 7.
- The "independent reviewer" definition only says the reviewer is independent of the item reviewed. It does not say the auditor is independent of reviewer determinations.

**MINOR:**
- The dual-role exception covers only owner authorship of the synthesis (Gov §3 line 128; Protocol §20). An owner who also authors the preregistration, packets or lanes, or who authored the protocol they qualify, is not addressed.
- Protocol §0 step 1 says "independent protocol audit", but O1 imposes strictness only for adjudications. STATE next-action requires a strict auditor. The Protocol never says which standard applies to a qualification audit.

## 4. BACKGROUND / MIRACLE / REVELATION
**What works:**
- I1 is symmetric: it rejects the naturalist presumption, the supernaturalist presumption, and the gap-fallacy in both directions.
- The I3, I6 and I7 sequences are separated and complete.
- I4 requires running every truth-critical inference under each live register and bars `TRUTH_WARRANTED` and prescribes `FRAMEWORK_DEPENDENCE` on a flip.
- Priors are constrained (I5).
- Natural catch-alls must be specified before they can defeat a specified rival.

**MAJOR-2: The background register has no admission rule.**
- Candidates get symmetric admission (B1), blind elicitation (B2) and independent exclusion review (B4). Backgrounds get none of these.
- A8 and I4 depend on "serious live" backgrounds, but nothing defines seriousness, liveness, or who decides.
- The register fixes whether `FRAMEWORK_DEPENDENCE` triggers and whether `TRUTH_WARRANTED` is reachable. A narrow register manufactures robustness. A broad one forces fragility.
- No independent pre-evidence review of the register is required. Topic 11 tests robustness, not register construction.

**MINOR:**
- "Flips", "outcome changes" (F) and "robust" (N2 #8, truth-warrant condition 7) are used interchangeably and never operationalized. It is unclear whether a drop from `SUPPORTED` to `NOT_ESTABLISHED` with no ranking reversal counts.
- The Phase I trigger names "supernatural prophecy" while the A4 tag is `prophecy`. A tagger could avoid Phase I by calling a prophecy non-supernatural while the theological use depends on foreknowledge.
- Phase G has no template line mapping miracle or prophecy tags to mandatory elements.
- The named catch-all classes are only naturalistic. I1 covers the supernatural-unspecified case, so this is a clarity gap only.

**NOTE:** I4's exemption for "rival backgrounds independently rejected by canonical adjudication" is vacuous until a canonical adjudication exists (STATE `canonical_adjudications: []`).

## 5. LANE COMBINATION / INFERENTIAL BRIDGE
**What works:**
- L1–L5 give a defeater-first order, no vote-counting, a repetition-does-not-promote rule, a weakest-necessary-facet rule, and "what survived/changed" and dependence records.
- Without numerical scoring this is reproducible up to disciplined judgment. That is the carried limitation, not a defect.

**MAJOR-4: Discriminator tiers and the dominance rule do not connect.**
- A11 defines `CRITICAL`, `MATERIAL` and `CONTEXTUAL`, but only `CRITICAL` appears in N2 and N3. The other two tiers have no consequence anywhere.
- Dominance (lines 933–938) uses "makeable truth-critical comparison", which is neither a defined term nor mapped to the tiers.
- Two auditors could disagree on whether A dominates B when A leads on `CRITICAL` but trails on `MATERIAL` discriminators.
- This directly governs `BEST_SUPPORTED`, the most likely stress-test outcome.

**MINOR:**
- "Undefeated CRITICAL/MAJOR defeater" is used in `SUPPORTED`, L2 and truth-warrant #5, but defeater severity is undefined.
- "Direct vs indirect" and "sufficiently strong" (L3) are undefined.
- The L4 cumulative-fragility note has no decision consequence. Eight MODERATE links in the I3 chain can still produce `TRUTH_WARRANTED` with a note. Only a `LOW` link carries a consequence.
- The Q confidence anchors are defined for "result" but applied to nodes and arrows. How `SUPPORTED` relates to `LOW` confidence is not stated.
- `NONE_ADEQUATE` requires failing A12 (line 995), but A12 item 3 covers only prior canonical contradiction. If all candidates are contradicted within the study (N2 #1), no label fits.
- `CLOSEST_TO_TRUTH` can be earned on a one-proposition margin. Its approximate-truth assertion is weaker than its name implies.

## 6. AMENDMENT GATING
**What works:** C4 covers all eleven items the prompt lists and defines three classes. Post-evidence outcome-material changes are barred from improving a canonical result. Retyping is explicitly gated. K5 requires re-analysis and rerun.

**MAJOR-3: The gate is incomplete and internally inconsistent.**
- **(a) Unlisted frozen items.** Phase A freezes items C4 does not list:
  - A1 exact question and A2 scope;
  - A3 role matrix;
  - A5 link and arrow structure;
  - A13 expected, weakening and contradiction evidence;
  - A14 coverage target and underdetermination/insufficient-signal conditions;
  - A15 audit criteria;
  - the N3 shared proposition map ("frozen at G0" but absent from Phase A).

  Editing the A14 coverage target or A13 weakening evidence post-evidence can turn `COVERAGE_INCOMPLETE` into complete, or redefine what counts as weakening. That is a quiet improvement route.
- **(b) K5 conflicts with C4.** K5 says a material lane amendment is re-analyzed, re-frozen and rerun, which implies the result is usable. C4 says `POST_EVIDENCE_OUTCOME_MATERIAL` cannot improve a canonical result. A genuine lane error correction therefore has no determinate status.
- **(c) Adverse amendments.** The ban is one-directional ("cannot be used to improve"). A newly found defeater or rival background that worsens a result has no stated treatment.

**MINOR:**
- There is no evidence-exposure ledger, so `PRE_EVIDENCE_AMENDMENT` timing is unverifiable except by versioning.
- The protocol version a study runs under is not frozen at G0 and is not in the STATE schema. There is no protocol change-control rule.

## 7. AUDIT SEMANTICS
**What works:** Severity definitions are usable. The five audit outcomes are distinct. The O2 topic list is concrete, auditor disagreement and program-lead disagreement are handled (O4, O5), and repair and re-audit are specified (O6). `PASS_WITH_LIMITATIONS` is propagated into the acceptance record and STATE (O7).

**MINOR:**
- O2 has five statuses but no MINOR-level one. A topic with a MINOR defect can only be recorded as `PASS` or `LIMITATION`, and `LIMITATION` is defined as non-defect. Severity says a MINOR needs "repair or explicit limitation", which conflicts with that.
- `INSUFFICIENT_SIGNAL` has three meanings: an audit outcome, a proposition disposition and a study outcome. K6 uses `INVALID_COMPARISON` at G2, although it is defined as a G4 outcome. §23 says "the method fails" without a status mapping.
- The cold-start test is a mandatory topic (#17) and a G4 check. O8 says who performs it but not what it consists of or what passing means.
- The §23 anti-heuristic test is miscalibrated. For a binary question, any determinate result matches some listed slogan. Taken literally, only `UNDERDETERMINED` or `INSUFFICIENT_SIGNAL` escape without an "independent justification". It should test dispositions across the matrix, not one headline outcome.
- The gate map misassigns phases (see section 13).
- Protocol audits have no defined mandatory topics. O2 is written for study audits.

## 8. CANDIDATE / STEELMAN / CLAIM-TYPE
**What works:**
- B1–B7 are symmetric. Blind elicitation is required "where feasible", a major candidate class is defined, packets have defined contents, and exclusions are reviewed.
- Late and post-evidence candidates are labelled and barred from winning the same confirmatory study. Meta-outcomes are not candidates.
- The type set is expanded, with trigger tags and a typing freeze.
- C2 caps a claim at its weakest necessary component. C3 and Phase G block a faith commitment from public `SUPPORTED`. Retyping is gated.
- `SUFFICIENCY_RECORD` makes `SUPPORTED` auditable. Mandatory elements with `MET`/`NOT_MET`/justified `NOT_APPLICABLE` constrain expert judgment enough to avoid a free-standing assertion.

**MINOR:**
- Governance §9 (independent construction, freeze before comparative exposure) is not carried into B3, and there is no equal-strength check across packets.
- Governance §6 and the Method Seed list 10 claim types while A4 lists 17. A cold-start reader sees two lists.

**NOTE:** B2 asks for elicitation "without the initial candidate list", but A2 scope includes "traditions/candidates in view". The two conflict unless scope is stated generically.

## 9. PHILOSOPHY / SOURCE / CONTINUITY
**Phases H, I and J: satisfactory.**
- Premise-warrant categories, validity and strength, defeasible intuition, rival frameworks, theoretical virtues and sensitivity are all present.
- Phase J rejects earlier-is-better and later-is-worse, and handles dependence, preservation and independence.
- E4 and E5, L5, B7 and M cover the Method Seed's plausibility versus attestation, source proximity, survived/changed, and alternative-source rules.

**Phase M: satisfactory structurally.** It has C0–C7 as relation types, the patterns branching, convergence, loss, recovery, refunctionalization and discontinuity, the no-jump rule, and truth relevance.

**MINOR:**
- The independent-reinvention null is required in Method Seed §9 and STATE `methodology`, but the Protocol never operationalizes it. Only "parallel construction" and the no-jump rule partly cover it.
- Phase M lists C0–C7 names only, without definitions or a pointer to the Seed.
- The symmetry sentence (line 890) reads "face evidential burdens" with no "comparable" or "equal".

## 10. OUTCOMES / ACCEPTANCE / STATE
**What works:**
- `PROPOSED_` prefixing is correct. Truth-warrant conditions 11–12 are explicitly pending gates, not assumed facts.
- Single-proposition handling is present.
- Human acceptance (P1) and outcome promotion (P2) are specified.
- The P3 schema matches STATE `canonical_adjudication_schema` field for field.
- The legacy EMT rule (P4) matches STATE `legacy_state`. Program-level truth commitments are protected (P5).

**Defects:** see MAJOR-4 and the MINORs on `NONE_ADEQUATE` and `CLOSEST_TO_TRUTH` in section 5, and MINOR-11 in section 13. The Protocol does not say who edits STATE after acceptance. This is implicit in Governance §21 and minor.

## 11. UNCERTAINTY / STOP / REOPEN
**What works:**
- HIGH, MODERATE and LOW have anchors. The Q list is complete, and confidence and scope are separate.
- Stop requires a coverage record before low-information-gain applies (Q2), consistent with Governance §16.
- Every CLOSED or HELD study must define `reopen_if`, including philosophical defeaters. Flip conditions are recorded.

**Defects:** the confidence-anchor application gap (section 5) and the STATE stop-rule conflict (section 13).

## 12. COLD-START REPRODUCIBILITY
A competent researcher can determine, without lore:
- who authorizes, leads, reviews and accepts;
- how candidates enter and are steelmanned;
- what evidence to acquire and how coverage is judged;
- how propositions and arrows are disposed;
- how miracle, revelation and prophecy claims are treated;
- how provisional outcomes become canonical;
- what STATE records;
- when to stop and reopen.

A researcher **cannot** determine without lore:
- who may not both review and audit (MAJOR-1);
- which backgrounds qualify and who decides (MAJOR-2);
- which post-freeze edits are gated, or the status of a corrected lane (MAJOR-3);
- how discriminator tiers feed dominance (MAJOR-4);
- what the cold-start test and the anti-heuristic test consist of;
- how a MINOR defect is recorded.

## 13. REGRESSION FINDINGS
- **Gate map (lines 77–85).** G2 reads "F–L … continuity", but continuity is Phase M. G3 reads "M–N", but M is continuity and G3 is N, N2 and N3. Phase-map error. MINOR.
- **K5 versus C4** and the overloaded labels are repair-introduced and are covered by MAJOR-3 and section 7.
- **STATE stop-rule conflict.** STATE `hold_when_expected_information_gain_is_low: true` is unqualified. Governance §16 and Protocol Q2 require a coverage record first. STATE is stale against Governance 0.1.1. MINOR.
- **STATE protocol pointers.** `adjudication_protocol` still names 0.1.0, which is not qualified, and no `qualified_protocol` key exists, though Protocol §0 step 4 requires one. This risks a reader treating 0.1.0 as operative. MINOR.
- **STATE authority list.** STATE `authority.human_owner_final_authority` omits G0 authorization, G5 acceptance and protocol qualification, though they appear in `roles.human_owner` and Governance §21. MINOR.
- **Stale version headers:** none found. Governance 0.1.1, Charter 0.1.1 and Seed 0.1.0 are referenced consistently.
- **Circularity:** no circular requirements found beyond the K6 handling, which is adequate. No provisional outcome depends on a future event without a pending-gate label.
- **NOTE:** The Charter says `MAJOR_DOCTRINAL_COMPARISON = NOT_YET_AUTHORIZED`, while STATE and the Protocol say `held`. The labels differ without conflict.

## 14. REQUIRED REPAIRS
**R1 (MAJOR-1):** Extend the strict-auditor exclusion in Governance §3 and Protocol §0/O1/A3 to anyone who made an outcome-determinative reviewer determination (B4, C4, E3, K5) in the same study. Require the auditor to be disjoint from the named reviewers. This also needs a human-owner Governance change.

**R2 (MAJOR-2):**
- Add a symmetric admission criterion for background registers.
- Add independent elicitation of the register and independent exclusion review.
- Require independent pre-evidence review of the register.
- Define "serious live", and define "flip" and "robust" operationally.

**R3 (MAJOR-3):**
- Extend C4 to every Phase A item (A1–A15), the shared proposition map, and role changes.
- Resolve K5 against C4: state whether a re-frozen lane can feed a canonical synthesis.
- State the treatment of adverse post-evidence amendments.

**R4 (MAJOR-4):**
- Define "truth-critical comparison" in terms of discriminator tiers.
- State what `MATERIAL` and `CONTEXTUAL` discriminators do in dominance and outcome rules.

**R5 (MINORs):** Repair or explicitly limit the 13 MINORs listed above.

## 15. LIMITATIONS
The three carried limitations are correctly treated as limitations, not hidden defects. None is a MAJOR or BLOCKING defect for the intended second stress test.

1. `SUPPORTED_WITHIN_SCOPE` retains disciplined expert judgment. It is bounded by the sufficiency elements and record, and by the topic 12 and 13 audit checks. MAJOR-4 and the defeater-severity MINOR sit on the rule side, not the threshold side, and are repairable.
2. Metaphysical and revelation questions may often remain underdetermined. I4 prohibits `TRUTH_WARRANTED` under a flip, and no canonical rejection of a rival background exists yet. Therefore `TRUTH_WARRANTED` on contested metaphysical claims is effectively unreachable in the first such study, though `BEST_SUPPORTED` and conditional results remain available. This should stay attached to qualification.
3. AI-session and model independence is procedural. The Protocol records provenance but gives it no downstream consequence, such as capping confidence at MODERATE or requiring a different model family for the auditor. This is acceptable as a limitation. I recommend, as a non-binding suggestion, that downstream disclosures state provenance diversity.

## 16. QUALIFICATION DECISION
Protocol 0.1.2 is **not yet ready to be considered for qualification**. By its own §0 step 2 and §19, four unresolved MAJOR defects bar qualification until repaired and independently re-audited.

I have not qualified the Protocol, and nothing here authorizes a theological stress test or resurrection research.

**STOP.** The report is returned to the human owner. STATE names `TFP_ADJUDICATION_PROTOCOL_0_1_2_FOCUSED_REAUDIT_REPORT.md` as the target artifact. I did not write it, because the audit forbids modifying repository state. The owner can commit this text under that name.