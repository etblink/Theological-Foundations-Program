# TFP-STRESS-2 — Reviewer A S2 Human Source Relay Instructions 0.1.0

**Status:** `SOURCE_RELAY_REQUIRED_AFTER_INVALID_REVIEW`  
**Purpose:** restore Reviewer A's access to the exact three formulation sources without relaxing the review standard.

Reviewer A's prior attempt was correctly returned as `INVALID_REVIEW` because its web access was blocked. Do not substitute memory, alternate websites, or Program Lead conclusions.

## Exact session

Use only:

`session_012EWsCBUVctdyhhk3v5ZxuF`

## Exact branch

`research/tfp-stress-2-resurrection-g0`

## Human relay rule

The human operator should open the exact three URLs below in an ordinary browser and paste the relevant source text **verbatim** into the same Reviewer A session.

Do not paraphrase the source text while relaying it.

Do not add an interpretation before Reviewer A freezes its own conclusion.

### Source A — Quran 4:157 page

Exact URL:

`https://quran.com/4/157?translations=20`

Relay:
- the English translation of 4:157 shown on that page;
- the immediately displayed 4:158 context if visible, because the page presents the raising statement in direct context.

### Source B — IslamQA 10277, “Jesus in Islam”

Exact URL:

`https://islamqa.info/en/answers/10277`

Relay the complete subsection:

**“Was Jesus crucified?”**

and continue through the first substantive paragraph under:

**“Second coming of Jesus”**

This captures the substitution/resemblance account, Jesus being saved/raised, and the article's stated post-event location/future-return formulation.

### Source C — IslamQA 224199, “The crucifixion of the Messiah between Islam and Christianity”

Exact URL:

`https://islamqa.info/en/answers/224199`

Relay these complete local passages:

1. The passage in section III where the page discusses who witnessed the crucifixion and reports what Matthew/Mark/Luke say about the women later meeting Jesus.
2. The Quran 4:157–158 discussion where the page states that Jesus was not crucified and was raised.
3. The Ibn Taymiyah discussion explaining that some disciples/People of the Book could sincerely have believed Jesus was crucified while being mistaken, including the immediately following substitution/confusion alternatives.

These passages are all relevant to the narrow question whether the permitted native/traditional material actually contains or clearly implies:
- mistaken crucifixion/death attribution;
- later access to living Jesus;
- transmission of that access into the founding movement.

## Relay completion message

After pasting all three source extracts, append exactly:

> The material above is a human-operator verbatim relay from the three exact formulation-source URLs authorized by `TFP_STRESS_2_REVIEWER_A_S2_STEELMAN_FIDELITY_REVIEW_PROMPT_0_1_0.md`. Do not use any other external source. Please rerun that review now, treating these relayed texts as the permitted source material. Preserve the same required report structure and dispositions. If the relayed material is still insufficient to make the requested fidelity determination, return `INVALID_REVIEW` again and explain exactly what source text is missing.

## Independence safeguard

The Program Lead has re-accessed the exact sources only to identify which passages must be relayed. Reviewer A must make the candidate-status decision independently.

Do not relay:
- the Program Lead's recommendation;
- the Program Lead's interpretation of whether the access chain is satisfied;
- unrelated historical evidence for or against crucifixion/resurrection.

## Authorization boundary

```text
G0_AUTHORIZED = NO
G1_AUTHORIZED = NO
SUBSTANTIVE_EVIDENCE_ACQUISITION = NO
THEOLOGICAL_OUTCOME = NONE
S2_STATUS = UNRESOLVED_PENDING_VALID_REVIEWER_A_FIDELITY_REVIEW
WAVE_1_PACKET_FREEZE = BLOCKED
```
