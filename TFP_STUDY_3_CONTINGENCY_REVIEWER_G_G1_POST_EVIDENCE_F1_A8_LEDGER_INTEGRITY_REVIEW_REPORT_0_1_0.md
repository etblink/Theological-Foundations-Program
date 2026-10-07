# TFP-STUDY-3-CONTINGENCY — Reviewer G G1 Post-Evidence F1 A8 Ledger-Integrity Review Report 0.1.0

## SESSION / CONTINUITY

This is Anthropic Claude Opus 5.5, session ID NOT_EXPOSED_BY_PROVIDER. It is the same Reviewer-G conversation that returned every prior Reviewer-G status through `FINAL_A6_LEDGER_INTEGRITY_PASS`. There is no fork, subagent, or intervening role, and I did not consult past chats or memory files.

This lineage has not served as Program Lead, Reviewer C, Reviewer E, Reviewer F, or Reviewer H. Reviewer E is also recorded as an Anthropic Claude Opus 5.5 session, but a separate fresh one. That is a shared model, not a shared lineage.

I opened the following contents:
- the frozen input, which parses as valid YAML;
- the 28 authorized appends;
- the 13 control artifacts, read for status, operational, lineage, timing and consequence fields, plus the Program Lead C4 disposition in full and the chronology and consequence passages of the Reviewer F report;
- the pinned Protocol 0.1.7 blob, C4 section only.

For the S1–S5 acquisition artifacts I used identity metadata only. I did not open their contents, the substance of the Reviewer E report, the F1 variant content of register or matrix 0.1.2, or any source.

## BASELINE / ENDPOINT VERIFICATION

The branch fast-forwarded from my previous HEAD `fd0a7fa` with no rewrite. The fixed endpoint `6a1be98` is on linear ancestry. Every commit from `57a1180` to HEAD has one parent and adds exactly one file, with no modifications, renames, or deletions.

All 41 pinned identities resolve to objects of type blob and match at both the endpoint and HEAD, and each has exactly one history commit.

The three post-endpoint commits (`59cb827`, `a2e2f39`, `be7fb7f`) are Reviewer-G launch files and are outside the certification target.

## SEQUENCE 221-269 CONTINUITY

Append 221–222 pins the certified sequence-220 blob `ce480311…` with `prior_next_sequence: 221`. That is an exact bridge.

All 28 appends pin their predecessor's actual blob, and every pin is a true blob object. Every append declares `prior_entries_rewritten: false` and has a matching `prior_next_sequence`.

Sequences 221–269 each occur once, strictly monotonic, ending at `next_sequence` 270.

## COMMIT / BLOB / REWRITE AUDIT

All 38 commit-bearing entries bind correctly. For each:
- the cited commit is an ancestor of the endpoint;
- the cited path holds exactly the cited blob at that commit;
- the path is absent in the parent, so the artifact was newly added;
- the path has one history commit through HEAD;
- `timestamp_utc` equals the commit time in UTC;
- the event commit precedes its append container.

The range `57a1180..6a1be98` contains 66 commits: 38 ledgered event commits and 28 append containers. No Study-3 artifact commit is unledgered, and no reachable rewrite exists.

**A17 field defect.** Sixteen entries omit `amendment_surfaces`: 253–257 and 259–269. That set includes the repair drafts and amendment record (262–264) and the whole C4 sequence (265–269). Every earlier entry in the chain carries that field, and A17 requires it.

## OFF-REPOSITORY / NULL-COMMIT EVENT AUDIT

The ledger records 11 null-commit events in this extension, in sequences 223, 235–249, 255 and 267.

Five of them carry an order or chronology note:
- **Sequence 223:** my final-A6 exposure, now with an inline input blob as I recommended. I attest that it accurately records my exposure.
- **Sequence 235:** first evidence exposure.
- **Sequence 236:** further S1 source openings.
- **Sequence 255:** Reviewer E's blind external adverse-source probe.
- **Sequence 267:** Reviewer F's C4 review.

The other six are the Program Lead search-exposure entries 238, 240, 242, 244, 246 and 249. They have no order note. Their order is still fixed by repository facts: each sits in its own append, after the previous commit-bearing event and before its own container commit. For example, sequence 240 falls between 13:24:47Z and 13:31:42Z.

Sequence 255 also discloses a deviation: no repository input freeze was made for Reviewer E because GitHub writes were blocked. The deviation is recorded openly. It is a matter for the strict auditor, not a ledger defect.

**Unrecorded exposure.** No entry records Reviewer C's exposure to the F1 granularity-review material. Every earlier Reviewer C, D and F review in this chain has a separate null-commit exposure entry.

Here the ledger goes straight from the input and prompt freezes (258–259, at 14:45:59Z and 14:46:23Z, marked outcome-relevant) to Reviewer C's result (260, at 14:57:26Z). Reviewer C is an outcome-material reviewer and was exposed after evidence exposure had begun. That exposure must be recorded.

The repository bounds the event between 14:46:23Z and 14:57:26Z, so chronology is unaffected, but the exposure itself is not ledgered.

## G1 AUTHORIZATION / FIRST-EVIDENCE BOUNDARY

The boundary holds.

The G0 entries before it are clean. Sequences 221–233 are all `outcome_relevant_evidence: false` with `G1_authorized: false`, and sequence 233 records that G0 preregistration is complete and that human authorization is required.

Sequence 234 records the human authorization:
- It is commit `a92e38c` at 13:11:23Z, with lineage `HUMAN_OWNER → Program Lead`.
- Its status is `G1_EVIDENCE_ACQUISITION_AUTHORIZED`.
- It is still marked non-outcome, and its append sets `G1_authorized: true` with exposure not yet started.

Sequence 235 is the first entry marked `outcome_relevant_evidence: true`. It records the S1 discovery search, ordered after the ledgered authorization (container `220736e`, 13:11:42Z) and before its own container `46c8d77` (13:13:32Z). The exposure-started flag first becomes true in that append.

## F1 REPAIR CHRONOLOGY

The full chain runs in the required order:
1. G1 acquisition, S1 through S5 (235–251).
2. Reviewer E handshake prompt, acceptance and role assignment (252–254).
3. Blind exposure (255).
4. Blind pass (256, 14:41:37Z).
5. Program Lead reconciliation, which raised the F1 trigger (257, 14:43:52Z).
6. Reviewer C input and prompt (258–259).
7. Reviewer C exposure, which is not ledgered (see above).
8. Repair required (260, 14:57:26Z).
9. Program Lead replay (261, 14:58:06Z).
10. Non-operative register 0.1.2 draft (262, 14:58:52Z).
11. Non-operative matrix 0.1.2 draft (263, 14:59:30Z).
12. Amendment record (264, 15:00:14Z).
13. Reviewer F input and prompt (265–266).
14. Reviewer F exposure (267).
15. Reviewer F result, POST_EVIDENCE_FAVORABLE_OR_MIXED (268, 15:21:32Z).
16. Program Lead disposition (269, 15:22:10Z).

None of these artifacts claims the 0.1.2 repair was ever operative. Register 0.1.2 and matrix 0.1.2 are both marked non-operative with `supersedes_for_operational_use: false`. The amendment record sets `operational_before_reviews: false`, and the Program Lead disposition keeps 0.1.1 controlling.

## APPEND 260-264 BLOB CHECK

The observation is resolved.

`LEDGER_APPEND_260_264_0_1_0.yaml` has blob `dc1501f045782a69ed4a1f0b35315ca7fe048155`. It was created only by `4562486` (15:00:51Z), it is absent in that commit's parent, and it is unchanged through the endpoint and HEAD. Append 265–266 pins exactly that blob as its base. That is the same blob Reviewer F reports having read.

The Reviewer F input simply omitted the field. The content was uniquely fixed by the chain, so the omission changes no chronology.

## C4 TIMING CONSEQUENCE

The repair is unambiguously post-evidence. Sequence 235, at or before 13:13:32Z, precedes sequences 262–264 (14:58:52Z–15:00:14Z) by about 1 hour 45 minutes.

Reviewer F named sequence 255 as the first outcome-relevant entry, but that is only because Reviewer F's authorized view began at sequence 253. The canonical first exposure is 235, and the Program Lead disposition records it correctly. Either way PRE_EVIDENCE_AMENDMENT is unavailable.

Reviewer F's post-evidence timing premise for POST_EVIDENCE_FAVORABLE_OR_MIXED survives. I did not reclassify direction.

## POST-EVIDENCE CONTAMINATION CONTROL CHECK

The Program Lead disposition carries all the Protocol C4 rules for POST_EVIDENCE_FAVORABLE_OR_MIXED that I read in the pinned protocol blob. It records:
- `descriptive_correction_must_be_preserved: true`;
- `genuine_adverse_candidate_level_consequences_may_enter_current_confirmatory_study: true`;
- `favorable_or_mixed_effect_may_not_strengthen_any_candidate_confirmatorily: true`;
- `positive_comparative_use_requires_new_preregistered_cycle_or_genuinely_held_out_evidence: true`;
- a ranking-change rule mapping any change in relative dominance or ranking to `UNDERDETERMINED_WITHIN_SCOPE: POST_EVIDENCE_DIRECTIONAL_CONTAMINATION`;
- a ban on favorable-combination sampling.

It also requires a later operational acceptance to carry these controls verbatim. The Reviewer F report states the same restrictions.

The ledger's own role in these controls is weakened by the missing `amendment_surfaces` on the very entries that record the amendment and its C4 review.

## REQUIRED REPAIRS

Both repairs below are clerical, append-only and non-chronological. Neither prior entry may be edited.

**R1 (blocking).** Record Reviewer C's F1 review exposure in a supplemental append. The entry should be keyed as occurring between sequences 259 and 260 and should give:
- the lineage `XAI_GROK_4_7_REVIEWER_C` session;
- the input blob `87a79a27…` and prompt blob `6a037a63…`;
- the materials authorized to Reviewer C;
- the amendment surfaces;
- `outcome_relevant_evidence: true`;
- the order anchor 14:46:23Z → 14:57:26Z.

**R2 (blocking).** In the same supplement, annotate `amendment_surfaces` for sequences 253–257 and 259–269.

**R3 (recommended, non-blocking).** In the same supplement, add order anchors for sequences 238, 240, 242, 244, 246 and 249, using their bounding commit and container times.

After the supplement, a focused Reviewer-G recheck of the supplement alone is enough. These repairs do not reopen Reviewer C's, Reviewer E's, or Reviewer F's results.

Two items are ongoing or carried forward:
- This review's own provenance must be ledgered after the already-used sequences 270–271.
- The sequence-255 deviation (no input freeze) is carried forward to the strict auditor.

## G1 F1 A8 LEDGER INTEGRITY STATUS

The following are confirmed:
- the 220 → 221 bridge;
- continuity of sequences 221–269 and blob chaining;
- commit, blob and timestamp identity for all 38 commit-bearing entries;
- add-once history with no reachable rewrite;
- no unledgered artifact commits;
- the 234 authorization → 235 first-evidence boundary;
- the F1 repair order;
- append 260–264 at blob `dc1501f0…`;
- the post-evidence timing;
- preservation of the C4 consequence in the Program Lead disposition.

Certification is withheld for two A17 deficiencies: Reviewer C's F1 exposure is unrecorded, and `amendment_surfaces` is missing on 16 entries. Register 0.1.2 and matrix 0.1.2 remain non-operative.

`G1_F1_A8_LEDGER_INTEGRITY_REPAIR_REQUIRED`
