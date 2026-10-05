# TFP Adjudication Protocol 0.1.3: Strict Independent Qualification Re-Audit Report

**Auditor provenance** (Governance §3 requires this for AI reviewers): Claude Code cloud session `session_01L7oyaFw5bqUCpjD4PgxbKQ`, configured and last-served model `claude-sonnet-5-5`, effort `medium`.

- **Sources read.** Only the five governed files, in the prescribed order, from branch `repair/tfp-adjudication-protocol-0.1.3`. I read no README, prior audit, disposition, preregistration, compliance matrix or prior protocol version.
- **Repository state.** Unchanged.
- **Disjointness not verified.** I could not verify from the governed set that I am disjoint from the authors and outcome-material reviewers. I rely on the launch assertion. This is itself a finding (see §3).

---

## 1. DISPOSITION

**`REPAIR_REQUIRED`**

Three MAJOR defects remain, together with a cluster of MINOR defects. There are no BLOCKING defects.

## 2. EXECUTIVE FINDING

Protocol 0.1.3 is a large improvement and is mostly coherent. These parts hold up:

- Strict-independence disjointness for studies.
- The one-way ratchet on post-evidence amendments.
- Separation of `PROPOSED_` outcomes from canonical ones.
- Separation of protocol qualification from study authorization.
- The miracle, revelation and prophecy sequences.
- The sufficiency templates.

Three outcome-determinative surfaces are still gameable or internally inconsistent:

1. The central dominance rule contradicts itself and relies on an undefined magnitude.
2. The evidence-acquisition plan and the strongest coverage state have no independent control.
3. Background admission is reviewed only on the exclusion side, and the flip test has no rule for combinations of backgrounds.

Several smaller defects cluster around qualification mechanics, amendment classification, trigger tagging and vocabulary. Each MAJOR repair is small and local. None requires redesign. The carried limitations are genuine limitations and not blocking, but two of them are described too narrowly (§17).

## 3. GOVERNANCE / ROLES / STRICT INDEPENDENCE

**Topics: 1 authority/governance consistency = `FAIL_MINOR`. 2 roles/strict independence = `FAIL_MINOR`.**

**What holds**
- The precedence orders in Governance §22 and Protocol §0 are identical.
- The strict-auditor definition matches across Governance §3, Protocol §0 and O1. It excludes authors and any outcome-material reviewer, and the role matrix must show disjointness before launch.
- Human owner, program lead and human-owner dual-role are consistent.
- Reviewer-to-auditor self-review is closed for studies.

**Defects**
- **G-1 (MINOR). Qualification-cycle roles are undefined.** Protocol qualification borrows the strict-independence standard. The governed set never defines:
  - what an "outcome-material reviewer determination" is in a protocol cycle;
  - which artifact holds the qualification-cycle role matrix;
  - who authored 0.1.3.
  
  `STATE.roles` names only the human owner and program lead. It has no authorship record and no dual-role exception field. A cold-start reader therefore cannot tell whether Governance §3's two-audit rule applies to 0.1.3. The §0 qualification act also names a single audit and does not restate that rule.
- **G-2 (MINOR). "Same actor/session" is not operationalized for AI.** Nothing says whether these count as the same actor:
  - forked or resumed sessions;
  - subagents of one orchestrator;
  - sessions sharing memory or context lineage;
  - the same human operator launching reviewer and auditor.
  
  Formal disjointness can be satisfied by labelling alone. Carried limitation 3 covers shared priors, not shared context lineage, so this is a distinct defect.
- **G-3 (MINOR). The human owner as reviewer is unaddressed.** The dual-role exception covers authoring only. Nothing bars the human owner from making outcome-material reviewer determinations and then accepting at G5. P bars the owner from substituting for the audit, not from reviewing.
- **G-4 (MINOR). The program lead is not expressly disjoint from the strict auditor.** The bar is by authorship only. The program lead coordinates lanes, records coverage and gate completion, and performs the STATE update. None of those is on the auditor's exclusion list.
- **G-5 (NOTE). Governance version is not bound to the qualification.** The protocol takes its roles "from Governance 0.1.2", but nothing binds the qualification record to a Governance version or commit. `STATE.repair_candidate_governance` suggests Governance itself was touched by the repair. Governance changes that alter authority boundaries need human-owner action, and no ratification record is in the governed set.

**Collapse test.** For studies, the outcome-material reviewer and strict auditor cannot formally collapse into one actor. The G-2 and G-3 gaps leave informal collapse routes.

## 4. CANDIDATES / BACKGROUNDS / SYMMETRY

**Topic 3 candidate/background symmetry = `FAIL_MAJOR`.**

**What holds**
- B1 admission is symmetric.
- B2 independent elicitation, B3 equal-strength check, and B4 exclusion review are present.
- B5 late-candidate quarantine blocks fitting a post-evidence candidate to exposed evidence.
- B3 bars defining a candidate solely through an opponent's critique.
- The A8 admission criteria are symmetric on their face.

**Defects**
- **R3 (MAJOR). Background-register gaming.**
  - *One-sided review.* Every outcome-material exclusion gets independent review. Inclusions get none. The second reviewer verifies completeness, not that each admitted background meets A8(1)–(5). A program lead wanting underdetermination can over-admit weak backgrounds, since admission alone can force `FRAMEWORK_DEPENDENCE` and bar `TRUTH_WARRANTED`. A lead wanting warrant can rely on reviewed exclusions that nobody audits for symmetry.
  - *Elicitation escape hatch.* Elicitation is "where feasible", with no documentation duty when infeasible.
  - *Circular criterion.* A8(5) excludes backgrounds "contradicted by facts common to every admitted candidate". That makes the candidate set, which is itself gameable, a filter on backgrounds.
  - *No granularity rule.* Nothing says whether "naturalism" is one background or many, or how sub-variants are split or merged.
  - *Combinations undefined.* A8 and I4 define a flip as "changing from one admitted background to another" and test "each live register". With several background dimensions (metaphysical, historiographic, methodological), nothing says whether joint combinations are tested. Flips can therefore be avoided by varying one dimension at a time.
- **S-1 (MINOR). Necessary-proposition freeze is unreviewed.** A6 and B3 let candidate constructors define each candidate's necessary propositions. The set determines exposure to CRITICAL discriminators and eligibility for `TRUTH_WARRANTED`. It is frozen pre-evidence, which is good. No rule or reviewer governs how propositions are classified as necessary versus supporting, which would catch a candidate shielding hard propositions as non-necessary. The B3 equal-strength check partly mitigates this.
- **S-2 (MINOR). Premise-warrant vocabulary is lexically asymmetric.** The warrant categories include `confessional`, and `faith commitment` is barred from public `SUPPORTED`. No parallel label marks unargued secular or naturalist foundational premises. Those would be classed "theoretical/explanatory" or "empirical", a more flattering label. The structural burden of Phase I and A8 is symmetric, so the cost is limited, but it contradicts Governance §7.

**Steelman symmetry.** Procedurally symmetric (B3). The weak point is the lack of any threshold for "materially weaker" in the equal-strength check, which is minor.

## 5. EVIDENCE / CLAIM TYPES / SUFFICIENCY

**Topics: 4 evidence acquisition/provenance/coverage = `FAIL_MAJOR`. 5 claim typing and sufficiency = `FAIL_MINOR`.**

**What holds**
- The E1 provenance record, E2 negative and inaccessible evidence, E4 plausibility/attestation, E5 source proximity and E6 convergence are sound.
- The type-specific sufficiency templates in Phase G are reproducible.
- Source quality in Phase J is not hierarchical.
- Adverse out-of-plan discoveries must be incorporated (C4).

**Defects**
- **R2 (MAJOR). Source selection and coverage have no independent control.**
  - *Plan has no review.* A9 freezes the acquisition plan with no independent elicitation or pre-freeze symmetry and completeness review. Candidates and backgrounds get both; source strata get neither.
  - *Narrow plans pass.* A plan that omits tradition-native or hostile strata still reaches `COVERAGE_COMPLETE_FOR_FROZEN_SCOPE`.
  - *Strongest state self-certified.* E3 requires a reviewer only for `MATERIALLY_COMPLETE_WITH_LISTED_GAPS`. `COMPLETE_FOR_FROZEN_SCOPE`, which supports canonical comparison, needs no reviewer. Nobody is assigned to declare `COVERAGE_INCOMPLETE`.
  - *Disjointness has nothing to bite on.* Governance lists "evidence-coverage completeness review" among reviewer determinations, but the protocol never assigns it for these states. Disjointness from the auditor is moot if no review exists.
  - *Only post-hoc detection.* Audit topics 7 and 8 catch this at G4. A defect there can trigger `INVALID_COMPARISON` and a full restart.
- **T-1 (MINOR). Trigger tags are undefined and unreviewed.** `miracle/anomalous-event` is not defined. Anomaly is framework-relative (I3.4), so the tag cannot be applied before a framework is chosen. No reviewer checks the initial typing (C1, topic 4 audits drift only). An untagged event is judged under ordinary historical sufficiency, which can install a naturalistic reading silently, contrary to I1. Tag scope is also inconsistent: A4 says "any claim tagged", I2 says "truth-critical subclaim".
- **T-2 (NOTE). Judgment vocabulary.** Terms such as "sufficiently specified", "materially distinct", "serious" and "plausibly" recur in outcome-determinative steps without operational anchors. Most are bounded by reviewers or by the audit.

## 6. AMENDMENT / CHANGE CONTROL

**Topic 6 = `FAIL_MINOR`.**

**What holds**
- C4 covers every frozen G0 element, A1–A17.
- Adverse changes must be incorporated and trigger re-synthesis.
- Favorable or mixed changes are exploratory for the confirmatory study and need fresh preregistration or held-out confirmation.
- Mixed changes split: the adverse part is incorporated immediately and the favorable part is held exploratory.
- A "can only" test makes the default for uncertain direction favorable or mixed.
- Post-evidence candidate and protocol migration are handled (B5, A17).

On the specific test, favorable correction cannot quietly improve a confirmatory result, and adverse discoveries cannot be suppressed.

**Defects**
- **A-1 (MINOR). No reviewer is assigned to the direction classification.** C4 requires an independent reviewer for `PRE_EVIDENCE` outcome-material changes and for `POST_EVIDENCE_NONMATERIAL`. It names no reviewer for classifying a change `ADVERSE_MATERIAL` versus `FAVORABLE_OR_MIXED_MATERIAL`, though Governance counts "post-freeze amendment classification" as a reviewer determination. Direction labelling is the gate that stops quiet improvement. G4 inspection is after the fact.
- **A-2 (MINOR). The exposure ledger is self-reported and internally contradictory.** A17 says it is frozen at G0, but it records exposures that happen later. Nobody is assigned to maintain it, keep it append-only, or attest it. Classification depends entirely on it.
- **A-3 (NOTE). "Current result" is undefined before synthesis.** "Adverse" is defined relative to the current result, but no result exists at G1 or early G2.
- **A-4 (NOTE). The ratchet shifts outcomes toward weaker labels.** It is candidate-neutral and therefore not a structural asymmetry. It does skew the outcome distribution, which matters for the heuristic test (§15).

## 7. LANES / PROPOSITION CONSOLIDATION

**Topic 7 = `FAIL_MINOR`.**

K1–K6 and L1–L5 are well built: weakest necessary facet, independent-convergence conditions, ordered cross-lane conflict resolution with no vote-counting, chain attenuation, and a cumulative-fragility review that defaults to blocking.

- **L-1 (MINOR). `DEPENDENCY_CYCLE` is not in the enumerated subtype list.** K6 produces `UNDERDETERMINED_WITHIN_SCOPE: DEPENDENCY_CYCLE`, but Phase F enumerates only four subtypes, and `DEPENDENCY_CYCLE` is not among them.
- **L-2 (MINOR). The cumulative-fragility reviewer is unassigned.** `CUMULATIVE_FRAGILITY_REVIEW` and the LOW-confidence confirmation in L4 both have no named reviewer. They are outcome-material reviewer determinations under the Governance catch-all but are not enumerated.

## 8. DISCRIMINATORS / INFERENTIAL BRIDGE / OUTCOMES

**Topic 8 = `FAIL_MAJOR`.**

**What holds**
- The A11 tiers are preregistered with a result vocabulary.
- The unmakeable rule exists.
- The N2 defeater-first order is clear.
- N3 outcome definitions are mostly clean.
- `CLOSEST_TO_TRUTH` is appropriately restricted.

**Defects**
- **R1 (MAJOR). The dominance rule contradicts itself and depends on an undefined magnitude.**
  - *Outrank versus veto.* N2.6 says independent direct CRITICAL discriminators outrank MATERIAL evidence. The dominance rule, clause 1, lets an unresolved MATERIAL discriminator favoring B block A's dominance "strongly enough to create a MIXED_TRADEOFF", even when CRITICAL favors A. These produce different outcomes on the same facts. CRITICAL favors A and MATERIAL favors B gives A under N2.6 but `UNDERDETERMINED` under clause 1. That is the difference between `BEST_SUPPORTED` and `UNDERDETERMINED`.
  - *Undefined magnitude.* The only result vocabulary is categorical (`FAVORS_A`, `FAVORS_B`, `NEUTRAL`, `UNMAKEABLE`), so "strongly enough" has no referent. A11 defines `MIXED_TRADEOFF` only for conflicting MATERIAL directions, not for CRITICAL-versus-MATERIAL conflicts.
  - *Judgment outside the carried limitation.* This is an outcome-determinative judgment not covered by the carried expert-judgment limitation, which concerns only `SUPPORTED_WITHIN_SCOPE`.
  - *Who assigns priority.* Priority is assigned per discriminator, justified by "the candidate's" necessary propositions. A discriminator can be CRITICAL for A's necessary proposition and peripheral for B's, and no rule addresses this. No independent reviewer checks that priority assignments are symmetric across candidates.
- **B-1 (MINOR). Conflict between N2, N and N3 over unmakeable comparisons.** N says an unmakeable truth-critical comparison "normally" yields `UNDERDETERMINED` or `INSUFFICIENT_SIGNAL`. N2 says it does so "if outcome-relevant" (undefined). N3 `BEST_SUPPORTED` requires dominance "on makeable" comparisons, not omitting any. Whether `BEST_SUPPORTED` survives a recorded unmakeable CRITICAL comparison is ambiguous.
- **B-2 (MINOR). `TRUTH_WARRANTED` condition 8 versus L4.** N3 condition 8 blocks only LOW links "capable of flipping". L4 blocks any LOW link unless reviewer-confirmed. Condition 9 ("compared equally") describes process, not a result. There is no explicit "not dominated by, or tied on a CRITICAL discriminator with, an incompatible serious rival."

## 9. MIRACLE / REVELATION / PROPHECY

**Topic 9 = `FAIL_MINOR`.**

This is the strongest area.
- I1 is symmetric and explicitly bars both unknown-natural and unspecified-supernatural catch-alls.
- I3 requires comparing anomaly per live causal framework and requires specified causal classes.
- I4 and I5 bar hidden priors.
- I6 applies the same sequence to competing revelation claims and addresses circular self-authentication.
- I7 handles prophecy specificity and flexible reinterpretation.

The defect is trigger application (T-1, §5), plus the structural ceiling in the next paragraph.

**Structural note.** With both a naturalism-type and a supernaturalism-type background admitted as live, nearly any miracle-dependent study will register a `BACKGROUND_FLIP` (I3.6 metaphysical admissibility changes). The result is a forced `UNDERDETERMINED: FRAMEWORK_DEPENDENCE`, the only label permitted under flip (N2.10). The only escape is a backgrounds "independently rejected by applicable canonical adjudication", which would require a prior metaphysical adjudication that would face the same ceiling. This is symmetric, not a bias, but it is closer to structural than "may often remain underdetermined" (see §17).

## 10. PHILOSOPHY / SOURCE QUALITY / CONTINUITY

**Topic 10 = `FAIL_MINOR`.**

H, J and M are sound. Parsimony is never an automatic winner. J is non-lexical, including its rule that later sources may preserve earlier material. M includes the no-jump rule, the independent-reinvention null, and equal burdens for continuity and corruption claims.

- **P-1 (MINOR).** The warrant-vocabulary asymmetry (S-2).
- **P-2 (NOTE).** Continuity labels diverge slightly. Governance, STATE and the Seed use "material continuity" for C1. The Protocol says "form/material continuity" and adds textual formulae. Protocol C7 adds "recovers" beyond the Seed. Precedence resolves it, but a higher authority's labels differ from the lower one's definitions.

## 11. AUDIT SEMANTICS / QUALIFICATION

**Topic 11 = `FAIL_MINOR`.**

**What holds**
- The severity and outcome definitions are usable and non-circular.
- A `LIMITATION` status exists.
- The namespace rule separates audit, proposition and study "insufficient signal".
- `PASS_WITH_LIMITATIONS` is tightly bounded.
- The status vocabulary can represent every finding in this report.

**Defects**
- **U-1 (MINOR).** `INVALID_COMPARISON` and the O2 topic list are study-shaped. O9 says protocol audits "use the same severity/outcome semantics" without mapping `INVALID_COMPARISON` to a protocol context. O2 lists 17 topics, O9 lists 15, and the topic status vocabulary is defined only for O2.
- **U-2 (MINOR).** No criterion defines "irreducible" for `LIMITATION`. Any MAJOR defect can be re-labelled a limitation. "Cluster of MINOR defects" has no threshold.
- **U-3 (MINOR).** The qualification act pins nothing about the audited text. The act names "that exact protocol" but sets no commit or hash. STATE refers to the artifact by branch ref (`repair/tfp-adjudication-protocol-0.1.3:…`), which is mutable. Audit PASS on one commit followed by qualification of later edits is not prevented. The fix is one sentence.

## 12. STATE / ACCEPTANCE / LEGACY

**Topic 12 = `FAIL_MINOR`.**

**What holds**
- `canonical_adjudication_schema` matches P3 exactly, with 16 required fields.
- EMT is tagged legacy (P4).
- P5 blocks program-level truth commitments from a single study.
- The mechanical STATE update is separated from the human acceptance that creates the record.
- `PROPOSED_` outcomes are separate from canonical ones, with the prefix removed only after G4 and G5.
- `canonical_adjudications` is `[]`.
- Protocol qualification is separated from study authorization. §0 says qualification does not authorize a stress test, STATE has `second_stress_test_authorized: false`, and `TFP-STRESS-2` is `queued_not_authorized`.

**Defects**
- **ST-1 (MINOR).** No schema for a protocol-qualification record. STATE has `adjudication_protocol` and `qualified_protocol`, both null, plus a free-text status. Which is authoritative is not stated. Required qualification fields (audit artifact(s), disposition, acceptance artifact, commit, limitations) are unspecified.
- **ST-2 (MINOR).** `audit_artifact` is singular but the dual-role rule can require two audits. The Phase Q uncertainty items "known weaknesses", "flip conditions" and "underdetermination subtype" have no clear schema slot.
- **ST-3 (NOTE).** STATE accumulates version-specific audit history for 0.1.0–0.1.3, in parallel blocks. This slightly strains the Governance §23 succession standard. It also puts prior-audit findings inside the "independent" source set, so independence there rests on the launch prompt's discipline rather than on the governed set.
- **ST-4 (NOTE).** `held: MAJOR-DOCTRINAL-COMPARISON` has a reason that refers to the protocol being "not yet formalized or stress-tested". Qualification alone will not clear it. This is consistent with the separation but needs an explicit owner action.

## 13. UNCERTAINTY / STOP / REOPEN

**Topic 13 = `FAIL_MINOR`.**

Phase Q's confidence definitions are consistent between study and proposition level. Q2 and Governance §16 agree that the coverage record must exist before an information-gain stop. Every closed or held study must define `reopen_if`.

- **Q-1 (MINOR).** No protocol-level reopen, supersession or de-qualification rule exists. If a later audit finds a defect in a qualified protocol, nothing says how adjudications accepted under it (each records `protocol_version`) are treated.

## 14. COLD-START REPRODUCIBILITY

**Topic 14 = `FAIL_MINOR`.**

A competent unfamiliar researcher can recover, from the five files:
- what is currently authorized (re-audit only);
- that no protocol is qualified;
- the roles and prohibited combinations for studies;
- how a study is authorized, how candidates and backgrounds are constructed, how claims and links are typed and frozen, and how coverage is judged;
- how amendments are classified and how lane findings become dispositions;
- how the study-level outcomes are proposed and audit outcomes are interpreted;
- who accepts and how STATE is updated;
- how the work stops and reopens.

**Not recoverable from the governed set**
- How many strict audits qualification of 0.1.3 needs (G-1).
- The exact audited artifact (U-3).
- Which STATE field records qualification (ST-1).

No outcome-determinative step depends on undocumented project lore, so I apply O8's `FAIL_MINOR` branch and not `FAIL_MAJOR`. Outcome-determinative steps that rest on judgment the protocol documents but leaves unconstrained are R1, R2 and R3. They are reported under topics 8, 4 and 3. The carried limitation does not cover them.

## 15. REGRESSION / INTERNAL CONSISTENCY

**Topic 15 = `FAIL_MINOR`.**

**Consistent**
- Precedence orders, the schema field list, and the gate map.
- The first three INVALID_COMPARISON/INSUFFICIENT_SIGNAL namespaces.
- The `PROPOSED_` rules.

**Inconsistencies**
- N2.6 versus dominance clause 1 (R1, reported as MAJOR in §8).
- Unmakeable treatment across N, N2 and N3 (B-1).
- `DEPENDENCY_CYCLE` is outside the subtype list (L-1).
- A4 versus I2 trigger scope (T-1).
- N3.8 versus L4 (B-2).
- A17 "frozen" versus a ledger that is updated (A-2).
- C-label divergence (P-2).

**Shallow-heuristic test.** §23 sets a sound test (counterfactual evidence-integration) but gives no procedure. There is no required slogan-versus-disposition-matrix comparison log, and the "unless independently justified for the exact question" escape does not define who may so justify. The slogan list is first-order theological only. It omits meta-procedural slogans. "Always default to the weakest permitted label" would reproduce many outcomes, because of the A-4 ratchet, the defeater-first order, default-to-block rules and the structural `FRAMEWORK_DEPENDENCE` ceiling (§9). I add that slogan as a requirement in R5.

## 16. REQUIRED REPAIRS

**MAJOR (block qualification)**
- **R1. Dominance rule (topic 8).**
  - Reconcile N2.6 with dominance clause 1. State whether CRITICAL strictly outranks MATERIAL or whether a MATERIAL veto exists, and define it without "strongly enough".
  - Extend the discriminator result vocabulary, or the `MIXED_TRADEOFF` definition, to cover CRITICAL-versus-MATERIAL conflict.
  - Define discriminator priority per candidate pair, or require a symmetric rationale reviewed by an independent reviewer before freeze.
- **R2. Evidence acquisition (topic 4).**
  - Add an independent source-plan elicitation or review before the A9 freeze that tests completeness and symmetry. Cover each admitted candidate and live background, and include tradition-native, skeptical and adverse strata.
  - Require independent reviewer certification of every coverage state. `COVERAGE_COMPLETE_FOR_FROZEN_SCOPE` and `COVERAGE_INCOMPLETE` must be certified, not only `MATERIALLY_COMPLETE`.
  - Enumerate coverage-completeness review as a named reviewer determination.
- **R3. Background register (topic 3).**
  - Require independent review of inclusions as well as exclusions, and review of each admitted background against A8(1)–(5).
  - Require documentation whenever elicitation is infeasible.
  - Drop or constrain the A8(5) candidate-set filter.
  - Add granularity rules for what counts as one background.
  - Define how combinations are tested for `BACKGROUND_FLIP`, joint or per-dimension.

**MINOR (repair or bound under limitations)**
- **R4. Qualification mechanics (topics 1, 2, 11, 12).**
  - Require the qualification record to cite the audited commit hash and bind the Governance version.
  - Define the protocol-qualification role matrix and authorship/dual-role record, and restate the two-audit rule in §0.
  - Add a STATE schema for a qualified-protocol entry and say which of `adjudication_protocol` and `qualified_protocol` is authoritative.
  - Expand `audit_artifact` to allow more than one.
  - Operationalize "same actor/session" for AI. Address forked and resumed sessions, subagent trees and shared memory. Address the human owner as reviewer and program-lead disjointness from the auditor.
- **R5. Typing, amendment and heuristics (topics 5, 6, 15).**
  - Define the `miracle/anomalous-event` trigger, require an independent reviewer for initial typing and tagging, and align A4 with I2.
  - Assign a reviewer to the ADVERSE-versus-FAVORABLE classification. Make the exposure ledger append-only, attested and custodied. Define "current result" pre-synthesis.
  - Give the §23 heuristic test a procedure. Require a logged comparison of each slogan against the disposition matrix. Add the meta-procedural slogans, and define who may justify an exemption.
- **R6. Vocabulary and consistency (topics 7, 8, 10, 13, 15).**
  - Add a neutral label for unargued secular foundational commitments, parallel to `confessional`.
  - Add `DEPENDENCY_CYCLE` to the subtype list.
  - Name reviewers for `CUMULATIVE_FRAGILITY_REVIEW` and LOW-confidence confirmation.
  - Reconcile B-1 and B-2.
  - Add a protocol-level supersession and de-qualification rule.
  - Align C-labels.
  - Define "irreducible" for `LIMITATION`.
  - Map `INVALID_COMPARISON` to protocol audits.
  - Set a threshold for a "cluster" of MINORs.

## 17. LIMITATIONS

I assessed each carried limitation on whether it is a real limitation or a hidden defect.

1. **`SUPPORTED_WITHIN_SCOPE` retains expert judgment.** Genuine and not blocking. The `SUFFICIENCY_RECORD`, enumerated MET/NOT_MET elements and defeater rules constrain it adequately. It understates the locus of judgment: dominance magnitude and the vocabulary in T-2 are also judgment. R1 and R2 cover those, so the limitation text should not stretch to cover them.
2. **Metaphysical and revelation questions may often remain underdetermined.** A genuine limitation, and not blocking. `UNDERDETERMINED` is a legitimate Charter outcome and conditional results are reported. It should be restated more precisely: given N2.10, I4 and the canonical-rejection circularity, a flip-prone study cannot exceed `FRAMEWORK_DEPENDENCE` unless a prior background adjudication exists, and such an adjudication faces the same ceiling.
3. **AI-session and model independence is procedural.** Genuine, irreducible and not blocking. Keep it distinct from G-2, the operational-lineage defect, which is repairable.

**Limitations that must stay attached to any qualification**
- The three above, with limitations 1 and 2 restated as noted.
- Any MINOR from §16 not repaired before qualification, each demonstrated non-outcome-determinative per O2.

## 18. QUALIFICATION DECISION

Protocol 0.1.3 is **not ready** to be considered for human-owner qualification.

- **Disposition: `REPAIR_REQUIRED`.** Three MAJOR defects (R1, R2, R3) remain, plus a cluster of MINOR defects across qualification mechanics, amendment classification, trigger tagging and vocabulary.
- **Repair needed.** Each MAJOR is localized and repairable without redesign.
- **No qualification, authorization or repair done.** I have not qualified the protocol, authorized any theological stress test, or made any repair. Qualification remains a separate human-owner act. This report grants no authorization.

**STOP.** Returning the report to the human owner.