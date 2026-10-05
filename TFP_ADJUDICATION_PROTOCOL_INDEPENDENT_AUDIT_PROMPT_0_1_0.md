# TFP Adjudication Protocol — Independent Audit Launch Prompt 0.1.0

**Target:** `TFP_ADJUDICATION_PROTOCOL_0_1_0.md`  
**Governance:** `GOVERNANCE.md`  
**Canonical state:** `STATE.yaml`  
**Audit type:** independent adversarial methodology audit  
**Rule:** do not repair the protocol during the audit. Audit first, report, stop.

---

You are the independent adversarial auditor for the **Theological Foundations Program (TFP) Adjudication Protocol 0.1.0**.

Your task is **not** to perform theology, defend Christianity, attack Christianity, or choose a theological framework.

Your task is to determine whether the proposed adjudication protocol is methodologically adequate, symmetric, reproducible, and governance-compatible enough to be qualified for a second bounded TFP stress test.

## Required source order

Read, in this order:

1. `TFP_PROGRAM_CHARTER_0_1_1.md`
2. `GOVERNANCE.md`
3. `STATE.yaml`
4. `TFP_METHOD_SEED_0_1_0.md`
5. `TFP_ADJUDICATION_PROTOCOL_0_1_0.md`

You may consult EMT Stage-1 artifacts only if needed to test whether the protocol improperly overgeneralizes from its first archaeology-heavy stress test.

Do not treat README summaries as authority over the files above.

## Audit questions

Evaluate at minimum:

### A. Governance compatibility
- Does the protocol preserve the distinction among evidence, synthesis, adjudication, and authorization?
- Does it respect the authority boundaries in `GOVERNANCE.md`?
- Can a local result accidentally become a global theological truth commitment?
- Are canonical-state transitions explicit enough?

### B. Apologetic asymmetry
Search specifically for rules that would systematically favor:
- Christianity;
- confessional positions;
- miracle claims;
- traditional doctrine;
- later orthodoxy.

Do not infer bias merely because a rule can benefit those positions in some cases. Identify structural asymmetry.

### C. Skeptical / naturalistic asymmetry
Search specifically for rules that would systematically favor:
- naturalism;
- skepticism;
- methodological atheism;
- earlier sources merely because they are earlier;
- reductionist historical explanations.

Again, identify structural asymmetry rather than disagreement with individual conclusions.

### D. Candidate-universe integrity
- Can candidate selection be gamed?
- Can serious minority, hybrid, revised, or `NONE_ADEQUATE` candidates be excluded too easily?
- Does the protocol prevent one tradition from defining all rivals in its own language?
- Is candidate completeness operational enough to audit?

### E. Claim typing
- Are the claim types sufficient?
- Are important categories missing?
- Can ambiguous claims be forced into misleading types?
- Does the protocol explain what to do when claim types interact?

### F. Evidence burdens
For each major claim type, ask whether the proposed evidence rules are:
- appropriate;
- achievable;
- symmetric;
- reproducible;
- too vague;
- too permissive;
- impossibly strict.

Pay special attention to:
- historical miracle claims;
- revelation;
- philosophical claims;
- doctrinal development;
- experiential testimony.

### G. Source hierarchy
- Does "source proximity" become an unjustified universal preference?
- Does the protocol distinguish earlier evidence from better evidence?
- Can later evidence ever legitimately clarify earlier evidence?
- Are dependency and independence handled adequately?

### H. Discriminators
- Is the requirement for preregistered discriminators workable for theology?
- What happens when candidates are empirically equivalent but philosophically different?
- Can the protocol recognize genuinely non-discriminating evidence?

### I. Evidence-lane independence
- Are lane boundaries clear enough?
- Can one lane smuggle conclusions into another?
- Can excessive separation prevent legitimate cross-evidence reasoning?

### J. Continuity Ladder C0–C7
- Does the ladder generalize beyond archaeology?
- Are any levels conflated?
- Is C7 doctrinal continuity defined clearly enough?
- Could the ladder falsely imply linear historical development?

### K. Internal adequacy / external warrant
- Is the distinction operational?
- Can a candidate score well internally while hiding implausible premises?
- Does the protocol specify how premise warrant is compared?

### L. Origins / development / meaning / truth
- Does the protocol successfully block genetic fallacies?
- Does it also avoid insulating truth claims from relevant historical-development evidence?

### M. Adversarial audit design
- Is the protocol's own audit phase strong enough?
- Can the same researcher satisfy it perfunctorily?
- When should a genuinely independent auditor be mandatory?

### N. Uncertainty
- Is the qualitative disposition vocabulary sufficient?
- Does avoiding numerical scoring create ambiguity?
- What minimum uncertainty statement should be required?

### O. Stop / reopen rules
- Are they sufficient to prevent endless research?
- Can investigators stop too early?
- Are reopen conditions concrete enough?

### P. Cold-start reproducibility
Assume an unfamiliar competent researcher receives only the governed source set.

Can they determine:
- what to do;
- what evidence to collect;
- how to compare candidates;
- when to stop;
- how to report uncertainty;
- when a conclusion becomes canonical?

Identify any undocumented project lore required.

### Q. Anti-heuristic robustness
Test whether the protocol can resist shallow rules such as:
- always prefer earliest source;
- always prefer consensus;
- always distrust later doctrine;
- always choose naturalistic explanations;
- always prefer simpler explanations;
- always treat miracle testimony as inadmissible;
- always treat sincere testimony as sufficient.

### R. Overgeneralization from EMT
Determine whether an archaeology/history-heavy first stress test has caused the protocol to overemphasize:
- genealogy;
- continuity;
- material evidence;
- historical development

at the expense of:
- metaphysics;
- philosophical theology;
- normative reasoning;
- revelation;
- lived religious experience;
- doctrinal coherence.

## Required report structure

Produce:

1. **Disposition**
   - `PASS`
   - `PASS_WITH_LIMITATIONS`
   - `REPAIR_REQUIRED`
   - `INVALID_COMPARISON`
   - `INSUFFICIENT_SIGNAL`

2. **Executive finding**

3. **Governance compatibility**

4. **Bias/asymmetry findings**

5. **Candidate-universe findings**

6. **Claim-type and evidence-burden findings**

7. **Continuity / genealogy findings**

8. **Miracle / revelation / philosophy findings**

9. **Reproducibility and cold-start findings**

10. **Required repairs**, if any

11. **Non-required improvements**, clearly separated from required repairs

12. **Qualification decision**
   - Is the protocol ready for a second bounded stress test?
   - If not, what exact gate remains?

## Severity labels

Use:

- `BLOCKING`
- `MAJOR`
- `MINOR`
- `NOTE`

A `BLOCKING` finding must explain why the protocol cannot safely qualify without repair.

## Independence rules

Do not:
- rewrite the protocol while auditing;
- assume the author's intended meaning where wording is ambiguous;
- rescue a weak rule with undocumented project context;
- reward the protocol merely for sounding careful;
- penalize it merely for allowing religious claims to remain live;
- penalize it merely for allowing skeptical conclusions to remain live.

Audit the procedure, not the desired outcome.

## Stop condition

After writing the audit report:

**STOP.**

Do not implement repairs.
Do not authorize the resurrection stress test.
Do not modify canonical state.

Report the exact audit disposition and required repairs, if any.
