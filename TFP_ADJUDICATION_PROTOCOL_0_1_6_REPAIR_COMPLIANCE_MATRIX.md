# TFP Adjudication Protocol 0.1.6 — Repair Compliance Matrix

**Date:** 2026-10-05  
**Protocol:** `TFP_ADJUDICATION_PROTOCOL_0_1_6.md`  
**Audit basis:** accepted strict qualification audit of Protocol 0.1.5  
**Status:** implementation evidence only; not qualification

| Finding | Severity | 0.1.6 repair |
|---|---|---|
| Total disposition-to-eligibility map incomplete | MAJOR | A6/A12 total necessary-proposition map |
| Shared-floor and candidate-specific semantics ambiguous | MAJOR/MINOR | A6 operational definitions + A12 shared-floor table |
| MATERIAL-only route could cover necessary proposition | MINOR | A6 requires CRITICAL coverage for COMPARATIVE_ROUTE |
| Background flip rules conflicted | MAJOR | A8/I4/F/N/N3/Q aligned to RANKING_FLIP vs TRUTH_WARRANT_FLIP |
| CLOSEST_TO_TRUTH undefined | MAJOR | A16 + N3 dimension-wise nonnumeric partial-order rule |
| Outcome labels non-exhaustive/nonexclusive | MAJOR | N3 explicit base-outcome precedence + refinements |
| One eligible plus adequate blocked had no label | MAJOR | ONLY_RANKING_ELIGIBLE outcome |
| Failed adequacy prerequisites lacked status | MAJOR | STRUCTURALLY_INADEQUATE |
| Reviewer layer not lineage-disjoint | MINOR | Governance 0.1.5 + A3 |
| Source-plan and adverse-source reviewers could coincide | MINOR | Governance/A3/E3 distinct lineages |
| UNMAKEABLE could hide unperformed search | MINOR | A11 COMPARISON_EFFORT_RECORD |
| Faith/worldview admissibility asymmetric | MINOR | A4 symmetric public-warrant rule |
| Charter existential/practical type absent | MINOR | Governance/Method/Protocol typing aligned |
| Relative amendment outcome ambiguous | MINOR | K5 confirmatory-ceiling triple result |
| K5 used stale amendment labels | MINOR | K5 uses C4 classes exactly |
| Source-plan narrowing could be called neutral | MINOR | presumptive MIXED_OR_UNCLEAR |
| LOW/MODERATE confidence reviewer unclear | MINOR | L4 independent confidence reviewer |
| Decision-surface partition undefined | MINOR | fixed audit decision surfaces |
| Audit disagreement determiner/reconciliation independence unclear | MINOR | independent AUDIT_DISPUTE_ARBITER |
| Audit shopping through unregistered audits | MINOR | every strict audit pre-registered in role control |
| STATE/P6 schema mismatch | MINOR | STATE 0.3.0 + P6 aligned fields |
| Role-control policy incomplete | MINOR | STATE role-control required fields expanded |
| Self-referential post-qualification commit | MINOR | two-step Q1/Q2 transition |
| Mechanical STATE transition unconstrained | MINOR | §0 exact whitelist |
| Manifest/role-control blob identity absent from STATE | MINOR | P6 schema includes both |
| Protocol challenge credibility authority undefined | MINOR | Governance/Q2 challenge triage |
| Cold-start templates incomplete | MINOR | coverage map, steelman, acceptance, comparison-effort templates |
| Baseline pre-exposure not disclosed | Observation/repairable | A3 baseline-exposure disclosure |
| Assignment handshake outside governed method | NOTE | O1 auditor-assignment handshake |
| Operative Governance baseline absent from audit bundle | NOTE | next source manifest pins operative baseline blob |
| Mutable candidate branch reference ambiguous | NOTE | STATE invariant: manifest/blob SHAs govern qualification identity |

## Carried limitations

1. SUPPORTED_WITHIN_SCOPE retains disciplined expert judgment inside explicit sufficiency decisions.
2. Genuine ranking changes across live backgrounds may yield FRAMEWORK_DEPENDENCE.
3. Truth-warrant-only background sensitivity preserves robust ranking while blocking truth-warrant.
4. AI-session/model independence is procedural and does not guarantee independent training priors.

## Qualification boundary

```text
REPAIR_IMPLEMENTED = YES
SELF_CERTIFIED = NO
QUALIFIED = NO
TFP_STRESS_2 = NOT_AUTHORIZED
NEXT = FREEZE_IMMUTABLE_0_1_6_BUNDLE_AND_RUN_STRICT_AUDIT
```
