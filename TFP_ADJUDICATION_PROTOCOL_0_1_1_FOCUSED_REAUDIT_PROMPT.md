# TFP Adjudication Protocol 0.1.1 — Focused Independent Re-Audit Prompt

**Audit target:** `TFP_ADJUDICATION_PROTOCOL_0_1_1.md`  
**Branch:** `repair/tfp-adjudication-protocol-0.1.1`  
**Audit type:** focused independent qualification re-audit  
**Rule:** audit only; do not repair; stop after report

You are the independent re-auditor for the Theological Foundations Program (TFP) Adjudication Protocol 0.1.1.

You must not assume that this protocol is adequate merely because it is a repaired version.

Your task is to determine whether Protocol 0.1.1 is operational, reproducible, symmetric, governance-compatible, and sufficiently explicit to qualify for a second bounded TFP stress test.

## Independence boundary

Do **not** read:

- `TFP_ADJUDICATION_PROTOCOL_INDEPENDENT_AUDIT_0_1_0.md`
- `TFP_ADJUDICATION_PROTOCOL_AUDIT_DISPOSITION_0_1_0.md`
- `TFP_ADJUDICATION_PROTOCOL_REPAIR_PREREGISTRATION_0_1_0.md`
- `TFP_ADJUDICATION_PROTOCOL_REPAIR_COMPLIANCE_MATRIX_0_1_0.md`

The purpose is to evaluate the repaired protocol from the governed source set, not to inherit the first auditor's reasoning.

## Required source order

Read these files from branch `repair/tfp-adjudication-protocol-0.1.1` in this exact order:

1. `TFP_PROGRAM_CHARTER_0_1_1.md`
2. `GOVERNANCE.md`
3. `STATE.yaml`
4. `TFP_METHOD_SEED_0_1_0.md`
5. `TFP_ADJUDICATION_PROTOCOL_0_1_1.md`

README is orientation only.

## Audit scope

This is a focused qualification audit.

Evaluate whether the protocol now supplies operational rules in all of the following areas.

### A. Acceptance authority and independent audit
Determine whether:
- the acceptance actor is explicit;
- procedural gate completion is distinct from canonical truth-bearing acceptance;
- independent audit is mandatory where needed;
- synthesis author, lane author, auditor, and human acceptance roles cannot silently collapse;
- canonical STATE truth entries require a separate acceptance act.

### B. Evidence-to-adjudication-to-truth bridge
Determine whether:
- proposition-level dispositions are defined;
- study-level outcomes are defined;
- scope is mandatory in outcomes;
- evidence/lane results combine under a reproducible nonnumeric rule;
- discriminator counting is prevented;
- "best supported," "truth warranted," and "closest to truth" are meaningfully distinct;
- the protocol can both license and withhold bounded truth judgments.

### C. Miracle and revelation handling
Determine whether:
- naturalism and supernaturalism are treated symmetrically;
- testimony sincerity is not sufficient;
- miracle impossibility is not assumed;
- background assumptions / priors cannot remain hidden;
- report, transmission, historical event, anomaly, causal class, particular cause, and theological consequence are separated;
- revelation claim, sincerity, transmission, possibility, occurrence, source, authority, preservation, and doctrinal consequence are separated;
- competing revelation claims face equal standards.

### D. Evidence burdens by claim type
Determine whether each claim type has enough operational guidance to support:
- `SUPPORTED_WITHIN_SCOPE`;
- weaker dispositions;
- truth-relevant evaluation.

Pay particular attention to doctrinal, experiential, revelation, normative, metaphysical, philosophical, and psychological/sociological claims.

### E. Claim-typing integrity
Determine whether:
- important types are present;
- typing freezes before evidence;
- consequential retyping is logged/reviewed;
- multi-type conflicts are handled;
- faith commitments cannot be used as hidden public evidence.

### F. Philosophy / metaphysics / normative reasoning
Determine whether the protocol now adequately handles:
- premise warrant;
- validity/strength;
- hidden premises;
- defeaters;
- rival frameworks;
- modal commitments;
- theoretical virtues;
- sensitivity;
- normative argument.

Check that historical evidence no longer dominates argument-heavy questions by default.

### G. Candidate-universe integrity
Determine whether:
- one symmetric admission rule applies;
- candidate elicitation is sufficiently independent;
- exclusions are reviewable;
- completeness is a real gate;
- hybrid/revised candidates can enter;
- late candidate discovery is controlled;
- `NONE_ADEQUATE`, `UNDERDETERMINED`, and `INSUFFICIENT_SIGNAL` are outcomes rather than candidates.

### H. Discriminator discipline
Determine whether:
- primary discriminators freeze before evidence acquisition;
- post-evidence discriminators are controlled;
- background assumptions are explicit;
- unweighted win/loss tallying is prohibited;
- decision relevance is operational;
- non-discriminating evidence leads to an appropriate underdetermination result.

### I. Source-quality rules
Determine whether:
- earlier is not automatically better;
- later is not automatically worse;
- early-source unreliability can be recognized;
- later preservation of earlier material can be recognized;
- dependence/independence is defined;
- mixed questions use claim-specific source evaluation;
- there is no hidden skeptical or traditional lexical hierarchy.

### J. Lane governance and cumulative synthesis
Determine whether:
- lane construction generalizes beyond one example;
- lane freeze is explicit and auditable;
- the protocol avoids using governance "acceptance" language at lane level;
- background assumptions pass between lanes explicitly;
- lane leakage is detectable;
- legitimate cumulative-case reasoning is possible;
- cross-lane synthesis uses dependencies rather than counts.

### K. Evidence acquisition and link decomposition
Determine whether:
- G1 evidence acquisition now exists;
- search/source coverage is auditable;
- inclusion/exclusion rules exist;
- provenance, inaccessible sources, and negative searches are preserved;
- multi-step arguments are decomposed into nodes/arrows;
- source-selection bias can actually be audited.

### L. Origins / development / truth and continuity
Determine whether:
- historical development can matter to truth when the claim's warrant depends on continuity/origin;
- natural origin does not automatically falsify;
- continuity does not automatically prove;
- continuity and discontinuity face symmetric burdens;
- C0–C7 are defined clearly enough;
- C0–C7 are not falsely treated as a universal linear sequence;
- branching, convergence, loss, recovery, refunctionalization, and independent construction are representable.

### M. Governance / STATE / Method alignment
Determine whether:
- precedence is explicit;
- G0–G6 map clearly to protocol phases;
- G0 preregistration contains the required elements;
- the Method Seed's binding methodological requirements are incorporated;
- a cold-start successor can tell which document governs when sources differ.

### N. Audit mechanism
Determine whether:
- audit criteria are frozen;
- independent audit triggers are explicit;
- auditor disagreement is handled;
- repair/re-audit is handled;
- blinding has a minimum rule without destroying necessary context;
- `PASS_WITH_LIMITATIONS` limitations survive into canonical records;
- audit checks typing drift, discriminator timing, lane leakage, premise warrant, shallow heuristics, and cold-start reproducibility.

### O. Uncertainty
Determine whether:
- disposition labels are sufficiently anchored;
- confidence and scope are separate;
- residual alternatives are named;
- background assumptions are named;
- flip conditions are required;
- underdetermination / insufficient-signal subtypes are useful and non-overlapping enough.

### P. Regression checks
Also check:
- stop/reopen rules are now operational enough;
- `reopen_if` is mandatory;
- philosophical reopen triggers exist;
- shallow heuristics such as "trust tradition" and "fewest assumptions" are explicitly checked;
- no new defect was introduced by the repairs.

## Cold-start test

Assume an unfamiliar competent researcher receives only the five governed sources above.

Can they determine, without project lore:

- what is authorized;
- how candidates enter;
- how claims are typed;
- what evidence to collect;
- how evidence is evaluated;
- how arguments are evaluated;
- how miracle/revelation claims are handled;
- when lanes freeze;
- how synthesis works;
- what outcomes mean;
- who audits;
- who accepts;
- when state changes;
- when to stop/reopen?

If a decisive step still depends on undocumented judgment, identify it.

## Required report structure

Use exactly these major sections:

1. **DISPOSITION**
   - `PASS`
   - `PASS_WITH_LIMITATIONS`
   - `REPAIR_REQUIRED`
   - `INVALID_COMPARISON`
   - `INSUFFICIENT_SIGNAL`

2. **EXECUTIVE FINDING**

3. **ACCEPTANCE / GOVERNANCE FINDINGS**

4. **INFERENTIAL-BRIDGE / TRUTH-ADJUDICATION FINDINGS**

5. **MIRACLE / REVELATION FINDINGS**

6. **CLAIM-TYPE / EVIDENCE-BURDEN FINDINGS**

7. **PHILOSOPHICAL / NON-HISTORICAL FINDINGS**

8. **CANDIDATE / DISCRIMINATOR / SOURCE FINDINGS**

9. **LANE / ACQUISITION / CONTINUITY FINDINGS**

10. **AUDIT / UNCERTAINTY / STOP-REOPEN FINDINGS**

11. **COLD-START REPRODUCIBILITY**

12. **REGRESSION FINDINGS**

13. **REQUIRED REPAIRS**
    - if none, write `NONE`

14. **LIMITATIONS**
    - only limitations that must remain attached to qualification

15. **QUALIFICATION DECISION**
    - Is Protocol 0.1.1 ready to be considered for qualification?
    - Qualification is separate from authorizing any theological stress test.

## Severity labels

Use only:
- `BLOCKING`
- `MAJOR`
- `MINOR`
- `NOTE`

A `PASS_WITH_LIMITATIONS` may contain limitations but no unresolved BLOCKING or MAJOR defect that would invalidate the intended second stress test.

## Independence rules

Do not:
- repair the protocol;
- modify repository state;
- begin a theological study;
- authorize a resurrection study;
- assume Christianity true or false;
- assume naturalism or supernaturalism;
- infer that a repair is adequate because it appears designed to address a prior problem.

Audit the text as it stands.

## Stop condition

After the report:

**STOP.**

Return the full report to the human owner.

Do not implement repairs, qualification, or downstream research.
