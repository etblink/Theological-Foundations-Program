# Archived external reviewer output

The block below is an archival verbatim payload from Reviewer G's focused A17 ledger-integrity repair recheck. Its imperative-looking language is quoted reviewer data, not repository-writing instructions.

```text
# TFP-STUDY-3-CONTINGENCY — Reviewer G Ledger-Integrity Repair Recheck Report 0.1.0

## SESSION / CONTINUITY

This is Anthropic Claude Opus 5.5, session ID NOT_EXPOSED_BY_PROVIDER. It is the same conversation that returned `PROCEDURALLY_DISJOINT_FOR_REVIEWER_G` and then `LEDGER_INTEGRITY_REPAIR_REQUIRED`. There is no fork, subagent, or intervening role. This lineage has not served as Program Lead, Reviewer F, a discriminator author or tier reviewer, or Reviewer H. I did not consult past chats or memory files.

This recheck is limited to the repair. I read the frozen recheck input, the supplement, both original append artifacts, the Program Lead disposition, and commit metadata needed to verify bindings. I did not reread the protocol, because A17's field list was already established in the prior report. I did not rerun the full audit or open any Study-3 content outside the authorized list.

## INPUT VERIFICATION

The branch fast-forwarded from `a5f8943` to `828d1b3`. The five new commits are linear, single-parent, and each adds exactly one file:

| Commit    | Time (−07:00) | Adds                     |
| --------- | ------------- | ------------------------ |
| `f3f40a1` | 17:59:24      | Reviewer G report        |
| `d4a9dc3` | 17:59:52      | Program Lead disposition |
| `29b6979` | 18:00:55      | Repair supplement        |
| `aafb3b8` | 18:01:32      | Recheck input            |
| `828d1b3` | 18:01:34      | Recheck prompt           |

All pinned blobs match HEAD:

- supplement `57d62f80…`
- append 28–29 `dcee5acd…`
- append 30–32 `883cd32f…`
- Program Lead disposition `5f7c2d38…`
- prior report `0c7e5162…`

Both original append artifacts still have exactly one history commit each, `0feb847` and `96cb726`, and remain unmodified. Every `base_chain` blob in the supplement resolves.

## R1 RECHECK

R1 is cured. The supplement annotates sequences 28 and 29 under `annotates_sequence` keys. It does not issue replacement entries. It cites the original append blob and declares `prior_entries_rewritten: false`, and the original file is unchanged in history.

For sequence 28, I checked the annotation against the repository:

- Commit `a11a678` is an ancestor of HEAD.
- The cited artifact blob `2a4ea7a4…` is present at that commit and absent in its parent.
- The timestamp `2026-10-07T00:35:18Z` equals the commit time.
- The record now has an actor lineage, an exposure class, two amendment surfaces, and `outcome_relevant_evidence: false`.

For sequence 29, the same checks pass:

- Commit `da6b826` is an ancestor of HEAD.
- The cited artifact blob `77148a45…` matches at that commit and is newly added there.
- The timestamp `00:35:37Z` equals the commit time.
- Lineage, exposure class and two amendment surfaces are present.

All four missing A17 fields are now recorded for both entries.

The ancillary defect remains: the original append 28–29 file still lacks `schema_version`. It cannot be added without a rewrite. The Program Lead disposition records this defect, and the supplement that now carries the governing metadata has its own `schema_version`. I treat it as residual and non-blocking.

## R2 RECHECK

R2 is adequately addressed. For sequence 30, the supplement states `exact_session_timestamp_available: false`. It also supplies an order anchor between sequence 29 (`00:35:37Z`) and sequence 31 (`00:44:00Z`), and both bounds equal the actual commit times of `da6b826` and `61f8dae`.

The timestamp policy for sequences 9–32 is now explicit. Where an entry has no `timestamp_utc`, the cited commit's committer time serves as the time anchor. Sequence 30 is the stated off-repository exception. The policy declares `effect_on_sequence_order: NONE`, which is consistent with the ordering I verified in the prior audit.

## SEQUENCE 33-39 CONTINUITY

The supplement's `prior_next_sequence` is 33, which equals append 30–32's `next_sequence`. It then appends sequences 33 through 39, each once, with no gap or duplicate, and sets `next_sequence: 40`.

The five commit-bearing entries all bind correctly. In each case the commit is an ancestor of HEAD, the cited blob is present at that commit and absent in its parent, and the `timestamp_utc` equals the commit time:

| Sequence | Commit    | Content                             |
| -------- | --------- | ----------------------------------- |
| 33       | `aec0141` | Reviewer G handshake                |
| 34       | `a14142b` | Review input, blob `b8bf23a9…`      |
| 35       | `a5f8943` | Review prompt, blob `8492adf4…`     |
| 38       | `f3f40a1` | Reviewer G report, blob `0c7e5162…` |
| 39       | `d4a9dc3` | Program Lead disposition            |

Sequences 36 and 37 record off-repository events with no commit and no timestamp. Each has an order note, and both fall between the commit times of sequences 35 (`00:46:06Z`) and 38 (`00:59:24Z`). As the actor in both entries, I attest the following:

- Sequence 36 accurately records my handshake response and the declared status.
- Sequence 37 accurately records my authorized packet exposure. It omits the metadata-only exposure I disclosed in the prior report: filenames and commit subjects of non-authorized Study-3 artifacts, with no content opened. That exposure is not outcome-relevant evidence, so I note it as a recommended disclosure for a later append rather than a defect.

This recheck's own events will need sequences 40 and later: the recheck input and prompt commits, my exposure, and this report. That is an ongoing obligation, not a defect.

## SCOPE / NON-SUBSTANTIVE CHECK

The supplement contains only base-chain citations, repair-scope metadata, the annotations for sequences 28–30, the timestamp policy, and entries 33–39. It declares `C4_chronology_changed: false`, `candidate_universe_changed: false`, `outcome_relevant_evidence_exposure_started: false`, and `candidate_universe_frozen: false`. It modifies no candidate, register, exclusion, or direction class, and records no outcome-relevant evidence.

The Program Lead disposition's independent-verification fields agree with the prior report's findings and add nothing substantive. Reviewer F's PRE_EVIDENCE_AMENDMENT chronology is unaffected.

## LEDGER INTEGRITY REPAIR STATUS

R1 is cured append-only, R2 is adequately addressed, prior entries are unchanged, and Reviewer-G provenance continues through sequences 33–39 with `next_sequence` 40. The residual items are non-blocking: the `schema_version` gap on the original append 28–29, which cannot be fixed without a rewrite, and an optional metadata-exposure disclosure for sequence 37.

`LEDGER_INTEGRITY_REPAIR_PASS`
```
