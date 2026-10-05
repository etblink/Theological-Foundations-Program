I'll start by verifying the pinned commit and blob identities.

Identities all match. Reading in the required order.

# TFP Protocol 0.1.4: Strict Independent Qualification Re-Audit

## 1. SOURCE IDENTITY / INDEPENDENCE VERIFICATION

**Identity: VERIFIED.** The commit `9ef85fbd4c40d1a661db3a8219b3cd5c74934922` resolves locally. I read each file with `git show <commit>:<path>` and recomputed each blob SHA with `git hash-object`. All five match the pinned values.

| File | Blob SHA |
|---|---|
| `TFP_PROGRAM_CHARTER_0_1_1.md` | `22242b48…5c95` ✔ |
| `GOVERNANCE.md` | `dbf36501…d154` ✔ |
| `STATE.yaml` | `1be006ba…f3b` ✔ |
| `TFP_METHOD_SEED_0_1_0.md` | `bee2449a…4896` ✔ |
| `TFP_ADJUDICATION_PROTOCOL_0_1_4.md` | `fa8a2224…a1a` ✔ |

I read the five files in the required order. I did not read the README, prior audits, dispositions, repair artifacts, earlier protocol versions, or issue and PR text. I did not consult the source manifest, because it is optional launch control and the prompt already pins every SHA.

**Independence declaration**
- **Model and provider:** Anthropic, configured as `claude-sonnet-5-5`. The session metadata reports `last_served_model` as `claude-sonnet-5-5`.
- **Provenance:** claude.ai Code cloud session `session_01FCquymcXKWGge7622bEV2p`, lineage depth 0 (no parent session).
- **Fresh context:** yes. This is not a continuation, fork, resume or subagent.
- **Prior TFP exposure:** I have seen no prior TFP audit or re-audit reasoning. I am not in the `OPENAI_CHATGPT_TFP_PROGRAM_LEAD_LINEAGE` lineage and have made no outcome-material reviewer determination.
- **Disjointness:** I regard myself as procedurally disjoint under Governance's Actor-lineage rule. This is self-attestation. I cannot verify hidden persistent memory beyond my own knowledge of this session.
- **Repository state:** I made no changes. The session carries a standing instruction to push to the repair branch. Your prompt says not to modify repository state, and I followed your prompt.

## 2. DISPOSITION

**`REPAIR_REQUIRED`**

This follows from one FAIL_MAJOR in the discriminator and inferential-bridge surface. Five FAIL_MINORs on the same surface also meet the protocol's own three-or-more-MINOR threshold.

## 3. EXECUTIVE FINDING

The bundle is internally coherent in its main architecture, and I found no BLOCKING defect. Four things work well:
- Authority precedence agrees across Charter, Governance, STATE and Protocol.
- The STATE schemas match Protocol §P3 and §P6 field for field.
- The independence regime is strong: Actor-lineage rules, a role matrix, and a ban on self-qualification.
- The change-control design (adverse corrections mandatory, favourable ones exploratory) is sound in principle.

The weak point is the step that turns evidence into a study outcome. Dominance (§17) is computed only from preregistered discriminator results, and nothing requires those discriminators to cover each candidate's necessary propositions. Around that gap, the CRITICAL/MATERIAL boundary, the adequacy triggers, the unmakeable-comparison language, and the outcome vocabulary each have ambiguities that change which label a study returns. There are also qualification-act, role-matrix, audit-semantics and amendment gaps, mostly bounded and mostly procedural.

## 4. GOVERNANCE / ROLES / STRICT INDEPENDENCE

**Topic 1, authority and governance consistency: `FAIL_MINOR`**
- **1a.** `GOVERNANCE.md` calls itself "**active governance**". STATE (`candidate_governance_version`) and Protocol §0 treat Governance 0.1.3 as a *candidate pending owner ratification*. The file never says which prior version is in force. A cold-start reader cannot tell whether 0.1.3 is already authoritative, even though it defines the independence rules used to audit it.
- **1b.** Protocol §0.4 says the owner ratifies Governance "*if authority boundaries changed*". Governance §21 and the P6/STATE schema make `governance_ratification_artifact` mandatory. The conditional and the unconditional rule disagree, and no one is named to decide whether boundaries changed.
- **Note:** The Charter's "Authority" line rests on README and `RESEARCH_SEED`, which are outside the bundle. Governance ranks README as orientation only.

**Topic 2, role and strict-independence rules, lineage provenance: `FAIL_MINOR`**
- **2a.** Governance requires the qualification role matrix to be frozen before launch, including "intended strict auditor(s)". STATE carries `strict_auditor: TO_BE_ASSIGNED_FRESH_DISJOINT_LINEAGE`. Updating it would change the pinned STATE blob, so the matrix cannot be completed within the bundle.
- **2b.** Protocol O1 names the source-manifest preparer as a disjointness subject. Neither the Governance matrix nor the STATE matrix has a field for that role or for the relaying operator.
- **2c.** The matrix gives a lineage identifier only for the author and program lead.

The Actor-lineage rule itself is well drawn. It covers fork, resume, shared subagent context, shared memory and receipt of prior reasoning. It also correctly treats same-model-family sessions as procedurally distinct. The operator-relay clause is permissive but bounded.

## 5. CANDIDATES / BACKGROUNDS / SYMMETRY

**Topic 3, candidate and background symmetry: `PASS`**
- **Candidates:** Admission (B1), independent elicitation (B2), equal-strength check (B3), exclusion review (B4), late-candidate handling (B5) and the "meta-outcomes are not candidates" rule (B6) are symmetric across traditional, skeptical, hybrid and minority candidates.
- **Backgrounds:** A8(1)–(5) apply uniformly. A8.2 granularity and A8.3 interaction matrix block cherry-picking a favourable subset of joint combinations. The protocol says to narrow scope openly or return `INSUFFICIENT_SIGNAL` rather than sample.
- **Note:** A8(3) lets an "independently formulated argument" suffice for admission. This is loose but symmetric and review-gated. The `CONFESSIONAL_COMMITMENT` label (C3) has no named secular counterpart. The gap is closed by A4 type-burden review, A8's "no silent installation" rule and I1.

**Structural symmetry search.** I found no structural burden asymmetry favouring either camp. Specifically:

*Confessional side*
- E5, J1–J2, Phase G (authority/canon, faith commitment), I6 (no self-authentication) and Phase M (development is neither corruption nor maturation) are neutral.
- The TRUTH_WARRANTED conjunction (all necessary propositions SUPPORTED) penalises candidates with long necessary chains. That is a size effect, not a side effect (NOTE).

*Skeptical/naturalistic side*
- I1 (unspecified natural cause does not win by default) and I3 (natural classes must be specified before they defeat a rival) are neutral.
- A8/I4 give backgrounds equal treatment.
- The "independent reinvention null" is stated as a specified *rival* with symmetric burden (M, "Symmetry"), not as a free default.
- Harmonization versus maximal-contradiction readings are not named, but they are covered by "serious rival readings" (NOTE).

## 6. EVIDENCE / CLAIM TYPES / SUFFICIENCY

**Topic 4, evidence acquisition, provenance, coverage: `FAIL_MINOR`**
- **4a.** E3's `COVERAGE_COMPLETE_FOR_FROZEN_SCOPE` rests on the reviewer finding "no *known* outcome-material source class omitted". The reviewer inspects the plan and the acquisition log. No independent adverse-source probe is required. A narrow plan plus a compliant log could certify as complete. A9.1 pre-freeze elicitation mitigates this but does not remove it.
- **4b.** The scope of a coverage state (study, lane, proposition or comparison) is unspecified. MAKEABLE (A11) is defined as "independently certified sufficient", but no coverage-state definition says what certifies a single comparison.

**Topic 5, claim typing and sufficiency: `LIMITATION`**
- The Phase G templates list mandatory elements but no threshold for when an element is `MET`. This matches carried limitation 1.

## 7. AMENDMENT / CHANGE CONTROL

**Topic 6, amendment, change control, exposure ledger: `FAIL_MINOR`**
- **6a.** C4 defines ADVERSE_MATERIAL in absolute terms ("add a defeater… reduce candidate support… leave all candidates no better") and FAVORABLE in outcome terms ("could improve any candidate/outcome"). Dominance is relative. A defeater against B is adverse to B and favourable to A's standing. The split rule ("adverse incorporated, favourable exploratory") cannot be applied to a single relative ranking.
- **6b.** The ledger custodian (A17) has no independence requirement and no integrity mechanism. The amendment reviewer "attests" the ledger but has no way to verify completeness.

I do not rate the missing duty-to-file for known adverse errors as a defect. "Amendment-controlled", Governance §13 and §21 ("may not silently… erase negative knowledge"), and the G4 inspection of amendments cover it (NOTE).

## 8. LANES / PROPOSITION CONSOLIDATION

**Topic 7, lane and proposition consolidation: `FAIL_MINOR`**
- **7a.** Under L4 and Q, a LOW local confidence means "live uncertainty could plausibly downgrade/reverse the disposition". L4 lets a fragility reviewer waive a LOW necessary link for TRUTH_WARRANTED by confirming the uncertainty "cannot defeat any truth-warrant condition". But a plausible downgrade of a necessary link defeats TRUTH_WARRANTED condition 3 (all necessary propositions SUPPORTED). The waiver is therefore close to unsatisfiable. It is a dead or contradictory provision that invites rubber-stamping.

L1–L3 (weakest necessary facet, non-duplicative convergence, direct beats contextual, no vote-counting) and K6 (dependency cycles) are sound.

## 9. DISCRIMINATORS / INFERENTIAL BRIDGE / OUTCOMES

**Topic 8, discriminator priority and inferential bridge: `FAIL_MAJOR`**

**8-MAJOR: dominance does not depend on proposition-level warrant, and discriminator coverage is not mandated.**
- **What the text does:** §17 Stage 1 and Stage 2 decide dominance only from preregistered discriminator directions. Proposition dispositions (F) enter only through adequacy, defeaters and the TRUTH_WARRANTED gating (N2.1–N2.6). BEST_SUPPORTED (N3) requires only adequacy plus dominance on "makeable truth-critical comparisons".
- **What is missing:** No rule requires that each admitted candidate's necessary propositions are covered by at least one CRITICAL comparison. The A16 shared-proposition map applies only to CLOSEST_TO_TRUTH. A11 requires only that the symmetry of *assigned* priorities be reviewed. A6 reviews the classification of necessary propositions, not their coverage by discriminators. Audit topics 6 and 13 check timing and "equal-standard application" in general terms.
- **Exploit:**
  - A has three NOT_ESTABLISHED necessary propositions. B has three SUPPORTED ones.
  - The preregistered set contains one CRITICAL discriminator the author can foresee favouring A, with B-favouring evidence registered only as MATERIAL.
  - Stage 1 gives A the win. MATERIAL cannot veto a resolved CRITICAL, and only a proposition-level defeater of the supporting premise could reopen it.
  - A12 does not fail A: its coverage test only checks that evidence exists to evaluate its propositions.
  - The result is `PROPOSED_CANDIDATE_A_BEST_SUPPORTED_WITHIN_SCOPE` while B is better warranted on its own necessary propositions.
- **Severity basis:** this could materially change outcome and reproducibility. It is MAJOR under §19.
- **What blocks the attack today:** reviewer discretion only.
- **Repair direction (not applied):** require every necessary proposition of every admitted candidate to be covered by at least one preregistered comparison (or a documented non-comparative reason), and require the independent reviewer to certify that completeness before G0 freeze.

**FAIL_MINOR findings on the same surface:**
- **8a. CRITICAL/MATERIAL overlap (A11).** CRITICAL covers evidence that "bears directly on candidate adequacy or a necessary truth-bearing proposition for at least one member". MATERIAL covers evidence that "changes relative warrant… but does not by itself defeat a necessary proposition". Evidence that bears directly on a necessary proposition without defeating it fits both. The tier assignment decides Stage 1 versus Stage 2, so it is outcome-determinative, and it falls outside the "expert judgment inside sufficiency steps" carve-out.
- **8b. Inconsistent adequacy triggers.**
  - A12 uses a canonical contradiction.
  - N2.1 uses a `CONTRADICTED` necessary proposition.
  - N3 `NONE_ADEQUATE` adds "undefeated TRUTH_CRITICAL_DEFEATER defeats a required candidate condition".
  - F says a TRUTH_CRITICAL_DEFEATER blocks only `SUPPORTED` and `TRUTH_WARRANTED`.
  - N2.2 labels `EVIDENCE_AGAINST` on a necessary proposition as a MATERIAL_DEFEATER, though F's TRUTH_CRITICAL_DEFEATER definition covers evidence that "directly undermines a necessary truth-bearing proposition".
  - So it is unclear whether such a candidate can still be `BEST_SUPPORTED`.
- **8c. UNMAKEABLE versus NEUTRAL.**
  - A11 defines UNMAKEABLE purely by coverage.
  - Phase N says to use `UNDERDETERMINED` for an unmakeable comparison "when adequate coverage exists but the evidence is genuinely non-discriminating".
  - That case is NEUTRAL under A11, not unmakeable.
- **8d. Mixed adequate and inadequate fields.**
  - "A dominates B only when… both candidates pass adequacy."
  - If B fails adequacy, A literally cannot dominate B.
  - `UNDERDETERMINED` requires two or more adequate candidates, and `NONE_ADEQUATE` requires that all fail.
  - So a field with exactly one surviving adequate candidate has no clean outcome label. Intent is obvious but the text is not.
- **8e. Background flip versus `BEST_SUPPORTED`.**
  - BACKGROUND_FLIP includes a change in "eligibility for TRUTH_WARRANTED".
  - I4 then says to "use `UNDERDETERMINED: FRAMEWORK_DEPENDENCE`", and N2.11 says the "strongest background-sensitive result" is that.
  - A candidate that is `BEST_SUPPORTED` under every live background but warrant-eligible under only some falls to `UNDERDETERMINED`. It is unclear whether the robust ranking survives. This is conservative and symmetric, but it loses information and is ambiguous.
- **8f. Unmakeable "poison pill".** No pre-G0 feasibility check applies to CRITICAL discriminators. A preregistered CRITICAL comparison that can never be made would force `INSUFFICIENT_SIGNAL`. A9.1(5) flags bottlenecks but does not require demoting or removing such a discriminator. Post-evidence demotion is an exploratory amendment. The failure mode is conservative (a no-result outcome, not a false winner).

## 10. MIRACLE / REVELATION / PROPHECY

**Topic 9: `FAIL_MINOR`**
- **9a.** Phase I is mandatory for any `revelation`-tagged claim, but A4 defines the miracle and prophecy trigger tags and gives no operational definition of `revelation`.
- **9b.** An authority/canon claim whose warrant rests on a revelation premise has no automatic trigger. A candidate-favouring description could keep Phase I from firing. Only the A4 typing review guards this.

Phase I is otherwise strong and symmetric:
- The triggers are candidate-symmetric.
- I1 gives a two-sided symmetric start.
- I3 requires specified causal classes.
- I4 and I5 require background robustness and prohibit hidden priors.
- I6 prohibits self-authentication.

## 11. PHILOSOPHY / SOURCE QUALITY / CONTINUITY

**Topic 10: `PASS`**
- Phase H, the premise-warrant categories (including worldview/foundational subtypes), the J1–J7 source rules and the Phase M no-jump rule are consistent with Charter §3 and §4 and with the Seed.
- Phase M symmetry places continuity and corruption claims under comparable burdens.

## 12. AUDIT SEMANTICS / QUALIFICATION

**Topic 11, audit semantics: `FAIL_MINOR`**
- **11a.** O4 and O5 allow requesting "another independent audit" or a "frozen reconciliation response". They define no aggregation rule when audits disagree, no duty to carry every audit of the same frozen bundle forward, and no statement of who authors the reconciliation. This is audit-shopping exposure. It is bounded, because Governance and §0.3 keep an unresolved MAJOR blocking and the owner holds final authority.
- **11b.** "Decision surface" and "interacting MINOR defects" (REPAIR_REQUIRED thresholds) are undefined.

The severity scale is otherwise coherent: PASS, PASS_WITH_LIMITATIONS, REPAIR_REQUIRED, INVALID_COMPARISON and INSUFFICIENT_SIGNAL have distinct triggers. The O2 and O9 topic vocabularies agree, and the namespace rule keeps study-level, proposition-level and audit-level `INSUFFICIENT_SIGNAL` distinct.

## 13. STATE / ACCEPTANCE / LEGACY

**Topic 12: `FAIL_MINOR`**
- **12a.** Q2 requires CLOSED/HELD/SUPERSEDED/REOPENED states and `REVIEW_REQUIRED` marking for adjudications. The P3 and STATE adjudication schema has no status or lifecycle field to carry them.
- **12b.** The adjudication schema does not reference the G0 authorization artifact, the role matrix or the exposure ledger.
- **12c.** The `qualified_protocol.status` vocabulary (`QUALIFIED`, `QUALIFICATION_CHALLENGED`, `DEQUALIFIED`) is only partly specified.

Both schemas are field-for-field identical between the protocol and STATE. EMT is correctly tagged `legacy_research_disposition`, consistent with P4. Its lowercase, non-vocabulary labels are tolerated as legacy (NOTE).

## 14. UNCERTAINTY / STOP / REOPEN / SUPERSESSION

**Topic 13: `PASS`**
- Phase Q confidence definitions are consistent, including local meanings.
- Q2 stop and reopen rules, the "low information gain only after a coverage record" rule, and the supersession and de-qualification sequence are coherent and aligned with Governance §14 and §16.
- **Note:** "credible" defect reports are undefined, and the owner arbitrates.

## 15. COLD-START REPRODUCIBILITY

**Topic 14: `FAIL_MINOR`**

A competent unfamiliar researcher can recover authorization, roles, outcome vocabulary, STATE transitions and stop and reopen conditions from the bundle. They cannot recover the following without inference:
- the formats of the named artifacts (`SOURCE_PLAN`, `BACKGROUND_REGISTER_REVIEW`, `BACKGROUND_INTERACTION_MATRIX`, `SUFFICIENCY_RECORD`, `PROPOSITION_EVIDENCE_MATRIX`, `EVIDENCE_EXPOSURE_LEDGER`);
- the meaning of "serious rival";
- who certifies MAKEABLE comparisons;
- where G0 authorization is recorded in STATE.

These are procedural. The outcome-determinative gap is the topic 8 MAJOR, which is a missing rule rather than undocumented lore, so I do not escalate topic 14 to FAIL_MAJOR.

## 16. REGRESSION / INTERNAL CONSISTENCY

**Topic 15, immutable source identity and regression/internal consistency: `FAIL_MINOR`**
- **15a. The §0 immutability rule conflicts with the qualification act.**
  - §0 says any post-audit change to one of the five blobs invalidates the PASS "unless the replacement is byte-identical".
  - Qualification step 5 writes `qualified_protocol` into `STATE.yaml`, and STATE is the "sole canonical mutable" file.
  - Read literally, the prescribed final step voids step 2. STATE's `audited_state_blob_sha` field shows STATE changes are intended, but §0 never exempts STATE or says which edits are permitted.
- **15b. Stale status strings in the audited blobs.**
  - The protocol header and §24 hard-code `CANDIDATE__REPAIR_PENDING_REAUDIT` and `NEXT = STRICT_INDEPENDENT_QUALIFICATION_REAUDIT`.
  - Under §0 these cannot be updated without invalidating the audit, so a qualified protocol would carry stale "candidate/pending" text.
  - §0 and P6 say STATE governs, which mitigates this.
- **Identity itself:** all five blobs verified.

**Together, 15a and 15b could leave a successor unable to tell whether a given later edit invalidates qualification.** This interaction is the main reason I count topic 15 as more than isolated minor wording.

## 17. ADVERSARIAL ATTACK RESULTS

| Attack | Result |
|---|---|
| Weak candidate wins via necessary/supporting classification | **Classification itself blocked** (A6 review, no demotion of vulnerable claims, comparable criteria). **Adjacent path succeeds**: the discriminator-coverage gap (topic 8 FAIL_MAJOR). |
| Narrow the source plan | **Mostly blocked** (A9.1 independent elicitation and plan review). Post-freeze narrowing is a favourable amendment and stays exploratory. Residual: 4a. |
| Manufacture `COVERAGE_COMPLETE_FOR_FROZEN_SCOPE` | **Mostly blocked** (independent certification, uncertified means no canonical comparison). Residual: 4a, 4b. |
| Over/under-admit backgrounds | **Blocked** (A8(1)–(5), independent register review, blind elicitation). Over-admission can only push toward `FRAMEWORK_DEPENDENCE` or scope narrowing, and that is symmetric and visible. |
| Exploit background granularity and interaction | **Blocked** (A8.2, A8.3, no silent sampling). |
| Exploit CRITICAL/MATERIAL/CONTEXTUAL priority | **Partly succeeds**: 8a (boundary overlap) and the topic 8 MAJOR. |
| Exploit an `UNMAKEABLE` comparison | **Partly succeeds, conservatively**: a poison-pill CRITICAL yields `INSUFFICIENT_SIGNAL` (8f); 8c is a text inconsistency. No false winner results. |
| Post-evidence amendments to improve a favourite | **Blocked** (C4 classes, ledger, favourable amendments exploratory only). Residual: 6a, 6b. |
| Suppress adverse corrections | **Blocked** (mandatory incorporation, re-synthesis, G4 inspection). No explicit duty to file (NOTE). |
| Collapse reviewer and auditor via AI context/session lineage | **Blocked** (Governance Actor-lineage rule, O1 attestation, role matrix). Self-attestation limit applies. |
| Bypass miracle/revelation/prophecy triggers | **Mostly blocked** (A4 definitions, I2 symmetry, relabelling barred). **Residual**: 9a and 9b (revelation is undefined). |
| Confessional or secular-naturalist premise as hidden public evidence | **Blocked** (C3 for faith commitments, A8 "no silent installation", I1, A4 type-burden review). Residual is the missing secular label (NOTE). |
| `PROPOSED_` converted to canon without G4/G5 | **Blocked** (N3 prefix rule, P2, Governance §5, G5 owner step). |
| Qualify a different version than audited | **Blocked** (§0 manifest, blob SHAs, `protocol_blob_sha` in P6). Residual: 15a and 15b. |
| Shallow heuristic ("always weakest permitted disposition") | **Blocked** (§23 `HEURISTIC_MATRIX_AUDIT` lists it). "Permitted" depends on coverage, defeaters and background results, so the slogan cannot be applied without evidence integration. Weakest-link rules (C2, L1, L4) make the slogan a close approximation on necessary chains, which is why the matrix requires a material counter-case. |

## 18. REQUIRED REPAIRS

**Priority 1 (MAJOR)**
1. **R1:** require the preregistered discriminator set to cover every necessary proposition of every admitted candidate, with independent certification before G0 freeze. Tie `BEST_SUPPORTED` dominance to that complete set.

**Priority 2 (the six MINORs that make up the surface-level REPAIR_REQUIRED cluster on discriminators and bridge, plus qualification-act integrity)**
2. **R2:** resolve the A11 CRITICAL/MATERIAL overlap with a single exclusive test (8a).
3. **R3:** unify adequacy triggers across A12, N2.1, N3 and F, and state whether an undefeated TRUTH_CRITICAL_DEFEATER ends `BEST_SUPPORTED` eligibility (8b).
4. **R4:** align the Phase N wording with A11's MAKEABLE/NEUTRAL definitions (8c).
5. **R5:** define outcome labels for a field with one adequate and one or more inadequate candidates (8d).
6. **R6:** state whether a robust `BEST_SUPPORTED` survives a warrant-eligibility-only background flip (8e).
7. **R7:** specify the immutability exemption for STATE and the stale-status handling in the protocol and Governance blobs (15a, 15b).

**Priority 3 (remaining MINORs)**
8. **R8:** reconcile Governance self-status "active" with candidate status, and make the ratification condition unconditional or defined (1a, 1b).
9. **R9:** make the role matrix completable and add manifest-preparer and operator fields (2a, 2b, 2c).
10. **R10:** add an independent adverse-source probe to E3 and define coverage-state scope (4a, 4b).
11. **R11:** define relative-direction handling for amendments and add custodian independence and integrity (6a, 6b).
12. **R12:** repair or remove the L4 LOW-confidence waiver (7a).
13. **R13:** define `revelation` and add an authority/canon trigger (9a, 9b).
14. **R14:** add audit-set disclosure and aggregation rules, and define "decision surface" and "interacting" (11a, 11b).
15. **R15:** add an adjudication lifecycle status and a G0 reference to the schema (12a, 12b, 12c).
16. **R16:** document artifact templates and define "serious rival" and who certifies MAKEABLE (cold-start, topic 14).
17. **R17 (optional):** add a pre-G0 feasibility check for CRITICAL discriminators (8f).

## 19. LIMITATIONS

**The three carried limitations are genuine limitations, not hidden MAJOR/BLOCKING defects.**
- **L1, expert judgment in `SUPPORTED_WITHIN_SCOPE`:** genuine, provided it stays confined to the documented sufficiency steps. Priority classification (8a) sits outside that carve-out, so I counted it as a defect.
- **L2, `FRAMEWORK_DEPENDENCE`:** genuine and symmetric. For questions where the candidate is itself a background (for example a naturalism-versus-theism comparison), the outcome is `FRAMEWORK_DEPENDENCE` by construction. This is a consequence of the design rather than a defect, but it should be understood when authorizing metaphysical studies. Its interaction with `BEST_SUPPORTED` is ambiguous (8e).
- **L3, AI-session independence:** genuine. Two extensions:
  - the exposure ledger cannot capture pre-G0 author or model exposure to the literature, so "pre-evidence" is procedural;
  - the auditor's independence attestation is unverifiable self-report.

## 20. QUALIFICATION DECISION

**This exact Protocol 0.1.4 bundle is not ready to be considered for human-owner qualification.** The result is `REPAIR_REQUIRED`: one FAIL_MAJOR plus the MINOR clusters described above. A repaired bundle would need a new immutable commit and a new strict independent re-audit. I have not qualified the protocol, authorized any theological stress test, or modified any repository file.

**STOP.**