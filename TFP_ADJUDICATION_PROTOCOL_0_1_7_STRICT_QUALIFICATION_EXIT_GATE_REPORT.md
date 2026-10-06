I'll start with launch control: confirm the session ID, then check the two control files against their pinned blob SHAs.

Both control blobs match their pinned SHAs. Next I'll read the manifest and the role-control record.

Launch control checks pass—the role-control record confirms disjoint author/lead lineages, one assigned audit, and no outcome-material reviewers. Next I'll fetch the pinned commit and verify the five blob SHAs.

All five blobs match. I'll read them in the required order, starting with the charter.

The protocol is about 95KB, so I'll read it in parts.

The five governed files are read. Next is the regression reference, `main:GOVERNANCE.md`. I only need that one blob, so I'll fetch main and read that file only.

I found a transcription typo in the launch prompt's blob SHA (one character short) compared to the correct 40-character SHA in the manifest and STATE, which matches the fetched blob—I'll treat the manifest as authoritative and note this discrepancy in the report. Next, I'll read the regression reference.

Before writing the report, I'll confirm the session identity and configured model that the role-control record asserts.

# TFP Adjudication Protocol 0.1.7: Strict Independent Qualification Exit-Gate Audit

## 1. LAUNCH CONTROL / SOURCE IDENTITY / INDEPENDENCE

**Session and role**
- Audit session: `session_012EWsCBUVctdyhhk3v5ZxuF`, matching the assigned session.
- `get_session` shows configured model `claude-sonnet-5-5` and last-served model `claude-sonnet-5-5`.
- Lineage depth is 0. I used no subagents or workflows.
- The role-control record shows Anthropic / `claude-sonnet-5-5` / `PROCEDURALLY_DISJOINT_FOR_ASSIGNMENT`, with one registered audit, `TFP-0.1.7-STRICT-EXIT-GATE-AUDIT-1`, in ASSIGNED status.
- It lists no outcome-material qualification reviewers.
- The author, program-lead and manifest-preparer lineage is `OPENAI_CHATGPT_TFP_PROGRAM_LEAD_LINEAGE`, which is disjoint from mine.
- The human owner is recorded with no material authorship and no reviewer role.

**Control blobs (verified)**
- Source manifest: `de9223db5f57a287c90be7dc1df46c8c75d4dfde`. Match.
- Role-control: `4e3fe845ca5f6ff75674355bcdfeca33256ba032`. Match.

**Governed bundle `b9854f85…`, five blobs verified and read in the required order**

| File | Blob SHA |
|---|---|
| Charter 0.1.1 | `22242b48…` |
| Governance 0.1.5 | `02338ce3…` |
| STATE.yaml (schema 0.3.0) | `b03cba0c…` |
| Method Seed 0.1.0 | `13717514…` |
| Protocol 0.1.7 | `0d9406d9…` |

- All five match.

**Regression reference**
- Read only after the five files: `main:GOVERNANCE.md`, operative version 0.1.0.
- It has blob `45f3361781c32c04bb6055968dbaf24a120fb27c`, which matches the manifest and STATE.
- **Discrepancy:** the SHA printed in my launch prompt is 39 characters (`…968dbf24a…`), one character short of the real value (`…968dbaf24a…`).
- I treated this as a transcription typo. The manifest, STATE and the fetched object all agree on the 40-character value.
- I did not return `INVALID_COMPARISON` for it. The human owner should confirm it was a typo.

**Independence**
- I read only the launch prompt, the manifest, the role-control record, the five pinned files and the one regression blob.
- Fetching the branch brought other repository objects into the local store, and the checkout contains other files. I opened none of them.
- I did not read the README, prior audits, dispositions, repair preregistrations, compliance matrices, prior protocol versions, issues or PRs. I also did not read the assignment-declaration file the role-control cites.
- I saw no prior audit or repair reasoning outside the permitted set.
- Inside the permitted set, STATE and the manifest disclose metadata only:
  - predecessor 0.1.6 returned `REPAIR_REQUIRED`;
  - two prior auditor sessions are barred;
  - the 0.1.7 cycle was scoped to "five accepted MAJOR defects plus interacting MINORs".
- None of this is substantive reasoning, and I did not use it.
- The launch prompt's exit-gate framing and carried-limitation list came from the program-lead side. I treated them as scoping only. Protocol O-phase severity rules decided every finding.

**Audit-set disclosure**
- The permitted launch-control sources disclose exactly one registered strict audit of this bundle: this one.
- `required_strict_audit_count` is 1.
- Predecessor audits (0.1.5, 0.1.6) are different targets and are not part of this audit set.

## 2. DISPOSITION

**`PASS_WITH_LIMITATIONS`**

- No BLOCKING or MAJOR defect found.
- Two MINOR defects are carried: **MINOR-1** and **MINOR-2**. They sit on different decision surfaces and do not interact. No surface has three MINORs.
- I judged the MINORs individually bounded and not outcome-determinative.
- 14 NOTES are recorded, none of which is a defect.

## 3. EXECUTIVE FINDING

The bundle is internally consistent on authority and role separation. Its ranking, truth-warrant and amendment machinery is largely closed against the listed attacks. The audited STATE and Protocol P6/P3 schemas match field for field. Governance 0.1.5 regresses nothing from 0.1.0.

Remaining issues are drafting seams, not structural failures:
- **MINOR-1:** `INSUFFICIENT_SIGNAL` has two consequence paths with an undefined threshold between them.
- **MINOR-2:** the protocol-challenge lifecycle is incomplete.

Both have conservative defaults in the text. Repairing either before qualification would require a new immutable bundle (§0, "substantive change invalidates audit"), so carrying them is the proportionate course.

## 4. GOVERNANCE / ROLES / REVIEWER INDEPENDENCE

**Authority and precedence**
- Precedence is identical in Governance §22, Protocol §0 and the Method Seed. Candidate Governance 0.1.5 is declared non-operative until ratified.
- Gov §21 makes qualification incomplete without human-owner ratification of the exact Governance blob.
- Protocol §0 item 6 repeats this, and QT1 sets `active_governance_*` only after ratification. Skipping ratification is blocked.

**Bootstrap (NOTE-10)**
- The candidate rules govern their own audit, and operative Governance 0.1.0 has no protocol-qualification provisions.
- This is inherent to a bootstrap and is closed by the ratification requirement.

**Role separation**
- The A3 and Governance reviewer-separation rules match, and A3 adds the direction-result reviewer.
- Lineage disjointness covers the program lead, the authors and the strict auditor.
- The actor-lineage rule covers fork, resume, subagent and shared-memory descent, and it correctly says a checkout or branch name is not descent.
- The qualification role-control record carries every Governance-required field.
- The audit-handshake and registration-before-launch rules were observed in this cycle.

## 5. CANDIDATES / BACKGROUNDS / SYMMETRY

- Phase B has symmetric admission, independent elicitation without the initial list "where feasible", steelman packets with an equal-strength check, and exclusion review.
- Late and post-evidence-constructed candidates (B5) cannot win the same confirmatory comparison.
- Backgrounds have five admission criteria, a blind elicitation pass, independent inclusion and exclusion review, split and merge rules tied to truth-critical inferences, and an interaction matrix.
- Silent sampling of favorable combinations is forbidden. An oversized combination set means narrowing scope openly or returning `INSUFFICIENT_SIGNAL`.
- Symmetry across confessional, secular, naturalistic and supernaturalist backgrounds is explicit (A8, A4 worldview rule, I1).

## 6. EVIDENCE / CLAIM TYPES / SUFFICIENCY

- The 16 types and 2 trigger tags are defined.
- Trigger tags cannot be avoided by candidate-favoring wording, because A4 binds an independent typing review.
- Worldview and faith commitments of every subtype need independent warrant to count as public support.
- Type-specific sufficiency templates exist, including existential/practical. Multi-type claims are capped at the weakest necessary component (C2).
- **Carried limitation 1 is legitimate.** `SUPPORTED` rests on disciplined judgment inside a documented `SUFFICIENCY_RECORD` with named mandatory elements. Dominance, source selection, background selection and eligibility are not left to judgment.

## 7. NECESSARY-PROPOSITION COVERAGE / ELIGIBILITY

**What is closed**
- A6 gives an operational necessity test and a frozen CANDIDATE_SPECIFIC vs SHARED_FLOOR classification against the G0 candidate set. Later candidate failure cannot reclassify.
- Exactly one coverage mode applies per proposition. A COMPARATIVE_ROUTE needs a CRITICAL discriminator. MATERIAL-only coverage is barred twice (A6 and A11).
- Reviewer independence and a no-asymmetric-routes certification apply.
- The A12 statuses are mutually exclusive.
- The disposition-to-eligibility map is total for candidate-specific propositions, with a separate shared-floor map.
- TRUTH_WARRANTED #4 requires every necessary proposition `SUPPORTED`.

**MINOR-1 — `INSUFFICIENT_SIGNAL` has two consequence paths and no threshold between them (surface 9/6)**
- A12 prerequisite 4 requires "evaluable evidence access/coverage … at the level required to proceed". Its failure is `STRUCTURALLY_INADEQUATE`, and N3 row 1 then gives study-level `INSUFFICIENT_SIGNAL`.
- The disposition map separately says a proposition-level `INSUFFICIENT_SIGNAL_WITHIN_SCOPE` is only "ranking-blocking".
- The shared-floor map says it leaves ranking unaffected and blocks TRUTH_WARRANTED. A literal reading of prerequisite 4 would instead push the study to row 1.
- "The level required to proceed" is never defined, so it is unclear when each path applies.
- Worst case, an analyst reads A's evidence gap as ranking-blocking and gets `ONLY_RANKING_ELIGIBLE(B)`.

**Why it is bounded**
- Row 1 is evaluated first.
- Phase N states "if required evidence/access/provenance is inadequate after the documented effort record, use INSUFFICIENT_SIGNAL".
- A12 forbids "manufactur[ing] ONLY_ADEQUATE" from another candidate's surviving structure.
- A14 requires each study to preregister its insufficient-signal condition.
- TRUTH_WARRANTED #11 blocks any truth label for B while A is neither compared nor shown inadequate.
- The worst-case output is a non-ranking, non-truth label.

## 8. DIRECTION RULES / DISCRIMINATORS / MAKEABILITY

- Each CRITICAL or MATERIAL discriminator needs a frozen DIRECTION_RULE covering FAVORS_A, FAVORS_B, NEUTRAL and UNMAKEABLE, with an independent pre-evidence review.
- After evidence, an independent DIRECTION_RESULT_REVIEWER, disjoint from the discriminator author, records whether the rule was followed without criterion change. Unreviewed directions cannot enter dominance.
- Post-hoc criteria are blocked by C4.
- Priority is pair-relative and exclusive. MATERIAL cannot veto a resolved CRITICAL result. CONTEXTUAL never decides.
- UNMAKEABLE requires a COMPARISON_EFFORT_RECORD. "Unperformed search is never UNMAKEABLE; it is COVERAGE_INCOMPLETE."
- MAKEABLE requires an independent comparison-scoped coverage certification.
- The NEUTRAL catch-all means no outcome falls outside the four direction states, except a rule whose FAVORS_A and FAVORS_B conditions both fire. C4 amendment control then governs conservatively.
- N2 pairwise logic is consistent: opposing CRITICAL directions give MIXED_TRADEOFF, and an UNMAKEABLE CRITICAL comparison blocks dominance.

## 9. BASE OUTCOME PARTITION / CLOSEST-TO-TRUTH / TRUTH-WARRANT

**Base outcomes**
- The N3 table is ordered and exhaustive over (ADEQUATE count) × (RANKING_ELIGIBLE count) × (flip, no dominance, dominance). I found no case with no row and no case with two rows. Order resolves overlaps.
- A12 states "only RANKING_ELIGIBLE candidates participate in dominance, BEST_SUPPORTED, or CLOSEST_TO_TRUTH". This resolves the ambiguity in row 9's phrase "every serious rival" (NOTE-1).
- The ONLY_ADEQUATE / ONLY_RANKING_ELIGIBLE / BEST_SUPPORTED distinctions are explicit. An adequate but ranking-blocked rival is never ranked and can't take a pairwise label.

**CLOSEST_TO_TRUTH**
- It attaches only to BEST_SUPPORTED. It needs at least 2 preregistered independent shared dimensions with per-dimension rules.
- It needs at least one A_BETTER CRITICAL dimension, no CRITICAL B_BETTER or UNMAKEABLE dimension, and any MATERIAL favoring B excluded only by preregistered redundancy.
- No global score is permitted.
- Any ranking flip makes it unavailable.
- **NOTE-3:** A16 has no explicit independent pre-evidence review of the shared-dimension map, tiers or independence, unlike A11. The G4 audit and C4 mitigate this. It's an optional refinement.

**TRUTH_WARRANTED**
- It has 14 conjunctive conditions. These include every necessary proposition `SUPPORTED`, no LOW necessary node or arrow (no waiver), and no unresolved fragility review.
- It also needs TRUTH_WARRANT_ROBUST across all serious live backgrounds, and every serious rival compared or shown inadequate.
- The conditions can't be met by coherence or consensus. A truth-warrant-only background flip bars it even when the relative outcome survives.

## 10. AMENDMENT / EXPOSURE LEDGER / CONFIRMATORY CONTAMINATION

**Amendment classes**
- C4 classes depend on exposure and on per-candidate direction (ADVERSE / FAVORABLE / NEUTRAL / MIXED_OR_UNCLEAR), reviewed independently.
- Favorable or mixed amendments cannot strengthen any candidate's confirmatory outcome. A resulting ranking or dominance change terminates the comparison as `POST_EVIDENCE_DIRECTIONAL_CONTAMINATION`.
- Source-plan narrowing after exposure is presumptively favorable.
- N3 row 2 precedes the adequacy rows.

**NOTE-2:** rule 3 forbids a stronger confirmatory label, but its remedy is defined only for "ranking/dominance" changes. A favorable amendment that changes only ranking eligibility has no explicit remedy. Rule 5 and the conservative reading of rule 4 resolve it.

**Ledger**
- It is append-only with a custodian. Every outcome-material actor attests to the ledger at lane freeze.
- An independent integrity reviewer checks sequence, history and ordering at each amendment.

**NOTE-4:** the ledger doesn't say whose exposure makes an amendment "post-evidence". The clean reading is that any outcome-material actor's exposure counts, because transmitted summaries are exposures. A relay-through-unexposed-author attack is therefore blocked in principle but should be stated.

## 11. LANES / CONSOLIDATION / FRAGILITY

- Lanes are by competence, not by favored candidate (K1). Lane amendments reuse C4. A circular dependency becomes a proposition-level `DEPENDENCY_CYCLE`.
- The proposition-evidence matrix defines direct vs indirect evidence and "sufficiently strong conflict". Mere repetition never promotes a disposition. Dependent sources count as one stream.
- Chain attenuation caps a chain at its weakest necessary link.
- LOW confidence blocks truth-warrant with no waiver.
- Independent confidence review applies wherever MODERATE vs LOW changes truth-warrant eligibility. Cumulative fragility review is triggered by 2 or more MODERATE nodes or arrows, and an unresolved result blocks truth-warrant.

## 12. MIRACLE / REVELATION / PROPHECY / AUTHORITY

- Phase I is mandatory on any miracle, revelation, prophecy or revelation-dependent authority tag. It is candidate-symmetric, and a serious live background can also trigger it.
- The independent A4 typing review controls trigger assignment, and relabeling cannot bypass Phase I.
- I1 forbids installing naturalism, supernaturalism, "sincerity suffices", or "unknown beats supernatural" or the reverse.
- Separate miracle, revelation and prophecy sequences keep report, transmission, historical core, anomaly, causal class, admissibility, agent and consequence distinct. UNKNOWN and UNSPECIFIED are residual statuses, not winners.
- Priors must be stated, applied symmetrically and sensitivity-tested, or not used.
- I4 re-runs every dependent judgment per background and combination, and ranking flip and truth-warrant flip are separated.

## 13. PHILOSOPHY / SOURCE QUALITY / CONTINUITY

- Phase H records the argument form, premise-warrant category, defeaters, rival frameworks and sensitivity. The category list includes worldview/foundational. Intuition is defeasible, and parsimony is never an automatic winner.
- Phase J has no lexical source hierarchy. Earlier is not better and later is not worse. Dependence is graded.
- Phase M carries C0–C7 as relation types, not a ladder. It includes a no-jump rule from C0/C1 to C6/C7 and an independent-reinvention null that is preserved whether or not it is favored.
- Origin, development, meaning and truth stay separate.
- The Charter's "multiple frameworks preserving true components" outcome is reachable via proposition-level dispositions and the `REVISED_CANDIDATE_REQUIRED` routing result.

## 14. AUDIT SEMANTICS / AGGREGATION / DISPUTE HANDLING

**Severity and outcome rules**
- Severity, outcome and topic vocabularies are coherent. The fifteen decision surfaces are fixed.
- MINOR clusters are defined: 3 or more on one surface, or an interacting pair.
- PASS vs PASS_WITH_LIMITATIONS is explicitly not a material dispute when the canonical action is the same.

**Disputes**
- Registered audits cannot be silently discarded.
- A dispute produces `DISPUTED_AUDIT`, which blocks qualification and brings in a lineage-disjoint arbiter and a non-deleting reconciliation record.
- Any BLOCKING or MAJOR finding keeps §0 item 3 failing until repair, so there is no majority shopping route.

**NOTES**
- **NOTE-8:** the protocol never says how a `DISPUTED_AUDIT` closes short of repair or another audit. This is conservative, since it blocks.
- Two mandatory-topic lists exist (O2 with 17 topics, O9 with 15). O9 is explicitly the qualification set.

## 15. STATE / QT1-QT2 / GOVERNANCE RATIFICATION

**What is closed**
- QT1 has an enumerated allowed-field list. QT2 may change only `updated_at` and `qualified_protocol.qualification_transition_commit`.
- Neither may touch canonical adjudications, evidence, negative knowledge, reopen conditions or governed text.
- QT2 supplies QT1's own commit SHA, so the transition is not self-referential.
- QT1 can't set `held` entries, so it can't authorize `TFP-STRESS-2`, and qualification is stated not to authorize a theological study.
- Any substantive change to the governed sources invalidates the audit. The P6 and P3 schemas match STATE field for field.
- The audited STATE blob stays immutable evidence.

**NOTE-5, harmless inconsistencies**
- QT1 can't update `qualification_candidate.qualified: false`, nor the `held[MAJOR-DOCTRINAL-COMPARISON].reason` text "no protocol is yet qualified".
- The STATE invariant that `qualified_protocol` is the sole authority resolves both.
- Protocol P6 says "Q2/Q1" where the rest of the file says "QT2/QT1", and "Q" is also a phase letter.
- Identity of the audit, acceptance and ratification artifacts is pinned through the QT1 commit tree, not through per-artifact blob SHAs.

## 16. UNCERTAINTY / STOP / CHALLENGE / REOPEN / SUPERSESSION

- Confidence (HIGH / MODERATE / LOW) is defined by non-overlapping capability tests.
- The stop rule requires an auditable coverage record before low information gain can justify stopping.
- The stop and reopen rules, adjudication lifecycle states and `reopen_if` requirements are present.

**MINOR-2 — Challenge-lifecycle gaps (surface 13)**
- A qualifying defect report automatically creates `QUALIFICATION_CHALLENGE_PENDING`. The program lead must record it, and an independent triage reviewer classifies it.
- Four things are unspecified:
  - what a PENDING protocol permits (G0 authorizations and G5 acceptances are not paused until a CREDIBLE classification);
  - a triage deadline;
  - the transition out of PENDING after NONCREDIBLE or INSUFFICIENT_DETAIL;
  - any appeal route.
- Suppression is blocked at the recording step. Delay and a stuck PENDING status are not blocked.
- The human owner retains authority and STATE is public, so I rated this MINOR.

## 17. COLD-START REPRODUCIBILITY

Using only the five governed files, the manifest, the role-control record and the regression blob, an unfamiliar successor can recover:
- the authority chain and role boundaries;
- the qualification act and QT1/QT2;
- severity and aggregation rules;
- the base-outcome table;
- the amendment and ledger procedure;
- the audit handshake;
- the stop and reopen rules.

Every outcome-determinative step is either a stated rule or a documented-judgment step inside a `SUFFICIENCY_RECORD` or DIRECTION_RULE. I found no undocumented outcome-determinative rule (O8), so topic 14 is not a FAIL.

**NOTE-9:** templates are missing for some reviewer outputs (coverage-state review, confidence and fragility review, adverse-source probe, audit reconciliation, A16 map, qualification acceptance and ratification records). Their required contents are in prose, so this is non-outcome.

## 18. REGRESSION / INTERNAL CONSISTENCY

- Governance 0.1.5 versus the operative 0.1.0: every 0.1.0 section survives. 0.1.5 tightens or extends §2, §3, §5 (G6 challenge), §6, §15, §17 and §20, and drops nothing.
- Charter 0.1.1, STATE, Governance and Protocol agree on precedence and on the STATE-controlled operative status.
- The Method Seed vocabulary is a subset of the Protocol's.
- Internal seams (the NOTES above) are drafting issues, not contradictions of authority.
- **NOTE-11:** the protocol has two static candidate-status strings (the header and §24). §0 designates such text as historical metadata.
- **NOTE-13/14:** the meaning of `NONE_ADEQUATE` says "evidentially inadequate" while the table counts 0 ADEQUATE, which includes structural inadequacy. Subtype selection for `UNDERDETERMINED` when several apply is unprioritized. Neither is outcome-determinative on its own.

## 19. ADVERSARIAL ATTACK RESULTS

Rule citations are Protocol sections unless noted.

| Attack | Result and governing rule |
|---|---|
| Hide or demote a necessary proposition | Blocked: A6 operational test plus independent confirmation. |
| Candidate-specific burden as SHARED_FLOOR | Blocked: A6 definition, frozen against the G0 set, and review of the exclusion that would create it (B4). |
| MATERIAL-only coverage of a necessary proposition | Blocked: A6 and A11. |
| Invent direction criteria after evidence | Blocked: A11 freeze, direction-result review, C4. |
| Ranking with a candidate-specific proposition below threshold | Blocked: A12 map. |
| TRUTH_WARRANTED with a necessary proposition below SUPPORTED | Blocked: N3 condition 4. |
| 0/1/multiple adequate or ranking-eligible edge cases | Blocked, with caveats: rows 3–9. Background-dependent statuses carry NOTE-1 and MINOR-1. |
| No base outcome at all | Blocked: ordered, exhaustive table. |
| Two conflicting base outcomes | Blocked: first satisfied row wins, subject to NOTE-1. |
| CLOSEST_TO_TRUTH by hidden weighting | Blocked: N3 dimension rule and no global score. Pre-selection residue is NOTE-3. |
| Declare unperformed search UNMAKEABLE | Blocked: A11, "unperformed search is never UNMAKEABLE". |
| Manufacture MAKEABLE | Blocked: certifier plus COMPARISON-scoped review; uncertified is COVERAGE_UNCERTIFIED (E3). |
| Same lineage for source-plan and adverse-source review | Blocked: A3, E3 and Governance §3. |
| Manipulate background granularity | Blocked: A8.2/A8.3 reviews and re-run results decide flips. |
| Convert a truth-warrant-only flip to ranking underdetermination | Blocked: I4 rules 1–2. |
| Preserve BEST_SUPPORTED when ranking flips | Blocked: I4 rule 1 and N3 row 7. |
| Improve a confirmatory outcome via favorable amendment | Blocked: C4 rules 3–5. Remedy residue is NOTE-2. |
| Evade POST_EVIDENCE_DIRECTIONAL_CONTAMINATION | Blocked: independent direction and ledger review. Exposure-scope residue is NOTE-4. |
| Omit exposure from the ledger | Mostly blocked: attestation, integrity review at each amendment, and G4 audit. Deliberate false attestation can't be prevented by any protocol. |
| Truth-warrant with LOW necessary nodes | Blocked: L4 and N3 condition 9, no waiver. |
| Smuggle confessional or secular commitments as public evidence | Blocked: A4 worldview rule, premise-warrant categories, I1. |
| Bypass revelation or authority triggers | Blocked: I2 candidate-symmetric trigger and typing review. |
| Shop among conflicting audits | Blocked: registration, disclosure, `DISPUTED_AUDIT`, arbiter (O-phase). |
| Treat PASS vs PASS_WITH_LIMITATIONS as a material dispute | Blocked: audit-terminology definition. |
| Skip Governance ratification | Blocked: Gov §21 and Protocol §0. |
| QT1/QT2 altering research truth, negative knowledge or adjudications | Blocked: QT1/QT2 prohibitions and allowed-field list. |
| Self-referential qualification transition | Blocked: QT2 design. |
| Qualify a later branch-tip protocol | Blocked: manifest pins the commit and blobs, and P6 records `protocol_blob_sha`. |
| Suppress a credible post-qualification challenge | Partly blocked: recording is mandatory, but delay and stuck PENDING are not blocked (MINOR-2). |
| Reproduce the outcome matrix by shallow slogan | Blocked: the mandatory `HEURISTIC_MATRIX_AUDIT` and topic-14 FAIL_MAJOR rule. |
| Choose a favorable "current background" for base-outcome counting | Partly blocked: A8 forbids silent installation and I4 requires per-background re-run. A residual seam exists (NOTE-1). |
| Exploit route assignment (PARTIALLY_SUPPORTED allowed under COMPARATIVE_ROUTE, not under NONCOMPARATIVE) | Largely blocked by independent necessity and route-symmetry certification (A6); residue is NOTE-7. |

## 20. MANDATORY TOPIC STATUS TABLE

Protocol-qualification topics, O9:

| # | Topic | Status |
|---|---|---|
| 1 | Authority/governance consistency | PASS (NOTE-10) |
| 2 | Role/strict-independence and actor-lineage provenance | PASS; LIMITATION 4 applies |
| 3 | Candidate/background symmetry | PASS |
| 4 | Evidence acquisition/provenance/coverage | PASS |
| 5 | Claim typing and sufficiency | PASS; LIMITATION 1 applies |
| 6 | Amendment/change control and exposure ledger | PASS (NOTE-2, NOTE-4) |
| 7 | Lane/proposition consolidation | PASS |
| 8 | Discriminator priority, inferential bridge, base-outcome partition | **FAIL_MINOR** (MINOR-1; NOTE-1, NOTE-3, NOTE-7) |
| 9 | Miracle/revelation/prophecy | PASS |
| 10 | Philosophy/source/continuity | PASS |
| 11 | Audit semantics | PASS (NOTE-8) |
| 12 | STATE/schema/legacy alignment | PASS (NOTE-5) |
| 13 | Uncertainty/stop/reopen | **FAIL_MINOR** (MINOR-2) |
| 14 | Cold-start reproducibility | PASS; LIMITATION 1 applies (NOTE-9) |
| 15 | Immutable identity and regression/consistency | PASS (NOTE-5, NOTE-11, NOTE-13, NOTE-14) |

Prompt focus items 1–22:
- PASS: items 1–8, 14, 15, 17, 19, 21 and 22.
- PASS with notes: items 10 and 11 (NOTE-3, NOTE-7), 12 and 13 (NOTE-2, NOTE-4), 16 (NOTE-1), 17 and 18 (NOTE-8, NOTE-5).
- FAIL_MINOR: item 9 (MINOR-1) and item 20 (MINOR-2).

## 21. REQUIRED REPAIRS

**NONE.**

No BLOCKING or MAJOR defect exists. The two MINORs don't form a protocol-defined repair-triggering cluster. They are on different surfaces, and neither surface reaches three. The two don't interact: they feed different transitions (outcome-row selection vs post-qualification lifecycle status).

I considered whether NOTE-1 and MINOR-1 might interact, since both touch which base-outcome row applies. I kept NOTE-1 as a NOTE because N2 Step 1 and Step 4 use "eligibility" for the whole A12 status, and I4 states it governs all background-sensitive outcomes. That gives a coherent conservative reading. If the human owner reads NOTE-1 as a defect, the pair would trigger `REPAIR_REQUIRED`.

## 22. LIMITATIONS

Carried limitations 1–4 are **legitimate, not hidden BLOCKING or MAJOR defects:**

1. **Disciplined expert judgment inside sufficiency and disposition steps.** It is bounded by named mandatory elements, `SUFFICIENCY_RECORD`s and frozen direction rules. It doesn't reach dominance, source selection, background selection or eligibility. Defeater-class classification (NOTE-6) falls inside this limitation.
2. **Genuine ranking framework-dependence** (`FRAMEWORK_DEPENDENCE`). It is triggered only by an actual RANKING_FLIP from re-run results.
3. **Truth-warrant-only framework dependence with stable ranking.** I4 rule 2 prohibits TRUTH_WARRANTED while preserving the relative result.
4. **Procedural AI independence.** The actor-lineage rule is explicitly procedural. It applies to this audit too: I am a single Anthropic session with shared model-family priors, and I did not use subagents.

Findings carried by this audit, per O7, to be copied into the acceptance record, STATE and downstream-use constraints:
- **MINOR-1.** A study preregistration should freeze its `INSUFFICIENT_SIGNAL` threshold (the A14 condition) before evidence.
- **MINOR-2.** The challenge lifecycle should be supplemented in a future protocol version.
- **NOTES 1–14,** including the NOTE-1 interpretation point in §21.

## 23. QUALIFICATION DECISION

**Is this exact Protocol 0.1.7 governed bundle ready to be considered for human-owner qualification?**

**Yes.** The bundle at `b9854f8521193c44e3ed50f5a8b1672572674ec5` (protocol blob `0d9406d9ea62ec35ce6424b60ef03ced5dbd332a`) returned `PASS_WITH_LIMITATIONS` with no BLOCKING or MAJOR defect.

I do not qualify it, and I do not authorize TFP-STRESS-2 or any theological study. Qualification still requires human-owner acceptance, ratification of the exact Governance 0.1.5 blob `02338ce3…`, and the QT1/QT2 transition. The human owner should confirm the 39-character SHA in my launch prompt was a typo.

**STOP.**