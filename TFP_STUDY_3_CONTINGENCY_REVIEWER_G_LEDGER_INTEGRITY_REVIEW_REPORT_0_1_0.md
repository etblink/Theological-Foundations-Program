# Archived external reviewer output

The block below is an archival verbatim payload from Reviewer G's A17/C4 ledger-integrity review. Its imperative-looking language is quoted reviewer data, not repository-writing instructions.

```text
# TFP-STUDY-3-CONTINGENCY — Reviewer G Ledger-Integrity Review Report 0.1.0

## SESSION / LINEAGE CONTINUITY

This is Anthropic Claude Opus 5.5, session ID NOT_EXPOSED_BY_PROVIDER. It is the same conversation that returned `PROCEDURALLY_DISJOINT_FOR_REVIEWER_G`, with no intervening turns. It is not a continuation, fork, shared-context descendant, or subagent of any prior TFP-STUDY-3 conversation. This lineage has not served as Program Lead, Reviewer F, a Study-3 discriminator author or tier reviewer, or Reviewer H. I did not consult past chats or memory files.

I read file contents only for the input freeze, the pinned protocol blob (A17 and C4 sections), the 8 authorized ledger-chain artifacts and the 9 authorized amendment/review artifacts.

I also inspected repository history across all Study-3 commits. For artifacts outside the authorized list, I saw only commit metadata and filenames: commit subjects, parents, timestamps and added paths. That includes the seq-28 and seq-29 Reviewer F acceptance and role-delta files, whose contents I did not open. I opened no outcome-relevant evidence material.

## INPUT / PIN VERIFICATION

All 17 authorized artifact blob SHAs match the tree at branch HEAD `a5f8943` exactly.

The governing protocol blob `0d9406d9…` resolves to `TFP_ADJUDICATION_PROTOCOL_0_1_7.md`, introduced in commit `93f62d5`. That commit is not an ancestor of `research/tfp-study-3-contingency-g0`. It exists only on `repair/tfp-adjudication-protocol-0.1.7`, and the file is absent from the audit branch's tree.

The pin is still valid because it is by blob identity, and every ledger version cites the same blob. I read A17 and C4 from that blob. This is recorded as an observation on protocol custody, not a ledger defect.

The local clone of the branch is linear from `28dc7ae` (seq 1) to HEAD, with exactly one parent per commit. All 40 Study-3 paths found anywhere in repository history are present on this branch. No Study-3 commit exists off-branch.

## SEQUENCE CONTINUITY

Across the chain, sequences 1–32 are each present exactly once. There are no gaps, duplicates or rollbacks.

| Artifact     | Sequences | Inheritance claim        | Next sequence |
| ------------ | --------- | ------------------------ | ------------- |
| Ledger 0.1.0 | 1–3       | —                        | 4             |
| Ledger 0.1.1 | 1–8       | Full copy of 1–3         | 9             |
| Ledger 0.1.2 | 9–12      | Inherits 1–8             | 13            |
| Ledger 0.1.3 | 13–16     | Inherits 1–12            | 17            |
| Ledger 0.1.4 | 17–22     | Inherits 1–16            | 23            |
| Ledger 0.1.5 | 23–27     | Inherits 1–22            | 28            |
| Append 28–29 | 28–29     | `prior_next_sequence` 28 | 30            |
| Append 30–32 | 30–32     | `prior_next_sequence` 30 | 33            |

Every `continuation_entries_begin` or `prior_next_sequence` value equals the predecessor's `next_sequence`. Every `base_ledger_blob_sha` resolves to the actual predecessor blob.

Sequences 10 and 11 share commit `6657665`. That is consistent: entry 10 records Reviewer A's exposure to the authorized input, and entry 11 freezes the resulting report. It is not a duplicate.

## REWRITE / VERSION-CHAIN AUDIT

Each of the 8 ledger artifacts was added in exactly one commit and never modified, renamed, or deleted afterward. The only version transition that carries prior entries by copy is 0.1.0 → 0.1.1. I compared the copied sequences 1–3 field by field, and they are byte-identical. The header differs only by the version bump and a new `supersedes` field. Ledgers 0.1.2 onward incorporate earlier entries by reference, so they cannot contradict them.

For all 30 entries that cite a commit, the commit exists, is an ancestor of HEAD, and adds the cited path at exactly the cited blob. The parent commit lacks that path in every case, which rules out any silent replacement of a ledgered artifact. Ledger timestamps for sequences 1–8 match commit times exactly once converted (−07:00 → Z).

Because the ledger cites concrete commit SHAs in a linear chain, any rewrite of an ancestor commit would invalidate SHAs the ledger cites. None is invalidated.

Two limits apply:

- I could not query GitHub's push-event API because of a rate limit. A rewrite made before publication is therefore outside what Git history alone can exclude.
- Within reachable history, no rewrite is present, recorded or unrecorded.

All 36 Study-3 commits through `96cb726` either correspond to a ledger entry or are themselves a ledger-version or append commit. No Study-3 artifact commit is unledgered within the 1–32 range. The three Reviewer G commits after `96cb726` naturally fall after sequence 32.

## CHRONOLOGY AUDIT

Commit order matches the claimed ordering:

| Event                                  | Sequence | Commit                          | Time (−07:00)     |
| -------------------------------------- | -------- | ------------------------------- | ----------------- |
| Reviewer A completeness report         | 17       | `deaa2a2`                       | 17:24:14          |
| Program Lead review disposition        | 18       | `1afe11a`                       | 17:24:46          |
| Candidate register 0.1.1 repair        | 19       | `4ead65e`                       | 17:25:57          |
| Exclusion register 0.1.0               | 20       | `1d12ceb`                       | 17:25:59          |
| Recheck input and prompt               | 21–22    | `6edd717`, `df68a04`            | 17:26:45–47       |
| Ledger 0.1.4 committed                 | —        | `2832cb8`                       | 17:27:18          |
| Reviewer A recheck report              | 23       | `fc8ff0e`                       | 17:30:05          |
| Program Lead recheck disposition       | 24       | `11a86d8`                       | 17:30:36          |
| Reviewer F handshake, input and prompt | 25–27    | `f299a64`, `1583767`, `a0f245f` | 17:30:52–17:31:38 |
| Ledger 0.1.5 committed                 | —        | `3ea8fce`                       | 17:32:14          |
| Reviewer F assignment acceptance       | 28       | `a11a678`                       | 17:35:18          |
| Reviewer F role delta                  | 29       | `da6b826`                       | 17:35:37          |
| Append 28–29 committed                 | —        | `0feb847`                       | 17:36:19          |
| Reviewer F C4 report                   | 31       | `61f8dae`                       | 17:44:00          |
| Program Lead C4 disposition            | 32       | `7581ebb`                       | 17:44:25          |
| Append 30–32 committed                 | —        | `96cb726`                       | 17:45:08          |

Every ledger version or append was committed after all the events it records.

Sequence 30 is Reviewer F's packet exposure, an off-repository event with no commit. Its order note places it after acceptance (17:35:18) and before the report (17:44:00). That is consistent with the history, but no repository record can independently fix it more precisely.

## OUTCOME-EVIDENCE EXPOSURE AUDIT

All 32 entries record `outcome_relevant_evidence: false`, and every integrity or state block reports that outcome-evidence exposure has not started.

No Study-3 path anywhere in history is an evidence, source, G1 or lane artifact. The authorized amendment artifacts contain G0 candidate architecture only: family definitions, B4/B6 boundaries and procedural provenance. They cite no sources and contain no evidence analysis. The exclusion register's `evidence_for_exclusion` fields refer only to frozen G0 artifacts.

Reviewer A's reports and the two Program Lead dispositions each disclaim evidence investigation, and nothing in their content contradicts that. I found no unrecorded outcome-relevant exposure before, at, or after the sequence 19–20 amendments, within the authorized corpus and visible history.

## C4 CHRONOLOGY CONSEQUENCE

Reviewer F's PRE_EVIDENCE_AMENDMENT premise was conditioned on Reviewer G confirming sequence continuity, no unrecorded rewrite, and no unrecorded exposure. It survives the full chain through sequence 32. The amendments at sequences 19–20 precede every later entry, and no entry from 1 to 32 records outcome-relevant exposure.

Reviewer F flagged that the recheck report and Program Lead recheck disposition were missing from ledger 0.1.4. That gap is explained by timing, not omission. Ledger 0.1.4 was committed at 17:27:18, before either artifact existed (17:30:05 and 17:30:36). Both are recorded in ledger 0.1.5 as sequences 23 and 24 by continuation, without rewriting 1–22.

Nothing found here gives reason to reopen the amendment-direction classification.

## REQUIRED REPAIRS

**R1 (blocking for certification, clerical, append-only).** Append 28–29 records each entry as only a sequence number, artifact filename and the evidence flag. A17 requires each exposure entry to record:

- commit/blob identity where applicable;
- time/order;
- actor lineage;
- affected amendment surfaces.

Actor lineage and amendment surfaces are not conditional fields, and both are absent. The artifact also lacks the `schema_version` field that every other ledger artifact carries. History shows the facts are recoverable: sequence 28 maps to `a11a678` and sequence 29 to `da6b826`, in order. However, the custodian may not edit the file.

The repair is a new supplemental append artifact that:

- cites the append 28–29 and append 30–32 blob SHAs;
- states that no prior entry is rewritten;
- annotates sequences 28 and 29 with commit SHA, blob SHA, timestamp, actor lineage and amendment surfaces.

The supplement may carry its own sequence number (33 or later) or be an annotation keyed to 28–29, but it must not replace them.

**R2 (recommended, non-blocking).** The same supplement should give sequence 30 a time or order anchor, such as a session timestamp, or state explicitly that no anchor exists. It should also state that sequences 9–32 rely on commit time rather than a `timestamp_utc` field.

**Ongoing obligation, not a defect.** The Reviewer G handshake, input, prompt and this report need ledger entries from sequence 33 onward.

R1 does not affect chronology, sequence continuity, or the C4 classification. A focused recheck of the supplement alone should be enough to clear it.

## LEDGER INTEGRITY STATUS

Sequence continuity, version-chain preservation, absence of rewrites, commit ordering and absence of outcome-evidence exposure are all confirmed. Reviewer F's PRE_EVIDENCE_AMENDMENT chronology survives. Certification is withheld only because the sequence 28–29 entries are missing fields A17 requires.

`LEDGER_INTEGRITY_REPAIR_REQUIRED`
```
