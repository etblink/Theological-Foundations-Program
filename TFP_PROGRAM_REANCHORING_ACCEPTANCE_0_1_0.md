# TFP Program Re-Anchoring Acceptance 0.1.0

**Date:** 2026-10-05  
**Human-owner decision:** `APPROVED`  
**Checkpoint:** `TFP_PROGRAM_REANCHORING_CHECKPOINT_0_1_0.md`

## Decision

The human owner approves the program re-anchoring checkpoint.

The following steering rules are now accepted:

1. TFP remains a truth-seeking program. Protocol development is infrastructure, not the program's terminal product.
2. One bounded Protocol 0.1.7 repair cycle is authorized.
3. The 0.1.7 repair is limited to:
   - the five accepted MAJOR defects from the Protocol 0.1.6 strict qualification audit; and
   - MINOR defects that directly interact with those MAJOR surfaces, qualification validity, or cold-start executability.
4. No new generalized meta-methodological machinery may be added without direct necessity for one of those repair surfaces.
5. The next strict audit is an exit gate:
   - `PASS` or `PASS_WITH_LIMITATIONS`, with no protocol-defined repair-triggering defect cluster, is sufficient to proceed to human-owner qualification;
   - a new repair loop is not automatic.
6. If a future audit failure is driven mainly by newly created meta-machinery, perform a simplification review before considering another protocol version.
7. After qualification:
   - freeze the protocol;
   - place methodology in maintenance mode;
   - prepare and separately authorize a bounded substantive theological truth study;
   - let later method revisions be driven primarily by observed study failures rather than speculative protocol-only perfection.
8. `TFP-STRESS-2` remains unauthorized until protocol qualification and a separate study preregistration/authorization.

## Governing maxim

> The protocol exists to help TFP discover what is true. TFP does not exist to perfect the protocol.

## Authorized next transition

```text
PROGRAM_REANCHOR = ACCEPTED
PROTOCOL_0_1_7_REPAIR = AUTHORIZED
REPAIR_SCOPE = FIVE_MAJOR_PLUS_DIRECTLY_INTERACTING_MINORS
NEW_META_MACHINERY_DEFAULT = PROHIBITED
NEXT_AUDIT = QUALIFICATION_EXIT_GATE
TFP_STRESS_2 = NOT_AUTHORIZED
```
