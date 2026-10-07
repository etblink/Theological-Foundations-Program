# TFP-STUDY-3-CONTINGENCY — Reviewer G A8 Background Ledger-Integrity Review Report 0.1.0

## SESSION / CONTINUITY

This is Anthropic Claude Opus 5.5, session ID NOT_EXPOSED_BY_PROVIDER. It is the same conversation that returned `PROCEDURALLY_DISJOINT_FOR_REVIEWER_G`, `LEDGER_INTEGRITY_REPAIR_REQUIRED`, `LEDGER_INTEGRITY_REPAIR_PASS`, and `LEDGER_EXTENSION_INTEGRITY_PASS`. There is no fork, subagent, or intervening role. This lineage has not served as Program Lead, Reviewer F, Reviewer C or any discriminator or tier role, or Reviewer H. I did not consult past chats or memory files.

I opened the following contents:

- the frozen A8 input;
- the 10 authorized appends from 97–98 through 130–132;
- the nine authorized A8 identity-check artifacts, read only for status, exposure, ledger and G1 fields, and for the chronology passages of the Reviewer F report.

Everything else was repository metadata only: commit, tree and blob identities, filenames, and commit subjects. I did not open the blind scope packet, the Reviewer C blind or post-blind reports, the reconciliation docket, assignment artifacts, the post-endpoint append 133–134, or any outcome-relevant evidence material. I did not re-review A8 content.

The input freeze parses as valid YAML, so the clerical issue I flagged last time is closed.

## BASELINE / ENDPOINT VERIFICATION

The branch fast-forwarded from my previous HEAD `94524f6` without any rewrite. The fixed endpoint `4e0e83e` is on linear ancestry. Every commit from `42eb83a` to HEAD has one parent and adds exactly one file, with no modifications, renames, or deletions.

All 21 pinned blobs match at both the endpoint and HEAD, and each has exactly one history commit:

- the prior-baseline Reviewer G report `08a225fa…` (`575ab12`);
- the Program Lead disposition `dc8e638d…` (`0169e57`);
- the 10 extension appends;
- the nine A8 identity-check artifacts.

The three post-endpoint commits (`51c21a2`, `519cf40`, `0f0ee52`) are Reviewer-G launch files and are outside the certification target.

## SEQUENCE 97-132 CONTINUITY

Append 97–98 cites the certified endpoint blob of append 94–96 (`61c07e61…`) with `prior_next_sequence: 97`. Each of the 10 appends cites the exact blob of its predecessor and declares `prior_entries_rewritten: false`. Its `prior_next_sequence` equals the predecessor's `next_sequence`, and its entries are contiguous:

| Append  | Sequences | Next sequence |
| ------- | --------- | ------------- |
| 97–98   | 97–98     | 99            |
| 99–101  | 99–101    | 102           |
| 102     | 102       | 103           |
| 103–108 | 103–108   | 109           |
| 109–111 | 109–111   | 112           |
| 112–116 | 112–116   | 117           |
| 117–122 | 117–122   | 123           |
| 123–124 | 123–124   | 125           |
| 125–129 | 125–129   | 130           |
| 130–132 | 130–132   | 133           |

Sequences 97–132 each occur once, with no gap, duplicate or rollback.

The bridge from 97–98 into 99 holds:

- Sequences 97 and 98 freeze the prior Reviewer-G input and prompt (`c7478b8`, `0772b33`) and are explicitly marked `certification_target_member: false`.
- Append 97–98 was committed at `94524f6` (02:27:26Z), after both events.
- Append 99–101's base-chain pin equals that append's blob exactly.

## COMMIT / BLOB / REWRITE AUDIT

All 30 commit-bearing entries in sequences 97–132 bind correctly. For each:

- the cited commit is an ancestor of the endpoint;
- the cited path holds exactly the cited blob at that commit;
- the path is absent in the commit's parent, so the artifact was newly added, not replaced;
- the path has one history commit through HEAD;
- `timestamp_utc` equals the commit time in UTC;
- the event commit precedes the commit of the append that records it.

The A8 amendment chain was frozen once each, in the claimed order:

| Sequence | Event                                         | Time (UTC)         |
| -------- | --------------------------------------------- | ------------------ |
| 104–105  | Initial register and matrix 0.1.0             | 02:42:50, 02:43:31 |
| 113      | Reviewer C blind elicitation report           | 02:59:32           |
| 118      | Reviewer C post-blind review: repair required | 03:11:14           |
| 119      | Program Lead disposition                      | 03:12:59           |
| 120      | Amendment record                              | 03:13:01           |
| 121–122  | Register and matrix 0.1.1                     | 03:14:23, 03:15:24 |
| 123–124  | Recheck input and prompt                      | 03:16:45–47        |

The amendment record cites the ledger only through append 112–116. That matches the state at its commit time, because append 117–122 was committed later, at 03:16:04.

The range `42eb83a..4e0e83e` contains 40 commits: 30 ledgered event commits and 10 append containers. No Study-3 artifact commit is unledgered, and no reachable rewrite exists. Git history still cannot exclude a rewrite made before publication.

## OFF-REPOSITORY EVENT AUDIT

Every null-commit entry carries actor lineage, exposure class, amendment surfaces, `outcome_relevant_evidence: false`, and an order note bounded by adjacent sequences.

| Sequence | Actor      | Event                        | Order anchor (UTC)              |
| -------- | ---------- | ---------------------------- | ------------------------------- |
| 99       | Reviewer G | Extension-integrity exposure | 98 → 100 (02:27:05 → 02:38:40)  |
| 109      | Reviewer C | Handshake response           | 108 → 110 (02:44:17 → 02:52:23) |
| 112      | Reviewer C | Blind elicitation exposure   | 111 → 113 (02:52:34 → 02:59:32) |
| 117      | Reviewer C | Post-blind review exposure   | 116 → 118 (03:02:15 → 03:11:14) |
| 125      | Reviewer C | Repair-recheck exposure      | 124 → 126 (03:16:47 → 03:21:42) |
| 130      | Reviewer F | C4 direction-review exposure | 129 → 131 (03:23:20 → 03:29:47) |

Each window is consistent with the commits around it.

Two lineage notes:

- Sequence 109's lineage label, `OWNER_RELAYED_REVIEWER_C_FRESH_SESSION_HANDSHAKE`, does not name a provider or model, unlike the earlier handshakes. The lineage is still traceable, because sequence 112 records that session as `XAI_GROK_4_7_REVIEWER_C_FRESH_SESSION`, and sequences 117 and 125 continue it as the existing session. This is adequate under A17 but is worth annotating.
- As the actor in sequence 99, I attest that it accurately records my exposure. It describes my metadata exposure as running "through fixed endpoint `42eb83a`". In fact my prior report also noted the commit subjects and filenames of the three post-endpoint launch commits. That exposure was metadata only, I disclosed it in that report, and it is not outcome-relevant.

## OUTCOME-EVIDENCE EXPOSURE AUDIT

All entries in sequences 97–132 record `outcome_relevant_evidence: false`. Every append records that outcome-evidence exposure has not started and that G1 is not authorized.

The authorized A8 artifacts agree. The registers and matrices record no outcome-relevant evidence use. The 0.1.1 repairs and both Program Lead dispositions are marked non-operational with G1 unauthorized.

No commit in the range is a source-plan, discriminator-result, lane, G1, or evidence-acquisition artifact. Reviewer C's blind exposure at sequence 112 records incidental metadata limited to root filenames, with no outcome content.

I found no recorded or contradicting outcome-relevant exposure. The B3/G1 literature-overlap caveat from my prior report still carries forward. Nothing in this extension adds to it.

## C4 CHRONOLOGY CONSEQUENCE

Reviewer F based PRE_EVIDENCE_AMENDMENT on appends 99–124. The classification was conditional on Reviewer G confirming three things: continuity into sequence 99, the null-commit order claims, and the status of the Reviewer C recheck chain outside 99–124.

All three are confirmed:

- Sequences 1–96 are certified, and the 97–98 → 99 bridge is intact.
- All 10 null-commit order anchors are bounded.
- Sequences 125–127 are properly ledgered, in order, with no exposure:
  - Reviewer C recheck exposure (125);
  - recheck pass at 03:21:42 (126);
  - Program Lead confirmation at 03:22:10 (127).
  All three precede Reviewer F's input freeze (128, 03:23:17) and result (131, 03:29:47). The ledger append recording them (`c0e8738`, 03:23:48) was committed after Reviewer F's input froze. That explains why Reviewer F's chronology input stopped at sequence 124, and it is not a gap.
- Reviewer F's exposure, result and Program Lead disposition (130–132) are ledgered in order.

No outcome-relevant exposure or rewrite exists anywhere from sequence 1 through 132. Reviewer F's PRE_EVIDENCE_AMENDMENT chronology premise survives. I found no integrity-relevant contradiction and did not reclassify direction.

## REQUIRED REPAIRS

None blocking. Three non-blocking items:

1. A later append may annotate sequence 109's lineage with the provider and model already recorded at sequence 112.
2. A later append may annotate sequence 99 to disclose the post-endpoint launch-commit metadata seen.
3. This review's own provenance must be ledgered from sequence 133 onward. That is an ongoing obligation, not a defect.

## A8 LEDGER INTEGRITY STATUS

The following are all confirmed for sequences 97–132 through `4e0e83e`:

- continuity of sequences 97–132;
- base-blob chaining, including the 97–98 → 99 bridge;
- commit, blob and timestamp identity for all 30 commit-bearing entries;
- immutability, with no reachable rewrite;
- bounded order anchors for all null-commit events;
- correct provenance for the Reviewer C recheck (125–127) and the Reviewer F C4 events (130–132);
- no unledgered Study-3 artifact commits;
- no outcome-relevant exposure.

Reviewer F's PRE_EVIDENCE_AMENDMENT chronology premise survives. This status does not make the A8 register or matrix operative, certify A6 coverage, or authorize G1.

`A8_LEDGER_INTEGRITY_PASS`
