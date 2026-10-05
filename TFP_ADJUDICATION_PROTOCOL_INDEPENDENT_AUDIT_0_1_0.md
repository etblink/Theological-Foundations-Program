# Independent Adversarial Audit: `TFP_ADJUDICATION_PROTOCOL_0_1_0.md`

**Sources read, in the required order:** Charter 0.1.1, GOVERNANCE.md, STATE.yaml, Method Seed 0.1.0, then the Protocol. I did not consult EMT artifacts, because the overgeneralization question could be answered from the five governing files. I changed no repository state. Line citations are to the protocol file.

---

## 1. DISPOSITION

**REPAIR_REQUIRED**

---

## 2. EXECUTIVE FINDING

The protocol is **not qualified** for a second bounded stress test in its current form.

**What it gets right.**
- It preserves the evidence, synthesis, adjudication and authorization separations.
- It keeps local results distinct from global ones (§18, §19).
- It rejects a global score (§8).
- It makes `NONE_ADEQUATE` and `UNDERDETERMINED` nominally available.
- It names the right risks, including asymmetry, candidate completeness, lane leakage and the genetic fallacy.

**What it does not do.** It names risks and lists headings but supplies almost no decision rules. I found two blocking gaps.
1. **Acceptance and audit authority are undefined.** An audit PASS and an agent-updated STATE.yaml could together stand in for an explicit acceptance step.
2. **There is no inferential bridge from evidence to adjudication to truth.** None of the evidence labels or outcome labels is defined, no aggregation rule exists, and "best supported" is never connected to "true" or "closest to truth."

I also found a cluster of major gaps that would let outcomes be determined by unrecorded researcher judgment or smuggled background assumptions. They concern miracle and revelation handling, evidence burdens, claim typing, candidate admission, discriminator freezing, source hierarchy, lanes, the ladder, evidence acquisition, and the protocol's relationship to STATE.yaml and the Method Seed.

The protocol is more plausibly a well-organized *checklist of concerns* than an operational protocol. A cold-start researcher would recover what to worry about, but not what to do or how to decide.

---

## 3. GOVERNANCE COMPATIBILITY

**Preserved.**
- Phase N says synthesis "cannot canonize" (l.376–378).
- Phase O says audit PASS "is not itself canonical acceptance" (l.405).
- Phase Q says an accepted result does not authorize a wider conclusion (l.453–457).
- §18 states that "Christianity is true" requires far more than one bounded adjudication.
- These match GOVERNANCE §3 and STATE.yaml invariants.

**Defects.**

1. **The acceptance actor and criteria are undefined (BLOCKING).**
   - GOVERNANCE G5 requires "an explicit acceptance step." The protocol never says who performs it, under what criteria, or by what recorded act.
   - Phase P lists what a record *contains*.
   - Phase Q says "After a study is accepted, STATE.yaml may be updated," in the passive voice.
   - GOVERNANCE §20 lets research agents "update STATE.yaml to reflect … completed gates." So the audit PASS, the acceptance and the STATE update can all be performed by the same agent.
   - That meets the letter of the separations while bypassing their purpose. The protocol does not say which bounded adjudications fall under the human owner's "consequential program-level truth commitments" and which agents may accept.

2. **Audit PASS is made conditional on itself (MAJOR).** "Audit PASS is necessary where the protocol requires it" (l.405). The protocol never says where it requires it.

3. **The G0 authorization step is missing (MAJOR).**
   - Phase A "freezes" the question but does not authorize it.
   - GOVERNANCE G0 also requires frozen "major alternatives," "expected evidence," and "potential falsifiers or weakening evidence." Phase A omits all three.
   - GOVERNANCE §9 preregistration requires the dependency structure, candidate set, evidential expectations and disposition vocabulary. The protocol omits or only loosely addresses these.
   - There is no mapping between Phases A–R and G0–G6. G1 evidence acquisition has no counterpart at all (see §12 below).

4. **The protocol conflicts with STATE.yaml `methodology` (MAJOR).**
   - STATE sets `link_decomposition_required: true`. The protocol never mentions link decomposition (Seed §3).
   - STATE's other requirements appear only loosely: `independent_reinvention_null_required_when_applicable` is partly in Phase J, and `candidate_completeness_gate` is only a synthesis checklist item.
   - Seed §4, which separates plausibility from attestation, and Seed §16, scope discipline, are also absent.
   - The protocol does not say whether it incorporates, supersedes or sits beside the Seed, so precedence is unspecified.

5. **Local result becoming global.**
   - Outcome labels such as `CANDIDATE_A_SUBSTANTIALLY_SUPPORTED` (l.428) carry no scope tag in the label itself.
   - Scope protection depends on prose in the record. Nothing prevents a downstream summary from dropping the "within scope" qualifier.
   - The protocol's own outcome vocabulary mixes "within scope" and unscoped forms.

6. **Self-attestation (MINOR).** "GOVERNANCE_COMPATIBLE = YES_BY_CONSTRUCTION" (l.555) is an unauditable author assertion. It sits inside a document that says it is unqualified.

7. **Stale Seed reference (NOTE).** The Seed's authority line cites `TFP_PROGRAM_CHARTER_0_1_0.md`, which Charter 0.1.1 supersedes. This is outside the target but affects the source-set coherence a cold-start reader would depend on.

---

## 4. BIAS / ASYMMETRY FINDINGS

### A. Apologetic / traditional / confessional asymmetry

**Structural features that tilt toward confessional or traditional positions:**

1. **Asymmetric candidate-admission paths (MAJOR).**
   - A candidate is admitted if it is "seriously represented in relevant scholarship or tradition," or if it is "independently generated by the evidence **and sufficiently specified to test**" (l.102–106).
   - Tradition-sourced candidates face a representation test. Evidence-generated candidates face a specification test.
   - "Inherited doctrinal positions" are listed first among candidate classes (l.92).

2. **The "faith commitment" claim type is a possible shelter (MAJOR).**
   - The type is defined as "accepted beyond public adjudication" (l.155).
   - The protocol never says whether faith commitments are excluded from truth adjudication or what burden applies if included.
   - Typing a contested claim as a faith commitment could remove it from burdens. Retyping is not constrained (see §6).

3. **Origins, development and truth run in one direction only (MAJOR).**
   - Phase M says "No result in the first three categories automatically decides the fourth" (l.359).
   - That blocks "natural origin → false." It gives no route by which origin or development evidence *can* bear on truth, for example when a claim's warrant is its apostolic origin or a revelation's faithful transmission.
   - Read alone, the text gives truth a standing that insulates it from historical-development evidence. This is a structural leaning toward the confessional position.

4. **Internal adequacy can substitute for warrant (MINOR).** Phase L separates internal adequacy from external warrant but gives no procedure for testing premise warrant (see §10).

**Features that guard against apologetic asymmetry** (credited because they are in the text): "Conflicts are recorded, not harmonized" (l.274), Phase K's burden-symmetry checks, the prohibition on suspending historical standards for miracles, and the requirement that institutional consensus be justified as evidence (l.323–324).

### B. Skeptical / naturalistic asymmetry

**Structural features that tilt skeptical or naturalistic:**

1. **A one-directional independent-reinvention null (MAJOR).**
   - Phase J makes independent invention the null for any concept that could arise repeatedly. It lists divine creator concepts, afterlife imagery and triadic language as examples. "Transmission requires evidence beyond resemblance" (l.307).
   - Combined with the ladder's "no jumping" rule, the structural burden falls on claims of continuity and transmission.
   - No parallel burden applies to claims of discontinuity, corruption or invention. The Seed's "one documented later development ≠ doctrine invented ex nihilo" (§16) was not carried into the protocol.
   - A "no C-level evidence, so discontinuity" inference is therefore not constrained.

2. **Source hierarchy discounts later sources but not early ones (MAJOR; see §7).**

3. **The miracle clause bars only the skeptical error as written (see §9).** "Do not: assume naturalism; suspend ordinary historical standards" (l.204–206). There is no matching "do not assume supernaturalism."

4. **"Ordinary historical standards" is an unexamined baseline.** Mainstream historiographic standards embed analogy and uniformity assumptions that are methodologically naturalistic. Using them as the neutral reference class is a hidden premise (see §9).

5. **The "additional unsupported assumption" clause of the strong discriminator encodes a fewest-assumptions heuristic (MAJOR; see §7).**

The two sets of asymmetries do not cancel. They interact with the missing decision rule (see §13): with no aggregation rule, whichever tilt the researcher prefers decides.

---

## 5. CANDIDATE-UNIVERSE FINDINGS

1. **Exclusion criteria can be gamed (MAJOR).**
   - "Dependent on assumptions already rejected within scope" (l.113) is circular. Scope is set in Phase A by the same researcher, so a scope choice can pre-reject a rival.
   - "Too underspecified" can exclude serious minority or hybrid positions that tradition-native sources have not yet spelled out.
   - "Materially distinct from already admitted candidates" (l.106) can exclude revised or hybrid candidates as "not distinct."
   - No one other than the researcher reviews exclusions before adjudication. They need only be "documented."

2. **`NONE_ADEQUATE` and `UNDERDETERMINED` are listed as candidates (l.97–98), which is a category error (MAJOR).**
   - They are meta-outcomes, not rival hypotheses.
   - "Adequate" is undefined (adequate to what: evidence, coherence, both?), so `NONE_ADEQUATE` has no threshold.
   - These outcomes are live in the outcome list but not operationally reachable.

3. **Candidate completeness is not operational (MAJOR).**
   - GOVERNANCE §7 calls completeness "a gate." The protocol's only appearance of it is a synthesis checklist item, "candidate-universe completeness check" (l.372).
   - No criteria say when the universe is complete enough to adjudicate. No independent candidate-elicitation or red-team step exists.
   - Nothing sits before adjudication to stop a missing serious rival from being found only by an auditor after the fact.

4. **There is no procedure for post-freeze additions.**
   - Phase B says the universe is built "before comparative closure."
   - Hybrids and revised syntheses often become visible only after lane work.
   - Nothing separates legitimate evidence-driven additions from post hoc ones.

5. **Vocabulary capture is only partly guarded.** Phase C ("avoid defining one candidate entirely through an opponent's critique") helps but is "where practical." The protocol has no tradition-neutral test vocabulary requirement. The audit question (l.388) asks "did one framework define the test language?" but no construction step prevents it.

6. **Closed-world risk.** "Best supported among admitted candidates" can be mistaken for "true," because the true answer may lie outside the set (see §13).

7. **Resurrection-shaped examples.** The protocol's only worked lane set and its proposed second test (§25) are the resurrection. Candidate-universe rules have no non-Christian or non-miracle exemplar. This is weaker evidence of Christian-centered shaping than of overfitting to the next planned test (NOTE).

---

## 6. CLAIM-TYPE AND EVIDENCE-BURDEN FINDINGS

### Claim typing

1. **Missing categories (MAJOR).**
   - **Normative and moral claims.** The Charter lists "existential/practical consequences." The protocol and GOVERNANCE §5 renamed this "experiential/practical," and the protocol's row covers testimony and phenomenology, not practical consequences or normative claims.
   - **Metaphysical claims.** They are folded into "philosophical" without distinction.
   - **Psychological, sociological and cognitive explanatory claims.** These are central to naturalistic candidates (hallucination, grief, social formation) and have no row, so they must be forced into "empirical" or "historical."
   - **Revelation and authority claims.** Scriptural authority and canon claims are listed in the Charter (§7) but have no row.

2. **Overlap and ambiguity.** Doctrinal, interpretive and philosophical overlap. So do historical, archaeological/material and empirical. Nothing says which prevails when a claim fits two rows.

3. **Retyping can change the burden.** The protocol does not say who types a claim, when typing freezes, or how a typing dispute is resolved. Since the burden depends on type, retyping can lower or raise a burden. Typing is not on the audit checklist.

4. **Multi-type claims are inadequately handled.** The only rule is "state which evidence class is carrying which inference" (l.159–160). When types yield conflicting evidence, nothing says what happens, apart from Phase H's "conflicts are recorded, not harmonized," which concerns lanes, not types.

### Evidence burdens

1. **The protocol states no burdens (MAJOR).**
   - The matrix (l.144–155) lists "typical evidence" and "typical failure mode." It does not say what burden each type must meet for each disposition.
   - GOVERNANCE §5 says "the evidence burden must match the type." Phase F lists attributes (quality, independence, proximity, directness, provenance, replicability, discriminatory power) but no thresholds.
   - Assessing appropriateness, achievability, symmetry or strictness is therefore impossible.

2. **Several types lack a route to truth.**
   - Doctrinal: the row's evidence ("creeds, councils, theologians") shows what a system *asserts*, not whether it is *true*. The protocol never says how a doctrinal claim's truth is evidenced, for example by decomposing it into historical, philosophical or revelation sub-claims.
   - Empirical: "observationally testable" excludes claims not directly testable, but nothing says what evidence applies to those instead.
   - Experiential: the row gives only a failure mode ("sincerity mistaken for external truth") and no positive evidential role for religious experience.

3. **Burden vocabulary is too vague to be either permissive or strict.** I cannot call any burden "too permissive" or "impossibly strict" because none is stated. That is itself a defect: the protocol is non-reproducible at the point where the equal-standard principle needs content.

---

## 7. SOURCE-HIERARCHY AND DISCRIMINATOR FINDINGS

### Source hierarchy

1. **Proximity is ranked first and reliability is mixed in (MAJOR).**
   - Textual: "earliest/most reliable manuscript evidence" (l.169). Historical: "contemporaneous or near-contemporaneous evidence" first (l.177). Doctrinal development: "source at the period being studied" first (l.185).
   - "Earliest" and "most reliable" are conflated in the textual list. Elsewhere only the ordering signals preference.
   - The numbered "Prefer" lists read as lexical orderings. The protocol does not say they are defeasible.
   - It never states "earlier ≠ better."

2. **The discount is applied to later sources only.** Historical item 5 asks for "explicit discount for temporal distance/dependence" on later testimony. There is no parallel rule for the unreliability of early sources (partisanship, genre, interest, anonymity, redaction).

3. **Later sources preserving earlier material is not recognized.** The Seed (§8) says later texts "may preserve." The protocol omits this. Doctrinal-development item 5 ranks "retrospective harmonizations last."

4. **Dependence and independence.** "Independent source streams" and the Phase F "independence" attribute appear, but no criterion defines independence (shared tradition, literary dependence, common community, common informant). The Seed's warning that convergence needs "genuinely independent" sources is only partially carried over.

5. **Mixed questions have no resolution rule.** The protocol's own Trinity example (l.59) spans textual, historical and philosophical elements. Nothing says which hierarchy governs.

6. **Question-relativity is real but incomplete.** The hierarchies differ by question type, but each is internally proximity-dominated for historical questions.

### Discriminators

1. **No freeze point (MAJOR).**
   - Phase G says discriminators are identified "Before comparative synthesis" (l.245). GOVERNANCE G0 freezes expectations *before* evidence acquisition.
   - The phrase leaves open that discriminators are chosen after seeing evidence or after lane analysis.
   - No registry, timestamp or amendment log exists, and no distinction between pre-evidence and post-evidence discriminators.

2. **The strong-discriminator definition is background-dependent.** "Candidate B requires an additional unsupported assumption" (l.254–255) leaves open whose background decides what counts as unsupported. A naturalist and a theist will list different "unsupported" assumptions for the same case. It also builds in the fewest-assumptions heuristic.

3. **Evidentially equivalent but philosophically different candidates, and evidence supporting several candidates equally.** The only guidance is "the study may be intrinsically underdetermined" (l.257). The protocol does not distinguish:
   - evidence that fails to discriminate;
   - discriminators that depend on philosophical premises;
   - discriminators that depend on unavailable evidence.

4. **Discriminators "won/lost" (l.373) invites tallying.** No weighting rule exists, which sits in tension with GOVERNANCE §16 (no opaque global score). A tally is an opaque score in all but name.

5. **Theology's capacity to generate discriminators is unaddressed.** Some disputes are metaphysical, with no observational discriminator. For those, "discriminator" must mean an argument. The protocol says "observation or argument" in the definition but gives no standard for what makes an *argument* discriminating.

---

## 8. CONTINUITY / GENEALOGY FINDINGS

1. **The ladder is only labeled in the protocol (MAJOR).**
   - Phase I (l.278–289) lists C0–C7 with short labels and no definitions. C7 is defined only in the Seed: "preserve or intentionally develop a specific earlier proposition strongly enough that the relation is not merely thematic."
   - "Strongly enough" and "not merely thematic" are undefined.

2. **The ladder is not a ladder.**
   - The rungs are different *kinds* of relation: material, carrier, practice, functional-semantic, explicit naming, causal derivation, and propositional preservation.
   - A textual quotation chain can reach C5/C6 with no C1–C4. A pure philosophical argument has no material or carrier rungs.
   - "No study may jump from C0/C1 to C6/C7" (Seed §5) is not stated in the protocol, which also never says which rungs are prerequisites for which.
   - C6 is a causal claim, C4 a functional-similarity claim, and C7 a mixed semantic and intentional one, so levels are conflated.

3. **Linear and non-linear development.**
   - Nothing represents branching, convergence, loss and recovery (ressourcement), independent construction, or parallel formulation. These are the commonest doctrinal-development patterns.
   - Link decomposition (nodes and arrows), which could represent them, is absent from the protocol.
   - The ladder is silent on *discontinuity* claims. It tests continuity claims only.

4. **Generalization beyond archaeology is poor.**
   - C1 ("material/form") and C2 ("carrier") are archaeology-shaped.
   - Doctrinal and philosophical questions need relations such as entailment, logical dependence and conceptual development, which the ladder does not express.

5. **Truth caveat.**
   - Phase I protects the line "a later doctrine may reach C7 locally without proving the truth of the doctrine" (l.291–293). That is sufficient as far as it goes.
   - The converse is missing: continuity or discontinuity evidence may *legitimately bear on* a claim whose warrant depends on historical continuity. The protection is therefore one-directional (see §4A.3).

---

## 9. MIRACLE / REVELATION / PHILOSOPHY FINDINGS

### Miracle claims

The entire treatment is eight lines (l.202–211). It lists four labeled buckets (historical evidence, natural explanations, philosophical admissibility, theological identification of cause) but states no procedure for moving among them.

1. **Asymmetric prohibition (MAJOR).** The "Do not" list bars assuming naturalism. It does not bar assuming supernaturalism, treating sincere testimony as sufficient, or treating miracles as impossible by definition.

2. **Internal tension.**
   - "Do not assume naturalism" and "do not suspend ordinary historical standards" conflict wherever those standards embed naturalistic assumptions.
   - The protocol never says whether the standards are being treated as neutral, or how the conflict is resolved.

3. **No comparison of explanations.**
   - Natural explanations are listed (step 2) and admissibility is listed (step 3), but there is no step that compares explanations on a common footing. Prior probabilities, background weight and likelihood handling are never mentioned.
   - Priors will be set silently inside "philosophical admissibility" by whoever fills it in. That avoids stating arbitrary priors only by hiding them.

4. **Two of the five required separations are fused.** The protocol's step 4, "theological identification of cause," merges "which supernatural cause" with downstream theological inference. It also lacks an intermediate step: "an anomalous event occurred" is separate from "a non-natural cause is established." "Something unusual happened" can still collapse into "the proposed theological cause is established."

5. **Testimony.** The experiential row warns that "sincerity is mistaken for external truth," but there is no handling of testimony reliability, transmission distortion, or multiple attestation beyond the historical-row list.

### Revelation claims

1. **Revelation is handled only by sharing the miracle clause (MAJOR).** The heading is "Revelation/miracle question." The seven distinctions the question asks for are not available:
   - a person claiming revelation;
   - sincere belief that it occurred;
   - historical transmission of the claim;
   - philosophical possibility;
   - evidence that it occurred;
   - identification of its source;
   - doctrinal consequences.
2. Only the first four partly map onto existing rows (experiential and historical). Evidence for the occurrence of revelation, identification of source, and consequence tracing have no machinery.
3. No safeguard separates a revelation claim's content from its warrant, or addresses competing revelation claims from different traditions.

### Philosophical claims

1. **Over-weighted toward historical evidence (MAJOR).**
   - Phases F, I, J and M are specialized to historical and genealogical questions. The philosophy source rule is six bullets (l.191–200).
   - It covers premises, validity, soundness, explanatory reach, internal consistency and rival arguments. It omits:
     - how premise warrant is assessed (intuition, abduction, plausibility);
     - defeaters;
     - theoretical-virtue weighting;
     - comparison of rival metaphysical frameworks as wholes.
   - The listed topics (necessity, modality, personhood, identity, causation, morality, consciousness, free will, evil, divine attributes) have no dedicated treatment.

2. **"Evidence" is implicitly narrow.** The Phase F attributes (proximity, provenance, replicability) do not apply to arguments. A philosophical proposition has no recorded "quality" or "directness" dimension, so it cannot be scored on the same page as historical propositions.

---

## 10. EVIDENCE-LANE AND SYNTHESIS FINDINGS

1. **Lane definitions exist only for one case.** The protocol defines lanes only for the resurrection example (T, H, A, P, D). No general rule says how to define lanes for another question.

2. **"Frozen" is undefined (MAJOR).** Phase N says synthesis begins "after evidence lanes are frozen" (l.363). The protocol gives no definition of frozen, no freezer, and no artifact marking it.

3. **"Accepted evidence" is ambiguous.** Rule 2 permits a lane to cite another lane's "accepted evidence" (l.273). "Accepted" is the governance term for G5 canonical acceptance, and it violates OBSERVATION ≠ ACCEPTANCE if read at lane level. The protocol does not say who accepts evidence at lane level or whether it is the same act.

4. **Leakage in both directions is unaddressed.**
   - A philosophical assumption can silently set a historical lane's probability range. Lane P, which holds admissibility of supernatural causation, sits beside the others but no rule says how its background assumptions are passed into H and A in explicit form.
   - Historical conclusions can silently push on theological conclusions, because Lane D's inputs are unspecified.

5. **Over-separation risk.** Historical judgment about a miraculous report depends on background that other lanes supply. Complete separation prevents cumulative-case reasoning. The protocol names "synthesis" as the integration point but supplies only a checklist, not a method (see §13).

6. **The lane names carry framing.** "Lane H, historical core" presupposes a recoverable core event. "Lane A, alternative historical explanations" frames non-traditional accounts as the alternatives to a default (MINOR).

7. **Evidence collection is unaddressed.**
   - The required outputs list a "Source/evidence map" (item 4) but no phase produces it. GOVERNANCE G1 requires evidence acquisition, provenance and recording of inaccessible or missing evidence.
   - The Seed's "negative searches" requirement is also absent.
   - There is no search strategy, inclusion rule or coverage record. Source selection therefore cannot be audited, although audit question 3 asks "did source selection favor the conclusion?"

---

## 11. UNCERTAINTY / STOP / REOPEN FINDINGS

### Uncertainty

1. **The vocabulary is undefined and mixes levels (MAJOR).**
   - Phase F proposes eight labels (l.230–237), none defined.
   - `PARTIALLY_SUPPORTED` and `PLAUSIBLE_BUT_UNATTESTED` have no boundary. `NOT_ESTABLISHED`, `INSUFFICIENT_SIGNAL` and `UNDERDETERMINED` overlap.
   - The labels apply to propositions, and Phase P's outcomes apply to the study, with no mapping between the two.
   - There is no label for "attested but unreliable" or "contested among experts."

2. **Avoiding numbers is defensible.** GOVERNANCE §16 prefers typed dispositions. But the protocol does not replace numeric precision with anchored qualitative definitions, so the ambiguity cost is paid without the benefit.

3. **No minimum uncertainty statement.** Phase P lists "uncertainty" and "known weaknesses" but not what they contain. I would expect a statement to include:
   - named residual live alternatives;
   - the key background assumptions on which the verdict depends;
   - what evidence would flip the result;
   - confidence stated separately from evidential scope, so that "weak evidence" is distinguishable from "narrow scope."

4. **Deep underdetermination has one label.** It does not distinguish:
   - evidence equally supporting several candidates;
   - framework-dependence;
   - unavailable evidence;
   - evidential equivalence with philosophical difference.

### Stop and reopen

1. **Early-stop gaming.** Early stopping can be reached through `INSUFFICIENT_SIGNAL` or "low expected information value." Neither is audited, and there is no search-coverage requirement a reviewer could check. "Another program gate has higher value" (l.466–467) is a non-epistemic stop reason (MINOR).

2. **"Expected information value" is not operational.** No assessor, scale or method is given. This is the same phrase used in GOVERNANCE §15. The protocol adds no reproducible content.

3. **Endless literature.** Nothing handles the case where literature keeps growing but is unlikely to change the result, other than the same vague criterion. A bounded search window or a defined stopping test would help.

4. **Reopen rules are partly concrete.** Phase A6 and Phase R require `reopen_if` conditions, but "should state" (l.469) is not "must." Philosophical results have no analogue of "new evidence" (for instance, a new argument or a defeater). The protocol also never says which of GOVERNANCE G6's states (closed, held, superseded, reopened) a stop yields (MINOR).

---

## 12. REPRODUCIBILITY AND COLD-START FINDINGS

A competent researcher receiving only the five governing files can:
- recover the phase sequence;
- find the question template (A1);
- find candidate classes;
- list claim types;
- find the 14 required outputs.

**What they cannot determine without lore:**

1. **Who authorizes G0, who accepts at G5, and which results need the human owner.** This is unspecified.
2. **How candidates are finally selected**, given discretionary words such as "serious," "normally," "materially distinct" and "too underspecified."
3. **What evidence to collect, and how.** No acquisition phase exists.
4. **How evidence is classified into dispositions.** The labels are undefined.
5. **How candidates are compared.** There is no aggregation rule (see §13).
6. **When cross-lane synthesis is allowed.** The condition "frozen" is undefined.
7. **When to stop.** The criteria are not operational.
8. **How uncertainty is reported.** There is no minimum content.
9. **How phases map to the G0–G6 gates**, and which of the Seed's rules (link decomposition, plausibility vs attestation, refunctionalization) apply.
10. **What an "audit PASS" binds**, given the circular "where the protocol requires it" wording.

The fact that a researcher must fall back on the Seed and unstated judgment calls for items 4, 5 and 9 constitutes undocumented lore. **Cold-start fails at the decisive steps.**

The audit's own tenth question (l.395), "would an unfamiliar competent researcher recover the same reasoning?", has no check procedure.

---

## 13. TRUTH-ADJUDICATION FINDINGS

**Path from evidence to bounded adjudication: absent as a rule.** The protocol has an ordered sequence of phases but no inferential step linking them.
- Evidence attributes (Phase F) are not mapped to dispositions.
- Dispositions are not mapped to the study-level outcomes (Phase P).
- "Discriminators won/lost" is a tally with no weighting.

An unfamiliar researcher given the same evidence could reach different outcomes, and no artifact would show the reasoning was wrong.

**Truth vocabulary is incomplete in both directions.**
- *Too hard to reach truth judgments.* Every bounded outcome in Phase P is a *support* label (`BEST_SUPPORTED_WITHIN_SCOPE`, `SUBSTANTIALLY_SUPPORTED`), not a truth or closeness-to-truth label.
- The protocol's purpose (l.19) is truth or closest-to-truth. The Charter (§10) forbids reducing "true" to "merely best supported within a restricted source set." The protocol has no stated way to go from best-supported to truth-warranted, or to say why that move is not warranted.
- A study may therefore generate increasingly refined descriptions without ever licensing a truth judgment.
- *Too easy to reach one.* "Substantially supported" is undefined and carries no scope tag, so a loose reading could treat it as a truth-adjacent verdict. The closed-world risk compounds this (§5.6).

**The four notions are not properly kept apart.** "Best supported," "most coherent," "historically earliest" and "true" are distinguished only by Phase L (internal adequacy vs external warrant) and Phase I (continuity ≠ truth). "Best supported" is itself undefined. No rule says how coherence, support and warrant combine, or which outranks the others.

**Heuristic robustness.** Because outcomes depend on unrecorded judgment, a shallow rule can be applied silently through "judgment." In addition:
- the hierarchy lists (§7) approximate "prefer the earliest";
- the strong-discriminator wording approximates "prefer fewest assumptions";
- the reinvention null approximates "prefer independent origin."

Of the prompt's heuristics, the protocol's own prohibited list (l.504–513) omits "always trust established tradition" and "always prefer the interpretation with the fewest assumptions" (MINOR). It also says the protocol "should *eventually* be tested" against them (l.501–502), so no mechanism enforces the prohibition now.

---

## 14. REQUIRED REPAIRS

### R1: Acceptance authority and audit independence: **BLOCKING**
- **Exact defect.**
  - Phase P/Q never say who performs the G5 acceptance step or on what criteria.
  - Audit independence is "where practical" and "possible forms" (l.471–483).
  - "Audit PASS is necessary where the protocol requires it" (l.405) is circular.
  - GOVERNANCE §20 lets agents update STATE.yaml for completed gates.
- **Why it matters.** A single researcher can produce synthesis, audit, acceptance and the STATE update. This bypasses the acceptance gate the program exists to protect. The protocol cannot safely qualify while that is possible.
- **Minimum sufficient repair.**
  - Name the acceptance actor for each class of adjudication, and the human-owner threshold for program-level commitments.
  - State triggers for a *mandatory* independent auditor, at least for any study that proposes a canonical adjudication.
  - Require that the auditor not be the lane author, and that the audit not be self-certifying.
  - Require that a canonical STATE entry cite a recorded acceptance act separate from the audit result.

### R2: No inferential bridge from evidence to adjudication to truth: **BLOCKING**
- **Exact defect.**
  - Labels are undefined, with no mapping from proposition-level labels to study-level outcomes.
  - There is no aggregation rule (discriminators are "won/lost").
  - "Best supported" is undefined.
  - No rule connects best-supported to truth or closeness-to-truth.
  - Outcome labels carry no mandatory scope tag.
- **Why it matters.** The decisive step is unreproducible, and the protocol can neither license truth judgments nor withhold them on a principled basis. It cannot be tested as an adjudication protocol without this.
- **Minimum sufficient repair.**
  - Define each disposition and each outcome label with anchored criteria.
  - State how lane results combine, including how conflicts are weighed and recorded without a numerical score.
  - State what additional conditions, if any, allow a "true" or "closest to truth" statement beyond "best supported within scope."
  - Fix the scope tag as part of the label itself.

### R3: Miracle and revelation procedure: **MAJOR**
- **Exact defect.**
  - The protocol bars only the naturalist error.
  - It leaves "ordinary historical standards" unexamined against "do not assume naturalism."
  - It provides no explanation-comparison step and no statement on priors or background.
  - It conflates cause identification with downstream inference.
  - Revelation has no distinct treatment.
- **Why it matters.** Any study involving miracle or revelation, including the queued resurrection study, would be decided by unrecorded priors.
- **Minimum sufficient repair.**
  - State symmetric prohibitions (no naturalism assumed, no supernaturalism assumed, sincerity not sufficient, no definitional impossibility).
  - Resolve what "ordinary standards" means.
  - Add the missing separations: anomaly established, non-natural cause admissible, particular cause identified, downstream theological inference.
  - Require an explicit, recorded statement of background assumptions and how they were handled.
  - Add the seven revelation distinctions listed in §9.

### R4: Evidence burdens by claim type: **MAJOR**
- **Exact defect.** No burdens or thresholds are stated. Doctrinal, non-testable empirical and experiential claims have no route to truth.
- **Why it matters.** The equal-standard principle has no content, and nothing can be assessed for symmetry or strictness.
- **Minimum sufficient repair.** For each type, state the minimum evidential content for each disposition level, and state how truth is evidenced for doctrinal, revelation-dependent and non-testable claims.

### R5: Claim typing integrity: **MAJOR**
- **Exact defect.**
  - Missing categories: normative, metaphysical, psychological/sociological explanatory, and revelation/authority.
  - There is no typing authority, no freeze point and no dispute procedure.
  - Faith-commitment status is undefined.
  - No rule governs conflicting evidence across types.
- **Why it matters.** The burden follows type, so retyping can launder a claim's burden.
- **Minimum sufficient repair.**
  - Add or define the missing types, or state explicitly why they fall under existing ones.
  - Freeze typing at Phase A and put typing on the audit checklist.
  - State whether faith commitments are in or out of truth adjudication, and with what burden.
  - Add a conflicting-types rule.

### R6: Philosophical and non-historical evidence machinery: **MAJOR**
- **Exact defect.** Phase F's evidence attributes are historical. The philosophical treatment lacks premise-warrant assessment, defeaters, theoretical-virtue handling and comparison of metaphysical frameworks.
- **Why it matters.** Overgeneralization from EMT would tilt every philosophically heavy study toward whichever side the historical lane favors.
- **Minimum sufficient repair.** Define evidence for arguments (premise warrant, defeaters, rival frameworks) and add a non-historical attribute set to Phase F. Give normative and doctrinal-logical reasoning a place in the lane structure.

### R7: Candidate-universe operationalization: **MAJOR**
- **Exact defect.**
  - Asymmetric admission paths.
  - Circular and underspecification-based exclusions.
  - `NONE_ADEQUATE` and `UNDERDETERMINED` listed as candidates with no adequacy threshold.
  - No completeness test.
  - No post-freeze addition rule.
- **Why it matters.** Candidate selection is the easiest place to game a result before any evidence is read.
- **Minimum sufficient repair.**
  - Use one admission test for all candidate sources.
  - Constrain exclusion grounds and require independent review of exclusions.
  - Treat `NONE_ADEQUATE` and `UNDERDETERMINED` as outcomes with defined thresholds, not candidates.
  - Add a completeness checklist (including independent candidate elicitation) and a logged, labeled procedure for post-freeze additions.

### R8: Discriminator discipline: **MAJOR**
- **Exact defect.** There is no freeze point relative to evidence. "Unsupported assumption" depends on background. "Won/lost" tallying is possible. Non-discriminating evidence and philosophical equivalence are not distinguished.
- **Why it matters.** Post hoc discriminators can be chosen after seeing which candidate benefits.
- **Minimum sufficient repair.**
  - Require discriminators to be registered before evidence acquisition, with a dated amendment log distinguishing post-evidence additions.
  - Define "unsupported assumption" relative to a stated background.
  - Forbid unweighted tallying.
  - Add typed outcomes for the underdetermination cases in §7.

### R9: Source hierarchy: **MAJOR**
- **Exact defect.** "Earliest" and "reliable" are conflated. Only later sources are discounted. Later preservation, independence criteria and mixed-question handling are absent. The "Prefer" lists are not stated to be defeasible.
- **Why it matters.** Proximity can become a universal preference that tilts toward skepticism on questions where early evidence is sparse.
- **Minimum sufficient repair.** State that earlier is not automatically better. Add reliability criteria for early sources and recognition of later preservation. Define independence. Declare the lists defeasible, and say how mixed questions choose a hierarchy.

### R10: Lane governance: **MAJOR**
- **Exact defect.** "Frozen" is undefined. "Accepted evidence" is ambiguous. There is no channel for stating background assumptions across lanes. No cumulative-case method exists. Lane definitions exist for one case only.
- **Why it matters.** Lane conclusions can leak, or be over-separated, with no recorded boundary.
- **Minimum sufficient repair.** Define lane freeze. Replace "accepted" with a term that is not a governance term. State how philosophical and background assumptions enter other lanes explicitly. Specify the cross-lane synthesis method.

### R11: Evidence acquisition and link decomposition: **MAJOR**
- **Exact defect.** No evidence-acquisition phase (search strategy, inclusion rules, provenance, inaccessible and negative searches). Link decomposition, required by STATE.yaml, is absent.
- **Why it matters.** Source selection cannot be audited, and the protocol conflicts with canonical state.
- **Minimum sufficient repair.** Add an evidence-acquisition phase consistent with GOVERNANCE G1. Add the link-decomposition requirement, and state how the Seed's relevant rules are incorporated.

### R12: Origins, development and truth; continuity ladder: **MAJOR**
- **Exact defect.**
  - Phase M and Phase I state the "no automatic inference to falsity" direction only.
  - The reinvention null is one-directional.
  - Ladder levels are undefined in the protocol, conflate relation types, and do not represent non-linear development or discontinuity claims.
- **Why it matters.** The protocol can insulate truth from relevant historical evidence, and puts the burden structurally on continuity claims only.
- **Minimum sufficient repair.**
  - State when development evidence legitimately bears on truth (where a claim's warrant depends on it).
  - Give discontinuity and corruption claims a parallel evidential burden.
  - Define C0–C7 in the protocol (including C7's "strongly enough").
  - State that the ladder is a set of relation types, not a strict sequence, and allow for branching, loss and recovery.

### R13: Protocol–Governance–STATE alignment: **MAJOR**
- **Exact defect.** There is no phase-to-G0–G6 mapping. G0's required contents are incomplete. The protocol's precedence relative to the Seed is unspecified. It does not say how STATE's `methodology` flags are met.
- **Why it matters.** A successor cannot tell which document governs when they differ.
- **Minimum sufficient repair.** Add an explicit mapping and precedence statement. Complete the G0 and preregistration contents.

### R14: Audit mechanism details: **MAJOR**
- **Exact defect.** There are no frozen audit criteria. There is no rule for auditor disagreement, multiple auditors, what the auditor is blinded to, re-audit after repair, or carrying `PASS_WITH_LIMITATIONS` limitations into the record. Gaming checks (typing, discriminator timing, lane leakage, premise warrant) are not on the checklist.
- **Why it matters.** Audit criteria could drift after the result is seen, and the same researcher could satisfy the audit perfunctorily.
- **Minimum sufficient repair.** Freeze audit criteria before the audit. Add the missing audit questions. State the disagreement and re-audit rule and the blinding minimum. Bind limitations to the canonical record.

### R15: Uncertainty statement: **MAJOR**
- **Exact defect.** Labels are undefined (overlap with R2 on definitions). There is no minimum uncertainty statement. Confidence and scope are not separated. Residual alternatives are not named. Underdetermination has one type.
- **Why it matters.** Uncertainty is the main safeguard against over-claiming, and it has no required content.
- **Minimum sufficient repair.** Require a fixed-format statement covering named residual alternatives, key background assumptions, what would flip the result, and confidence reported separately from scope. Subtype underdetermination.

### R16: Stop and reopen operationalization: **MINOR**
- **Exact defect.** "Expected information value" is undefined. "Should state" `reopen_if` is permissive. No search-coverage criterion exists. Stops yield no GOVERNANCE G6 state. Philosophical reopen conditions are missing.
- **Why it matters.** Investigators could stop early, or continue indefinitely.
- **Minimum sufficient repair.** Make `reopen_if` mandatory. Define a coverage-based stopping test. Map stops to closed, held, superseded or reopened.

### R17: Anti-heuristic list and mechanism: **MINOR**
- **Exact defect.** The list omits "trust established tradition" and "fewest assumptions," and tests are deferred ("eventually").
- **Why it matters.** Shallow rules can operate unnoticed.
- **Minimum sufficient repair.** Complete the list and require the audit to check that no single heuristic reproduces the study's outcome.

---

## 15. NON-REQUIRED IMPROVEMENTS

These are not defects and are kept separate from the repairs.

- Add a worked example in a non-Christian and non-miracle domain, so the protocol is not shaped by one anticipated test.
- Add a qualitative likelihood-ratio template for explanation comparison, with no numbers, to make R3 easier to apply.
- Add a sensitivity analysis step: "which single assumption change flips the outcome?"
- Add a glossary of recurring terms ("serious," "within scope," "adequate").
- Rename lanes H and A to remove implied framing (see §10.6).
- Add an artifact-naming and template appendix for the 14 required outputs.
- Fix the Seed's stale Charter reference and align the Charter's "existential/practical" wording with the protocol and GOVERNANCE.
- Replace "YES_BY_CONSTRUCTION" (l.555) with "NOT_YET_AUDITED" until qualification.
- Note that the held `MAJOR-DOCTRINAL-COMPARISON` state (STATE.yaml) may cover a resurrection study. Qualification of the protocol does not remove that hold or authorize `TFP-STRESS-2`. Both remain with the human owner.

---

## 16. QUALIFICATION DECISION

**Is `TFP_ADJUDICATION_PROTOCOL_0_1_0.md` ready to govern a second bounded stress test?**

**NO.**

**Exact remaining gate.**
1. Repair both BLOCKING items (R1, R2).
2. Repair the MAJOR items (R3–R15). The project lead may defer a specific MAJOR item only by documenting an explicit scope limitation that excludes the affected claim types from the stress test. For example, R3 can be deferred only if the stress test contains no miracle or revelation claim, and R6 only if it contains no philosophically heavy lane.
3. Freeze the repaired protocol and obtain a **focused independent re-audit** limited to R1–R15. It should be done by an auditor who has not seen the first-pass reasoning, using criteria frozen beforehand.

A re-audit PASS or PASS_WITH_LIMITATIONS would then allow the project lead to consider qualification. Qualification is separate from authorizing any particular study.

**Limitations that must stay attached once qualified.**
- Qualification is not authorization, and the `MAJOR-DOCTRINAL-COMPARISON` hold is unaffected.
- Any adjudication produced remains bounded and non-global (GOVERNANCE §3).
- The protocol remains provisional (`TFP-METHOD-REVISION`) until after the second stress test.

I made no repairs, began no theological study and authorized nothing.