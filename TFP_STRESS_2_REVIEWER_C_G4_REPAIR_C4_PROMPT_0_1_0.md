# TFP-STRESS-2 — Reviewer C G4 Repair C4 Review

Use a brand-new clean xAI/Grok conversation. Do not continue any prior Reviewer-C conversation.

Repository: https://github.com/etblink/Theological-Foundations-Program

Read first:

`TFP_STRESS_2_REVIEWER_C_G4_REPAIR_C4_INPUT_FREEZE_0_1_0.yaml`

Expected blob:

`231ae4685f4e6acd7047f1ea771d326334a7fc3b`

Your role is only **Reviewer C / amendment-direction reviewer** under Protocol 0.1.7 C4.

For each item A-H in the input freeze:

1. verify the pinned artifact identity;
2. independently identify every affected candidate/outcome condition;
3. classify each effect as exactly one of:
   - `ADVERSE`
   - `FAVORABLE`
   - `NEUTRAL`
   - `MIXED_OR_UNCLEAR`
4. assign exactly one aggregate C4 class:
   - `POST_EVIDENCE_NONMATERIAL`
   - `POST_EVIDENCE_ADVERSE_ONLY`
   - `POST_EVIDENCE_FAVORABLE_OR_MIXED`
5. state whether the item may be used in the current confirmatory record;
6. state whether it triggers `UNDERDETERMINED_WITHIN_SCOPE: POST_EVIDENCE_DIRECTIONAL_CONTAMINATION` or requires a fresh confirmatory cycle for positive comparative use.

Do not presume the Program Lead's provisional classifications are correct. Do not re-rank candidates, re-adjudicate Q1, act as Reviewer D, act as strict auditor, or modify the repository.

Return one complete report with:
- SESSION / LINEAGE IDENTITY
- PIN VERIFICATION
- C4 STANDARD
- ITEMS A-H REVIEW TABLE
- ITEM-BY-ITEM REASONS
- BATCH SUMMARY
- CURRENT-STUDY USE ANSWER

Return the report verbatim and stop.
