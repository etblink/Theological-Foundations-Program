# TFP-STRESS-2: Reviewer B re-review of packets, source plan, and coverage (report 0.1.0)

**Prompt:** `TFP_STRESS_2_REVIEWER_B_PACKET_SOURCE_COVERAGE_REREVIEW_PROMPT_0_1_0.md`
**Date:** 2026-10-06
**What this is:** a pre-G0 control re-review. It is not an evidence review, a ranking, G0 authorization, or G1.

---

## 1. SESSION / SOURCE IDENTITY

| Field | Value |
|---|---|
| Provider / model | Anthropic / `claude-opus-5-5`. The session record shows configured model = session model = last-served model = `claude-opus-5-5` (checked with `get_session` at the start of my original review in this same conversation). |
| Session ID | `session_01TsM4WriYnAiRn71ireaVfK` |
| Same Reviewer B lineage | **Yes.** This is the same continuous conversation that produced `TFP_STRESS_2_REVIEWER_B_G0_CONTROL_REVIEW_REPORT_0_1_0.md` (blob `bfa73b9e…`, commit `2c3a852`). |
| Saw any Reviewer A report or reasoning since the original report | **No.** I opened no Reviewer A report. The permitted artifacts contain frozen disposition strings and provenance pointers naming Reviewer A. Under prompt §1 these are not direct exposure. |
| Saw external resurrection evidence in this turn | **No.** No web access. I opened none of the formulation sources the packets name, and searched for nothing. |

**Source identity.** Every pinned blob was checked with `git rev-parse HEAD:<path>` on branch `research/tfp-stress-2-resurrection-g0` (HEAD `dac30d0`). Content was then read only with `git cat-file -p <blob>`.

- All 14 control artifacts in prompt §3 match.
- All 15 packets in manifest 0.1.1 match:
  - 11 status-bearing packets;
  - the R-PHYS refinement packet;
  - 3 node-rival packets, including the noncrucifixion packet **0.1.3**, blob `02d543418536e6e38adf0b6abb5b2f3b0bc461fa`.
- Protocol 0.1.7 (`0d9406d9…`) and Governance (`02338ce3…`) match at commit `b9854f85…`.

I did not open the superseded S2/S3 packets. I did not open the amendment files referenced by the register (S2/S3/P-CRUC amendments, the 224199 verification), because prompt §3 does not list them.

**Exposure to be appended to the ledger.** This review exposed the Reviewer B lineage to the 14 control artifacts and 15 packets above. It involved no external sources.

---

## 2. OVERALL DISPOSITION

| Surface | Disposition |
|---|---|
| Packet set | **`STEELMAN_EQUAL_STRENGTH_REPAIR_REQUIRED`** |
| P-CHET-BODY | **`P_CHET_BODY_CONTROL_REPAIR_REQUIRED`** |
| Source plan | **`SOURCE_PLAN_REPAIR_REQUIRED`** |
| Coverage | **`NECESSARY_PROPOSITION_COVERAGE_REPAIR_REQUIRED`** |
| Q1 | **`Q1_CONTROL_REPAIR_REQUIRED`** |
| **Overall** | **`G0_REVIEW_REPAIR_REQUIRED`** |

There are 0 BLOCKERs, 6 MAJORs, and 3 MINORs, plus notes.

The repair work since my first report is substantial and mostly successful:

- B-2, M-4, M-8 and M-9 are closed.
- The coverage map now lists every necessary proposition, and each has exactly one route.

Six bounded MAJOR defects remain. Each changes either a candidate's burden or how an outcome is reported, so each must be repaired before Reviewer C. All six can be repaired before any evidence is gathered.

---

## 3. ORIGINAL REVIEWER-B FINDINGS CLOSURE MATRIX

| Original finding | Status | Basis / residual |
|---|---|---|
| **B-1** Coverage map not certifiable | **PARTIALLY_CLOSED** | Every proposition in the 11-candidate register is in the map. I checked this mechanically: none missing, none extra, no duplicates. Each entry has one route. Every COMPARATIVE entry names at least one discriminator proposed as CRITICAL. Every NONCOMPARATIVE entry has a direct route. The section-23A fields are present. *Residual:* NB-1 (route asymmetry) and NB-2 (P-CHET-BODY semantics). |
| **B-2** Positive embodiment definition | **CLOSED** | EMB-1/2/3 are positive, conjunctive, and tied to evidence classes. V must fail EMB-1 or EMB-2. Nonidentity failures of EMB-3 route to the node rival. The background rule bars text meaning from proving occurrence. |
| **M-1** Symmetric route principle | **PARTIALLY_CLOSED** | The principle is written (`route_principle.symmetry`). Its application is asymmetric for R's occurrence and identity facets (NB-1). |
| **M-2** Submodel status / evidence binding | **PARTIALLY_CLOSED** | Status is closed: R-PHYS is non-status; H is split three ways; S2/S3 became node-only; umbrellas are not status-bearing. The binding rule is written. *Residual:* the body-evidence binding for R-TRANS and F can be chosen after exposure (NB-3). |
| **M-3** Q1 threshold | **PARTIALLY_CLOSED** | Closed: the causal ladder, PRE-PAULINE, PAUL-A/B/C with symmetry, the stream / same-stream / split-result rules, the existential-quantifier guard, the answer table, and SUPPORTED as the positive threshold. *Residual:* row 6 of the answer table is placed before row 7 (NB-6). |
| **M-4** Founding-proclamation identification and freeze | **CLOSED** | The generic criteria, the existence/content split, the ledgered freeze before direction results, and C4 re-identification are all in place. |
| **M-5** Insufficient-signal hardening | **PARTIALLY_CLOSED** | All six cases are now closed by rule (Q1 control `insufficient_signal_hardening` and source plan `inaccessible_source_rule` / `absence_rule`). *Residual:* the prospective truth-critical designation is incomplete, and the meaning of `expected_extant` is ambiguous (NB-5). |
| **M-6** C-HET fields | **PARTIALLY_CLOSED** | The 12 required fields are present: closed interactions, a frozen evidence-class taxonomy, no optional modules, predicted and contradiction patterns, non-subsumption, and Q1 entailment. *Residual:* P-CHET-BODY (NB-2). |
| **M-7** Source-plan strata and service map | **PARTIALLY_CLOSED** | Strata SRC-01 to SRC-19 are concrete, and a service map, a formulation/evidence split, and substitutes all exist. *Residual:* NB-5, plus the SRC-05 mapping in NB-3. |
| **M-8** Pre-G0 exposure ledger | **CLOSED** | The ledger has been active before G0 since sequence 1. All formulation sources in both source records appear as entries 7–15 and 27–35. Internal repairs are entries 36–37. |
| **M-9** Empirical background retirement | **CLOSED (Reviewer B surface)** | Former BGD-4 to BGD-8 moved to the empirical-model register. There is a rule that a CONTRADICTED premise cannot force a ranking flip, and every live background has retirement conditions. See §11. |
| m-1 S-label collision | CLOSED | Strata are now SRC-nn. |
| m-2 One-sided absence clause | CLOSED | `absence_rule.symmetric: true`. |
| m-3 Stale references | **REOPENED (new instances)** | See MINOR NM-1. |
| m-4 P-HIST-JESUS shared floor | CLOSED | A B4 exclusion is recorded. The text was sharpened to "identifiable as". There is a direct route plus a nonhistoricity steelman. |
| m-5 Reviewer B role coupling | CLOSED | Reviewer B recuses from post-G0 ledger-integrity, direction-result and confidence roles. Reviewer D was created. |
| m-6 Finalization sequence | CLOSED | `g0_finalization_sequence` steps 1–9. |

---

## 4. STEELMAN EQUAL-STRENGTH REVIEW

**Disposition: `STEELMAN_EQUAL_STRENGTH_REPAIR_REQUIRED`**

### 4.1 What passes

| Check | Result |
|---|---|
| Strongest version rather than easiest to refute | R-TRANS deliberately uses the common-denominator embodied core and does not load continuity, which strengthens it. Each of V, H-*, L, F and C-HET has a caricature-rejection list that removes weak versions ("mass psychosis", "disciples lied because skeptics say so", "some of everything"). **PASS** in content. |
| Necessary propositions and causal-role burdens preserved | Each packet's `necessary_propositions` matches register 0.1.9 exactly. Each `internal_success_conditions` restates the profile in the causal-partition artifact. **PASS** |
| No mechanism borrowing after exposure | The register's `no_candidate_switching_after_exposure`, the partition's unmatched-vector rule (→ REVISED_CANDIDATE_REQUIRED), and the manifest's `no_packet_may_absorb_unlisted_mechanisms`. **PASS**, except for the body-evidence binding (NB-3). |
| Synthetic candidates disclosed | V, H-IND, H-SOC, H-SEED-SPREAD, L and C-HET-* are explicitly SYNTHETIC. R-TRANS is SYNTHETIC_COMMON_DENOMINATOR. **PASS** |
| Formulation sources not counted as event evidence | Every source is tagged `FORMULATION_ONLY…` with an `anti_overreach` statement. SRC-17 is `FORMULATION_ONLY_UNLESS_INDEPENDENTLY_ELIGIBLE_AS_EVIDENCE`. **PASS** |
| Expected and weakening evidence meaningful | The packets give expected evidence plus recognized objections. The coverage map gives per-proposition weakening evidence. **PASS** |
| No support merely from rival failure | Stated explicitly in H-IND, F and C-HET, and in register `candidate_failure_does_not_strengthen_rival_by_default`. **PASS**, except P-CHET-BODY clause 1 (NB-2). |
| R-PHYS non-status, no sibling burden | `N3_competitor: false`, `truth_warrant_gate_for_R_EVENT: false`, `R_sibling_non_rivalry_rule`. **PASS** |
| V realist and nonembodied | It requires an extramental referent (not H), identity, and failure of EMB-1 or EMB-2 (not a weak R). Its own objections disclose that the proponent source may be less technically realist. **PASS** |
| H-IND / H-SOC / H-SEED-SPREAD causally disjoint | Under the partition, H-IND needs IND=PRIMARY with SOC nonnecessary. H-SOC needs SOC=PRIMARY with IND nonnecessary. H-SEED-SPREAD needs both necessary. The three are pairwise disjoint on the IND/SOC necessity boundary. Interpretation is nonnecessary in all three, which separates them from C-HET. **PASS** |
| L requires M-INTERP PRIMARY and does not absorb experience | `experience_nonprimary_definition` excludes NECESSARY_CONTRIBUTING experience. P-L-ENCOUNTER-CLAIM-ORIGIN is separately burdened. **PASS** |
| F requires positive knowing deception and does not equate error with fraud | `fabrication_definition`, P-F-DELIBERATE on a NONCOMPARATIVE route, and the error/development exclusions. **PASS** |
| C-HET closed conjunctions | Closed interactions, no optional modules, and a contradiction pattern for each profile. **PASS**, except M-BODY (NB-2). |

### 4.2 Defects

**NB-3 (MAJOR): Body-evidence binding can be chosen after exposure for R-TRANS and F.**

R-TRANS:
- Q1 control lists "body/tomb/disposition evidence where relevant" as an EMB-2 evidence class.
- The register lets body evidence bear on R "only through a registered expectation tied to EMB-1/2/3".
- The R-TRANS packet's `expected_evidence` registers no body/tomb expectation. It registers only "evidence capable of satisfying spatiotemporal/causal embodiment".

The result is that after exposure an analyst can treat favorable body evidence as EMB-2 support for R-TRANS, or treat unfavorable body evidence as bearing only on the non-status R-PHYS refinement. That is the benefit-without-burden pattern my original M-2 targeted.

F:
- The packet says the strongest form "includes deliberate body removal… but F does not require a tomb/body-removal mechanism unless that subroute is explicitly supported".
- That is an optional subroute switched on by evidence. Positive body-removal evidence would support F, while contrary body evidence only closes the subroute and never weakens F.

**Repair.** For each of R-TRANS and F, freeze one of two positions:

- (a) body/tomb evidence is a registered expectation. Then materially contrary body evidence weakens that candidate under the register's binding rule.
- (b) body/tomb evidence is not registered. Then it is neutral for that candidate, and for R it routes only to P-RPHYS-CONTINUITY.

For F, either freeze the body-removal implementation as a registered disjunct with its own weakening consequence, or exclude it. The source plan must also give SRC-05 to R-TRANS (if (a)), S1 (whose register weakening rule depends on body disposition) and F. See NB-5.

**NB-4 (MAJOR): Formulation sources are unequal in strength for the H family and L.**

The formulation records give:

| Candidate | Formulation sources reviewed |
|---|---|
| R-TRANS / R-PHYS | A tradition-native source and a contemporary scholarly proponent of the full model |
| V | A proponent of the nonphysical-real family |
| S1 | Tradition-native proponents |
| Nonhistoricity rival | A modern proponent |
| F | A historical proponent (Reimarus), from a web mirror whose provenance is limited, plus a secondary summary |
| L | Mechanism sources (Sutton/Le Donne; Galbraith on a later text) plus a 19th-century development theory known only through a secondary summary (Schweitzer on Strauss) |
| H-IND / H-SOC / H-SEED-SPREAD | **Only modern psychology mechanism papers.** No proponent of a subjective-experience model of resurrection origins was reviewed, even as a non-exact family source. |

Synthetic disclosure is honest, but it does not cure the gap:

- Source plan SRC-17's own search rule is "find strongest serious formulation before steelman freeze".
- Protocol B3 requires "strongest serious proponent source(s)", and its equal-strength check covers "source quality".
- The H packets' expected evidence is therefore built only from mechanism analogues. R's comes from proponents who argue directly about the historical case.

**Disclosed limitation.** My general pretrained knowledge (not verified here, and not used as evidence) suggests that modern scholarly proponent formulations of subjective-vision and interpretation-first origin models exist. I have not checked this and do not assert it.

**Repair.** Run and ledger a FORMULATION_ONLY proponent search under SRC-17 for the H family and for L, analogous to V's use of a family proponent. Then either:

- add the strongest proponent formulation(s) and revise expected and weakening evidence where they add argument forms; or
- record a documented negative search with independent confirmation.

For F, a primary-text check of a scholarly edition of the Reimarus formulation would remove the mirror-provenance limitation. This is optional and bounded; the limitation can instead be carried and disclosed.

**NB-2 (MAJOR): C-HET carries a necessary body burden that no comparable candidate carries.** See §6. Requiring P-CHET-BODY makes every C-HET profile strictly harder to make ranking-eligible than its H or L neighbour. That burden has no partition function: the C-HET profiles are already disjoint from H and L on the founding role vector alone. This is a steelman defect as well as a P-CHET-BODY defect.

### 4.3 Notes

- **NOTE:** The candidate packets carry no separate `weakening_evidence` field. Only the node rivals do. Section 23A does not require one: A13 weakening evidence is carried by `recognized_objections` plus the per-proposition coverage map. This is uniform across candidates, so it is not asymmetric.
- **NOTE:** The C-HET-SOC expected-evidence item "jointly fit the founding pattern better than either alone" is phrased as comparative fit. D9 should evaluate it through the frozen joint pattern, not as a global fit judgment. **DEFER_TO_REVIEWER_C** for D9 wording.
- **NOTE:** I did not verify that the source summaries are faithful to the external texts (prompt §5). The only fidelity issue I flag is the one visible inside the record (NB-4).

---

## 5. NODE-RIVAL REVIEW

### X-NONCRUCIFIXION-SUBSTITUTION-FAMILY (0.1.3): PASS

- **Section 23A schema:** complete. NOTE: it uses `node_level_propositions` where the template has `necessary_propositions`. That is the appropriate label for a node rival and is not a defect.
- **Source roles:** explicit. Tradition-native sources are `FORMULATION_ONLY__TRADITION_NATIVE` / `…PROPONENT`. Loke is `FORMULATION_ONLY__CRITICAL_DESCRIPTION`, with a B3 limit stated.
- **Per-variant evidence:** each variant has expected and weakening evidence, and the weakening evidence is symmetric. The standard throughout is "independent, convergent identification under the same source-quality and dependence rules".
  - NOTE: some weakening items are formulation-level ("no independent warrant beyond secondary reporting"). They bound a variant's live-ness. They do not bear on P-CRUC evidence, which is acceptable.
- **Argument forms:** native argument forms are FORMULATION_ONLY.
- **Loke counterarguments:** explicitly not pre-applied (`EVIDENCE_LEVEL_NOT_PRE_APPLIED`).
- **D0 / P-CRUC route:** the route plus its sufficiency record can weaken or defeat P-CRUC. This is stated in the register (`P_CRUC_shared_floor_effect`) and the coverage map (`weakening_evidence`).
- **No illicit credit:** the family receives no full-candidate credit (stated several times).
- **Revised-candidate path:** `PROPOSED_REVISED_CANDIDATE_REQUIRED_WITHIN_SCOPE` stays live with an explicit trigger and a no-retrofit prohibition.

### X-NONHISTORICITY-NODE-RIVAL: PASS, with a source-plan dependency

- P-HIST-JESUS is directly testable. The packet states "Minority status or majority consensus is not an evidence type", and the route is a direct sufficiency record.
- Arguments from silence are constrained in principle: absence counts only "where such evidence is prospectively expected and adequately searchable".
- However, no frozen register of prospectively expected evidence classes exists. The source plan's `expected_extant` flag is not that register (NB-5). Until the register exists, the silence constraint is stated but not operational.
- Its planned strata (SRC-01/02/19) also omit SRC-03 and SRC-07, which carry the rival's own native comparanda and development evidence (NB-5).

### X-REAL-REFERENT-NONIDENTITY-NODE-RIVAL: PASS on the packet, with route and source dependencies

- Extramentality is barred from proving identity ("Evidence for a real referent is not double-counted").
- Mere possibility does not block anything. The weakening evidence explicitly includes uncertainty that "arises only from abstract possibility with no case-specific route", and the objections state that logical possibility must not block R/V.
- A specific alternative agent routes to the revised-candidate path.
- The packet's direct route targets **EMB-3 and P-V-IDENTITY-JESUS with a separate identity sufficiency record**. In the coverage map, however, EMB-3 is folded inside the COMPARATIVE P-R-BODY entry while P-V-IDENTITY-JESUS is NONCOMPARATIVE. That inconsistency is NB-1.
- The source plan has no service entry for this node rival (NB-5).

---

## 6. P-CHET-BODY CERTIFICATION

**Disposition: `P_CHET_BODY_CONTROL_REPAIR_REQUIRED`** (finding NB-2, MAJOR)

| Criterion | Finding |
|---|---|
| Sufficiently specific | **No, in the sparse-evidence case.** Clause 1 ("no warranted body-disposition proposition requires an embodied postmortem Jesus") is a negative proposition. The packets let a "frozen complete-search rule" support it. Clause 2 ("every positively supported body fact *used by* C-HET remains compatible…") is empty if C-HET uses no positive body fact. Clause 3 says "mere ignorance… does not by itself satisfy". Take the case where the inventory is complete, no body proposition requires embodiment, and nothing positive is known about the body's fate. The definition does not say whether P-CHET-BODY is then SUPPORTED (clauses 1–2 met) or NOT_ESTABLISHED (clause 3). P-CHET-BODY is on a NONCOMPARATIVE route, so only SUPPORTED permits ranking eligibility. Its outcome in that case can therefore be chosen after exposure. |
| Falsifiable | Yes. The weakening conditions are concrete: body evidence requiring embodiment, a founding deceptive removal (→ F or revised candidate), inadequate coverage, and post-hoc use. |
| Non-residual | **Partly.** Clause 1 is the negation of R's body route. The prohibition "do not infer P-CHET-BODY merely because R is weak" is right, but clause 1 can be met *exactly* by the failure of R's body evidence. The only separate positive content would come from clause 3, whose positive requirement is undefined. |
| Symmetric with R / S1 / F body burdens | **No.** Body-related burdens differ by candidate: C-HET has a **necessary**, ranking-blocking proposition; R-TRANS has none (and its binding is ambiguous, NB-3); R-PHYS has a non-status refinement; S1 has a weakening condition only; F has an optional subroute; H, L and V are neutral. The C-HET profiles are disjoint from H and L on the founding role vector alone (module map `non_subsumption`), so M-BODY necessity serves no partition purpose. A naturalistic vector such as {IND PRIMARY, INTERP NECESSARY_CONTRIBUTING} has only C-HET-IND as its home. Under thin body evidence, C-HET-IND would be ranking-blocked by a burden that H-IND, L and R-TRANS do not bear. |
| Separated from founding causation | Yes. `founding_causal_role: NONE`, and "used post hoc to explain founding subjective experiences" is a weakening condition. |
| Cannot gain merely because R weakens | **Not fully guaranteed**, for the reason in the non-residual row. |

**Repair.** Choose one before evidence exposure, as a PRE_EVIDENCE_AMENDMENT with its direction classified:

- **(A)** Make M-BODY `CANDIDATE_EXPECTATION_ONLY` for C-HET, as it already is for H and L. P-CHET-BODY then leaves the necessary list, and body evidence that requires embodiment remains a contradiction condition. This is symmetric and recommended.
- **(B)** Recast P-CHET-BODY as a contradiction/compatibility condition that is not ranking-blocking. Under this option it can only defeat C-HET, for example when body evidence requires EMB-1/2/3. It can never block ranking for want of positive knowledge.
- **(C)** Keep P-CHET-BODY necessary, but:
  - define its positive content as at least one positively supported ordinary-disposition pathway class from a frozen list;
  - state that the sparse case yields NOT_ESTABLISHED;
  - delete clause 1 as a success condition (keep it only as a weakening condition);
  - record a candidate-native rationale for why C-HET, unlike H and L, must carry a positive body burden.

Whichever option is chosen, the coverage-map entry and the three C-HET packets must change in step with it.

---

## 7. P-CRUC SHARED-FLOOR IMPLEMENTATION CHECK

I have not re-adjudicated Reviewer A's A6 inclusion decision.

| Check | Result |
|---|---|
| One NONCOMPARATIVE_SHARED_FLOOR route, not 11 comparative routes | **PASS.** There is one entry in `shared_floor_propositions`, covering all 11 candidate IDs, with `discriminator_ids: []`. |
| D0 is only a node-rival evidential / sufficiency control | **PASS.** `candidate_selecting_comparative_route: false`. D0 is not in `proposed_critical_discriminators`. |
| D0 does not feed N2 dominance blocking | **PASS.** `feeds_N2_steps_2_3: false`, `dominance_blocking: false`, `unmakeable_blocks_candidate_dominance: false`. Infeasibility routes through the Q1 insufficient-signal rule. |
| No shortfall propagation into P-DEATH etc. | **PASS.** An identical `shared_floor_noninheritance_rule` appears in Q1 control, the coverage map and the admission freeze. P-DEATH is evaluated conditional on P-CRUC. |
| Q1 row 3 handles below-SUPPORTED P-CRUC | **PASS.** Row 3 → `R_EVENT_NOT_WARRANTED_WITHIN_SCOPE`. EVIDENCE_AGAINST and CONTRADICTED route to row 2, because P-CRUC is an affirmative R conjunct. |
| CONTRADICTED P-CRUC cannot yield a winner | **PASS.** `contradicted_shared_floor_rule`: all 11 become INADEQUATE_BY_EVIDENCE, so N3 gives NONE_ADEQUATE. |
| Relative labels carry the conditional qualifier | **PASS.** Q1 `relative_outcome_reporting_rule`, register, admission freeze. |
| Revised-candidate trigger explicit | **PASS.** Identical trigger text in register, Q1, coverage map, packet and admission freeze. |

**Route inconsistencies flagged (MINOR, see NM-2):**

- The coverage certification label `SHARED_FLOOR:P-CRUC` is not in protocol E3's scope vocabulary (STUDY / LANE / PROPOSITION / COMPARISON). It should read `PROPOSITION:P-CRUC`.
- P-HIST-JESUS and P-EARLY-PROCLAMATION-EXISTENCE are repeated in every candidate block, while P-CRUC is centralized. The routes are identical, so this does not change semantics; harmonizing the format would avoid confusion.

**DEFER_TO_REVIEWER_C:** D0's output vocabulary, i.e. how its result maps onto a P-CRUC disposition. It is not a DIRECTION_RULE between candidates, but it still needs a frozen evidence-to-disposition rule.

---

## 8. SOURCE-PLAN CERTIFICATION

**Disposition: `SOURCE_PLAN_REPAIR_REQUIRED`** (findings NB-5 MAJOR, NB-3 SRC-05 part, NB-4 SRC-17 execution)

### 8.1 What passes

- **Concrete strata.** SRC-01 to SRC-19 each have the section-23A fields. The search routes are named (critical editions, INTF/NT.VMR, TLG/Perseus, ATLA, JSTOR, PsycINFO, PhilPapers, citation chaining), with an access note. Exact titles are not required.
- **Original M-7 gaps filled:**
  - Second Temple / scriptural material (SRC-06);
  - Greco-Roman comparanda (SRC-07);
  - comparative movements and reference classes (SRC-16, for BGD-10);
  - postmortem survival and apparition research plus critique (SRC-13, for V);
  - metaphysics of embodiment and identity (SRC-14);
  - formulation-only versus evidence use (SRC-17).
- **Adverse sources and controls.** There is a candidate service map with native and adverse columns. Every candidate has an adverse stratum (SRC-18). The global rules pair every native search with an adverse one, and dependence and provenance are searched separately (SRC-02). Absence handling is symmetric, and the non-extant and inaccessible rules match my original M-5 cases.
- **Adverse probe** assigned to Reviewer C, which keeps it lineage-disjoint from the source-plan reviewer (A9.1 / E3).
- **Pre-G0 exposures ledgered.** Every formulation source in both records appears in the ledger as PRE_G0_FORMULATION_ONLY, so none is silently treated as G1 evidence.
- **No systematic tilt.** Native and adverse service is broadly comparable across candidates, with no systematic favoring of R/V or of naturalistic/deception rivals, apart from the items below.

### 8.2 Defects (NB-5, MAJOR, unless noted)

1. **Per-proposition truth-critical designation is incomplete.** `truth_critical_strata_and_substitutes` designates P-HIST-JESUS, P-CRUC, P-DEATH, P-EARLY-PROCLAMATION-EXISTENCE, P-R-BODY, P-R-FOUNDING-ENCOUNTER and P-V-REAL-REFERENT, plus grouped H, L, S1, F-DELIBERATE and C-HET entries.
   - It omits: P-R-CAUSAL, P-V-IDENTITY-JESUS, P-V-NONEMBODIED, P-V-FOUNDING-CAUSAL, the H-* occurrence / nonveridical / founding-causal propositions, P-L-ENCOUNTER-CLAIM-ORIGIN, P-S1-POSTCRUC-ACCESS, P-S1-FOUNDING-CAUSAL, P-F-ORIGIN-MATERIAL / -MOTIVE / -TRANSMISSION / -FOUNDING-CAUSAL, P-CHET-BODY on its own, and the joint-pattern propositions.
   - The default is safe: an undesignated proposition cannot route to insufficient signal. But it is uneven across candidates. Some candidates' propositions can reach `MISSING_CRITICAL_EVIDENCE` while analogous propositions of others cannot.
   - Q1 row 1 depends on this designation for every affirmative R conjunct, and P-R-CAUSAL is undesignated.
   - My original M-5 Case 4 asked for designation **per necessary proposition**.
2. **`expected_extant` is ambiguous.** It mixes two different expectations:
   - (a) the stratum or sources are expected to exist and be accessible, which governs insufficient-signal routing;
   - (b) evidence for the proposition is expected to exist if the proposition is true, which governs probative absence under E2.

   The `absence_rule` needs (b) ("frozen expectation that applies symmetrically"), but no (b) register exists. The nonhistoricity packet's silence constraint depends on (b). So does any argument from silence for or against R, F, S1 or the node rivals. As written, `false` flags on P-R-BODY / P-R-FOUNDING-ENCOUNTER / P-V-REAL-REFERENT / F-DELIBERATE, and `true` flags on H / L / C-HET / S1, can be read either way after exposure. **Repair:** split the field into `stratum_access_expected` and a frozen, symmetric `probative_absence_expectations` register per proposition.
3. **The nonidentity node rival has no service-map entry.** It needs at least SRC-01 / 02 / 14 plus SRC-18 adverse, and a truth-critical designation for EMB-3 / P-V-IDENTITY-JESUS.
4. **The nonhistoricity route omits the rival's native strata.** SRC-03 (development / reception through about 150 CE) and SRC-07 (comparanda) are where the rival's own native evidence classes sit, and they should be added. Also, the service-map key `X-NONHISTORICITY-AS-FULL-CANDIDATE` does not match the packet ID `X-NONHISTORICITY-NODE-RIVAL` (see NM-1).
5. **SRC-05 (burial / body disposition) serves only R-PHYS, L and C-HET.** S1's register weakening rule depends on body disposition, and F's packet registers a conditional body-removal expectation. Depending on NB-3, R-TRANS's EMB-2 may too. Add SRC-05 to their service and adverse lists in step with the NB-3 resolution. For symmetry, consider adding SRC-05 for H, V and L as an adverse-only route.
6. **SRC-17's search rule was not executed for the H family and L** (NB-4).

None of these requires knowing what the evidence will show.

---

## 9. NECESSARY-PROPOSITION COVERAGE CERTIFICATION

**Disposition: `NECESSARY_PROPOSITION_COVERAGE_REPAIR_REQUIRED`** (findings NB-1 MAJOR, NB-2 MAJOR)

### 9.1 Verified

- Every necessary proposition in register 0.1.9 is in the map for all 11 candidates, either per candidate or through the P-CRUC shared-floor entry. Mechanical diff: 0 missing, 0 extra, 0 duplicates.
- Every entry has exactly one route.
- Every COMPARATIVE entry names at least one proposed-CRITICAL discriminator (D1–D5, D9, D-S1-ORIGIN). Whether each tier is legitimate is **DEFER_TO_REVIEWER_C**.
- Every NONCOMPARATIVE_CANDIDATE_SPECIFIC entry has a direct route, an evidence description and lanes.
- The shared-floor entries are genuinely noncomparative: no discriminators, and the identical-truth-condition checks are recorded.
- The C-HET module routes match module map 0.1.4: proposition IDs, the direct-route pointers, and P-CHET-BODY's text.
- Node-rival sufficiency routes are represented: D0 for P-CRUC, P-HIST-JESUS through its direct route, and the identity rival in P-V-IDENTITY-JESUS's route text.
- No necessary proposition was omitted or demoted.

### 9.2 Defects

**NB-1 (MAJOR): Routes are asymmetric on occurrence and identity facets.**

The map's own symmetry clause says analogous propositions follow the same route principle, and the NONCOMPARATIVE criterion explicitly names "occurrence/mechanism/identity" burdens. Yet:

| Facet | R-TRANS | Comparable rival propositions |
|---|---|---|
| Founding-stream **occurrence** | P-R-FOUNDING-ENCOUNTER → **COMPARATIVE** (D2/D3) | P-HIND-EXPERIENCE-OCCURRED, P-HSOC-GENUINE-SUBJECTIVE-EXPERIENCES, P-HSOC-SOCIAL-PROCESS-OCCURRED, P-HSEED-INDIVIDUAL-EXPERIENCE, P-S1-POSTCRUC-ACCESS → **NONCOMPARATIVE** |
| Personal **identity** | EMB-3 folded into P-R-BODY → **COMPARATIVE** (D3) | P-V-IDENTITY-JESUS → **NONCOMPARATIVE** |

Under protocol A12, PARTIALLY_SUPPORTED blocks ranking on a NONCOMPARATIVE route but not on a COMPARATIVE one. R-TRANS is the only candidate with no NONCOMPARATIVE candidate-specific proposition. A PARTIALLY_SUPPORTED identity or occurrence facet would therefore leave R-TRANS ranking-eligible while blocking V or the H-* candidates. This affects the reported relative labels. The Q1 answer is protected, because rows 4–5 require SUPPORTED.

The nonidentity node-rival packet already gives EMB-3 a separate identity sufficiency record, so the coverage map is inconsistent with that packet.

**Repair.** Either:

- split P-R-BODY's EMB-3 identity facet (and, if analogous, a founding-stream occurrence facet of P-R-FOUNDING-ENCOUNTER) into propositions with the same route as P-V-IDENTITY-JESUS and the H/S1 occurrence propositions; or
- move those H/S1/V analogues to COMPARATIVE with a named CRITICAL discriminator.

Record the choice with a distortion rationale.

**NB-2 (MAJOR):** P-CHET-BODY's success/failure semantics can be chosen after exposure (§6). Under protocol A6, a route whose outcome is choosable cannot be certified.

Coverage certification will be issued once NB-1 and NB-2 are repaired. I have not certified it in this report.

---

## 10. Q1 CONTROL CERTIFICATION

**Disposition: `Q1_CONTROL_REPAIR_REQUIRED`** (finding NB-6 MAJOR; everything else on the original Q1 surfaces passes)

| Surface | Result |
|---|---|
| Positive embodiment definition | PASS (EMB-1/2/3; §3 B-2). |
| Common causal-role threshold | PASS. One four-value ladder. Every candidate's founding-causal proposition uses PRIMARY or NECESSARY_CONTRIBUTING. NOTE: the ladder does not say whether more than one mechanism may be PRIMARY. The C-HET wording "at least one PRIMARY" suggests yes. If not, state uniqueness; no outcome change either way. |
| Pre-Pauline rule and Paul symmetry | PASS (definition; PAUL-A/B/C; `symmetry_rule`). |
| Founding-proclamation identification and freeze | PASS. |
| Insufficient-signal hardening | PASS on rules. The completeness of the designation is a source-plan item (NB-5). |
| Shared-floor consequence logic | PASS (§7). |
| Revised-candidate fallback | PASS (P-CRUC trigger, unmatched role vectors, split-result rule, nonidentity specific-agent trigger). |
| Candidate switching / outcome manipulation | PASS on the structure: no switching, umbrellas not status-bearing, unmatched vectors go to REVISED, same-stream rule. The residual binding ambiguity is NB-3. |
| **Q1 answer table, row order** | **NB-6 (MAJOR)**, below. |

**NB-6: Row 6 comes before row 7.**

- Row 6 assigns `UNDERDETERMINED` whenever "no earlier row applies and N3 yields UNDERDETERMINED_WITHIN_SCOPE".
- Row 7 assigns `R_EVENT_NOT_WARRANTED_WITHIN_SCOPE` when "R-TRANS remains non-prevailing, ranking-blocked, inadequate, or one or more affirmative R propositions are below SUPPORTED".

Suppose P-R-BODY is NOT_ESTABLISHED or PARTIALLY_SUPPORTED, so R-TRANS is ranking-blocked, and N3 is UNDERDETERMINED among rivals (for example H-IND vs L, MIXED_TRADEOFF). Row 6 fires first, and Q1 reads `UNDERDETERMINED` rather than `NOT_WARRANTED`. That softens the Q1 report in R's direction, even though R_EVENT cannot be warranted when any conjunct is below SUPPORTED. It also contradicts the table's own rationale: "rival-sibling inseparability cannot convert a defeated R_EVENT into 'undetermined'". The table protects only EVIDENCE_AGAINST (row 2), not NOT_ESTABLISHED.

**Repair.** Restrict row 6 to cases where both hold:

- (i) R-TRANS belongs to the unresolved set (it is ADEQUATE, and its dominance or ranking is what N3 leaves unresolved, including FRAMEWORK_DEPENDENCE where an R conjunct is SUPPORTED under at least one required background); and
- (ii) no affirmative R conjunct is below SUPPORTED under every required background.

Otherwise the answer falls through to row 7. Alternatively, move row 7's "affirmative R proposition below SUPPORTED under all required backgrounds" clause above row 6.

---

## 11. BACKGROUND / EMPIRICAL-CONTROL BOUNDARY

My original M-9 surface only:

- **Empirical propositions are not hidden as backgrounds that cannot be rebutted.** PASS. Former BGD-4 to BGD-8 are now EMP-* surfaces with ordinary lane dispositions. The background register keeps only framework and method dimensions (BGD-1, 2, 3, 9, 10, 11), and every one states that empirical premises are adjudicated separately.
- **Retirement rules prevent keeping a background alive just to force underdetermination.** PASS. The empirical register has a rule that a CONTRADICTED premise cannot be kept alive as a framework variant. The background register has the same rule for defining premises, and every live variant has `retire_if` conditions.
- **The source plan and the empirical register connect.** PASS. The EMP-* surfaces appear in the SRC served lists (SRC-01/02/04/05/06/08/09/12/14). NOTE: EMP-EXPERIENTIAL-MECHANISM-CAPACITY lists the H/C-HET mechanism propositions but not P-HSOC-GENUINE-SUBJECTIVE-EXPERIENCES. This is harmless because those are occurrence propositions.
- **DEFER_TO_REVIEWER_C:** what study-level label applies when *surviving* empirical-model alternatives (not backgrounds) flip a ranking. The register says they are "not automatically a SERIOUS_LIVE_BACKGROUND", so presumably the label is UNDERDETERMINED with an evidential subtype or a confidence reduction rather than FRAMEWORK_DEPENDENCE. The mapping should be frozen.
- **DEFER_TO_REVIEWER_C:** the BGD-11 × BGD-1 split/merge, and the embodiment × identity compatibility matrix (both already listed as C tasks).

---

## 12. NEW DEFECTS

| ID | Severity | Surface | Summary |
|---|---|---|---|
| NB-1 | MAJOR | Coverage | R-TRANS occurrence and identity facets are on COMPARATIVE routes while the analogous H/S1/V propositions are NONCOMPARATIVE. This conflicts with the map's symmetry clause and with the nonidentity packet's separate EMB-3 route. |
| NB-2 | MAJOR | P-CHET-BODY / packets / coverage | The sparse-evidence outcome can be chosen after exposure. Clause 1 can be met by R's failure. A necessary body burden is unique to C-HET and serves no partition function. |
| NB-3 | MAJOR | Packets / source plan | The body-evidence binding for R-TRANS (EMB-2 class vs packet expectations) and F (optional removal subroute) can be chosen after exposure. SRC-05 is not mapped to R-TRANS, S1 or F. |
| NB-4 | MAJOR | Packets / SRC-17 | H-family and L formulation sources are unequal in strength: no historical-model proponent search was recorded, while R, V, S1 and the nonhistoricity rival received proponent formulations. |
| NB-5 | MAJOR | Source plan | The per-proposition truth-critical designation is incomplete. `expected_extant` is ambiguous and no probative-absence register exists. The nonidentity node rival is unmapped. The nonhistoricity route omits its native strata. |
| NB-6 | MAJOR | Q1 | Answer-table row 6 comes before row 7, so a below-SUPPORTED R_EVENT can be reported as UNDERDETERMINED. |
| NM-1 | MINOR | Clerical | Stale or mismatched references: register `P_DEATH` points to Q1 control 0.1.5; partition 0.1.1 points to Q1 0.1.2 and still shows "PENDING_REVIEWER_A_SHORT_CONFIRMATION" (ledger seq 6 records it complete); the source-plan key `X-NONHISTORICITY-AS-FULL-CANDIDATE` does not match the packet ID; SRC-08's served list omits H-SEED-SPREAD although the service map lists it as native. |
| NM-2 | MINOR | Coverage format | `SHARED_FLOOR:P-CRUC` should be `PROPOSITION:P-CRUC`. Also consider listing P-HIST-JESUS and P-EARLY-PROCLAMATION-EXISTENCE in the same centralized format as P-CRUC. |
| NM-3 | MINOR | F packet / register | F's `q1_relation` ("does not require a veridical postmortem referent") does not say whether F excludes a NECESSARY_CONTRIBUTING veridical founding encounter. L's packet effectively excludes one; F's should say so, or state that the two are compatible. This is a boundary clarification only. |

---

## 13. REQUIRED REPAIRS

All are PRE_EVIDENCE_AMENDMENTs. Each needs a direction classification and a ledger entry.

1. **NB-1:** Make routes symmetric for the occurrence and identity facets. Either split the EMB-3 identity facet (and, if analogous, a founding-stream occurrence facet) out of the R conjuncts, routed to match P-V-IDENTITY-JESUS and the H/S1 occurrence propositions, or move those analogues to COMPARATIVE with a named CRITICAL discriminator. Record a distortion rationale either way.
2. **NB-2:** Choose P-CHET-BODY option (A), (B) or (C) from §6. Update module map 0.1.4, the three C-HET packets and the coverage map to match.
3. **NB-3:** Freeze body-evidence registration for R-TRANS and F, choosing (a) or (b) in §4.2. Add SRC-05 to the R-TRANS (if a), S1 and F service and adverse routes.
4. **NB-4:** Run and ledger a FORMULATION_ONLY proponent search under SRC-17 for the H family and L. Integrate the strongest formulations, or record a documented negative with independent confirmation. Optionally, verify F's Reimarus text against a scholarly edition.
5. **NB-5:** Complete truth-critical strata and substitutes **per necessary proposition**. Split `expected_extant` into `stratum_access_expected` and a frozen, symmetric probative-absence register. Add a service entry for the nonidentity node rival. Add SRC-03 and SRC-07 to the nonhistoricity route and fix its key.
6. **NB-6:** Restrict Q1 row 6 as described in §10, or move row 7's below-SUPPORTED clause above it.
7. **NM-1 to NM-3:** Clerical fixes. These may ride along with the repairs above.

After these repairs, a **narrow Reviewer B confirmation** limited to NB-1 to NB-6 should be enough to issue `SOURCE_PLAN_PASS` and `NECESSARY_PROPOSITION_COVERAGE_COMPLETE`.

---

## 14. NEXT-GATE DECISION

> **Is the TFP-STRESS-2 packet/source-plan/coverage/Q1 control bundle now sound enough to leave Reviewer B's gate and proceed to the fresh, lineage-disjoint Reviewer C discriminator/background/CRITICAL-feasibility review?**

**NO, not yet.** The architecture is close, and every remaining defect can be repaired before any evidence is gathered. But six MAJOR defects change candidate burdens, route semantics or Q1 reporting, and Reviewer C's tiering and direction rules would be built on them:

- route symmetry (NB-1);
- P-CHET-BODY (NB-2);
- body-evidence binding (NB-3);
- formulation strength for the H family and L (NB-4);
- source-plan designation and probative absence (NB-5);
- Q1 row order (NB-6).

Once those are repaired and a narrow Reviewer B confirmation passes, the bundle should be ready for Reviewer C.

This decision does not authorize G0 or G1. It does not mean any candidate is true, likely, or best supported. No candidate was ranked and no resurrection evidence was adjudicated.

**Overall: `G0_REVIEW_REPAIR_REQUIRED`**

**STOP.**