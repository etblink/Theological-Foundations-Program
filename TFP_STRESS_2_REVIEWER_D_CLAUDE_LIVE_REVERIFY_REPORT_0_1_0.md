Both blob hashes match. Reading the input file first.# TFP-STRESS-2 — Reviewer D Live A17 Reverification Report

## 1. Session and lineage continuity

- **Provider / model:** Anthropic, Claude Opus 5.5. Session ID: NOT_EXPOSED_BY_PROVIDER.
- **Handshake:** This is the same fresh conversation that returned `PROCEDURALLY_DISJOINT_FOR_REVIEWER_D`. No past-chat search was run and no memory files were opened.
- **Role:** Reviewer D / ledger-integrity reviewer only.
- **Repository access:** Read-only. I made a local clone and accessed objects only with `git show`, `git ls-tree` and `git log`. The local working tree has 0 modifications. Nothing was pushed.
- **Order of reading:**
  1. Input `63b67f57…` (blob match confirmed).
  2. Prompt `a4c5ef62…` (blob match confirmed).
  3. Both control files were read from `origin/research/tfp-stress-2-resurrection-g3`, solely to obtain the frozen assignment.
- **Substantive review:** Done only against the target commit, plus ancestor commits it cites. Protocol 0.1.7 was read by its frozen blob `0d9406d9…`, which lives on `repair/tfp-adjudication-protocol-0.1.7` and is not in the target tree.
- **Not read:** No later Reviewer-D report, G5-readiness artifact, later STATE, or Program-Lead commentary. No post-determination comparison was performed.

## 2. Immutable target verification

- **Commit:** `43ee1477fc500a28372710f3a57127b4edcaef6a` exists. Its tree resolves to `378b7904abe6afb27395ef32c5cc636adcef102a`, which matches.
- **Branch:** The target is an ancestor of the g3 branch tip.
- **History:** Linear, with 514 commits up to the target and 0 merges.
- **Current ledger:** `TFP_STRESS_2_EVIDENCE_EXPOSURE_LEDGER_0_1_76.yaml` is blob `853668f6…`, which matches.
- **Authority blobs:**
  - Role architecture `cade6816…` is `TFP_STRESS_2_ROLE_ARCHITECTURE_0_1_14.yaml` in the target tree.
  - Protocol blob `0d9406d9…` is `TFP_ADJUDICATION_PROTOCOL_0_1_7.md`. It resolves only on the repair branch, not in the target tree. That is consistent with how the input pins it by blob.

## 3. A17 standard (Protocol 0.1.7, blob `0d9406d9…`)

**What the ledger must be:** an append-only `EVIDENCE_EXPOSURE_LEDGER`. Each entry records:
- a monotonically increasing sequence number;
- the commit/blob identity;
- time/order;
- the actor lineage;
- the source/artifact class;
- the amendment surfaces affected.

The custodian may append entries but may not rewrite prior ones.

**What Reviewer D verifies when any amendment is classified:**
- (a) sequence continuity;
- (b) that commit history contains no unrecorded ledger rewrite;
- (c) that the relevant exposure precedes or follows the amendment as claimed.

**Related amendment-control rule (§ amendment control):** every amendment must:
- cite the A17 ledger;
- receive independent direction-classification review **before use**.

## 4. Full ledger-version chain check (0.1.0 → 0.1.76)

All 77 version files are present at the target and every one parses as YAML. For each of the 76 adjacent transitions I ran two comparisons:
- **Parsed comparison:** every pre-existing `entries[]` item, compared by position and sequence number.
- **Byte comparison:** each entry's raw text block.

**Sequence entries.** Exactly one prior-entry mutation exists in the whole chain:

| Transition | Entry | Change |
|---|---|---|
| 0.1.1 → 0.1.2 | seq 3 | `repository_commit` changed from `2c3a852` to `2c3a852cb5a00416a6f214318a356fc0019f2edf` |

- The 0.1.1 blob (`b5c75233…`) and the 0.1.2 blob (`6db3720c…`) match the input.
- No other entry was mutated, deleted, reordered or inserted mid-list in any transition.
- Every version only appends at the tail.
- seq 2 still carries the short form `2c3a852`, unnormalized. That is consistent; it is not a rewrite.

**Non-entry sections** (outside the sequence entries):
- **0.1.0 → 0.1.1:** `baseline_exposure_disclosures` was rewritten in place. `treatment` lines were removed, the Reviewer-A category and detail were reworded, and the Reviewer-B baseline was added. In the same transition:
  - `ledger_policy` changed from `append_only_after_activation` to `append_only: true`;
  - `integrity_reviewer.role_slot` changed from `REVIEWER_B` to `REVIEWER_D_FUTURE`;
  - `activation_record` was replaced by `g0_activation_record`.

  0.1.0 was `INACTIVE_UNTIL_AUTHORIZATION` with an append-only-after-activation policy and `entries: []`. So this was a pre-activation, non-sequence revision, not an append-only violation. It is not disclosed anywhere.
- **0.1.72 → 0.1.73:** `g0_activation_record` went from null to populated. This was the required F3 fill-in.
- **Every version:** `integrity_state` changes as mutable metadata. `next_sequence` equals entry count + 1 in all 76 versions that have it.
- **Header self-identity defect (not disclosed anywhere at the target):**
  - Versions 0.1.63 through 0.1.76 all declare `schema_version: "0.1.62"` and `supersedes: "…_0_1_61.yaml"`. That is 15 distinct files claiming the same version identity, including 0.1.62 itself.
  - `status` stays `ACTIVE_PRE_G0` in 0.1.73–0.1.76, although `g0_activation_record` there records G1 activation at `54299f37…`.
  - The F7 stale-header errata covers the Q1 control and G0 preregistration headers only, not the ledger.

## 5. Current sequence continuity (0.1.76)

- **Continuity:** Entries 1–156 are contiguous and strictly increasing. `next_sequence` is 157. Continuity also holds in every historical version.
- **Commit-reference checks:**
  - All 69 `path blob <sha>` claims verify against `git ls-tree <commit> <path>`.
  - Every full-SHA `repository_commit` is an ancestor of the target.
  - No entry cites a commit later than the ledger version that first recorded it.
- **Commit-order inversions (observation):** Commit order runs against sequence order in three places:
  - **51/52:** seq 52 is an explicit preservation-correction entry pointing back to 6dab8d4.
  - **137/138:** adjacent artifacts in the same append batch (ledger 0.1.72), reversed by one position.
  - **145/146:** adjacent artifacts in the same append batch (ledger 0.1.73), reversed by one position.

  The ledger does not claim that sequence order equals commit order. These inversions do not affect any claimed exposure-before-amendment relation.

## 6. Git history and rewrite check

- **Version files:** Each of the 77 ledger version files is touched by exactly one commit, the one that adds it. There are no in-place modifications, deletions or renames.
- **Commit order:** The adding commits are distinct and strictly ordered by version number, from position 69 (0.1.0) to position 514 (0.1.76, the target).
- **Other ledger-named files:** None, apart from the F3 errata and the Reviewer-D control files.
- **The only historical prior-entry rewrite** is seq 3 (0.1.1 → 0.1.2). It is disclosed in two places:
  - the 0.1.76 `integrity_state` (`rewrite_detected: true`, plus `historical_rewrite_note`);
  - the F3 errata `TFP_STRESS_2_G4_E1_F3_LEDGER_ERRATA_0_1_0.yaml` (blob `d05af3bd…`, seq 149). This errata also discloses that `rewrite_detected` was falsely `false` in 0.1.2–0.1.72.
- **seq 39 correction:** Done append-only via seq 45. seq 39's text was never altered, and the correction is mirrored in `integrity_state`.
- **Conclusion for A17(b):** Commit history contains no unrecorded rewrite of any sequence entry.

## 7. Amendment chronology and C4 pairing

Positions below are the commit's index in the target's linear history.

| Amendment | Amendment (seq / commit pos) | Pre-C4 citations or uses | C4 (seq / pos / result) |
|---|---|---|---|
| L1 0.1.1 `8406e121` | 88 / 398 | seq 89 (pos 400): the L2 evidence matrix cites it as `l1_clerical_repair`, with no dispositions assigned. | 91 / 405 / `CONFIRM_POST_EVIDENCE_NONMATERIAL_NEUTRAL` |
| L2 0.1.1 `181ab979` | 93 / 408 | seq 94 (pos 410) founding-stream freeze and seq 95 (pos 412) L3 matrix cite it as `l2_pointer_repair` authority. | 97 / 417 / `CONFIRM_POST_EVIDENCE_NONMATERIAL_NEUTRAL` |
| Phase-L 0.1.1 `150e8e71` (item A) | 129 / 474 | It is the operative consolidation blob for these later records: G2 completion and G3 request (seq 130), human G3 authorization (131), G3 launch (132), A12 status (133), N3/Q1 provisional outcome (134), and E1 audit target (138–140). | 152 / 508 / A: all NEUTRAL, `POST_EVIDENCE_NONMATERIAL` |
| Post-audit B–H (seq 143–149) | 143–149 / 497–503 | None. Only the C4 input and prompt follow (150–151). | 152 / 508 / B–H all NEUTRAL, `POST_EVIDENCE_NONMATERIAL` |

- All amendment and C4 report blobs match the input. Each was added once and is unchanged at the target.
- Every classified amendment has independent C4 review.
- **However, not every classified amendment was reviewed before use:**
  - **Phase-L 0.1.1** was the basis of G3 authorization and the A12, N3 and Q1 determinations about 23 ledger sequences (34 commits) before its C4. At the time, seq 129 recorded it as `…LIFECYCLE_GATE_CORRECTION__NO_DISPOSITION_CHANGE`, not as an amendment pending C4. The amendment itself removed the `reviewer_D_gate: REQUIRED_NEXT` (ledger-integrity and confidence review) that 0.1.0 had imposed before G3.
  - **L1 0.1.1 and L2 0.1.1** were cited as authority inputs in non-disposition artifacts before their C4. Their pending-C4 status was disclosed in seq 88 and seq 93.
- Neither the current ledger nor the C4 closure records the pre-review use of Phase-L 0.1.1, or the pre-C4 citations of L1 and L2.
- C4 reported for each of these that its review is required "before use". The C4 report does not address the fact that item A was used before review.

## 8. Phase-L A17 binding check

The closure record `TFP_STRESS_2_G4_REVIEWER_C_C4_INTEGRATION_CLOSURE_0_1_0.yaml` (blob `ebe2ae42…`, seq 153) binds item A to ledger 0.1.74 (blob `e3569805…`, verified) and to sequences 128, 129, 150 and 151. All of these verify. The frozen Phase-L 0.1.1 blob is untouched.

- **Sufficient:** As a citation of the A17 ledger for cold-start use, this additive binding is sufficient. Rewriting the frozen artifact is neither necessary nor desirable.
- **Not sufficient:** It does not cure, or disclose, the chronology defect in §7. The binding is dated after use, and nothing in the ledger states that G3 relied on the amendment before its independent review.

## 9. F6 pin caveat check (ledger and use-control only)

- **The bad pin:** F6 (blob `d79543aa…`, seq 146) cites `C_HET_module_map` as `8f31eb6152716c75f5d850af6ce6335410102a1b`. That object does not exist in any fetched ref. `TFP_STRESS_2_C_HET_MODULE_MAP_0_1_6.yaml` has only ever had one blob, `ac10a99a…`.
- **Use control:** The closure record preserves the bad pin rather than silently substituting the correct one. It restricts F to `NO_DISPOSITION_CHANGE_RECONCILIATION_NOTE_ONLY` and prohibits any new sufficiency or module-map finding.
- **Ledger notes:** The seq 152 and seq 153 notes disclose the failed pin and the use limitation.
- **Assessment:** Adequate as a ledger-integrity and use-control matter. No pin rewrite occurred, and the defect is not hidden.

## 10. Outcome-materiality check

- **Sequence history:** The only sequence-entry rewrite (seq 3) normalizes a short commit ID to its own full form. It is content-neutral.
- **Header and pre-activation defects:** The header self-identity defect and the pre-activation baseline revision touch no exposure, amendment surface or result.
- **Pre-review use:** On the ledger record, the Phase-L, L1 and L2 pre-review uses were later independently classified NEUTRAL / `POST_EVIDENCE_NONMATERIAL`. I found no ledger fact suggesting a different A12, N3 or Q1 result. (Direction classification itself is outside my role and was not performed.)
- **Effect on A12, N3, Q1:** None of the identified defects changes them on the ledger record.
- **Effect on G5 eligibility:** G5 eligibility is affected procedurally. G5 readiness at the target is waiting on Reviewer-D ledger-integrity closure, and that closure cannot be confirmed while:
  - the amendment-before-use chronology deviation is undisclosed;
  - the ledger's own version headers misidentify 14 version files (0.1.63–0.1.76).

## 11. Findings

**D-1 — MAJOR (A17(c) and amendment-control chronology, undisclosed)**
- Phase-L 0.1.1 (seq 129) was used operatively in seq 130–134 (G3 authorization, A12, N3/Q1) and was the E1 audit target (seq 138–140) before its independent C4 (seq 152).
- The current ledger and the seq 153 closure bind it additively but do not disclose this pre-review use.
- Lesser instances, also undisclosed as uses:
  - L1 0.1.1 was cited at seq 89 before its C4 at seq 91.
  - L2 0.1.1 was cited at seq 94–95 before its C4 at seq 97.

**D-2 — MINOR (ledger self-identity, undisclosed)**
- Ledger versions 0.1.63–0.1.76 carry the stale `schema_version: "0.1.62"` and `supersedes: "…_0_1_61.yaml"`.
- The `status` value `ACTIVE_PRE_G0` persists after the recorded G1 activation (0.1.73–0.1.76).

**D-3 — OBSERVATION (disclosure completeness)**
- The 0.1.0 → 0.1.1 in-place revision of `baseline_exposure_disclosures`, `integrity_reviewer` and the policy fields happened before activation and outside the sequence entries.
- It is permitted under the 0.1.0 policy but is not recorded in `integrity_state`.

**D-4 — OBSERVATION**
- In two same-batch pairs (137/138 and 145/146), sequence order inverts commit order by one position. This is not material.

**Confirmed items:**
- Sequence continuity and monotonicity hold in all 77 versions.
- The only prior-entry mutation in the full chain is seq 3, and it is disclosed.
- There is no unrecorded ledger rewrite in Git history.
- All 69 path/blob claims verify.
- Every classified amendment has an independent C4.
- The F6 use-control is adequate.

## 12. Overall result

`LEDGER_INTEGRITY_NOT_CONFIRMED`

## 13. Required next action

Smallest exact repair: an additive change only, with no historical artifact modified.

1. **Append ledger `TFP_STRESS_2_EVIDENCE_EXPOSURE_LEDGER_0_1_77.yaml`**, preserving entries 1–156 byte-for-byte, with:
   - correct headers: `schema_version: "0.1.77"`, `supersedes: "TFP_STRESS_2_EVIDENCE_EXPOSURE_LEDGER_0_1_76.yaml"`, and a `status` reflecting the post-G1/G4 state;
   - an appended `integrity_state` note plus one new sequence entry (157) recording:
     - (a) D-1: Phase-L 0.1.1 was used at seq 130–134 and 138–140 before its C4 at seq 152; L1 0.1.1 was cited at seq 89 before its C4 at seq 91; L2 0.1.1 was cited at seq 94–95 before its C4 at seq 97. Each is cross-referenced to its NEUTRAL / `POST_EVIDENCE_NONMATERIAL` C4 result.
     - (b) D-2: header staleness in 0.1.63–0.1.76, with filename and Git order declared authoritative.
     - (c) Optionally, D-3: the pre-activation 0.1.0 → 0.1.1 non-entry revision.
2. **Re-run a narrow fresh Reviewer-D delta check.** It should confirm three things:
   - 0.1.77 preserves entries 1–156 unchanged;
   - the disclosures are accurate;
   - no further rewrite occurred.

   After that, ledger integrity can be confirmed.

**Surfaces affected by the repair:**
- Ledger versions 0.1.63–0.1.76 (headers, by disclosure only).
- Amendments Phase-L 0.1.1 `150e8e71` (ledger seq 129/152/153), L1 0.1.1 `8406e121` (seq 88/89/91) and L2 0.1.1 `181ab979` (seq 93/94/95/97).