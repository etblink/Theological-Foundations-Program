# TFP-STRESS-2 — Reviewer B G0 Control Review Report 0.1.0

**Role:** REVIEWER_B (pre-G0 study-design control review)
**Prompt:** `TFP_STRESS_2_REVIEWER_B_G0_CONTROL_REVIEW_PROMPT_0_1_0.md`
**Date:** 2026-10-06
**Review type:** study-design control review. This is not a theological evidence review, not a G4 audit, and not G0 authorization.

---

## 1. SESSION / SOURCE IDENTITY / INDEPENDENCE

### Session identity

| Field | Value |
|---|---|
| Provider | Anthropic |
| Configured model | `claude-opus-5-5` (session record: `configured_model` = `session_context.model` = `last_served_model` = `claude-opus-5-5`) |
| Session ID | `session_01TsM4WriYnAiRn71ireaVfK` (Claude Code remote session, created 2026-10-06T03:17:58Z, origin `web_claude_ai`) |
| Distinct from `session_012EWsCBUVctdyhhk3v5ZxuF` | Yes |
| Fresh conversation | Yes. The only user turn in this conversation is the instruction to follow this prompt on branch `research/tfp-stress-2-resurrection-g0`. |
| Seen any prior TFP-STRESS-2 reviewer report, comparison record, program-lead discussion, candidate-list deliberation, or outcome reasoning | **No.** I have not read Reviewer A's blind report, the Reviewer A comparison/amendment record, the superseded 0.1.0 preregistration, issues, PRs, chat logs, or any other TFP-STRESS-2 artifact. |
| Persistent project/context source containing such reasoning | **No.** This session has no memory source carrying earlier TFP-STRESS-2 reasoning. The repository checkout contains other files, but I opened only the prompt and the four permitted blobs. |

**Disclosure of in-scope second-hand exposure.** The permitted 0.1.1 preregistration and the 0.1.1 role YAML themselves contain the program lead's summary of how Reviewer A's work was integrated. Examples are "Reviewer A's blind elicitation showed that the original worldview-only register was too coarse", "the former stand-alone C-BX model is not retained", and Reviewer A's disposition string and report blob SHA. Because the prompt explicitly permits these files, I read them, and I disclose here that this program-lead summary is in my context. I did not see Reviewer A's own reasoning.

### Source identity verification

All four identities were checked with `git rev-parse <rev>:<path>` against the exact SHAs in the prompt. Content was then read with `git cat-file -p <blob>`, so only the pinned blobs were read and branch-tip drift could not leak in.

| # | File | Required blob | Verified blob | Status |
|---|---|---|---|---|
| 1 | `TFP_STRESS_2_RESURRECTION_G0_PREREGISTRATION_0_1_1.md` (branch HEAD) | `b3811b5a04feab583a45aaf1360dd85266e7ac34` | `b3811b5a04feab583a45aaf1360dd85266e7ac34` | MATCH |
| 2 | `TFP_STRESS_2_ROLE_ARCHITECTURE_0_1_1.yaml` (branch HEAD) | `a77349497819469204036b89758e5c63b9e9903c` | `a77349497819469204036b89758e5c63b9e9903c` | MATCH |
| 3 | `TFP_ADJUDICATION_PROTOCOL_0_1_7.md` @ commit `b9854f8521193c44e3ed50f5a8b1672572674ec5` | `0d9406d9ea62ec35ce6424b60ef03ced5dbd332a` | `0d9406d9ea62ec35ce6424b60ef03ced5dbd332a` | MATCH |
| 4 | `GOVERNANCE.md` @ commit `b9854f8521193c44e3ed50f5a8b1672572674ec5` | `02338ce337de0a115d6942962ce360427080db8d` | `02338ce337de0a115d6942962ce360427080db8d` | MATCH |

Exact source identity holds. The review is not invalid on identity grounds.

### Independence statement

- I am lineage-disjoint from the program lead (`OPENAI_CHATGPT_TFP_PROGRAM_LEAD_LINEAGE`), from Reviewer A (`ANTHROPIC_CLAUDE_SESSION_session_012EWsCBUVctdyhhk3v5ZxuF`), and from any Reviewer C or strict-auditor session. The four Governance §3 actor-lineage conditions are not met: this is not a continuation or fork, I am not a co-subagent, I did not receive Reviewer A's reasoning, and I share no persistent memory.
- **Shared-training-prior limitation.** Reviewer A was `claude-sonnet-5-5` from the same provider (Anthropic). Under Governance §3, two clean sessions can be procedurally distinct, but shared training priors remain a disclosed limitation, not proof of independence.
- I did not search the web, did not consult external resurrection literature, and did not adjudicate any evidence.

---

## 2. DISPOSITION

**`G0_REVIEW_REPAIR_REQUIRED`**

Finding counts: 2 `G0_BLOCKER`, 9 `G0_MAJOR`, 6 `G0_MINOR`, and several `NOTE`s.

---

## 3. EXECUTIVE FINDING

The 0.1.1 design is sound in its overall control architecture:

- it uses the correct pinned protocol identity;
- it has one active truth question with a four-part conjunctive threshold;
- it explicitly bars "minimal facts" or consensus from serving as evidence;
- it bars free-form late candidates;
- it bars hidden fraud inside C-HET;
- it bars inference from "weaker rival" to "stronger candidate";
- its A14 insufficiency text is broadly the right shape.

Most of the required attacks are at least partially blocked by explicit text.

The design is **not yet certifiable**. The gaps are concrete and repairable:

1. **The necessary-proposition coverage map cannot be certified under Protocol A6 as written (BLOCKER).**
   - Several candidates' necessary propositions are not enumerated. P-CRUC per candidate, P-EARLY-PROCLAMATION, P-DEATH for L/F/C-HET, the S1–S3 origin links, the C-HET module propositions, and the R-PHYS/R-TRANS specific propositions are all missing.
   - Several entries carry two coverage modes ("X plus comparison").
   - Some COMPARATIVE_ROUTE entries have no CRITICAL discriminator.
   - The dual-mode labels can be exploited directly. They let an analyst choose after evidence exposure whether `PARTIALLY_SUPPORTED` blocks ranking (A12 table).

2. **"Embodied living postmortem state" has only a negative definition (BLOCKER).** Nothing operationally separates R-TRANS from V. As a result V-type outcomes can be absorbed into a positive R_EVENT, and Q1 is not operational at its most important internal boundary.

3. **The Q1 threshold and the founding-stratum definition contain movable parts (MAJOR).** These are:
   - undefined and asymmetric causal-role terms: "materially caused", "materially contributed", "primarily", "sufficient to account for";
   - an undefined "pre-Pauline";
   - a Paul restriction applied to R only;
   - an existential "at least one stream" quantifier with no same-stream comparison rule;
   - no frozen rule for identifying the founding proclamation stratum;
   - no table mapping study outcomes to the Q1 answer.

4. **The A14 insufficiency threshold leaves one open route between INSUFFICIENT_SIGNAL and weak or neutral evidence (MAJOR).** Protocol A11 defines UNMAKEABLE to include a search "completed without sufficient signal". The study must close that path, and must decide in advance how bounded dating/provenance uncertainty and non-extant evidence are classified.

5. **C-HET, the umbrella families, the source plan, the pre-G0 exposure ledger, and empirical backgrounds each need bounded repairs (MAJOR).**

These defects are repairable before evidence exposure as `PRE_EVIDENCE_AMENDMENT`s. None requires substantive evidence acquisition to fix.

---

## 4. NECESSARY-PROPOSITION ARCHITECTURE

### 4.1 Candidate-by-candidate specification check

| Candidate | Necessary propositions named | Specified enough for a non-gamed map? | Defects |
|---|---|---|---|
| R (umbrella) | P-DEATH, P-R-BODY, P-R-FOUNDING-ENCOUNTER, P-R-CAUSAL | **No** | P-HIST-JESUS, P-CRUC, and P-EARLY-PROCLAMATION are not listed against R although the A5 chain runs through them. The R-PHYS and R-TRANS specific propositions are deferred to packets that do not exist. The umbrella is not declared status-bearing versus its submodels (see 4.3). |
| R-PHYS | "own necessary body/tomb consequences where specified by its steelman packet" | **No** | No proposition IDs and no route mode. "Cannot be demoted" is asserted but there is nothing yet to demote. |
| R-TRANS | "transformed-body consequence" | **No** | No IDs. The route mode is not stated. There is no positive embodiment criterion separating it from V (BLOCKER B-2). |
| V | P-DEATH, P-V-REAL-REFERENT, P-V-NONEMBODIED, P-V-FOUNDING-CAUSAL | Partly | Missing referent **identity** (the referent was Jesus rather than another extramental agent or content). R carries identity inside P-R-BODY ("Jesus subsequently existed"); V should carry it too, for symmetry. Theistic and non-theistic submodels are not frozen as status-bearing or as one conjunctive candidate. |
| H | P-DEATH, P-H-EXPERIENCES, P-H-NONVERIDICAL, P-H-MECHANISM-SUFFICIENT, P-H-FOUNDING-CAUSAL | Partly | Individual and collective variants are to be "separately specified where they differ materially". Until then, H can switch between them after exposure. |
| L | P-L-INTERPRETIVE-ORIGIN, P-L-EXPERIENCE-NONPRIMARY, P-L-DEVELOPMENT-SEQUENCE, P-L-FOUNDING-CAUSAL | **No** | **P-DEATH is missing**, although D1 treats L as death-requiring. There is no proposition for **how the secondary encounter claims arose**. Without one, L can silently borrow H's experiential mechanism or F's invention mechanism to explain encounter reports while claiming neither burden. The body-disposal/non-burial variant is still "may include" and must be decided now. |
| S1 | "survival/non-death" | **No** | Only the non-death half is mapped. S1's own core also requires that encounters with the surviving Jesus materially generated the proclamation. That origin-link proposition has no ID or route. |
| S2 | "substitution/misidentification" | **No** | "Later events/beliefs produced the resurrection proclamation" is not a specified mechanism. It needs its own origin proposition. Its relation to P-CRUC (attribution of the crucifixion to Jesus) must be explicit. |
| S3 | "divine rescue/non-death" | **No** | Needs IDs for non-death, the nonordinary-rescue process (which carries the Phase I trigger symmetrically with R), and the origin link. Whether S3 affirms P-CRUC must be stated. |
| F | P-F-DELIBERATE, P-F-ORIGIN-MATERIAL, P-F-MOTIVE-OPPORTUNITY-ROUTE, P-F-TRANSMISSION-SUFFICIENT | Partly | **P-DEATH is missing**, although D1 treats F as death-requiring. If F has a non-death variant, it must be declared and burdened. |
| C-HET | "module sufficiency", "frozen map adequacy" | **No** | No proposition IDs at all. See §6. **P-DEATH is missing**, although D1 treats C-HET as death-requiring. |

### 4.2 Missing, overbroad, or misclassified propositions

1. **P-EARLY-PROCLAMATION is defined in A5 but absent from the A6 map.**
   - Every candidate's causal proposition takes "the founding proclamation" as its explanandum. If no recoverable founding proclamation exists, every *-FOUNDING-CAUSAL proposition lacks an object.
   - It is a natural SHARED_FLOOR candidate **only if** its truth conditions are content-neutral across candidates.
   - That is not currently true. The stratum is defined as a "resurrection/exaltation proclamation", while A1 item 4 and P-R-CAUSAL refer to the "founding **resurrection** proclamation". Whether the earliest proclamation is resurrection-shaped or exaltation-shaped is itself discriminating between R and L, and is BGD-7-sensitive.
   - **Repair:** split into
     - (a) `P-EARLY-PROCLAMATION-EXISTENCE` (content-neutral; SHARED_FLOOR if necessary for all), and
     - (b) `P-PROCLAMATION-CONTENT` (candidate-specific: what each candidate requires the founding proclamation to have said).
   - Each must then receive exactly one route.

2. **P-CRUC is not assigned to any candidate's necessary list.** Its route is written as "COMPARATIVE_ROUTE / candidate-specific where S2/S3 differ", which is two modes. No discriminator in A11 lists P-CRUC as served, so it has no CRITICAL coverage.
   - P-DEATH ("died from/around the crucifixion event") presupposes the crucifixion event in its truth conditions. P-DEATH therefore cannot be cleanly evaluated while P-CRUC's per-candidate status is undefined.

3. **P-DEATH must be explicitly listed as necessary for L, F, and C-HET**, or explicitly declared non-necessary with a frozen B4-style rationale. D1 already assumes they require it.

4. **Proposition-level identity for V** (see 4.1).

5. **Origin-link propositions for S1, S2, and S3** (see 4.1).

6. **An L encounter-claim-origin proposition.** This closes the route by which H collapses into L (§11, attack 6).

7. **Q1-conjunction integrity.** P-R-FOUNDING-ENCOUNTER entails P-R-BODY: it is an encounter "with that embodied living Jesus". The map must state that P-R-FOUNDING-ENCOUNTER is established only by evidence bearing on the **founding stream's referent**. It cannot be established by conjoining P-R-BODY (supported from any source, including later tomb or narrative layers) with "an encounter occurred". D3's first `FAVORS_R` bullet gestures at this, but the necessary-proposition map itself must encode it, because D12 is satisfied by four dispositions alone (§7).

### 4.3 Umbrella structures that remain too flexible

**R.** A1 defines R_EVENT at umbrella level. Only S1–S3 are declared "separately status-bearing". As a result:

- if an R-PHYS tomb/body proposition fails, R's A12 status is unaffected, because that proposition is not necessary for the umbrella;
- the sentence "the umbrella R family may not discard a vulnerable submodel-specific proposition merely to preserve eligibility" has no mechanism to enforce it;
- R-TRANS is "not forced to inherit every R-PHYS tomb proposition", but nothing stops it from **using** tomb/body evidence as positive support for P-R-BODY. That takes R-PHYS's benefit without its burden.

**H.** Individual and collective variants are not separated.

**V.** Theistic and non-theistic forms are not separated. Each must "keep its own metaphysical burdens", but they are not status-bearing.

**Repair (G0_MAJOR M-2):**

- Declare R-PHYS and R-TRANS as separately status-bearing submodels with their own necessary-proposition sets. Do the same for H-IND/H-SOC and V-variants where they differ on any necessary proposition, or freeze each family as a single conjunctive candidate.
- State that R_EVENT is answered by whichever R submodel(s) meet the Q1 table (§7). Each submodel's status is recorded separately and cannot be absorbed into the umbrella.
- **Evidence-binding rule:** a submodel may cite an evidence class as positive support only if its frozen packet registers the corresponding expectation. Registering an expectation makes its failure weakening evidence for that submodel.

### 4.4 Demotion control

Protocol A6 and the prereg ("no candidate may lower its burden by shifting a vulnerable necessary proposition into a supporting/contextual category after evidence exposure") block **post-exposure** demotion. Pre-G0 demotion is the live risk, because the missing enumerations will be written during finalization. The equal-necessity test (A6: "comparable rivals face comparable necessity criteria") must therefore be applied by the coverage-map reviewer to the **repaired** map, not this one.

---

## 5. COVERAGE-ROUTE ARCHITECTURE

### 5.1 Entry-by-entry A6 check

Discriminators in the right-hand column are the program lead's proposed tiers. Final tiering belongs to Reviewer C.

| Entry | Stated route | A6 defect |
|---|---|---|
| P-HIST-JESUS | NONCOMPARATIVE_SHARED_FLOOR | Valid in form **only after** a frozen B4 exclusion of the non-historicity rival (A6 classifies against the G0 admitted set). See G0_MINOR m-4. |
| P-CRUC | "COMPARATIVE_ROUTE / candidate-specific" | **Two modes. No CRITICAL discriminator serves it.** |
| P-DEATH | COMPARATIVE | OK (D1). |
| P-R-BODY | COMPARATIVE | OK (D3). |
| P-R-FOUNDING-ENCOUNTER | COMPARATIVE | OK (D3, D2), subject to 4.2 item 7. |
| P-R-CAUSAL | COMPARATIVE | OK (D2, D5), subject to the causal vocabulary in §7. |
| R-PHYS tomb/body | "candidate-specific route" | **Mode not stated.** If COMPARATIVE, its discriminators (D7 "MATERIAL or CRITICAL"; D10 "reviewer-determined") may be tiered MATERIAL, which would leave a necessary proposition MATERIAL-only. |
| R-TRANS transformed body | "textual/interpretive/metaphysical burden" | **Mode not stated.** |
| P-V-REAL-REFERENT, P-V-NONEMBODIED, P-V-FOUNDING-CAUSAL | COMPARATIVE | OK in form (D4, D3, D2/D5). |
| P-H-EXPERIENCES | COMPARATIVE ("historical/experiential route") | **No identified CRITICAL discriminator decides whether the experiences occurred.** D4 decides veridicality, not occurrence. D5 decides primacy. Either assign a CRITICAL discriminator or move to NONCOMPARATIVE with an explicit direct route. |
| P-H-NONVERIDICAL, P-H-FOUNDING-CAUSAL | COMPARATIVE | OK in form. |
| P-H-MECHANISM-SUFFICIENT | "NONCOMPARATIVE_CANDIDATE_SPECIFIC plus comparison" | **Two modes.** |
| P-L-INTERPRETIVE-ORIGIN, P-L-EXPERIENCE-NONPRIMARY, P-L-FOUNDING-CAUSAL | COMPARATIVE | OK in form (D5, D2). |
| P-L-DEVELOPMENT-SEQUENCE | "NONCOMPARATIVE plus comparison" | **Two modes.** |
| S1 | COMPARATIVE | Covers non-death only (D1). The origin link is unmapped. |
| S2 | "NONCOMPARATIVE plus comparison" | **Two modes.** D1 says S2 needs "its own candidate-specific direction rule", but none exists. |
| S3 | "NONCOMPARATIVE plus Phase I comparison" | **Two modes.** Same missing rule. |
| P-F-DELIBERATE | NONCOMPARATIVE | Valid mode. The direct route is a label only ("direct historical/psychological burden"). |
| P-F-ORIGIN-MATERIAL | COMPARATIVE | No clearly serving CRITICAL discriminator. D6 decides deliberateness, not origin-materiality. D2 is only "relevant to F". |
| P-F-MOTIVE-OPPORTUNITY-ROUTE | COMPARATIVE | **No discriminator addresses motive or opportunity.** |
| P-F-TRANSMISSION-SUFFICIENT | COMPARATIVE | The only plausible discriminator is D8, which is **MATERIAL**. A MATERIAL discriminator can never be sole coverage (A11). |
| C-HET module sufficiency | "NONCOMPARATIVE per module plus comparisons" | **Two modes.** No proposition IDs. |
| C-HET map adequacy | NONCOMPARATIVE | A process constraint, not a truth-bearing proposition. It belongs in the D9 / C4 control layer, not the coverage map. |

### 5.2 Why the dual-mode entries are exploitable (BLOCKER B-1 core)

Under the protocol A12 disposition table:

- `PARTIALLY_SUPPORTED_WITHIN_SCOPE` **does not block ranking** on a COMPARATIVE_ROUTE;
- on a NONCOMPARATIVE_CANDIDATE_SPECIFIC route, **only SUPPORTED** permits ranking eligibility.

An entry labelled "NONCOMPARATIVE plus comparison" therefore lets the analyst decide **after** seeing a PARTIALLY_SUPPORTED disposition whether that disposition blocks the candidate. This is a direct status-manipulation route (prompt §4 item 10). Each such entry must be resolved to exactly one mode before G0. Where a direct route **and** a comparison both genuinely bear on the proposition, the fix is to:

- choose the single governing mode;
- list the other as supplementary evidence that cannot change the mode-governed A12 consequence; or
- split the proposition into two separately routed facets (protocol L1).

### 5.3 Asymmetric route burdens (G0_MAJOR M-1)

R and V's core truth-bearing propositions (P-R-BODY, P-R-FOUNDING-ENCOUNTER, P-V-REAL-REFERENT, P-V-NONEMBODIED) are all COMPARATIVE, so `PARTIALLY_SUPPORTED` leaves them ranking-eligible. The rivals' core mechanism propositions are NONCOMPARATIVE or dual-mode leaning NONCOMPARATIVE: P-H-MECHANISM-SUFFICIENT, P-L-DEVELOPMENT-SEQUENCE, P-F-DELIBERATE, S2, S3, and C-HET modules. Those rivals need full SUPPORTED to stay ranking-eligible. The R-PHYS and R-TRANS specific burdens have **no stated mode**.

There may be a principled reason for some of these assignments. Protocol A6 permits NONCOMPARATIVE where "pairwise comparison would distort the proposition". None is stated, however, and the pattern as written makes ranking eligibility easier for R/V than for H/L/F/S2/S3/C-HET. Protocol A6 requires "no candidate's burden is reduced by asymmetric route assignment".

**Repair:**

- Freeze a written **mode-assignment principle** applied uniformly. One example: "a candidate's core mechanism/ontology proposition receives NONCOMPARATIVE_CANDIDATE_SPECIFIC when it requires direct warrant that no pairwise comparison supplies; otherwise COMPARATIVE".
- Apply it to every candidate's analogous propositions, including R-PHYS/R-TRANS ontology and the Phase I admissibility facet of P-R-BODY and S3.
- Record a one-line distortion rationale for every NONCOMPARATIVE entry.

I do not prescribe which direction the symmetry should go. I require that it be symmetric and stated.

### 5.4 Missing A6 / 23A fields

None of the map entries yet carries:

- `necessary_test_rationale`;
- comparator/discriminator IDs;
- an explicit direct route for NONCOMPARATIVE entries (evidence classes plus the applicable Phase G sufficiency elements);
- expected evidence;
- weakening evidence;
- lanes;
- coverage certification.

Labels such as "direct historical/psychological burden" are not routes. The prereg acknowledges the map is "initial". This is part of B-1.

### 5.5 Flags for Reviewer C (not decided here)

- Final tiers of D7, D8, D10, and any discriminator newly required for P-CRUC, P-H-EXPERIENCES, P-F-ORIGIN-MATERIAL, P-F-MOTIVE-OPPORTUNITY-ROUTE, and P-F-TRANSMISSION-SUFFICIENT.
- The S2 and S3 direction rules required by D1's own text.
- `FEASIBLE_WITHIN_SCOPE` / `INFEASIBLE_WITHIN_SCOPE` statuses for every CRITICAL discriminator. These are required by A11 before G0 closes and do not yet exist. They bear directly on A14 (§8).

---

## 6. C-HET ANTI-TAILORING CONTROL

### 6.1 What is already sound

- The five frozen module classes.
- The "exactly one primary module" requirement.
- The bar on adding, deleting, or reassigning modules after exposure except through C4.
- Fabrication is excluded as a hidden module.
- D9 requires independent warrant per module and no post-exposure module.
- D5 bars "mixed result therefore C-HET".
- A13 includes "single-process rival explains same pattern" as a weakening condition.

These block the crude form of post-exposure module **reassignment**.

### 6.2 Why it is not yet sufficient

**Overlap.** "Exactly one *primary* module" leaves secondary and contributory assignments unbounded. "Explicitly permitted module interactions" is an open category. With five modules allowed to co-contribute to any proposition, nearly every evidence pattern fits. The "overlapping modules" attack succeeds as written.

**Evidence-class taxonomy not frozen.** The requirement is to map "each necessary proposition/evidence class" to one module. If the evidence-class partition is drawn after exposure, the mapping can be tailored without formally reassigning any module.

**Module necessity undeclared.** It is not stated whether all five modules are necessary. If any are optional, an optional module can in effect be "switched off" after exposure without a C4 event.

**No stratum assignment.** It is not stated which modules operate at the **founding** stratum and which only at later layers (e.g., M-NARR). Without this, C-HET can relocate a mechanism in time.

**No falsifiable pattern prediction.** D9 requires that "the predicted heterogeneous pattern is supported", but no pattern is predicted. C-HET has no frozen contradiction condition beyond module failure.

**Non-subsumption undemonstrated.** B1(4) requires that a candidate not be subsumed by another. Nothing yet shows what C-HET predicts that the union of H and L (with M-BODY) does not.

**Q1 truth conditions.** It is not stated that C-HET entails the negation of P-R-BODY / P-V-REAL-REFERENT, i.e., that every module is non-veridical. If any module could carry a veridical referent, C-HET overlaps V or R.

### 6.3 Minimum additional pre-G0 map fields (G0_MAJOR M-6)

For each module `M-*`:

1. `module_id`, plus **proposition IDs** (e.g., `P-CHET-EXP-IND-OCCURRED`, `P-CHET-EXP-IND-FOUNDING-ROLE`).
2. `necessity`: NECESSARY or OPTIONAL. Optional modules are disallowed unless a frozen rule states the exact pre-registered condition under which the module is inactive, and that inactivity cannot raise C-HET's status.
3. `stratum_of_operation`: FOUNDING / TRANSMISSION / LATER_NARRATIVE.
4. `causal_role` on the frozen causal-role ladder (§7.3), e.g., PRIMARY / CONTRIBUTING / NONE, for the founding proclamation.
5. `primary_evidence_classes`, drawn from a **frozen evidence-class taxonomy** shared by all candidates. Each class has exactly one primary module, and **secondary assignments are a closed, enumerated list**.
6. `permitted_interactions`: a closed list of module pairs, each stating the specific joint prediction. No unlisted interaction may be invoked.
7. `independent_warrant_route`: the evidence/argument class that warrants the mechanism **independently of the resurrection evidence it is used to explain**, plus the applicable Phase G template, e.g., psychological/sociological explanatory.
8. `weakening_and_contradiction_conditions`.

For C-HET as a whole:

9. `predicted_pattern`: the specific heterogeneous configuration of evidence across strata that C-HET predicts.
10. `contradiction_pattern`: what single-process configuration would contradict it.
11. `non_subsumption_statement` against H, L, and H+L.
12. `q1_entailment`: the explicit statement that C-HET denies P-R-BODY and P-V-REAL-REFERENT.

---

## 7. Q1 EVENT THRESHOLD

### 7.1 Assessment against the four review criteria

| Criterion | Finding |
|---|---|
| **Noncircular** | Largely yes. The four conditions are distinct propositions, and Phase I separates report → transmission → core → ontology → causal sequence. One residual circularity route: P-R-FOUNDING-ENCOUNTER can be read as satisfied by conjoining a P-R-BODY drawn from non-founding evidence with any founding encounter. The repair is in 4.2 item 7. |
| **Sufficiently operational** | **No**, in four places: (a) "embodied" has only a negative definition (B-2); (b) causal-role terms are undefined; (c) "pre-Pauline" is undefined; (d) "supported at the required route threshold" (A1) vs "supported" (D12) is ambiguous between `SUPPORTED_WITHIN_SCOPE` and "ranking-non-blocking on a COMPARATIVE route", which would admit PARTIALLY_SUPPORTED. |
| **Protected against post-evidence redefinition** | Partly. C4 governs frozen elements, but the founding-stratum identification rule, the stream-identification rule, and the Q1 answer mapping are not yet frozen, so they can be filled in after exposure without formally amending anything. |
| **Appropriately strict about the pre-Pauline founding stream** | Strict for R on the direct route ("Paul alone cannot satisfy"). **Not symmetric**, and **not closed on the indirect route** (below). |

### 7.2 Embodiment boundary (G0_BLOCKER B-2)

"Embodied living postmortem state" is defined only as "stronger than dream, bereavement vision, purely internal religious experience, literary symbol, memory construction, non-veridical apparition, or survival without death". Those exclusions separate R from H, L, and S1. They do **not** separate R-TRANS ("transformed/pneumatic embodiment") from V ("a non-embodied or non-worldly mode"). A veridical extramental encounter that is not a dream, not internal, and not non-veridical satisfies the negative definition whether or not it is embodied.

**Consequence:** a V-type result can be recorded as R-TRANS, making R_EVENT positive. Protocol F says a non-operationalized question fails G0. This is that defect, at the one internal boundary that decides Q1.

**Repair:** freeze a **positive** operational criterion, or a short conjunctive set of criteria, for "embodied" that:

- is stated in candidate-neutral ontological terms, not in terms of any source's vocabulary;
- R-PHYS and R-TRANS both satisfy, and V by definition does not;
- comes with a frozen statement of which evidence classes can bear on each criterion.

Candidate criteria might concern public/intersubjective perceptibility, spatiotemporal location, causal interaction with ordinary physical objects, or a relation to the pre-mortem body. **Choosing among them is the program lead's and candidate packets' job, not mine.** I am not supplying content.

BGD-8 (Pauline-body interpretation) must then be tied to this criterion. A Pauline-body reading may decide what a text **claims**. It cannot decide whether the criterion was **met**.

### 7.3 Causal-role vocabulary (part of G0_MAJOR M-3)

The candidates use incommensurable causal thresholds:

| Candidate | Causal wording |
|---|---|
| R | "materially caused or generated" |
| V | "materially contributed" |
| H | "sufficient to account for" |
| L | "primarily", plus experience "non-primary" |
| F | "can account for" |

As written, R ("material cause") and L ("primary interpretive origin, experience non-primary") can both be SUPPORTED at once, because an experience can be a material yet non-primary cause. Equally, a weak reading of "material" can let R pass on a contributing-cause showing that would not suffice for H.

**Repair:** freeze one ladder used by every candidate. For example:

- `NECESSARY_CONTRIBUTING` (but-for within scope);
- `PRIMARY` (the largest contributor under a frozen comparison rule);
- `SUFFICIENT`;
- `CONTRIBUTING`;
- `NONE`.

Restate every *-FOUNDING-CAUSAL proposition and P-L-EXPERIENCE-NONPRIMARY on that ladder. Pair-specific D2/D5 wording then belongs to Reviewer C.

### 7.4 "Pre-Pauline" and the Paul restriction (part of M-3)

**Define "pre-Pauline".** It could mean chronologically before Paul's own claimed experience, before Paul's letters, or tradition that Paul received rather than composed. Each choice changes which material can satisfy item 3.

**Separate three Paul-related evidence uses:**

- (a) Paul's first-person experience;
- (b) Paul's transmission of tradition about others' encounters;
- (c) Paul's own interpretive or theological categories, e.g., body vocabulary.

Only (b) can bear on the founding stream directly. (c) may not supply the **ontological content** of the founding stream without a transmission argument (E5).

**Make the restriction symmetric.** As written, "Paul's later first-person experience … cannot by itself satisfy items 3 or 4" constrains R only. The mirror projection is equally invalid: characterising Paul's experience as visionary, subjective, or non-embodied and generalising that to the founding stream for H or V. The rule should read: *Paul's first-person experience cannot by itself establish the ontological character (embodied / non-embodied veridical / subjective) or the causal role of the pre-Pauline founding encounter stream for any candidate.*

### 7.5 Stream identification and the existential quantifier (part of M-3)

"At least one pre-Pauline founding encounter stream" is existential, and streams are not identified in advance. This lets the analysis pick, after exposure, whichever stream best supports R, while H, V, or L are evaluated on a different stream. A named-episode list is **not** required at G0. It would also risk importing source-specific factual assumptions, which the prompt forbids. Instead, freeze:

1. a **stream-identification rule** in generic terms: what makes a claimed-encounter tradition a distinct "stream", how dependence collapses streams (D8), and what places a stream in the founding stratum;
2. a **same-stream comparison rule**: every candidate's founding-encounter and founding-causal propositions are evaluated against the **same inventoried set of streams**;
3. a **stream-inventory freeze point**: the inventory is fixed and ledgered after G1 source inventory but **before** any direction rule is applied, and any later change is a C4 amendment;
4. a **split-result rule**: if the evidence supports one stream as R-type and another as H-type, what the outcome is. This is plausibly a C-HET or REVISED_CANDIDATE_REQUIRED routing, but it must be decided now. Otherwise R_EVENT ("at least one") can be declared positive while a rival is credited with the rest of the origin.

### 7.6 Q1 answer table (part of M-3)

There is no frozen mapping from protocol outcomes to the answer to Q1. A1 asks whether evidence *warrants* R_EVENT. D12 says R_EVENT "may be positive only if" all four are "supported". N3 produces base outcomes (BEST_SUPPORTED, ONLY_RANKING_ELIGIBLE, …) and an optional TRUTH_WARRANTED refinement.

Is a "positive" Q1 answer R BEST_SUPPORTED, or does it require TRUTH_WARRANTED? What are the negative and neutral Q1 answers? Without a frozen table, the same G3 state can be reported as different Q1 answers after exposure. **Repair:** freeze a table with these columns:

- the four D12 propositions' dispositions;
- each R submodel's A12 status;
- the N3 base outcome and refinements;
- the resulting Q1 answer value.

Example Q1 answer values: `R_EVENT_TRUTH_WARRANTED`, `R_EVENT_BEST_SUPPORTED_NOT_TRUTH_WARRANTED`, `R_EVENT_NOT_WARRANTED`, `R_EVENT_EVIDENCE_AGAINST`, `UNDERDETERMINED`, `INSUFFICIENT_SIGNAL`. Fix also whether "supported" in D12 means `SUPPORTED_WITHIN_SCOPE`. I recommend it should, for a positive answer, consistent with the protocol's single-proposition rule and TRUTH_WARRANTED condition 4.

---

## 8. INSUFFICIENT-SIGNAL THRESHOLD

### 8.1 What A14 now does well

The trigger is restricted to access, provenance, or coverage failure that prevents a required rule from being applied **at all**, after documented effort. There is an explicit list of non-qualifying cases: weak, not established, neutral, rivals live, and nondiscriminating. D12 is explicit that an adequately covered failure is not ISS. On its face, this distinguishes:

- true access failure → ISS;
- weak evidence → NOT_ESTABLISHED / PARTIALLY_SUPPORTED;
- neutral evidence → NEUTRAL_OR_NONDISCRIMINATING;
- underdetermination → UNDERDETERMINED.

### 8.2 Constructed cases where the analyst can still choose (G0_MAJOR M-5)

**Case 1 — UNMAKEABLE laundering.** Protocol A11 defines UNMAKEABLE to include "the frozen search has been completed without sufficient signal". A14 lists "a CRITICAL comparison cannot reach MAKEABLE" as an ISS trigger. Suppose an analyst runs a complete search, all strata are accessible with adequate provenance, and the comparison evidence is weak.

- They can call it NEUTRAL_OR_NONDISCRIMINATING, which leads to UNDERDETERMINED or MATERIAL-stage resolution.
- Or they can call it "completed without sufficient signal" → UNMAKEABLE → ISS.

Both labels are textually available. **Repair:** state that, for TFP-STRESS-2, "completed without sufficient signal" qualifies as UNMAKEABLE **only** when the shortfall is attributable to inaccessibility, provenance failure, or non-extant material in a **pre-designated** truth-critical stratum. Accessible, provenance-adequate, weak or neutral evidence is NEUTRAL_OR_NONDISCRIMINATING by definition.

**Case 2 — provenance failure vs bounded uncertainty.** Ancient sources routinely carry dating, authorship, and dependence uncertainty. An analyst can call a disputed date "provenance failure makes a CRITICAL evidence class uninterpretable" (ISS), or "weak evidence" (NOT_ESTABLISHED), or a BGD-4 variant (sensitivity → possible FRAMEWORK_DEPENDENCE). **Repair:** freeze the rule that:

- **provenance failure** means the item cannot be identified well enough to apply a Phase G mandatory element at all;
- **uncertainty that can be bounded** (a date range, competing dependence models) is propagated through BGD-4 sensitivity variants and disposition confidence, and is never ISS.

**Case 3 — non-extant evidence.** Suppose the evidence that would decide a facet (for example, the content of an early experience report) simply does not survive, and search is complete. This could be ISS (`MISSING_CRITICAL_EVIDENCE`), A12 prerequisite-4 failure, or NOT_ESTABLISHED/UNDERDETERMINED under complete coverage. **Repair:** decide now.

- My recommendation: under complete coverage, non-survival of a class that the frozen plan did not designate as **expected-extant** yields the proposition-level disposition (NOT_ESTABLISHED, PLAUSIBLE_BUT_UNATTESTED, or UNDERDETERMINED), not ISS.
- `MISSING_CRITICAL_EVIDENCE` is reserved for classes pre-designated as expected-extant whose absence is unexplained.
- E2's "expected-but-absent evidence where absence is probative" is applied symmetrically.

**Case 4 — "No adequate substitute" and "likely to change".** A14 example 1 turns on "no adequate substitute exists". MATERIALLY_COMPLETE turns on gaps "not likely to change" the disposition. Both are judged after the accessible evidence is seen, so either can be tuned. **Repair:**

- At source-plan freeze, record for each necessary proposition its **truth-critical strata** and their **acceptable substitutes**.
- ISS for that proposition is permitted only if a pre-designated truth-critical stratum fails and none of its pre-designated substitutes is available.
- Gap materiality is assessed against that prospective designation, not ad hoc.

**Case 5 — strategic non-search.** Protocol: "unperformed search is … COVERAGE_INCOMPLETE". A14 should add that COVERAGE_INCOMPLETE caused by unperformed search **cannot close as ISS**. The study remains open, or closes with an explicit "not adjudicated — coverage incomplete" record that is distinct from ISS.

**Case 6 — infeasibility after the fact.** A11 allows a known-infeasible CRITICAL discriminator only where the prereg states ISS is the intended consequence. No feasibility statuses exist yet (flagged to Reviewer C in §5.5). Until they do, an analyst can declare infeasibility post hoc. A14 must state that a CRITICAL discriminator not marked INFEASIBLE at G0 cannot later produce ISS through infeasibility alone. It must go through a COMPARISON_EFFORT_RECORD under the Case 1 rule.

The reverse attack is calling genuine missing critical access merely NOT_ESTABLISHED. It is blocked by the same prospective designation (Case 4). If a pre-designated truth-critical stratum is genuinely inaccessible, NOT_ESTABLISHED is impermissible for the dependent proposition, and the ISS subtype must be recorded.

---

## 9. SOURCE-PLAN ARCHITECTURE

**Scope note.** Under A9.1, the source-plan reviewer should elicit missing strata *before* seeing the draft plan, where feasible. That was infeasible here: the prompt supplies the preregistration, which contains the draft strata. This review is therefore a **non-blind architecture review**. The actual SOURCE_PLAN (repositories, search routes, 23A fields) does not exist yet, so `SOURCE_PLAN_PASS` cannot be issued now. A further source-plan review of the concrete plan is required.

### 9.1 Coverage of required dimensions

| Dimension | Covered by | Assessment |
|---|---|---|
| Provenance | SRC-7 textual criticism; E1 | Adequate in architecture. |
| Source dependence | SRC-2; selection rules; D8 | Adequate in architecture. |
| Candidate-native evidence | SRC-10 (generic "proponent scholarship") | **Asymmetric gap.** See 9.2. |
| Adverse evidence | SRC-11 | Adequate in form. It needs a per-candidate service map. |
| Later-source controls | A2 scope; E5; selection rules | Adequate. |
| Psychology/social-science mechanisms | SRC-8 | Individual cognition is covered. **Sociology of religious movements and reference-class evidence are missing** (BGD-10 has no stratum). |
| Philosophy/metaphysics | SRC-9 | Testimony, inference, and miracle reasoning are covered. **Metaphysics of embodiment, personal identity, and postmortem survival is missing.** This is the very evidence class needed for R-TRANS, V, and the B-2 criterion. |

### 9.2 Missing or asymmetric strata (G0_MAJOR M-7)

These are stated as evidence **classes**, not literature titles.

1. **Second Temple Jewish and scriptural-interpretive texts** on resurrection, exaltation, vindication, and afterlife concepts, and the scriptural material used in early interpretive reasoning. This is L's primary candidate-native evidence class and the evidence base for BGD-7. SRC-4 is restricted to crucifixion, death, movement existence, and context, so it does not cover this.
2. **Greco-Roman comparanda**: apotheosis, translation, apparition, vanishing-body, and postmortem-appearance narratives and beliefs. These bear on L, V, H, and the reading of embodiment language. Their absence leaves those candidates without native or adverse comparanda.
3. **A reference-class / comparative-movement stratum**: historical and social-scientific studies of movements after a founder's death, failed expectation, and similar cases. BGD-10 requires reference classes to be stated and sensitivity-tested, but there is no stratum to supply them.
4. **Postmortem-survival / apparition research literature**, together with its critical literature. This is a native and adverse class for V, especially non-theistic V, symmetric with SRC-8's treatment of H. Including it endorses nothing.
5. **Metaphysics of embodiment, personal identity, and survival** (see 9.1).
6. **A distinction between formulation sources and evidence sources.** Some candidates (S2, S3, F, and possibly V or L variants) have their strongest **formulations** in material later than the 150 CE evidence window, or in polemical or tradition-specific sources. The plan must give each candidate access to its native formulation for steelman purposes (B3) without treating that material as early evidence (E5).
7. **A stratum-to-candidate/background service map.** Template 23A requires `candidate_or_background_served` for every stratum. Symmetry can only be checked once every admitted candidate and every admitted background has at least one native and one adverse stratum mapped to it.
8. **Per-proposition truth-critical designation and substitutes.** These are required by §8 Case 4.

### 9.3 Hidden source-selection asymmetry

- **SRC-4 note (G0_MINOR m-2).** "Absence of direct resurrection attestation is not automatically treated as disproof" is a one-sided protective clause. The symmetric rule already exists in protocol E2 ("expected-but-absent evidence where absence is probative"). Replace the clause with a symmetric statement: absence is evaluated under E2 for every candidate, and neither presence nor absence of attestation is automatically probative for any candidate.
- **SRC-10 / SRC-11** are symmetric in wording but generic. Without the service map (9.2 item 7), candidate-native access cannot be verified as equal.
- **Stratum dropping.** After exposure, narrowing is presumptively FAVORABLE_OR_MIXED (C4), which is a strong block. **Before G0**, dropping a stratum during plan finalization is not ledgered (M-8).

### 9.4 Label collision (G0_MINOR m-1)

Source strata are labelled "S1"–"S12", which collides with candidate submodels S1–S3. A future dispute about "S1/S2 burdens" or "S2 coverage" could be ambiguous between a candidate and a stratum. Rename the strata, e.g., `SRC-1`…`SRC-12`. This report already uses SRC-n for strata.

---

## 10. ROLE-SEPARATION CHECK

Scope is confined to Reviewer B's separation, per §6.G of the prompt.

| Separation | Status |
|---|---|
| B vs program lead | **Separated.** Different provider and lineage (OpenAI program-lead lineage vs this Anthropic session); no shared context. |
| B vs Reviewer A | **Separated procedurally.** Different session; no access to A's report or reasoning. **Limitation:** same provider and model family (Sonnet vs Opus), so training priors are shared. Second-hand exposure to the program lead's integration summary inside permitted files is disclosed in §1. |
| B vs Reviewer C | **Separated by design.** C is unassigned, and the YAML intends a different provider. The minimum-separation pairs (source plan B / adverse source C; necessary proposition B / discriminator tier C; ledger integrity B / amendment direction C; discriminator tier C / post-evidence direction B) are satisfied. |
| B vs future strict auditor | **Separated by design.** B is barred from strict audit, and the auditor must be disjoint. |

### Defects affecting my own role (G0_MINOR m-5)

1. **Authorship coupling on discriminator content.** My repairs touch the content of D3, D9, and D12: the embodiment criterion, the C-HET pattern fields, and the Q1 table. Protocol A3 requires the discriminator author or tier reviewer to differ from the post-evidence direction-result reviewer, and the YAML assigns B the latter role. If the program lead adopts my repair wording, B becomes a de facto co-author of those rules.
   - **Repair:** the program lead authors the repairs in their own words, and the reconciliation record states which B findings they answer.
   - Alternatively, B recuses from post-evidence direction-result review for any discriminator whose rule text incorporates B-supplied wording.
2. **Self-certification risk.** If the repaired coverage map incorporates B's proposed proposition IDs, B's later `NECESSARY_PROPOSITION_COVERAGE_COMPLETE` certification partly reviews B's own suggestions. Record this coupling as a limitation, or have B confirm only conformance to this report's stated requirements.
3. **Lineage continuity for post-G0 roles.** The YAML assigns B the ledger-integrity, post-evidence direction-result, and confidence roles after G0. This conversation runs in an ephemeral container. A later "Reviewer B" in a **new** session is a different actor lineage under Governance §3. That is acceptable, but it must be recorded as a new assignment with its own provenance, not presumed continuous with this session.
4. **Unassigned role affecting my review.** The P-HIST-JESUS shared-floor classification depends on a final B4 exclusion review of the non-historicity rival, "after comparison". The YAML assigns that final candidate/exclusion review to no one. Reviewer A performed only the pre-comparison elicitation and design review. This affects m-4.

---

## 11. ADVERSARIAL ATTACK RESULTS

| # | Attack | Result | Basis / finding |
|---|---|---|---|
| 1 | Treat P-HIST-JESUS as shared floor while silently excluding a live node-level rival | **Partially blocked** | A B4 record and independent review are required, and the rival is preserved at node level. However, shared-floor validity rests on an exclusion whose final reviewer is unassigned, and "a historical subject corresponding to Jesus" has soft truth conditions. → m-4, m-5(4) |
| 2 | Let S1/S2/S3 share burdens opportunistically | **Partially blocked** | They are status-bearing, and a no-swap rule plus "S2/S3 cannot inherit S1" exist. But S proposition IDs, origin links, and S2/S3 direction rules are absent, so the burdens cannot yet be kept apart. → B-1 |
| 3 | R-PHYS escapes tomb/body consequences by retreating into R-TRANS or the umbrella | **Succeeds; requires repair** | R is not declared submodel status-bearing, Q1 is defined at umbrella level, and the R-PHYS propositions are unenumerated. The anti-discard sentence has no enforcement mechanism. → M-2, B-1 |
| 4 | R-TRANS inherits support from R-PHYS while its own burden is unreviewed | **Succeeds; requires repair** | No evidence-binding rule. → M-2 |
| 5 | V collapses into R, or into H | **Into R: succeeds; requires repair.** **Into H: partially blocked.** | Embodiment has only a negative definition (B-2). For H, D4 separates the burdens, but "extramental referent" warrant criteria are still Reviewer C's rule work. |
| 6 | H collapses into L | **Partially blocked** | D5 exists, but "primary/material" are undefined and L has no proposition for the origin of its encounter claims. → M-3, B-1 |
| 7 | C-HET reassigns modules after exposure | **Partially blocked** | The C4 bar and D9 block formal reassignment. The unfrozen evidence-class taxonomy allows reassignment in effect. → M-6 |
| 8 | C-HET uses overlapping modules so every evidence pattern fits | **Succeeds; requires repair** | Secondary assignments and interactions are open, and there is no predicted or contradiction pattern. → M-6 |
| 9 | F is strengthened merely because another candidate lacks evidence | **Blocked** | A13's closing rule, D6's direct-support requirement, D3's last line, and P-F-DELIBERATE requiring SUPPORTED. This holds provided the M-1 symmetry repair does not weaken F's direct route without the equivalent change elsewhere. |
| 10 | Make a necessary proposition MATERIAL-only | **Partially blocked** | A11 and A6 forbid it. In practice, R-PHYS tomb (D7/D10 tier open) and P-F-TRANSMISSION-SUFFICIENT (D8 MATERIAL) would end up MATERIAL-only. → B-1; tiers flagged to C |
| 11 | Use a NONCOMPARATIVE route without an explicit direct burden | **Partially blocked** | The protocol requires an explicit route, but current entries are labels only. → B-1 |
| 12 | Call weak or neutral evidence INSUFFICIENT_SIGNAL | **Partially blocked** | A14's exclusions are good. The UNMAKEABLE "without sufficient signal" route and the provenance/uncertainty ambiguity remain. → M-5 |
| 13 | Call genuine missing critical access merely NOT_ESTABLISHED | **Partially blocked** | There is no prospective truth-critical stratum designation. → M-5 Case 4 |
| 14 | Let Paul's later first-person experience satisfy the pre-Pauline founding-encounter threshold | **Partially blocked** | The direct route is blocked. Indirect projection via Paul's interpretive categories is open, "pre-Pauline" is undefined, and the restriction is R-only (asymmetric). → M-3 |
| 15 | Let "founding proclamation" move geographically or chronologically after evidence exposure | **Succeeds; requires repair** | Geography-neutrality is deliberate and proper, but the identification rule ("under the frozen source-critical rules") points to rules that are not frozen, and the proclamation content (resurrection vs exaltation) is undecided. → M-4 |
| 16 | Let minimal facts, consensus, canonical status, skeptical status, or prestige substitute for evidence | **Blocked** | A2 source-universe rule, A4's last paragraph, the source-selection rules, Phase I prohibited shortcuts, and A15 items 3–4. |
| 17 | Let the source plan omit a candidate-native or adverse class | **Partially blocked** | SRC-10/11 are generic. L, V, BGD-7, BGD-10, and metaphysics classes are missing, and there is no service map. → M-7 |
| 18 | Let a source stratum be silently dropped | **Partially blocked** | After exposure it is blocked (C4 presumption). During pre-G0 finalization dropping is unledgered. → M-8 |
| 19 | Project a later source backward without a transmission argument | **Blocked** | E5, the A2 later-material rule, D2's third bullet, D3's second bullet, and Phase I "later physical narrative therefore early physical event". Residual: criteria for embedded-tradition identification sit in BGD-3/4 and are sensitivity-tested. NOTE. |
| 20 | Reclassify a historical, linguistic, or psychological proposition as a background to avoid evidential burden | **Partially blocked** | BGD-4/5/6 carry anti-insulation language, but there are no retirement criteria. An empirical "background" variant can be kept alive to manufacture a RANKING_FLIP → FRAMEWORK_DEPENDENCE. → M-9 (joint with C) |
| 21 | Permit G1 evidence acquisition before the source plan, coverage map, role matrix, and exact G0 bundle are frozen | **Partially blocked** | Formal G1 is prohibited in prereg status, YAML gates, and the checklist. But steelman-packet and source-plan construction necessarily expose outcome-relevant material **before** G0, and the ledger activates only "once G0 is authorized". → M-8 |

---

## 12. REQUIRED REPAIRS

All are `PRE_EVIDENCE_AMENDMENT`s. None requires substantive evidence acquisition.

### G0_BLOCKER

**B-1 — Coverage map not certifiable under A6.**
1. Enumerate the necessary propositions, with IDs, for every admitted candidate and status-bearing submodel. This includes:
   - P-CRUC per candidate;
   - P-EARLY-PROCLAMATION, split into existence and content;
   - P-DEATH for L, F, and C-HET, or a frozen non-necessity rationale;
   - the S1/S2/S3 origin links;
   - V identity;
   - the L encounter-claim origin;
   - the R-PHYS and R-TRANS specifics;
   - the C-HET module propositions.
2. Resolve every dual-mode entry to exactly one mode, or split it into facets.
3. Make sure every COMPARATIVE_ROUTE names at least one discriminator proposed as CRITICAL. Currently missing: P-CRUC, P-H-EXPERIENCES, P-F-ORIGIN-MATERIAL, P-F-MOTIVE-OPPORTUNITY-ROUTE, P-F-TRANSMISSION-SUFFICIENT, R-PHYS tomb, and R-TRANS. Otherwise reroute to NONCOMPARATIVE with a direct route.
4. Fill every 23A field (`necessary_test_rationale`, `discriminator_ids`, `direct_route`, `expected_evidence`, `weakening_evidence`, `lanes`).
5. Move "C-HET frozen map adequacy" from the coverage map into the D9 / C4 control layer.
6. Encode 4.2 item 7: P-R-FOUNDING-ENCOUNTER requires founding-stream referent evidence.

**B-2 — Positive operational definition of "embodied".** It must separate R-PHYS and R-TRANS from V, be stated in candidate-neutral ontological terms, list the evidence classes that bear on each criterion, and tie BGD-8 to it.

### G0_MAJOR

**M-1 — Symmetric route-mode principle.** Write it, apply it uniformly across candidates' analogous core propositions, and give a distortion rationale per NONCOMPARATIVE entry.

**M-2 — Submodel status and evidence binding.**
- Declare R-PHYS and R-TRANS (and H-IND/H-SOC and V-variants where they differ) as status-bearing, or freeze each family conjunctively.
- Add the evidence-binding rule.
- Make R_EVENT answerable per submodel, with umbrella absorption prohibited.

**M-3 — Q1 threshold.**
- Adopt the causal-role ladder used by all candidates.
- Define "pre-Pauline".
- Separate Paul evidence uses (a), (b), and (c).
- Make the symmetric Paul rule.
- Freeze stream-identification, same-stream, inventory-freeze-point, and split-result rules.
- Freeze the Q1 answer table, and fix that "supported" in D12 means `SUPPORTED_WITHIN_SCOPE` for a positive answer (recommended).

**M-4 — Founding-proclamation stratum identification rule.**
- Freeze the generic criteria for "earliest recoverable" and "attributable to the founding movement", stated independently of any locus.
- The stratum is identified once, ledgered, and fixed before direction rules are applied; re-identification is a C4 amendment.
- Resolve the "resurrection/exaltation" content wording (see B-1 item 1).

**M-5 — A14 hardening (§8 Cases 1–6).**
- Close the UNMAKEABLE "without sufficient signal" route.
- Separate provenance failure from bounded uncertainty.
- Fix the non-extant-evidence rule.
- Add prospective truth-critical strata and substitutes per proposition.
- Rule that unperformed search cannot close as ISS.
- Rule that no post-hoc infeasibility can produce ISS.

**M-6 — C-HET fields.** Fields 1–12 of §6.3.

**M-7 — Source-plan strata and service map.** Items 1–8 of §9.2, followed by the concrete 23A SOURCE_PLAN and a further source-plan review before `SOURCE_PLAN_PASS`.

**M-8 — Pre-G0 exposure ledger.**
- Activate an append-only exposure ledger now, or a pre-G0 supplement, for every outcome-relevant exposure during steelman-packet construction, source-plan construction, and route-building searches (B3: "record any unavoidable contamination").
- Ledger any pre-G0 stratum removal with its reason.
- Without this, "pre-evidence" status of later amendments cannot be verified by the ledger-integrity reviewer.

**M-9 — Empirical-background retirement criteria (joint with Reviewer C).**
- For BGD-3, BGD-4, BGD-5, BGD-6, and any partly empirical background, freeze the evidence that would retire each variant (as A8.3 requires).
- A variant whose empirical premise is CONTRADICTED or EVIDENCE_AGAINST at G2 cannot generate a RANKING_FLIP.
- This prevents manufactured FRAMEWORK_DEPENDENCE. The final granularity and interaction design is Reviewer C's.

### G0_MINOR

- **m-1** Rename source strata S1–S12 to SRC-1–SRC-12.
- **m-2** Replace the one-sided SRC-4 absence clause with a symmetric E2-based rule.
- **m-3** Fix stale references:
  - A3 cites `…ROLE_ARCHITECTURE_0_1_0.yaml`, but the frozen file is 0_1_1;
  - A16 says "not enabled for TFP-STRESS-2 0.1.0";
  - A7/B2 says "Q1/Q2" although Q2 is deferred.
- **m-4** Make the P-HIST-JESUS SHARED_FLOOR classification explicitly conditional on the frozen B4 non-historicity exclusion. Sharpen its truth conditions ("corresponding to"). Assign the final post-comparison candidate/exclusion reviewer.
- **m-5** Role coupling: program-lead-authored repair wording or B recusal for D3/D9/D12; disclose the coverage-map self-certification coupling; record later B sessions as new lineage assignments (§10).
- **m-6** Freeze the G0 finalization **sequence**:
  1. candidate and exclusion freeze;
  2. steelman packets;
  3. background register;
  4. source plan and its review;
  5. coverage-map certification;
  6. Reviewer C;
  7. bundle freeze;
  8. human authorization.

  The sequence matters for anti-tailoring; for example, packets should not be built after the source plan's search routes reveal evidence.

---

## 13. NOTES / LIMITATIONS

- **NOTE (pretrained knowledge).** I have general pretrained familiarity with the resurrection debate, its usual candidate families, and its scholarly landscape. I used it only to recognise structural gaps, such as which evidence classes a candidate family typically relies on. I did not use it to assess any evidence, assign any disposition, or rank any candidate. Shared training priors with Reviewer A (same provider) are a disclosed limitation.
- **NOTE (protocol status text).** The pinned protocol blob carries in-file status `CANDIDATE__REPAIR_PENDING_REAUDIT`, and §24 reads `TFP_STRESS_2 = NOT_AUTHORIZED`. Protocol §0 states that static status text inside frozen files is historical metadata and that operative status is read only from canonical STATE. I was not permitted to read `STATE.yaml`, so I accept the "qualified" designation as given by the prompt and the preregistration. That designation is unverified by me.
- **NOTE (non-blind source-plan review).** See §9. A9.1 blind elicitation was infeasible in this assignment.
- **NOTE (no SOURCE_PLAN_PASS, no NECESSARY_PROPOSITION_COVERAGE_COMPLETE).** Neither certification is issued. The certifiable artifacts do not yet exist.
- **NOTE (candidate-universe residue, for the final candidate reviewer).** A model in which some founding claims were deliberately invented by a subset of actors while others were sincere has no clear home. F requires origin-material deliberate invention, and C-HET bars a fabrication module. This may be acceptable, since REVISED_CANDIDATE_REQUIRED exists, but it should be a deliberate B4-recorded decision, not an accident of the module list.
- **NOTE (flags for Reviewer C).**
  - Tiering of D7, D8, and D10, and any new discriminators B-1 requires.
  - S2/S3 direction rules.
  - CRITICAL feasibility statuses.
  - Extramental-referent warrant criteria in D4.
  - The D1 `FAVORS_DEATH_REQUIRED_CANDIDATES` condition partly depends on the rival's failure; check pair symmetry.
  - M-9 retirement criteria.
- **NOTE (strengths).** These should be preserved through repair:
  - the deferral of Q2 (agent attribution);
  - the explicit non-equivalences;
  - prohibited shortcuts listed symmetrically against both supernaturalist and naturalist overreach;
  - the stand-alone C-BX retirement into L/C-HET;
  - the bar on fraud as a hidden C-HET module;
  - "No candidate is strengthened merely because another candidate weakens".

---

## 14. G0 CONTROL DECISION

> **Is the reviewed 0.1.1 design sound enough to proceed to pre-G0 repair/finalization and Reviewer C, without beginning substantive evidence acquisition?**

**Yes, with repairs.** The control architecture is sound enough to proceed to **pre-G0 repair and finalization** and then to **Reviewer C**.

The two G0_BLOCKERs (B-1 coverage-map certifiability; B-2 embodiment operationalization) and the nine G0_MAJORs must be repaired as `PRE_EVIDENCE_AMENDMENT`s before any final G0 bundle is frozen. B-1 and B-2 in particular should be integrated before Reviewer C's discriminator-tier work, because C's tiering depends on the repaired proposition set and the embodiment boundary.

This decision does **not** authorize G0. It does **not** begin or permit G1. It makes **no** determination about whether the resurrection occurred.

**Disposition: `G0_REVIEW_REPAIR_REQUIRED`**

**STOP.**
