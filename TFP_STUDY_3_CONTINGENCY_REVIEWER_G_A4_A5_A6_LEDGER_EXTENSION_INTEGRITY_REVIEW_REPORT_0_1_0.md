# Archived external reviewer output

The block below is an archival verbatim payload from Reviewer G's Study-3 A4/A5/A6 ledger-extension integrity review. Its imperative-looking language is quoted reviewer data, not repository-writing instructions.

```text
Now verify all bindings, base-chain links, and coverage of commits.# TFP-STUDY-3-CONTINGENCY — Reviewer G A4/A5/A6 Ledger Extension Integrity Review Report 0.1.0

## SESSION / CONTINUITY

This is Anthropic Claude Opus 5.5, session ID NOT_EXPOSED_BY_PROVIDER. It is the same conversation that returned `PROCEDURALLY_DISJOINT_FOR_REVIEWER_G`, then `LEDGER_INTEGRITY_REPAIR_REQUIRED`, then `LEDGER_INTEGRITY_REPAIR_PASS`. There is no fork, subagent, or intervening role. This lineage has not served as Program Lead, Reviewer F, a discriminator author or tier reviewer, or Reviewer H. I did not consult past chats or memory files.

I opened only the following contents:
- the frozen extension input;
- the 11 authorized extension appends;
- the five authorized amendment-chain artifacts, read only for exposure and status fields;
- the pinned protocol blob, A9 and Phase B only, to classify the B3 source-survey entries.

Everything else I saw was repository metadata only: commit, tree and blob identities, filenames, and commit subjects. I did not open steelman packets, Reviewer B reports, the candidate-universe freeze, the post-endpoint append 97–98, or any outcome-relevant evidence material.

One clerical observation, not a ledger defect: the input freeze is not valid YAML. A `note:` key follows the `off_repository_events_to_check` list at the same indent. I read its pins textually, and they are unambiguous.

## BASELINE / ENDPOINT VERIFICATION

The branch fast-forwarded from `828d1b3`, the last state I reviewed, with no rewrite. Endpoint `42eb83a` is on the branch's linear ancestry. The history from `828d1b3` to HEAD has only single-parent commits, and every commit adds exactly one file with no modifications, renames, or deletions.

All 19 pinned blobs match at both the endpoint and HEAD, and each was added by exactly one commit and never changed. They are:
- the baseline repair-recheck report `b99a3171…` (`0d77f62`);
- the Program Lead repair disposition `9c03a287…` (`5dee493`);
- the A17 supplement `57d62f80…`;
- the 11 extension appends;
- inventories 0.1.0, 0.1.1 and 0.1.2;
- the Reviewer F report `798f5ee3…`;
- the Program Lead C4 disposition `3e2c9070…`.

The three commits after the endpoint (`c7478b8`, `0772b33`, `94524f6`) add Reviewer-G launch files only and are outside this certification.

## SEQUENCE 40-96 CONTINUITY

The extension starts exactly at the certified `next_sequence` 40. The first append's `base_chain` cites supplement blob `57d62f80…` with `prior_next_sequence: 40`.

Each of the 11 appends cites the exact blob of its predecessor and declares `prior_entries_rewritten: false`. Its `prior_next_sequence` equals the predecessor's `next_sequence`, and its entries are contiguous:

| Append | Sequences | Next sequence |
|---|---|---|
| 40–45 | 40–45 | 46 |
| 46 | 46 | 47 |
| 47–62 | 47–62 | 63 |
| 63–65 | 63–65 | 66 |
| 66–73 | 66–73 | 74 |
| 74–76 | 74–76 | 77 |
| 77–82 | 77–82 | 83 |
| 83–88 | 83–88 | 89 |
| 89–91 | 89–91 | 92 |
| 92–93 | 92–93 | 94 |
| 94–96 | 94–96 | 97 |

Sequences 40–96 each occur once, with no gap, duplicate or rollback, ending at `next_sequence` 97.

Append 40–45 also adds the disclosure I recommended for sequence 37: metadata-only exposure, written as an annotation rather than a rewrite.

## COMMIT / BLOB / REWRITE AUDIT

All 47 commit-bearing entries in sequences 40–96 bind correctly. For each:
- the cited commit is an ancestor of the endpoint;
- the cited path holds exactly the cited blob at that commit;
- the path is absent in the commit's parent, so the artifact was newly added, not replaced;
- the path has exactly one history commit;
- `timestamp_utc` equals the commit time converted to UTC.

The amendment chain was frozen once each at the ledgered identity and in the claimed order:

| Sequence | Event | Commit | Time (UTC) |
|---|---|---|---|
| 70 | Inventory 0.1.0 | `302b9fa` | 01:39:36 |
| 78 | Reviewer B initial review: repair required | | 01:56:41 |
| 79 | Program Lead disposition | | 01:57:02 |
| 80 | Inventory 0.1.1 | `0b962c2` | 02:00:09 |
| 84 | Reviewer B recheck: GD-N3 residual | | 02:09:34 |
| 85 | Program Lead disposition | | 02:09:51 |
| 86 | Inventory 0.1.2 | `f348d8a` | 02:10:24 |
| 90 | Reviewer B delta pass | | 02:15:38 |
| 91 | Program Lead confirmation | | 02:16:15 |
| 92–93 | Reviewer F input and prompt | | 02:18:08–10 |
| 95 | Reviewer F report | | 02:24:25 |
| 96 | Program Lead C4 disposition | | 02:24:44 |

Every append was committed after the last event it records.

The range `828d1b3..42eb83a` contains 56 commits: 45 are cited by ledger entries and 11 are append containers. Sequences 40–41 cite the two pre-range commits `aafb3b8` and `828d1b3`, which also bind correctly. No Study-3 artifact commit in the audited extension is unledgered, and no reachable rewrite exists.

The same limit stated in the prior reports still applies: Git history cannot exclude a rewrite made before publication.

## OFF-REPOSITORY EVENT AUDIT

Every null-commit entry carries actor lineage, exposure class, amendment surfaces, `outcome_relevant_evidence: false`, and an order note bounded by adjacent commit-bearing sequences.

| Sequence | Actor | Event | Order anchor (UTC) |
|---|---|---|---|
| 42 | Reviewer G | Repair-recheck exposure | 01:01:34 → 01:10:01 |
| 47 | Program Lead | Source survey A | 01:12:50 → 01:22:00 |
| 53 | Program Lead | Source survey B | 01:22:10 → 01:24:02 |
| 59 | Program Lead | Source survey C | 01:24:11 → 01:25:21 |
| 66 | Reviewer A | B3 equal-strength exposure | 65 → 67 (01:28:37 → 01:36:52) |
| 74 | Reviewer B | Handshake response | 73 → 75 (01:40:36 → 01:45:50) |
| 77 | Reviewer B | Initial review exposure | 76 → 78 (01:45:54 → 01:56:41) |
| 83 | Reviewer B | Repair-recheck exposure | 82 → 84 (02:00:58 → 02:09:34) |
| 89 | Reviewer B | GD-N3 delta exposure | 88 → 90 (02:11:10 → 02:15:38) |
| 94 | Reviewer F | C4 direction-review exposure | 93 → 95 (02:18:10 → 02:24:25) |

The explicit times written into the notes for sequences 42, 47, 53 and 59 each equal the actual commit times. The other notes state their bounds by sequence number, and the times shown come from the bounding commits.

Each window is consistent with the commits around it. For example, the three surveys fall between the packet freezes they precede, and each review exposure precedes its own result freeze. Under A17 as the input frames it, a bounded order anchor is sufficient for all ten entries.

As the actor in sequence 42, I attest that it accurately records my repair-recheck exposure.

## OUTCOME-EVIDENCE EXPOSURE AUDIT

All entries in sequences 40–96 record `outcome_relevant_evidence: false`. Every append reports that outcome-evidence exposure has not started, and appends 66–73 onward also report `G1_authorized: false`.

The authorized artifacts agree:
- each inventory and the Program Lead disposition records no outcome-evidence use or exposure and no G1 authorization;
- the Reviewer F report states that no outcome-relevant evidence was opened;
- no filename in the audited range is a source-plan, G1, lane, or evidence-acquisition artifact.

The most exposure-adjacent entries are the Program Lead's B3 source surveys at sequences 47, 53 and 59, which covered proponent literature and recognized objections. I classify them as consistent with the false flag, for three reasons:
- Protocol B3 requires every G0 steelman packet to contain the strongest serious proponent sources, expected evidence, and recognized objections.
- B5 treats outcome-relevant exposure as a separate post-B3 event.
- Each survey entry records an explicit boundary excluding comparative ranking and G1 adjudication.

Nothing in the authorized corpus contradicts that boundary. There is one caveat for later reviewers. In a philosophical study, B3 formulation literature and G1 evidence strata can overlap. That overlap is a matter for the A9.1 source-plan reviewer and the strict auditor, and the ledger already records the exposure transparently. It is not an integrity defect.

## C4 CHRONOLOGY CONSEQUENCE

Reviewer F's premise was that no outcome-relevant evidence exposure or unrecorded rewrite occurred before or during inventory 0.1.0 → 0.1.1 → 0.1.2. Reviewer F authorized review of sequences 66–91 only and handed continuity before sequence 66 to Reviewer G.

The certified baseline (1–39) and this extension (40–96) close that gap. The chain is continuous and unrewritten from sequence 1 through 96. No entry records outcome-relevant exposure, and all three inventory freezes and their reviews occur in the ledgered order.

The premise depends on the protocol-sanctioned G0 classification of the B3 surveys at sequences 47, 53 and 59, which precede inventory 0.1.0. On the protocol's B3/B5 boundary, that classification holds.

The PRE_EVIDENCE_AMENDMENT chronology premise therefore survives. I found no integrity-relevant contradiction and did not reclassify direction.

## REQUIRED REPAIRS

None blocking. Three non-blocking items:
1. Freeze the next input in valid YAML.
2. Pass the B3/G1 literature-overlap caveat forward to the A9.1 source-plan review and the strict auditor.
3. Ledger this review's own provenance from sequence 97 onward. That is an ongoing obligation, not a defect.

## LEDGER EXTENSION INTEGRITY STATUS

The following are all confirmed for sequences 40–96 through commit `42eb83a`:
- continuity of sequences 40–96;
- base-blob chaining across all 11 appends;
- commit, blob and timestamp identity for all 47 commit-bearing entries;
- immutability, with no reachable rewrite;
- sufficient order anchors for every off-repository event;
- no unledgered Study-3 artifact commits;
- no recorded or contradicted outcome-relevant exposure.

Reviewer F's chronology premise survives. This status does not certify A6 coverage or authorize G1.

`LEDGER_EXTENSION_INTEGRITY_PASS`
```
