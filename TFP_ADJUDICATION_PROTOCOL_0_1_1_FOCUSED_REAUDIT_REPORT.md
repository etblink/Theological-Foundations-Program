# TFP Adjudication Protocol 0.1.1: Focused Independent Re-Audit Report

**Audited text:** `TFP_ADJUDICATION_PROTOCOL_0_1_1.md`, branch `repair/tfp-adjudication-protocol-0.1.1`.

**Sources read:** Charter 0.1.1, `GOVERNANCE.md`, `STATE.yaml`, Method Seed 0.1.0, Protocol 0.1.1. I did not open the four excluded files, and I did not read the README. I changed nothing in the repository and did not write the report to a file. Line references are to the Protocol unless another file is named.

---

## 1. DISPOSITION

**`REPAIR_REQUIRED`**

There are no BLOCKING defects. There are 5 MAJOR defects. Each is narrow and fixable by adding text, not by restructuring the protocol.

---

## 2. EXECUTIVE FINDING

Protocol 0.1.1 is much more operational than a skeleton. The following are present and coherent:

- G0 preregistration and a symmetric candidate-admission rule.
- A G1 acquisition log.
- A defeater-first bridge from proposition dispositions to study outcomes.
- A separate human acceptance gate.
- Miracle and revelation sequences that avoid assuming naturalism or supernaturalism.
- A non-hierarchical source-quality rule.
- Continuity as relation types, not a ladder.
- Mandatory `reopen_if`.
- An anti-heuristic check.

The remaining problems all sit at the points where the protocol hands a decisive step to unstated judgment or to roles it never defines. A researcher with only the five sources could not answer five questions without project lore:

1. Who counts as the "program lead" and as an "independent reviewer."
2. How two lanes' findings on the same proposition combine or resolve.
3. What happens when a result flips under a live rival background.
4. Which post-freeze changes need review.
5. What `PASS` and `REPAIR_REQUIRED` mean for an audit.

All five bear directly on a miracle or revelation study, which is the intended second stress test.

---

## 3. ACCEPTANCE / GOVERNANCE FINDINGS

**Working as intended**
- G5 is separate from G4. Human-owner acceptance is explicit (P2). The auditor, the synthesis author and a STATE update are each barred from substituting for acceptance (1087–1089).
- P3 requires a separate acceptance record with the audit limitations in it.
- P5 makes a canonical truth-bearing STATE entry require three cited artifacts.
- O7 says audit PASS never equals acceptance.
- Procedural gate completion (P1) is separated from truth-bearing acceptance (P2).

**MAJOR-1: roles and independence are only partly defined, so they can still collapse.**
- "Program lead" is used (artifact 14; P1, line 1068) and defined nowhere in the five sources. P1 lets the program lead record "audit completion," "lane freeze" and "repair completion," so the same actor can author, freeze and declare completion.
- "Independent" is defined only for the final auditor (O1). It is undefined for the B2 candidate elicitor, the B3 and B5 reviewers, the C2 retyping reviewer, and the K4 "independently validated" check. One person could elicit candidates, review exclusions, approve a late candidate and then audit, which is self-review.
- O1 bars the auditor only from authoring the comparative synthesis and from being the *sole* author of an outcome-determinative lane. A co-author of a lane, or the G0 preregistration author, may audit.
- Role assignments (lane authors, auditor, reviewers) are not frozen at G0 (A1–A12), so collapse cannot be detected afterward.
- Nothing prevents the human owner from also being the synthesis or lane author.
- A12 requires "who authorized" the study but does not require that the authorizer be the human owner. That is consistent with Governance §20 only by implication.

**MINOR**
- No act or actor is defined for "explicitly qualified" (line 6, §26), meaning how a protocol becomes operative and what changes in STATE.
- `canonical_adjudications: []` (STATE 59) has no schema. P5 and O7 require STATE to carry acceptance citations and audit limitations, but no fields exist.
- STATE already holds proposition-level dispositions for EMT (STATE 86–92) that do not meet P5. They use vocabulary the protocol lacks (`partially_supported_to_strong`). The protocol gives no legacy or transition rule, so a successor cannot tell whether those entries are canonical truth-bearing.
- The audit-mandatory trigger (O, line 986) says "canonical theological adjudication," while P5 says any "truth-bearing" STATE entry. "Theological" is undefined, so a historical sub-result could be framed to avoid the audit trigger.
- The outcome labels `TRUTH_WARRANTED`, `CLOSEST_TO_TRUTH` and `BEST_SUPPORTED` are defined to require audit PASS and human acceptance (lines 921–922, 935). Synthesis at G3 must assign them before those events occur. The protocol has no `PROPOSED_` or "pending" status, so a provisional label can read as canonical.

---

## 4. INFERENTIAL-BRIDGE / TRUTH-ADJUDICATION FINDINGS

**Working as intended**
- F1–F8 define proposition-level dispositions, and every disposition carries `WITHIN_SCOPE`.
- N2 priority is nonnumeric and defeater-first.
- F9, K5 and N3 prohibit counting.
- The protocol can both license a truth judgment (the 10 conditions for `TRUTH_WARRANTED`) and withhold one. The withholding routes are the `INSUFFICIENT_SIGNAL` and `NOT_ESTABLISHED` blocks in N2, and the `UNDERDETERMINED` and `NONE_ADEQUATE` outcomes.

**MAJOR-3: there is no rule for combining or reconciling lane findings on the same proposition.**
- The protocol states conjunction (the weakest necessary component, C3) and defeaters (N2).
- It does not say what happens when two independent lanes each give a partial disposition on one necessary proposition, or when two lanes disagree. L5 says conflicts "remain explicit" and L6 says cumulative force comes from "convergent independent support." Neither gives a decision rule for turning those into a single proposition-level disposition.
- Judgment is therefore unwritten at the step that most determines whether a proposition becomes `SUPPORTED`.

**MINOR**
- `BEST_SUPPORTED` and `CLOSEST_TO_TRUTH` are barely distinct. Both fire when no candidate is truth-warranted and A dominates. `CLOSEST` adds only "no necessary proposition contradicted" and a proposition-by-proposition statement. It supplies no truth-likeness criterion beyond warrant, and there is no rule for choosing between the labels.
- The boundary between `BEST_SUPPORTED` and `NONE_ADEQUATE` is undefined. `BEST_SUPPORTED` has no bar against a contradicted necessary proposition, and `NONE_ADEQUATE` rests on a "preregistered minimum adequacy gate" (946–947) that no A–D element preregisters.
- N3 dominance is evaluated only on "every truth-critical comparison that *can be made*." Unmakeable comparisons drop out silently.
- Weakest-link aggregation (C3, N2) ignores attenuation across a long chain of `SUPPORTED` links. Arrows (Phase D) have no disposition rule of their own.
- F7 and N2 define `UNDERDETERMINED` slightly differently ("live" versus "adequate"). F7 and F8 are proposition-level dispositions defined with candidate-level conditions.
- The subtypes `FRAMEWORK_DEPENDENCE` and `PHILOSOPHICAL_EQUIVALENCE` overlap. The `INSUFFICIENT_SIGNAL` subtypes can co-occur, and no tie-break exists. `QUESTION_NOT_OPERATIONALIZED` is really a G0 failure.
- Outcomes are candidate-shaped (`CANDIDATE_A_…`), while A1 admits a single-proposition question. The mapping from "did X occur?" to a candidate set is not stated.

---

## 5. MIRACLE / REVELATION FINDINGS

**Working as intended**
- I1 rejects assuming naturalism, assuming supernaturalism, or treating sincere testimony as sufficient. It also rejects treating miracles as impossible by definition.
- I2 separates eight steps: report, transmission, historical core, anomaly, causal class, admissibility, particular cause and theological consequence. I4 separates nine revelation steps. I4 also bars circular self-authentication unless a separate argument is defended and audited.
- I3 forbids hiding priors inside "ordinary" or "extraordinary" and routes unspecifiable priors to underdetermination.
- Competing revelation claims face the same sequence.

**MAJOR-2: background handling is incomplete, and `TRUTH_WARRANTED` has a loophole.**
- Condition 7 (919) is satisfied if the necessary background assumptions are "supported *or* sensitivity-tested." A result that flips under a live rival background has still been "tested," so it can be truth-warranted.
- A8 permits an explicit metaphysical background, but no procedure requires enumerating the live rival registers or evaluating under each. Nor does it say how a background-conditional result is labeled.
- H and Q say what *flips* the result but do not require that no live rival background does.
- I3 uses `FRAMEWORK_DEPENDENCE` only "where appropriate," which is discretionary.

**MINOR**
- I1 lists only one direction of the gap fallacy ("extraordinary claims are true because alternatives are incomplete"). It omits the converse, in which an unspecified "ordinary" or "unknown" natural cause is assumed adequate.
- I2 step 4 ("exceeds the ordinary explanation currently warranted") builds in a baseline the protocol forbids hiding elsewhere.
- The causal classes "unknown" and "fraud/error" (I2.5) escape the B1 specification burden that every candidate faces.
- There is no claim type for "miracle/anomalous event" or "prophecy," and nothing ties the Phase I trigger to a type. A miracle claim typed `historical` could bypass Phase I.
- The revelation-specific markers and source-warrant steps (I4.5–7) list what to evaluate but not what counts as sufficient. This is thin for D.

---

## 6. CLAIM-TYPE / EVIDENCE-BURDEN FINDINGS

**Working as intended**
- The type list is broad (15 types).
- Typing freezes at G0 (C1). Retyping is logged and reviewable (C2) and cannot lower a burden after contrary evidence appears.
- C3 resolves multi-type conflicts.
- C4 stops a faith commitment from acting as public evidence.
- The doctrinal rule that doctrine establishes what a system *teaches*, not whether it is true, is explicit and good (529–530).
- Phase G supplies per-type templates.

**MINOR**
- The G templates are expressly "necessary templates, not automatic sufficient conditions" (453–455), and no sufficiency threshold exists. There is also no requirement that a `SUPPORTED` disposition record how each template element was met (weaker dispositions must state which components failed; `SUPPORTED` has no equivalent). The `SUPPORTED` threshold is the most decisive undocumented judgment in the protocol.
- A simple proposition with positive but insufficient evidence has no clean label. F2 requires "components," and F4 requires evidence not favoring the rival.
- The experiential rule requires external corroboration "proportionate" to external-world claims (551). It does not say what rival-expected corroboration looks like, which leaves a latent evidentialist tilt.
- C2 stops retyping that lowers a burden but not retyping that raises a rival's burden.
- The normative, metaphysical and revelation rules are required-inputs lists with no sufficiency guidance.

---

## 7. PHILOSOPHICAL / NON-HISTORICAL FINDINGS

**Working as intended**
- Phase H covers proposition, form, premises, premise-warrant source, validity or strength, hidden assumptions, defeaters, rival frameworks, theoretical virtues treated as defeasible, and sensitivity.
- The metaphysical type covers modal commitments.
- "Fewest assumptions is not an automatic winner."
- L1 defines lanes by claim competence, so history gets no default priority (N2 treats necessary propositions of any type equally).
- Philosophical reopen triggers exist (Q2.3).

**MINOR**
- "Premise-warrant source" is not constrained, for example whether intuition counts or how it is treated across rival frameworks.
- Metaphysical `SUPPORTED` will rarely be reachable. It is symmetric across candidates, which is acceptable, but this should be a stated limitation.

---

## 8. CANDIDATE / DISCRIMINATOR / SOURCE FINDINGS

**Working as intended**
- B1 sets one symmetric admission rule.
- B3 requires exclusions to state their reason and whether they are substantive or merely out of scope. A "prior-canonical-rejection" exclusion is allowed only for a canonical adjudication within the same scope.
- B4 makes completeness a real gate.
- B6 makes the meta-outcomes outcomes, not candidates.
- Hybrids can enter (B1, B4, `REVISED_CANDIDATE_REQUIRED`).
- Primary discriminators freeze at G0 (K1). Post-evidence discriminators are `POST_EVIDENCE_EXPLORATORY` (K4). Tallying is prohibited (K5).
- J has no lexical hierarchy and defines independence with recorded degrees.

**MINOR**
- B2 does not require the independent elicitation pass to run blind to the initial list. One pass satisfies it. "Major candidate classes" (B4) is undefined.
- B5 covers a candidate "discovered" late, not one *constructed* after evidence exposure. A post-evidence hybrid satisfies the preregistered discriminators by construction, and only new discriminators are flagged as exploratory. N2 `REVISED_CANDIDATE_REQUIRED` handles part of this, but B5 is silent.
- There is no steelman-packet procedure, although steelman packets are a required artifact (artifact 4). Governance §8 independence rules (independent construction, tradition-native sources, freeze before comparative exposure) and Charter §4 are not implemented in any phase.
- The Seed's alternative-hypothesis-source rule (Seed §11) is only implicit.

---

## 9. LANE / ACQUISITION / CONTINUITY FINDINGS

**Working as intended**
- E exists, with a plan, provenance, negative and inaccessible evidence, and coverage states. Only the first two coverage states can support canonical adjudication.
- Phase D decomposes into nodes and arrows, with necessary versus optional links.
- L1 and L4 are general and auditable. L2 introduces `FROZEN_FINDING` and avoids "accepted" language.
- L3 passes the background register to every lane and requires exact-point citation.
- L6 uses dependency graphs, not counts.
- M defines C0–C7 as non-sequential relation types and lists branching, convergence, loss, recovery, refunctionalization and independent construction. M1 is a symmetric burden, M2 is the independent-reinvention null, and M3 and §19 say when development bears on truth.

**MAJOR-4: outcome-determinative degrees of freedom have no review gate (the same pattern as the elements that do have one).**
- N1 lets "necessary truth-bearing propositions" be "amended transparently." That is transparency only, with no independent review, exploratory labeling or sequencing. Candidates (B5), typing (C2) and discriminators (K4) all have gates.
- The K2 relevance class (`CRITICAL`, `MATERIAL`, `CONTEXTUAL`) can be reclassified post-evidence with no rule.
- The E1 search plan is not in the A-phase freeze list. It needs only be stated "before searching," and the inclusion and exclusion criteria have no amendment log. Source-selection bias is therefore auditable only against a plan that can be rewritten.
- L4 allows a post-freeze "versioned amendment" with no reviewer, trigger or re-synthesis requirement.

**MINOR**
- The "required lanes" for L6 are never defined or preregistered.
- Circular lane dependencies, such as a history lane needing a philosophy-lane finding and the reverse, are not handled.
- E4 "complete" and "materially complete" are undefined.
- **Governance conflict.** Governance §17 and Seed §5 call C0–C7 a "ladder" and say "do not jump from resemblance to genealogy" (Gov 356). The Protocol (M) says C0–C7 is not a ladder and omits the no-jump rule. Its own §0 says Governance governs and conflicts "must be repaired explicitly," but this one is not repaired. Continuity claims also need not state the C-level asserted.

---

## 10. AUDIT / UNCERTAINTY / STOP-REOPEN FINDINGS

**Working as intended**
- O2 lists 13 audit topics, including all of: typing drift, discriminator timing, lane leakage, premise warrant, shallow heuristics, and cold-start reproducibility. A11 freezes study-specific additions at G0.
- O5 handles auditor disagreement. O6 requires a frozen repair matrix, preservation of the original report, a focused re-audit, and bars self-certification. O7 carries limitations into the acceptance record and STATE.
- O3 gives a minimum blinding rule that keeps necessary context.
- Q lists 10 uncertainty items, including residual alternatives, named backgrounds and flip conditions. It separates confidence from scope.
- Q2 gives a coverage-based stop test. Q2.3 makes `reopen_if` mandatory for `CLOSED` and `HELD`. §24 explicitly lists "trust tradition" and "fewest assumptions."

**MAJOR-5: audit outcomes and defect severity are undefined in the protocol.**
- O4 gives only the five labels. Nothing defines `PASS`, `PASS_WITH_LIMITATIONS`, `REPAIR_REQUIRED`, `INVALID_COMPARISON` or `INSUFFICIENT_SIGNAL`, or what makes a limitation a limitation as opposed to a defect.
- No severity scale (`BLOCKING`, `MAJOR`, `MINOR`, `NOTE`) is in the protocol. The definition I applied came from the audit prompt, which is outside the five sources.
- O2 "frozen criteria" is a list of topics, not pass or fail tests. Yet `TRUTH_WARRANTED` condition 9 depends on audit PASS or `PASS_WITH_LIMITATIONS`.
- A cold-start auditor cannot reproduce another auditor's outcome from the sources.

**MINOR**
- O3 blinding is hedged ("where practical").
- There is no rule for resolving a dispute between the program lead and a *single* auditor, nor for how binding the program lead's response is (artifact 14).
- Confidence levels `HIGH`, `MODERATE` and `LOW` are unanchored.
- Q2.1 says "low expected information value alone is not sufficient," while Governance §15 lists low expected information gain as a stop reason. This is likely a permitted tightening, but the relationship is not stated.
- O7 says limitations "constrain downstream use" without saying how.

---

## 11. COLD-START REPRODUCIBILITY

A competent researcher with only the five sources can determine:
- what is authorized (STATE: `TFP-STRESS-2` is `queued_not_authorized`; a second stress test is `NOT_AUTHORIZED`);
- how candidates enter;
- how claims are typed and when typing freezes;
- what evidence to collect;
- how arguments are evaluated;
- the miracle and revelation sequences;
- when lanes freeze;
- what outcomes mean;
- who accepts (the human owner);
- when STATE changes (P5).

The following decisive steps still depend on undocumented judgment:

1. **Roles.** Who the "program lead" is, and what "independent review" means for each gate (MAJOR-1).
2. **Lane combination.** How lane findings combine or reconcile on the same proposition (MAJOR-3).
3. **Background handling.** Which live rival backgrounds must be run, and what a flip means (MAJOR-2).
4. **Gating.** Which post-freeze amendments need review (MAJOR-4).
5. **Audit outcomes.** What counts as `PASS` versus `REPAIR_REQUIRED` (MAJOR-5).
6. **Minor items.** The `SUPPORTED` sufficiency threshold, steelman construction, the qualification act, the STATE adjudication schema, and the minimum adequacy gate.

Which document governs when sources differ is mostly answerable. §0 precedence is explicit, and STATE correctly identifies 0.1.0 as the current protocol and 0.1.1 as a candidate. Two gaps remain. Governance §2 and §21 do not recognize the protocol, so it asserts a rank (5) that Governance never grants. STATE's re-audit requirement refers to criteria "R1–R15" whose definitions lie outside the five sources.

---

## 12. REGRESSION FINDINGS

**Checked and sound**
- Stop and reopen are operational: coverage-based test, mandatory G6 state, mandatory `reopen_if`, philosophical triggers.
- Anti-heuristic checks are explicit.

**New defects introduced by the repair**

- **MINOR: the §2 gate table disagrees with the body.** The table puts G2 at Phases F–K and G3 at Phases L–N. The body's G2 section covers F–M (including L lane freeze and M continuity), and G3 starts at N. Phase K (discriminators) is registered at G0 (K1, A7) but sits under G2. §19, §24 and §25 sit outside any gate. "N2" is used for both a phase and a section number.
- **MINOR: the cold-start check (§25) has no named performer.**
- **MINOR: the Method Seed incorporation claim (§0) is partial.**
  - The seven-level plausibility versus attestation separation (Seed §4) is implemented only as `PLAUSIBLE_BUT_UNATTESTED`.
  - The source-proximity rule (Seed §8) and evidence-convergence classes (Seed §10) are not stated.
  - The "what survived versus what changed" requirement (Seed §6) is missing.
- **MINOR: header versions are inconsistent.** The Charter heading says "0.1.0" in a `0_1_1` file. `GOVERNANCE.md` is version 0.1.0 and never mentions the adjudication protocol.

---

## 13. REQUIRED REPAIRS

1. **(MAJOR-1) Roles.**
   - Define "program lead" and "human owner" in the protocol or in Governance.
   - Define "independent" for the elicitor, the reviewers and the auditor.
   - Bar authors, co-authors and the G0 preregistration author from auditing.
   - Preregister role assignments at G0.
   - State that the human owner is authorizer and acceptor, and cannot also be synthesis author without a recorded exception.
2. **(MAJOR-2) Background handling.**
   - Require enumerating live rival background registers at G0.
   - Require the result to be tested under each.
   - Require condition 7 to demand robustness, not mere testing.
   - Provide a conditional or `FRAMEWORK_DEPENDENCE` outcome when it flips.
   - State the converse gap fallacy in I1, and apply a symmetric specification burden to catch-all causal classes.
3. **(MAJOR-3) Lane combination.**
   - Add a nonnumeric rule for combining independent partial support and for resolving cross-lane conflict on the same proposition.
   - Add an attenuation or independence note for chain-conjunction.
4. **(MAJOR-4) Amendment gating.**
   - Add gated amendment procedures for necessary-proposition classification, K2 priority, the E1 search plan and L4 lane amendments.
   - Freeze the E1 plan at G0.
   - Label any amendment made after evidence exposure `POST_EVIDENCE` and exploratory.
5. **(MAJOR-5) Audit outcomes.**
   - Define the five audit outcomes and a severity scale in the protocol.
   - Convert O2 into pass or fail tests.
   - Specify how a dispute between the program lead and a single auditor is resolved.
6. **Minor items to fold into the same revision.**
   - Add a `PROPOSED_` status for outcome labels before acceptance.
   - Differentiate `BEST_SUPPORTED` from `CLOSEST_TO_TRUTH`.
   - Define the adequacy gate.
   - Fix the §2 gate mapping.
   - Reconcile C0–C7 language and the no-jump rule with Governance §17.
   - Define the STATE adjudication schema and a legacy-entry rule.
   - Add a steelman procedure.
   - Add a miracle and prophecy trigger tied to typing.
   - Add per-component sufficiency recording for `SUPPORTED`.
   - Define the qualification act.

---

## 14. LIMITATIONS

These apply only to the *qualification* decision and must be carried forward, even after repair:

- The `SUPPORTED_WITHIN_SCOPE` threshold is a judgment, with templates but no sufficiency conditions, and confidence levels are unanchored.
- Metaphysical and revelation claims will seldom reach `SUPPORTED`, which makes `UNDERDETERMINED` common for those types.
- "Independence" between AI agents and sessions is not defined. The protocol does not address shared model priors between author and auditor.

---

## 15. QUALIFICATION DECISION

**No. Protocol 0.1.1 is not ready to be considered for qualification in its present text.**

There are no BLOCKING defects. The five MAJOR defects each leave a decisive step to undocumented judgment or role assignment in the places a resurrection-type study would stress hardest: miracle and revelation background handling, lane combination, audit independence, and audit pass criteria. The repairs are additive and narrow. A further focused re-audit of the repaired text, with these defects as frozen criteria, is the next gate.

This is a qualification finding only. It does not authorize or deny any theological stress test. `TFP-STRESS-2` remains `queued_not_authorized`, as STATE and §26 state.

**STOP.** I have implemented no repairs and no qualification, and begun no downstream research.