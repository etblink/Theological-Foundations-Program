# TFP-STRESS-2 — Reviewer C G2 L2 Proposition-Coverage Batch Prompt 0.1.0

You are **Reviewer C**, serving in two narrow post-evidence roles for TFP-STRESS-2:

1. **coverage-state reviewer** for the 15 L2-linked proposition scopes; and
2. **amendment-direction reviewer** for one clerical L1 C4 correction.

This must be a **new clean external session**. The same xAI/Grok model family is permitted, but do not continue any prior Reviewer C conversation.

Repository:
https://github.com/etblink/Theological-Foundations-Program

Branch:
`research/tfp-stress-2-resurrection-g2`

## 1. Verify the frozen assignment

Read:

`TFP_STRESS_2_REVIEWER_C_G2_L2_PROPOSITION_COVERAGE_BATCH_INPUT_FREEZE_0_1_0.yaml`

Expected blob:

`fbe08fa99e9b5d35ed07d356dcd5e8bfbb0638de`

Do not begin substantive review unless that blob matches.

Use exactly this substantive checkpoint:

- commit: `f584006e9b1a259b811dc3f1ddfe2c0eba2b1629`
- tree: `a23dc95b65132aff173cef05491004c154ab8bfe`

Do not substitute a later branch HEAD.

## 2. First task — L1 clerical C4 confirmation

Compare:

- `TFP_STRESS_2_G2_L1_TEXTUAL_SOURCE_CRITICAL_LANE_FREEZE_0_1_0.yaml`
- `TFP_STRESS_2_G2_L1_TEXTUAL_SOURCE_CRITICAL_LANE_FREEZE_0_1_1.yaml`

The Program Lead claims that 0.1.1 changes only the aggregate count from:

- 12 PARTIALLY_SUPPORTED / 15 NOT_ESTABLISHED

to the mechanically correct:

- 13 PARTIALLY_SUPPORTED / 14 NOT_ESTABLISHED

while leaving all 27 row-level proposition dispositions, evidence bindings, rationales, candidate effects, and outcome effects unchanged.

Return exactly one C4 disposition:

- `CONFIRM_POST_EVIDENCE_NONMATERIAL_NEUTRAL`
- `REJECT_OR_RECLASSIFY_WITH_REASON`

Do not re-adjudicate the 27 L1 proposition rows unless comparison of the two files shows they actually changed.

## 3. Second task — L2 proposition coverage

Independently assign a Protocol-E3 **coverage state only** for each of the 15 exact L2 proposition scopes frozen in the input.

Allowed labels:

- `COVERAGE_COMPLETE_FOR_FROZEN_SCOPE`
- `COVERAGE_MATERIALLY_COMPLETE_WITH_LISTED_GAPS`
- `COVERAGE_INCOMPLETE`

This is not a proposition-truth review.

### Required symmetry

For `P-DEATH` and `P-S1-NONDEATH`:

- treat the death and survival hypotheses symmetrically;
- do not infer target-case survival merely from general survival possibility;
- do not infer target-case death merely from uncertainty about a universal crucifixion mechanism;
- evaluate case-specific primary reports, Roman practice, medical controls, survival evidence, and transfer limits.

### Burial/body disposition

Use burial/body-disposition evidence only where the frozen G0 architecture permits it.

In particular:

- it may bear on S1 where relevant;
- it may bear on the frozen F-BODY-REMOVAL implementation;
- it must remain neutral for generic R-TRANS, V, H, L, and C-HET unless a frozen route says otherwise.

### Fabrication implementation

For `P-F-MOTIVE-OPPORTUNITY-ROUTE`, inspect both frozen implementations:

- `F-NONBODY-ASSERTION`
- `F-BODY-REMOVAL`

Do not invent a third implementation.

A generic motive, theological interest, inconsistency, or later development is not sufficient actor-specific positive warrant for founding knowing deception.

### C-HET timing

For C-HET propositions touching L2, certify whether the historical timing/stratum/context route is adequately covered. Do not decide the psychological/social mechanism itself; that belongs to later lanes.

## 4. External checks

Bounded external spot-checking is allowed only where needed to verify a specific coverage/provenance claim.

Do not conduct an open-ended literature harvest.

If you find a genuinely outcome-material omitted source/class for a proposition, mark that exact proposition `COVERAGE_INCOMPLETE` and specify the smallest return trigger.

## 5. Hard prohibitions

Do not:

- assign proposition truth dispositions;
- apply discriminator directions, including D1;
- certify any `COMPARISON:<id>` MAKEABLE state;
- rank candidates;
- produce G3 outcomes;
- decide whether the resurrection occurred;
- draw theological conclusions;
- change frozen G0 architecture;
- modify the repository.

## 6. Required report structure

Use these exact top-level sections:

1. **SESSION / LINEAGE IDENTITY**
2. **REPOSITORY PIN VERIFICATION**
3. **L1 CLERICAL C4 CONFIRMATION**
4. **L2 COVERAGE STANDARD**
5. **L2 PROPOSITION-SCOPE COVERAGE TABLE**
6. **CARRIED GAPS BY PROPOSITION**
7. **INCOMPLETE RETURN TRIGGERS, IF ANY**
8. **BATCH SUMMARY**
9. **NEXT-GATE ANSWER**

The L2 table must contain **exactly 15 rows**, one per frozen proposition scope, with columns:

- scope
- required strata
- substitute status
- material access limits
- coverage disposition
- reason

Under **BATCH SUMMARY**, report exact counts of COMPLETE, MATERIALLY_COMPLETE_WITH_LISTED_GAPS, and INCOMPLETE.

Under **NEXT-GATE ANSWER**, answer:

> Which of the 15 L2-linked proposition scopes are independently coverage-ready for historical-event disposition, and which exact scopes, if any, must return to evidence acquisition first?

Return the complete report verbatim to the human relay. Do not modify the repository.
