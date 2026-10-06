# TFP-STRESS-2 — Reviewer B Narrow NB-1 to NB-6 Confirmation Report 0.1.0

**Prompt:** `TFP_STRESS_2_REVIEWER_B_NARROW_NB1_NB6_CONFIRMATION_PROMPT_0_1_0.md`
**Date:** 2026-10-06
**Boundary:** narrow repair confirmation only. This is not an evidence review, not a ranking, not G0 and not G1.

---

## 1. SESSION / SOURCE IDENTITY

| Field | Value |
|---|---|
| Provider / model | Anthropic / `claude-opus-5-5` |
| Session ID | `session_01TsM4WriYnAiRn71ireaVfK` |
| Same Reviewer B lineage | **Yes.** This is the same continuous conversation that produced the first G0 control report and the re-review. |
| Reviewer A reports or reasoning seen since the re-review | **No.** I opened no Reviewer A report. The permitted artifacts mention Reviewer A only through disposition strings and pointers. |
| External resurrection evidence seen since the re-review | **No.** I did no web access and opened no formulation or event source. |

**Identity verification.**

- All 18 pinned repository blobs (prompt §§3–4) match on branch HEAD `ced0628`.
- Protocol 0.1.7 (`0d9406d9…`) and Governance (`02338ce3…`) match at commit `b9854f85…`.
- All 15 packets listed in manifest 0.1.2 match their manifest blobs:
  - 11 status-bearing;
  - R-PHYS 0.1.2;
  - nonhistoricity 0.1.1;
  - nonidentity 0.1.1;
  - noncrucifixion 0.1.4.
- Content was read only with `git cat-file -p <blob>`.

**Integrity defect in the pinned prior report (RECORD-1).** The pinned blob `3fff99e9…` for `TFP_STRESS_2_REVIEWER_B_PACKET_SOURCE_COVERAGE_REREVIEW_REPORT_0_1_0.md` matches its pin. Its content, however, is not my report. It is a 155-byte tool-error string ("The requested file reference is not currently visible…").

- The authentic report is held in this same session's scratchpad. That copy is byte-identical to what I delivered (git blob id `1ac620cdc1ca8abbdda8dc375080643442f2c6c2`; sha256 `255612c6…adecfc`).
- Because this is the same lineage, I used that authentic copy as the authoritative definition of NB-1 to NB-6 and NM-1 to NM-3. That is permitted under prompt §3.
- The repair record shows the Program Lead did receive the correct findings. Only the repository preservation failed.
- Ledger entry 39 states the report was "preserved unchanged". That statement is false for the committed blob.
- Because the blob identity itself matches, this is **not** treated as `INVALID_REVIEW`. It does require a clerical/integrity repair (§9).

**Ledger note.** This confirmation exposed the Reviewer B lineage to the 18 control artifacts and 15 packets listed above. It involved no external sources.

---

## 2. NARROW-SCOPE COMPLIANCE

- I reviewed only NB-1 to NB-6 and NM-1 to NM-3.
- I did not reopen any finding I previously marked CLOSED.
- Every residual reported below lies **on one of the six repaired surfaces**, and each was either created by the repair or left directly contradicting it.
- Where a residual traces partly to wording I recommended, I say so.
- I invented no style-only repairs.

---

## 3. NB-1 ROUTE-SYMMETRY CONFIRMATION — **`NB1_OPEN`**

| Check | Result |
|---|---|
| `P-R-BODY` carries EMB-1 + EMB-2 only | **Confirmed.** See Q1 `proposition_definition`, the coverage rationale and the R-TRANS packet. |
| R identity is separately necessary as `P-R-IDENTITY-JESUS` | **Confirmed.** It appears in the register, the packet and the coverage map. The register now has 49 propositions. |
| `P-R-IDENTITY-JESUS` is NONCOMPARATIVE with a direct same-referent route | **Confirmed.** |
| `P-R-FOUNDING-ENCOUNTER` is NONCOMPARATIVE | **Confirmed.** Partial support now ranking-blocks R. |
| Nonidentity node rival targets R and V identity | **Confirmed.** Packet 0.1.1 and the source-plan node map both name `P-R-IDENTITY-JESUS` and `P-V-IDENTITY-JESUS`. |
| Same-stream / Q1 logic requires body plus identity for the same referent | **Confirmed.** See `R_EVENT_existential_rule` and the Q1 conjunct list. |
| P-HIST-JESUS, P-EARLY-PROCLAMATION-EXISTENCE and P-CRUC are centralized without losing direct testing | **Confirmed.** All three are NONCOMPARATIVE_SHARED_FLOOR entries covering 11 candidates, each with a direct route and `sufficiency_record_required: true`. |
| No new asymmetry gives R an easier path | **Confirmed for R.** |

### Residual NB1-R1 (MAJOR): V is now the only encounter candidate without a direct occurrence burden.

The occurrence burdens across the encounter and experience candidates are:

| Candidate | Occurrence burden | Route |
|---|---|---|
| R-TRANS | `P-R-FOUNDING-ENCOUNTER` | NONCOMPARATIVE |
| H-IND | `P-HIND-EXPERIENCE-OCCURRED` | NONCOMPARATIVE |
| H-SOC | `P-HSOC-GENUINE-SUBJECTIVE-EXPERIENCES`, `P-HSOC-SOCIAL-PROCESS-OCCURRED` | NONCOMPARATIVE |
| H-SEED-SPREAD | `P-HSEED-INDIVIDUAL-EXPERIENCE`, `P-HSEED-SOCIAL-AMPLIFICATION` | NONCOMPARATIVE |
| S1 | `P-S1-POSTCRUC-ACCESS` | NONCOMPARATIVE |
| V | none separately | stream occurrence is folded into `P-V-FOUNDING-CAUSAL` (COMPARATIVE, D2) and `P-V-REAL-REFERENT` (COMPARATIVE, D4) |

As a result, a PARTIALLY_SUPPORTED founding stream now ranking-blocks R, the H candidates and S1, but not V. The map's own symmetry clause covers "founding-stream occurrence burdens… for R just as for analogous rivals", and V is an analogous rival.

Before the repair, R and V had the same treatment, so this asymmetry was created by the repair. **My NB-1 table in the re-review omitted V. That was my error, and I disclose it.**

**Repair.** Pick one:

- add `P-V-FOUNDING-ENCOUNTER`, NONCOMPARATIVE on the same frozen stream inventory, with entries in the register, packet, coverage map and truth-critical register (50 propositions); or
- record a principled distortion rationale for why V's occurrence must stay comparative while R's does not.

### Consequential residual NB1-R2 (MAJOR, shared with NB-5): identity and occurrence carry asymmetric absence semantics. See §7.

### Consequential sync NB1-S1 (MINOR, required)

Background register 0.1.4 still lists `P-V-IDENTITY-JESUS` but not `P-R-IDENTITY-JESUS` under `BGD-11.propositions_affected`. BGD-11 is the identity-theory dimension. After the NB-1 split, R identity must also be listed there, and under any other background whose variants affect EMB-3. Otherwise I4 reruns would test V identity for background sensitivity but not R identity. This is a mechanical synchronization. Final granularity and interaction review remain **DEFER_TO_REVIEWER_C**.

---

## 4. NB-2 P-CHET-BODY CONFIRMATION — **`NB2_CLOSED`**

| Check | Result |
|---|---|
| Option A implemented | **Confirmed.** Module map 0.1.5 states `reviewer_B_repair_basis: NB-2 option A`. |
| `P-CHET-BODY` absent from all three C-HET necessary lists and from coverage | **Confirmed mechanically.** It is in no register list, and the string does not occur in coverage map 0.1.9. |
| M-BODY is `CANDIDATE_EXPECTATION_ONLY__NON_RANKING_BLOCKING` | **Confirmed.** Module map shows `ranking_blocking: false` and `success_requirement: NONE`. The partition profiles read `CANDIDATE_EXPECTATION_ONLY`. |
| Sparse or unknown body evidence is neutral | **Confirmed.** All three packets record `sparse_or_unknown_case: NEUTRAL__DOES_NOT_BLOCK_RANKING`. |
| Compatibility cannot raise C-HET status | **Confirmed.** See `non_support_rules` and `M_BODY_cannot_raise_candidate_status`. |
| R or R-PHYS weakness cannot support C-HET | **Confirmed.** |
| Body evidence requiring embodiment may weaken or contradict C-HET | **Confirmed** (`contradiction_conditions`). See NB3-R1 for its cross-candidate consistency. |
| Deceptive founding removal routes to F or REVISED | **Confirmed.** |
| Partition, module map, packets, register and coverage agree | **Confirmed on substance.** The stale status and pointer text is listed under NM-1. |

---

## 5. NB-3 BODY-EVIDENCE BINDING CONFIRMATION — **`NB3_OPEN`**

**R-TRANS: confirmed.**

- `BODY_TOMB_NEUTRAL_FOR_GENERIC_R_TRANS` is frozen in the register and the packet.
- `positive_use` and `negative_use` are both PROHIBITED.
- Body evidence routes only to P-RPHYS-CONTINUITY.
- The `anti_switching` rule is present.
- The EMB-2 evidence class excludes tomb/body evidence.
- SRC-05 is absent from R-TRANS service and assigned to R-PHYS.

**F and S1: partly confirmed.**

- `F-BODY-REMOVAL` is a frozen non-status implementation with a positive-use rule and a weakening rule.
- `no_posthoc_activation` is set.
- SRC-05 is native and adverse for F, and is now in S1's service, packet expectation and truth-critical substitutes.

### Residual NB3-R1 (MAJOR): the body-evidence rule is incoherent across candidates.

| Location | What it says about body evidence |
|---|---|
| R-TRANS | Neutral both ways. Even evidence that "positively requires or strongly supports embodied postmortem continuity" cannot support generic R. |
| C-HET (all three) | That same evidence is a contradiction condition. |
| Source-plan service map | SRC-05 is **adverse** for V, H-IND, H-SOC, H-SEED-SPREAD and L. |
| Candidate register | Body evidence is neutral for V, the H candidates and L unless a packet registers it, and none does. |

So one class of evidence cannot help R, can defeat C-HET, is mapped as adverse to V, H and L in the source plan, and is neutral for V, H and L in the register.

**This combination partly traces to my own re-review wording.** Option A said to keep body evidence as a contradiction condition. The SRC-05 note suggested "adverse-only" routes for H, V and L. The Program Lead then chose the neutral option (b) for R.

**Repair.** Freeze one uniform rule. Either:

- **(i) Uniform neutrality.** Body evidence is neutral for every Q1-ontology candidate (R-TRANS, V, the H candidates, L, C-HET). It bears only on R-PHYS, F-BODY-REMOVAL, S1 compatibility and the revised-candidate and F routing triggers. SRC-05 serves the deniers only as a search route for those triggers, not as adverse evidence. **Recommended, because it matches the chosen R-TRANS neutrality.** Or:
- **(ii) Uniform binding.** Re-register body evidence as a P-R-BODY / EMB-2 expectation for R-TRANS (option (a)), and apply the same contradiction condition to every candidate that denies embodiment.

### Residual NB3-R2 (MAJOR): F's fallback implementation is undefined.

F packet `generic_F_rule` says: "Closure of F-BODY-REMOVAL does not by itself defeat generic F *only if another independently registered non-body deception implementation* satisfies P-F-MOTIVE-OPPORTUNITY-ROUTE."

No other implementation is registered. That leaves two possibilities, and the choice can be made after exposure:

- contrary body evidence defeats F, because no alternative is registered; or
- an alternative is registered later, which would breach `no_posthoc_activation`.

The sentence's logic is also garbled ("does not… only if").

**Repair.** Register the generic non-body implementation (knowing false encounter/proclamation assertion without body action) as a frozen F implementation with its own direct burden. Then rewrite the rule as: "Closure of F-BODY-REMOVAL leaves F dependent solely on the registered non-body implementation; body evidence cannot be borrowed by it."

---

## 6. NB-4 FORMULATION EQUAL-STRENGTH CONFIRMATION — **`NB4_CLOSED`** (with carried limitations)

| Check | Result |
|---|---|
| H packets have direct case-level proponent or family sources beyond mechanism literature | **Confirmed.** FORM-H-PROP-001 (Smith 2019) is used in H-SOC and H-SEED-SPREAD. FORM-H-PROP-002 (Lüdemann) is used in H-IND and H-SEED-SPREAD. |
| Not misrepresented as endorsing exact TFP subtypes | **Confirmed.** `exact_TFP_match: false`, and the packets keep their synthetic-subtype language. |
| L has a direct primary proponent source | **Confirmed.** FORM-L-PROP-001 is Strauss's own work, replacing secondary-only access. |
| Strict L conjunction remains explicitly synthetic | **Confirmed.** |
| Bounded negative modern search disclosed | **Confirmed.** Two non-selections are recorded with reasons and ledgered (entries 43–44). |
| FORMULATION_ONLY and ledgered | **Confirmed.** Ledger entries 40–44 use the `FORMULATION_ONLY` class. |
| Remaining asymmetry material? | **No.** Every candidate family now has at least one direct proponent-level formulation source. Exact-conjunction synthesis is disclosed for V, H, L and C-HET alike. No additional independent search is required to close NB-4. |

**Carried formulation-fidelity limitations.** These do not affect the structural determination.

- (a) Lüdemann's formulation comes from book/publisher metadata (ledger 41), not the text.
- (b) The access level for Smith (full text or abstract) is not stated.
- (c) I cannot verify, within scope, how Strauss's primary text relates to the strict L vector.
- (d) No H or L packet's expected evidence or objections changed after the proponent review. The record should state explicitly that the proponent sources added no new argument forms; this is a documentation-only item. Reviewer C's post-G1 adverse-source probe remains the route for any omitted formulation.

---

## 7. NB-5 SOURCE-PLAN / ABSENCE CONFIRMATION — **`NB5_OPEN`**

**Mechanical comparison: passes.**

- Register 0.1.10 has 49 unique necessary propositions.
- The truth-critical register lists 49, with 0 missing, 0 extra and 0 duplicates.
- Every entry has `required_strata`, `acceptable_substitutes`, `stratum_access_expected` and `probative_absence_expectation`.
- The coverage map plus the three shared-floor entries match the register for all 11 candidates, with 0 missing, 0 extra and no overlap.

| Check | Result |
|---|---|
| `expected_extant` retired | **Confirmed.** It is absent from the truth-critical register; admission freeze shows `expected_extant_retired: true`. |
| Unlisted absence non-probative | **Confirmed.** See the global rules and the source-plan `absence_rule`. |
| ISS tied to access, provenance or coverage failure | **Confirmed.** |
| Nonidentity node rival has a source route | **Confirmed.** SRC-01/02/14 direct, SRC-03/19 substitutes, SRC-18 adverse. |
| Nonhistoricity includes SRC-03 and SRC-07 and uses the frozen P-HIST-JESUS absence rule | **Confirmed.** |
| Service mappings reflect the NB-3 decisions | **Partly.** R-TRANS, F and S1 are right. The SRC-05 adverse mapping for V, the H candidates and L conflicts with register neutrality (NB3-R1). |
| SRC-08 includes H-SEED-SPREAD | **Confirmed.** |
| Node-rival keys match | **Confirmed.** `X-NONHISTORICITY-NODE-RIVAL`. |

### Residual NB5-R1 (MAJOR, also NB1-R2): absence modes are asymmetric between analogous propositions, and "may weaken" is undefined.

| Proposition | Absence mode |
|---|---|
| `P-R-IDENTITY-JESUS` | `CONDITIONAL_WEAKENING_IF_COMPLETE` |
| `P-V-IDENTITY-JESUS` | `NO_PROBATIVE_ABSENCE_BY_DEFAULT` |
| `P-R-FOUNDING-ENCOUNTER` | `CONDITIONAL_WEAKENING_IF_COMPLETE` |
| `P-HIND-EXPERIENCE-OCCURRED`, `P-HSOC-*` occurrence, `P-HSEED-*` occurrence, `P-S1-POSTCRUC-ACCESS` | `NO_PROBATIVE_ABSENCE_BY_DEFAULT` |

The two identity propositions are analogues, and so are the occurrence propositions. The register also does not say whether "may weaken" can reach `EVIDENCE_AGAINST_WITHIN_SCOPE` or only `NOT_ESTABLISHED`. That matters because EVIDENCE_AGAINST on an R conjunct triggers Q1 row 2 (`R_EVENT_EVIDENCE_AGAINST`) and creates a MATERIAL_DEFEATER. Absence could therefore move R to row 2 while analogous rival absences cannot move them comparably, and the size of the effect can be chosen after exposure.

**Repair.**

- Give analogous propositions the same mode: identity for R and V (and V occurrence if NB1-R1 adds it); founding-stream and experience occurrence for R, the H candidates, S1 and the C-HET experience modules.
- Freeze the maximum disposition that absence alone can produce, for example "absence under complete search can yield NOT_ESTABLISHED, never EVIDENCE_AGAINST, unless a separately registered expectation says otherwise".
- Apply the same cap to the shared-floor CONDITIONAL rules: P-HIST-JESUS, P-CRUC, and the DEFINITION_LINKED P-EARLY-PROCLAMATION-EXISTENCE.

---

## 8. NB-6 Q1 PRECEDENCE CONFIRMATION — **`NB6_CLOSED`**

| Check | Result |
|---|---|
| Row 6 requires R-TRANS to be in the unresolved adequate / ranking-eligible set | **Confirmed.** |
| Row 6 excluded when an R conjunct is below SUPPORTED under every required background | **Confirmed.** |
| Otherwise the case reaches row 7 | **Confirmed.** Row 7 now covers "outside the unresolved set" and "below SUPPORTED under every required live background". |
| FRAMEWORK_DEPENDENCE cannot soften a universally below-SUPPORTED R_EVENT | **Confirmed on the natural reading.** Its special clause requires "at least one required background leaves each affirmative R conjunct SUPPORTED". |

**MINOR wording note (NB6-M1).** The first row-6 clause quantifies conjunct by conjunct ("no affirmative R conjunct is below SUPPORTED under every required live background"). Read literally, conjunct A supported only under background 1 and conjunct B only under background 2 would satisfy it. The R_EVENT conjunction would then be supported under no single background. Add "under at least one common required background for all affirmative R conjuncts". This matches the table's stated rationale and does not change the intended logic.

---

## 9. MINOR CONSISTENCY CHECK

**NM-1 (stale references): not closed.** Remaining stale references:

- Register 0.1.10:
  - `family_rules.causal_partition_ref` points to PARTITION_0_1_1 (should be 0_1_2);
  - the noncrucifixion exclusion `steelman_packet_ref` points to `…_0_1_3` (should be 0_1_4);
  - `packet_stage_operationalization` still describes P-CHET-BODY as an "already-required" module awaiting certification;
  - the `X-REAL-REFERENT-NONIDENTITY` reason omits `P-R-IDENTITY-JESUS`.
- Q1 control 0.1.7: `causal_profile_partition_ref` points to 0_1_1.
- Causal partition 0.1.2:
  - `status` still reads `…PENDING_REVIEWER_A_SHORT_CONFIRMATION`;
  - `review.reviewer_A_short_confirmation: PENDING`, although the repair record says this was closed.
- C-HET module map 0.1.5: `founding_fabrication_definition_ref` points to PARTITION_0_1_1.
- Coverage map 0.1.9: node-rival packet refs point to NONCRUCIFIXION `0_1_3` (twice) and NONHISTORICITY `0_1_0`.
- Source plan 0.1.8: header `background_register_ref` points to 0_1_3, `empirical_model_register_ref` to 0_1_1, and the P-CRUC node-rival packet ref to 0_1_3.

**NM-2: CLOSED.** All three shared floors use `PROPOSITION:<id>`, are centralized, and are covered by the `shared_floor_format_rule`.

**NM-3: not closed in the register.**

- The F packet and the repair record are correct.
- In register 0.1.10, **F's** `q1_relation` still reads "Does not require a veridical postmortem referent."
- The new F boundary text was written into **L's** `q1_relation`, replacing L's own entry.
- Fix: restore L's q1_relation, and put the F boundary text in F's entry (optionally also in the partition F profile).

**RECORD-1 (integrity, clerical, required before G0 bundle freeze).**

- Replace the corrupted committed re-review report with the authentic text (blob id `1ac620cd…`).
- Append a ledger correction to entry 39. Do not rewrite it, because the ledger is append-only.

These are clerical and do not alter burdens. They are required in the same repair pass.

---

## 10. SUB-DISPOSITIONS

| Surface | Disposition | Basis |
|---|---|---|
| Packet equal strength | **`STEELMAN_EQUAL_STRENGTH_REPAIR_REQUIRED`** | NB-4 is cured. However, the F packet's undefined fallback implementation (NB3-R2) and the inconsistent body-evidence burdens across packets (NB3-R1) are still open. |
| P-CHET-BODY | **`P_CHET_BODY_CONTROL_PASS`** | NB-2 is fully implemented. NB3-R1 may change the wording of M-BODY's contradiction clause but cannot reintroduce a necessary body burden. |
| Source plan | **`SOURCE_PLAN_REPAIR_REQUIRED`** | NB5-R1 (absence-mode symmetry and cap) and the SRC-05 adverse mapping (NB3-R1). |
| Coverage | **`NECESSARY_PROPOSITION_COVERAGE_REPAIR_REQUIRED`** | NB1-R1 (V occurrence route). Everything else is mechanically complete. |
| Q1 | **`Q1_CONTROL_PASS`** | NB-6 closed, plus the minor NB6-M1. Q1's exposure to absence-driven row-2 triggering is carried under NB5-R1. |
| **Overall** | **`G0_REVIEW_REPAIR_REQUIRED`** | |

| Gate | Status |
|---|---|
| NB-1 | `NB1_OPEN` |
| NB-2 | `NB2_CLOSED` |
| NB-3 | `NB3_OPEN` |
| NB-4 | `NB4_CLOSED` |
| NB-5 | `NB5_OPEN` |
| NB-6 | `NB6_CLOSED` |

---

## 11. REMAINING LIMITATIONS

- Formulation fidelity for the newly added sources is carried, not verified: Lüdemann (metadata only), Smith (access level unstated), and Strauss in relation to the strict L vector (§6).
- The pinned re-review report blob is corrupted (RECORD-1). This confirmation relied on my in-session authentic copy.
- Shared training priors with Reviewer A (same provider) remain a disclosed limitation.
- Background interaction and granularity, D0 output vocabulary, and tiering remain **DEFER_TO_REVIEWER_C**.

---

## 12. NEXT-GATE DECISION

> **Are NB-1 through NB-6 now closed strongly enough for TFP-STRESS-2 to leave Reviewer B's gate and proceed to the fresh, lineage-disjoint Reviewer C discriminator/background/CRITICAL-feasibility review?**

**NO, not yet. The gap is now small.**

- NB-2, NB-4 and NB-6 are closed.
- Four bounded residuals remain on the repaired surfaces. All can be repaired before any evidence is gathered:
  - NB1-R1: add a V occurrence proposition or record a rationale;
  - NB5-R1: make absence modes symmetric and cap what absence alone can produce;
  - NB3-R1: adopt one uniform body-evidence rule;
  - NB3-R2: register F's non-body implementation.
- The clerical items (NM-1, NM-3, NB1-S1, NB6-M1, RECORD-1) should be fixed in the same pass.

A confirmation limited to those items should be enough to issue `SOURCE_PLAN_PASS` and `NECESSARY_PROPOSITION_COVERAGE_COMPLETE` and to release Reviewer C.

This decision does not authorize G0 or G1. It ranks no candidate and establishes no resurrection claim.

**STOP.**
