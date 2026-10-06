I'll start with launch control: the two launch-control blobs on the repair branch.

Both blobs match. Next I'll read the role-control record and the manifest to check the assignment.

Launch control passes. Next I'll verify the five governed blobs at the audit commit and read them in order.

Now the protocol itself (89KB). I'll read it in sections.

Now the regression reference, `main:GOVERNANCE.md`.

Before drafting the report, I'll check a few specifics: whether claim types have sufficiency templates, outcome-partition coverage, and a few cross-references.

I'll confirm the session identity through the platform so launch control rests on more than the attribution text.

# TFP Protocol 0.1.6 — Strict Independent Qualification Re-Audit

Line references (`L###`) are to `TFP_ADJUDICATION_PROTOCOL_0_1_6.md` at blob `a43ced9f…` unless noted.

## 1. LAUNCH CONTROL / SOURCE IDENTITY / INDEPENDENCE

| Check | Result |
|---|---|
| Session | `get_session` returned `session_01B3sShWagLWUZLVuRndLHNd`, configured and last-served model `claude-sonnet-5-5`, lineage depth 0. This is the assigned session. |
| Source manifest | `TFP_PROTOCOL_QUALIFICATION_SOURCE_MANIFEST_0_1_6.yaml` is `04e24321…` on the repair branch. ✔ |
| Role-control record | `TFP_PROTOCOL_0_1_6_QUALIFICATION_ROLE_CONTROL.yaml` is `27b4cff3…`. ✔ |
| Role-control assignment | It names Anthropic, `claude-sonnet-5-5`, this session, and `PROCEDURALLY_DISJOINT_FOR_ASSIGNMENT`. It is frozen before the audit and lists no outcome-material qualification reviewers. ✔ |
| Audit commit | `1b9ffb21…` exists. |
| Five governed blobs | All match, read in the assigned order: Charter `22242b48…`, Governance `02338ce3…`, STATE `bbff20c3…`, Method Seed `13717514…`, Protocol `a43ced9f…`. ✔ |
| Regression reference | `main:GOVERNANCE.md` is `45f33617…`, version 0.1.0. ✔ Read last, used only as a baseline. |

**Independence.** I did not read the README, prior audits or dispositions, the repair preregistration or compliance matrix, prior protocol versions, issues or PRs, or later branch-tip versions of governed files.

The governed STATE (a permitted source) names the predecessor audit's headline disposition (`REPAIR_REQUIRED`) and the filenames of several prior artifacts. I opened none of them. I saw no prior audit or repair reasoning, so I am not returning `INVALID_COMPARISON` on independence grounds.

The repository is unmodified. `git fetch` updated only remote-tracking refs, and my one working file is in the scratchpad.

## 2. DISPOSITION

**`REPAIR_REQUIRED`**

- Five MAJOR defects (R1–R5) and fourteen MINOR defects.
- It is not `INVALID_COMPARISON`. The five blobs, manifest and regression reference are consistent, stable and verifiable, so the merits can be evaluated.
- This audit does not qualify the protocol and does not authorize a theological stress test.

## 3. EXECUTIVE FINDING

The architecture is strong, and most of the attacks I tried are blocked by explicit rules. These pieces hold up:

- the necessary-proposition coverage map and total eligibility map;
- the CRITICAL/MATERIAL tiering and MAKEABLE/UNMAKEABLE machinery;
- the RANKING_FLIP / TRUTH_WARRANT_FLIP split;
- the preregistered, non-numeric CLOSEST_TO_TRUTH rule;
- reviewer-lineage separation and the audit-set disclosure rule;
- immutable blob identity.

The defects are concentrated at the joints between mechanisms, where one rule's output has to feed another's input:

- **R1.** The study-outcome partition is not exhaustive.
- **R2.** No rule converts typed dispositions into discriminator direction.
- **R3.** The post-evidence "confirmatory ceiling" contradicts its own worked example.
- **R4.** The Q1 STATE-transition whitelist would leave STATE internally inconsistent.
- **R5.** The role-control record does not meet the Governance, template and STATE requirements for such a record.

R1–R3 are outcome-determinative, and a cold-start successor cannot resolve them without lore.

## 4. GOVERNANCE / ROLES / REVIEWER INDEPENDENCE

**What works**

- Precedence is identical across Protocol §0 and Governance §22.
- The operative-versus-candidate Governance rule is coherent. Governance 0.1.5 governs only the package under evaluation, and Governance §21 requires human-owner ratification of that exact blob.
- Regression against 0.1.0 shows no weakened authority. Every 0.1.0 human-owner reservation is retained or expanded.
- A3, E3 and Governance §3 enforce the three minimum separations:
  - source-plan reviewer ≠ adverse-source reviewer;
  - necessary-proposition reviewer ≠ discriminator-tier reviewer;
  - amendment-direction reviewer ≠ ledger-integrity reviewer.
- The actor-lineage rule is operational. A bare repository checkout or branch name is not lineage descent (L1689).

**Defects**

- **R5 (MAJOR).** The completed role-control record omits several things.
  - Governance §3 "Role freeze" requires candidate protocol and Governance authors, human-owner authorship status, source-manifest preparer, and lineage provenance for every AI role.
  - Protocol template L2270–2297 and STATE `qualification_role_control_policy.required_fields` require the same.
  - The record omits `candidate_protocol_authors`, `candidate_governance_authors`, `human_owner_material_authorship`, `human_owner_outcome_material_reviewer`, `source_manifest_preparer(_substantive_reviewer)` and `operative_governance_baseline_blob_sha`.
  - It also uses non-template field names and has no per-audit `ASSIGNED|COMPLETED|ABORTED` status.
  - Consequences:
    - I can attest disjointness from the program-lead lineage and the 0.1.5 auditor, but not from unnamed protocol and Governance authors.
    - The audit count of 1 (versus 2 under the dual-role rule) rests on STATE fields, not on the record the protocol designates.
  - This is repairable without touching the five blobs. It does block the qualification act as written (§0 item 4: "completed/frozen").
- **M6 (MINOR).** The background-interaction matrix and granularity decisions (A8.2/A8.3) have no named reviewer in A3. Only inclusion and exclusion are reviewed (A8.1), although the template has a `reviewer:` field.

## 5. CANDIDATES / BACKGROUNDS / SYMMETRY

- Admission (B1), blind elicitation (B2), equal-strength steelman check (B3), the late and post-evidence candidate rule (B5), and the symmetric background criteria (A8) all hold.
- Attack results:
  - Background granularity and combinations: the rules are sound, but enforcement is partial because of M6.
  - Silent sampling of favorable combinations is blocked (L373).
- **M9 (MINOR).** "still relevant" and "remains relevant" (L269–275) in the SHARED_FLOOR and CANDIDATE_SPECIFIC definitions are undefined and read as dynamic.
  - If a rival later becomes inadequate, a candidate-specific proposition could arguably be re-read as SHARED_FLOOR, which removes its ranking effect.
  - C4 amendment control mitigates this, but the definition should say "at G0 freeze".

## 6. EVIDENCE / CLAIM TYPES / SUFFICIENCY

- Trigger-tag and typing review is symmetric. Faith commitments and worldview commitments of every subtype need independent public warrant (L240–241).
- Sufficiency templates exist for every claim type except one.
- **M1 (MINOR).** `existential/practical` is a defined claim type (L227, L242) with no Phase G template.
  - `SUPPORTED_WITHIN_SCOPE` requires "applicable mandatory elements all MET". With none defined, the requirement is vacuous.
  - A truth-critical subclaim typed only as existential/practical would escape Phase I and every other template.
  - The typing reviewer (L248–252) is the sole guard.
- **M11 (MINOR).** The MODERATE/LOW confidence boundary overlaps (L1971–1975). MODERATE means "could weaken", LOW means "plausibly downgrade". LOW blocks TRUTH_WARRANTED with no waiver, so the boundary is eligibility-determinative. The independent confidence reviewer mitigates this.

## 7. NECESSARY-PROPOSITION COVERAGE / ELIGIBILITY

- A6, A11 and A12 are well constructed:
  - the operational NECESSARY_FOR_CANDIDATE test;
  - exactly one coverage mode per proposition;
  - MATERIAL-only coverage forbidden;
  - the total disposition-to-eligibility map;
  - a stricter SUPPORTED-only threshold for noncomparative candidate-specific routes.
- Route-choice asymmetry is covered by the "no candidate's burden reduced by asymmetric route assignment" certification (L318).
- **R1 (MAJOR) — the outcome partition is not exhaustive.**
  - A12 (L538) sends "two or more adequate but fewer than two ranking-eligible" to the N3 partition.
  - N3 has no label for zero RANKING_ELIGIBLE with two or more ADEQUATE.
  - A realistic case is two adequate candidates whose candidate-specific necessary propositions are `PLAUSIBLE_BUT_UNATTESTED`, `NOT_ESTABLISHED` or `EVIDENCE_AGAINST`.
  - Outcome 1 fires only on "inadequate for the next outcome tier" (L1491), which is undefined.
  - Outcomes 2–4 do not apply (they need no adequate candidate, exactly one adequate candidate, or exactly one eligible candidate).
  - Outcome 5 covers only two or more eligible candidates, a RANKING_FLIP, or an unresolved tradeoff.
  - Two competent analysts could therefore assign different labels.
  - Contributing ambiguity: A12 defines `ADEQUATE` as "passes all five prerequisites" while `INADEQUATE_BY_EVIDENCE` is defined as "passes structural prerequisites but…", so the statuses overlap instead of partitioning.
  - A rival excluded for prerequisite-4 coverage failure is classed STRUCTURALLY_INADEQUATE. That can make another candidate "only adequate" instead of triggering INSUFFICIENT_SIGNAL. TRUTH_WARRANTED condition 7 blocks the strongest label, but the base label is weakly defined.
  - I considered BLOCKING and rejected it. The gap is repairable and fails toward a conservative reading. It cannot yield an unsupported positive outcome.

## 8. DISCRIMINATORS / MAKEABILITY / INFERENTIAL BRIDGE

**What works**

- Tiers are mutually exclusive and pair-relative.
- A known-infeasible CRITICAL discriminator needs a preregistered INSUFFICIENT_SIGNAL consequence (L460).
- Unperformed search is COVERAGE_INCOMPLETE, never UNMAKEABLE (L481).
- UNMAKEABLE needs a COMPARISON_EFFORT_RECORD, a COMPARISON-scoped coverage review and an independent MAKEABLE_CERTIFIER.
- MATERIAL evidence cannot veto a resolved CRITICAL result.
- The conservative "any UNMAKEABLE CRITICAL blocks" rule is symmetric and fails toward INSUFFICIENT_SIGNAL. It cannot be used to favor a candidate.

**R2 (MAJOR) — no rule maps dispositions to direction.**

- Dominance (N2 Step 2) is computed entirely from `FAVORS_A / FAVORS_B / NEUTRAL / UNMAKEABLE`.
- Nothing states how typed, sufficiency-governed proposition dispositions become a direction.
- NEUTRAL is defined only as "no warranted direction" (L471), and "warranted" is undefined.
- A11 requires a "directional result vocabulary" but not pre-specified decision criteria. A16 does require them explicitly ("what counts as A_BETTER_WARRANTED…"), so the omission in A11 looks accidental.
- No reviewer role is assigned to post-evidence direction calls. The reviews at L448–452 cover tier, symmetry, linkage and feasibility only, before evidence.
- A single FAVORS_A on one CRITICAL discriminator outranks any MATERIAL evidence, with no magnitude. Direction calls therefore carry the whole dominance outcome.
- Carried limitation 1 is scoped to "documented sufficiency/disposition steps" (L1991), so it does not cover this.

Related minors:

- **M8.** On an infeasible adverse-source probe, L797 caps coverage at MATERIALLY_COMPLETE unless a second reviewer confirms no route exists. The COMPLETE definition (L801–802) presupposes a performed probe, and the MATERIALLY_COMPLETE definition (L805) uses "infeasibility independently confirmed". The three passages do not align.
- **M10.** N2 Step 3 re-runs dominance under each background (L1454). A12 eligibility and adequacy are not explicitly re-run per background, although miracle admissibility and similar dispositions are background-relative.

## 9. STUDY OUTCOME PARTITION / CLOSEST-TO-TRUTH / TRUTH-WARRANT

- Precedence is explicit and mostly mutually exclusive. It is not exhaustive (see R1).
- BEST_SUPPORTED correctly requires at least two eligible candidates, full pairwise dominance and ranking robustness. ONLY_ADEQUATE and ONLY_RANKING_ELIGIBLE are explicitly labeled non-ranking and non-truth.
- CLOSEST_TO_TRUTH is a preregistered partial order with no score or weighting (L1537–1547). That blocks hidden weighting.
- TRUTH_WARRANTED has 14 conjunctive conditions, including every necessary proposition SUPPORTED, no LOW node or arrow, and TRUTH_WARRANT_ROBUST.
- **M7 (MINOR).**
  - "independently defeated/redundant" (L1541) has no assigned adjudicator.
  - It is unspecified whether dimension verdicts are re-run per background.
  - TRUTH_WARRANTED and CLOSEST do not state which base outcomes they may attach to. Candidate exclusivity or compatibility is never addressed.
  - MATERIAL_DEFEATER and condition 11 imply that an undominated rival blocks the warrant, but not explicitly.

## 10. AMENDMENT / CHANGE CONTROL / EXPOSURE LEDGER

- C4 classes, relational direction classification, an independent direction reviewer, and distinct ledger-integrity and direction reviewers are all in place.
- Post-evidence source-plan narrowing is presumptively MIXED (L1262).

**R3 (MAJOR) — the confirmatory ceiling contradicts its own worked example.**

- L724 says a defeater against B that improves A's relative standing is FAVORABLE_OR_MIXED. B's adverse consequence is incorporated, but "A may not claim the post-evidence improvement as confirmatory support."
- The ceiling (L1253–1260) says the confirmatory result may move only from (1) to an "equal-or-less-favorable" (2) ADVERSE_ONLY_RECOMPUTED_RESULT.
- Computed per the rule, (2) includes B's adverse effect. That can move UNDERDETERMINED to ONLY_RANKING_ELIGIBLE A, which is a more favorable result for A.
- "Favorable" has no metric across multi-candidate outcome labels. Either:
  - a genuine defeater of a rival is suppressed, contradicting "every ADVERSE effect enters immediately"; or
  - A's standing improves post hoc, which is the very attack the ceiling exists to stop.
- This is outcome-determinative.

**M2 (MINOR).** "Exposure" is undefined (L574–600, L706–712). The ledger integrity reviewer checks sequence continuity and commit history. An exposure that was never recorded leaves no gap, so completeness of the ledger cannot be verified. Reordering and rewriting are blocked.

## 11. LANES / CONSOLIDATION / FRAGILITY

L1–L5 hold:

- Mere repetition never promotes a disposition.
- Chain disposition cannot exceed its weakest link.
- A LOW node or arrow blocks TRUTH_WARRANTED with no waiver.
- Cumulative-fragility review is triggered by two or more partly independent MODERATE links.

The only issue is M11 (the confidence boundary, §6). K6 correctly keeps `INVALID_COMPARISON` as a G4-only outcome.

## 12. MIRACLE / REVELATION / PROPHECY / AUTHORITY

- Phase I is mandatory and candidate-symmetric (L1099–1118).
- Relabeling cannot bypass it, and the typing review covers initial tagging.
- Both naturalism and supernaturalism are barred as silent defaults, and the residual `UNKNOWN` and `UNSPECIFIED_SUPERNATURAL_CAUSE` classes are denied explanatory-winner status.
- Competing revelation claims face the same sequence.
- The remaining weaknesses are M1 (existential/practical escape) and the lack of an explicit mapping from Phase I steps to proposition dispositions. The latter is left to proposition formulation and the strict audit, and I treat it as acceptable.

## 13. PHILOSOPHY / SOURCE QUALITY / CONTINUITY

- Premise-warrant categories, the theoretical-virtue and parsimony rule, the no-lexical-source-hierarchy rule, C0–C7 as relation types, the no-jump rule and the independent-reinvention null are coherent and symmetric.
- This matches the Method Seed and Charter. I found no defects.

## 14. AUDIT SEMANTICS / AGGREGATION / DISPUTE HANDLING

**What works**

- The severity definitions, the MINOR-cluster rules and the pre-launch registration of every audit hold.
- The audit-set disclosure rule works: no registered same-target audit can be silently discarded.

**M3 (MINOR).** The "material disagreement" trigger includes any difference in final audit disposition (L1611–1615). PASS versus PASS_WITH_LIMITATIONS triggers `DISPUTED_AUDIT` and blocks qualification, although both are qualifying and entail the same canonical transition. Reconciliation "cannot delete/replace dissenting audits", and "convergence" is undefined, so the dispute cannot resolve.

**M4 (MINOR).** The reconciliation author is barred only from being a disputed auditor (L1657). It has none of the disjointness requirements imposed on the arbiter. A program-lead-lineage actor could author the record.

M3 and M4 are interacting MINORs on the same gate transition. Under the protocol's own L1631–1632 rule, that forces `REPAIR_REQUIRED` for that surface. For this cycle, one audit is required and two disputing audits are not registered, so the practical exposure is low. The defect remains in the rule.

## 15. STATE / QUALIFICATION TRANSITION / GOVERNANCE RATIFICATION

- The 25-field `qualified_protocol` and canonical-adjudication schemas match STATE field for field.
- The audited snapshot is preserved immutably.
- The Q1 and Q2 mechanical split avoids self-reference.

**R4 (MAJOR) — the Q1 whitelist is under-inclusive.**

- Q1 allows only `updated_at`, `program.active_governance_version`, `program.active_governance_ref`, `program.qualified_protocol`, and certain status fields (L68–75).
- STATE also carries `program.active_governance_blob_sha` (currently the 0.1.0 blob `45f33617…`), `program.candidate_governance_*` and the `qualification_candidate` block. Q1 cannot change them.
- After a literal Q1, STATE would say the active Governance is version 0.1.5 while its blob SHA field still points to 0.1.0.
- Governance §2 defines the operative version as "the version named by canonical STATE".
- No rule says how the ratified blob becomes the ref STATE names: by merging to main, or by pinning to the bundle commit.
- An executor must therefore either leave STATE inconsistent or violate Q1.

**M12 (MINOR).** The notation collides:

- "Q2" means both the finalization commit (§0) and "Phase Q2 — Stop, reopen…" (§22).
- "C4" means both the amendment class (L600) and the continuity relation (Phase M).

**M13 (MINOR).** The role-control record's lifecycle is unspecified. Governance permits later audits to be added, and the template has per-audit status (ASSIGNED/COMPLETED/ABORTED). Adding one changes the blob, so it is unclear which blob SHA the acceptance record and `qualification_role_control_blob_sha` must cite.

## 16. UNCERTAINTY / STOP / CHALLENGE / REOPEN / SUPERSESSION

Phase Q and Q2, the lifecycle states and the `reopen_if` requirement are present. Challenge handling is largely sound: automatic PENDING status, no program-lead discretion over credibility, an independent triage reviewer, and CHALLENGED pausing new studies.

**M5 (MINOR).** The lifecycle has gaps:

- no intake channel or deadline;
- no rule for who appoints the triage reviewer;
- no defined exit transitions for NONCREDIBLE_CHALLENGE and INSUFFICIENT_DETAIL;
- new studies are not paused during PENDING;
- no rule says who decides that a `reopen_if` condition has been met.

A program lead could stall a challenge. The human owner, however, retains final authority.

## 17. COLD-START REPRODUCIBILITY

Given only the five blobs, the manifest, the completed role-control record and the regression reference, a competent successor can recover almost everything: the authority chain, all phases and gates, templates for the main artifacts, and the severity and outcome semantics. A successor cannot recover the following without lore, and these are outcome-determinative:

- **R1.** The study outcome for zero RANKING_ELIGIBLE with two or more ADEQUATE, and when outcome 1 fires.
- **R2.** The criteria for FAVORS vs NEUTRAL, and who issues the direction.
- **R3.** What the confirmatory result is after a rival-defeater amendment.
- **R4.** The correct post-Q1 STATE field values.

Under O8, topic 14 is therefore `FAIL_MAJOR`.

**M14 (MINOR, non-outcome procedural).** Several outcome-material artifacts have no minimum schema, though their prose requirements are sufficient to build one:

- the amendment record;
- COVERAGE_STATE_REVIEW and ADVERSE_SOURCE_PROBE;
- CUMULATIVE_FRAGILITY_REVIEW;
- AUDIT_RECONCILIATION_RECORD;
- HEURISTIC_MATRIX_AUDIT;
- the shared-proposition map and DIMENSION_DOMINANCE_RULE;
- the qualification acceptance and Governance ratification records.

## 18. REGRESSION / INTERNAL CONSISTENCY

- Against Governance 0.1.0, no operating rule, human-owner reservation or conflict-resolution level is weakened. Additions are authority-clarifying.
- Governance 0.1.5, Protocol 0.1.6, STATE and the manifest agree on versions and statuses. Static status text in frozen files is treated as historical metadata, as the protocol states (L98–100).
- The STATE `qualification_candidate.status` ("SOURCE_BUNDLE_NOT_YET_PINNED") is stale in the audited snapshot. That is by design.
- Internal inconsistencies are the ones already listed:
  - R3 (ceiling versus example);
  - R4 (Q1 whitelist versus the STATE schema);
  - R5 (the role-control record versus its own template);
  - M8, M12.

## 19. ADVERSARIAL ATTACK RESULTS

| # | Attack | Result |
|---|---|---|
| 1 | Hide or demote a necessary proposition | **Blocked.** Operational test, pre-evidence freeze, independent anti-demotion review, equal-strength check; post-freeze change is a C4 amendment. Residual: reliance on one G0 reviewer. |
| 2 | Mislabel as SHARED_FLOOR | **Blocked** (L271–275, certification L317). Residual: M9. |
| 3 | MATERIAL-only coverage | **Blocked** (L295, L446). |
| 4 | Ranking with a below-threshold candidate-specific proposition | **Blocked** by the total map (L510–525). PARTIALLY_SUPPORTED is allowed on comparative routes by design, disclosed and barred from truth-warrant. |
| 5 | TRUTH_WARRANTED with a proposition below SUPPORTED | **Blocked** (L1556, shared-floor map). |
| 6 | Exactly-one-adequate or exactly-one-eligible | **Partly blocked.** The labels are non-ranking; BEST_SUPPORTED and CLOSEST are unavailable. **Not blocked:** the zero-eligible case (R1). |
| 7 | Hidden weighting for CLOSEST | **Blocked** (L1547). Residual: M7. |
| 8 | Infeasible CRITICAL poison pill | **Blocked** (L454–460). Residual: conservative UNMAKEABLE blocking. |
| 9 | Unperformed search as UNMAKEABLE | **Blocked** (L481). |
| 10 | Manufactured coverage completeness | **Blocked** (E3, COVERAGE_UNCERTIFIED). Residual: M8. |
| 11 | Same lineage for source-plan and adverse review | **Blocked** (A3, E3, Governance §3). |
| 12 | Background granularity or combination manipulation | **Partly blocked.** Rules exist; reviewer unassigned (M6). |
| 13 | Truth-warrant flip as ranking underdetermination | **Blocked** (I4, L898). |
| 14 | Favorable post-evidence amendment | **Partly blocked.** Direct cases yes; the cross-candidate case is self-contradictory (R3). |
| 15 | Omit or reorder ledger entries | **Partly blocked.** Reordering and rewriting yes; an unrecorded exposure is undetectable (M2). |
| 16 | Truth-warrant with a LOW node or arrow | **Blocked** (L1327, no waiver). Residual: M11. |
| 17 | Smuggle confessional or secular commitments | **Blocked** (L240–252, I1, A8). |
| 18 | Bypass the revelation or authority trigger | **Blocked** (I2). Residual: the existential/practical escape (M1). |
| 19 | Audit shopping | **Mostly blocked.** Pre-launch registration and no-discard hold; M3 and M4 weaken reconciliation. |
| 20 | Qualify a later branch-tip protocol | **Blocked.** Blob-pinned manifest, STATE invariant, and substantive change invalidates the audit (L98). |
| 21 | Abuse the Q1/Q2 transition | **Partly blocked.** Explicit whitelist, but it is under-inclusive (R4) and "status fields needed" is loose. |
| 22 | Suppress a credible challenge | **Mostly blocked.** Auto-PENDING and independent triage; stalling possible (M5). |
| 23 | Shallow slogan reproduction | **Blocked** at study level by HEURISTIC_MATRIX_AUDIT and the FAIL_MAJOR rule (L2049–2080). |

## 20. MANDATORY TOPIC STATUS TABLE

Topics follow O9 (L1817–1833).

| # | Topic | Status | Basis |
|---|---|---|---|
| 1 | Authority/governance consistency | PASS | Note: the candidate Governance defines the standard for its own qualification; ratification mitigates. |
| 2 | Roles / strict independence / lineage | **FAIL_MAJOR** | R5; M6 |
| 3 | Candidate/background symmetry | FAIL_MINOR | M6 |
| 4 | Evidence acquisition / provenance / coverage | FAIL_MINOR | M8 |
| 5 | Claim typing and sufficiency | FAIL_MINOR | M1 |
| 6 | Amendment / change control / ledger | **FAIL_MAJOR** | R3; M2 |
| 7 | Lane / proposition consolidation | FAIL_MINOR | M11 |
| 8 | Discriminator priority and inferential bridge | **FAIL_MAJOR** | R1, R2; M7, M9, M10 |
| 9 | Miracle / revelation / prophecy | PASS | |
| 10 | Philosophy / source / continuity | PASS | |
| 11 | Audit semantics | FAIL_MINOR | M3, M4 (interacting) |
| 12 | STATE / schema / legacy alignment | **FAIL_MAJOR** | R4; M13 |
| 13 | Uncertainty / stop / reopen | FAIL_MINOR | M5 |
| 14 | Cold-start reproducibility | **FAIL_MAJOR** | R1–R4 lore dependence; M14 |
| 15 | Immutable identity / regression / internal consistency | FAIL_MINOR | M12, M13 (blob identity itself verified PASS) |

## 21. REQUIRED REPAIRS

**Must repair (MAJOR):**

- **R1.** Make the outcome partition exhaustive.
  - Add an explicit outcome (or defined subtype mapping) for two or more ADEQUATE with zero RANKING_ELIGIBLE.
  - Define precisely when outcome 1 fires.
  - Turn the A12 statuses into a true partition.
  - Supply a decision table with tests covering 0, 1 and 2+ adequate and eligible candidates, and the prerequisite-4 coverage case.
- **R2.** Specify how dispositions and typed evidence map to FAVORS_A / FAVORS_B / NEUTRAL.
  - Require preregistered decision criteria per discriminator, as A16 does.
  - Assign an independent post-evidence direction reviewer.
- **R3.** Define the confirmatory result for rival-defeater amendments.
  - Specify an ordering or metric for "favorable", or restate the ceiling in terms of per-candidate effects.
  - Resolve L724 against L1259, with a worked example.
- **R4.** Amend the Q1 whitelist.
  - Cover `program.active_governance_blob_sha`, `candidate_governance_*` and associated STATE bookkeeping.
  - State which ref and blob STATE names after ratification.
- **R5.** Complete the role-control record.
  - Conform it to Governance §3, the template and STATE required fields.
  - Name the protocol and Governance authors and the human-owner authorship status.
  - Re-freeze it and re-register the audit before the next audit.

**Must repair or explicitly bound (MINOR):** M1–M14 as listed above.

## 22. LIMITATIONS

Assessment of the four carried limitations:

1. **Bounded expert judgment inside explicit sufficiency rules.** Genuine for `SUPPORTED_WITHIN_SCOPE` and its templates. It does not cover discriminator direction calls, MODERATE/LOW confidence boundaries, or the CLOSEST escape clause. Those are repairable and fall under R2, M11 and M7. As scoped (L1991), the limitation is not a hidden MAJOR.
2. **Genuine ranking framework-dependence.** Genuine. It is labeled, bounded by I4, and has a defined outcome (`UNDERDETERMINED: FRAMEWORK_DEPENDENCE`). M10 is about completeness of the background re-run, not the limitation itself.
3. **Truth-warrant-only framework dependence with stable ranking.** Genuine, correctly separated from ranking flips, and carried without erasing the relative result.
4. **Procedural AI independence.** Genuine and inherent. It is disclosed, and it does not excuse lineage collapse.

None of the four hides a MAJOR or BLOCKING defect, with the scope qualification noted on item 1.

## 23. QUALIFICATION DECISION

- Final audit disposition: **`REPAIR_REQUIRED`**.
- Qualification act items 2 and 3 (§0) are not met. Item 4 is not met until R5 is repaired.
- I do not qualify the protocol and do not ratify Governance. Only the human owner can do either, and only after a clean re-audit.
- No theological stress test is authorized, including the held `TFP-STRESS-2`.
- Any repair changes the five blobs and requires a new immutable bundle, manifest, role-control record and strict re-audit by another fresh independent session.

STOP.