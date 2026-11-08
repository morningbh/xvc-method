# Kill Ladder

Use this reference to convert a research plan into a sequence of cheap tests with explicit kill, preserve, and escalate criteria.

## Core idea

Research should not escalate because a topic is interesting. It should escalate only because the unresolved uncertainty still dominates the decision.

Every phase must have three possible outcomes:

### Kill
The keystone assumption is likely false, irrelevant, or already fully priced. Stop, redirect, or downgrade the research.

### Preserve
The keystone assumption remains plausible after the cheapest credible test, but evidence is not yet strong enough for decision-grade confidence.

### Escalate
The keystone assumption remains decisive, but available evidence is insufficient, contradictory, stale, or dependent on hidden facts. Move only to the next method that tests the unresolved link.

## Cheapest credible test

A cheap test is credible when it can materially change the research path even if it cannot fully answer the question.

Good cheap tests often include:
- reverse-engineering embedded expectations
- checking official documents or primary sources
- comparing recent data to a base rate
- identifying whether an assumption is already contradicted by observable evidence
- testing a single causal link rather than the whole thesis
- using AI to design extraction fields, not to invent evidence

Bad cheap tests include:
- reading many secondary summaries with no extraction schema
- asking experts broad opinion questions before isolating the key link
- building a complex model before knowing which variable matters
- generating a long list of sources without kill criteria

## Phase template

| phase | link tested | method | cost/time | kill evidence | preserve evidence | escalate trigger | postponed work |
|---|---|---|---|---|---|---|---|

## Default sequence

1. Keystone selection
   - Output: keystone uncertainty and what-has-to-be-true chain
   - Kill: the question is not decision-relevant or cannot be made falsifiable
   - Preserve: one uncertainty dominates and can be cheaply tested
   - Escalate: decision boundary is unclear; run short intake

2. Embedded-expectation or base-rate test
   - Output: what is already assumed by price, strategy, market consensus, or prior evidence
   - Kill: the attractive thesis requires extreme assumptions that are unsupported
   - Preserve: the embedded expectation appears modest or contestable
   - Escalate: embedded expectations are hard to infer or sources conflict

3. Mechanism test
   - Output: whether the mechanism can plausibly sustain the required outcome
   - Kill: a key link is contradicted by evidence
   - Preserve: links remain plausible and no obvious contradiction appears
   - Escalate: link depends on hidden data, expert knowledge, or primary evidence

4. Rival explanation test
   - Output: the strongest alternative explanation and evidence needed to distinguish it
   - Kill: the rival explanation explains the evidence better
   - Preserve: the original chain remains competitive
   - Escalate: both explanations fit; collect discriminating evidence

5. Heavier validation
   - Output: expert calls, structured sample, database analysis, experiment, or field test
   - Kill: primary evidence contradicts the thesis
   - Preserve: primary evidence supports the key link with limits
   - Escalate: decision is high-stakes and further confidence is worth the cost

## Evidence wording

Use:
- "evidence that would kill this path"
- "evidence that would preserve this path"
- "evidence that would justify escalation"

Avoid:
- "more research is needed" without specifying what uncertainty remains
- "deep dive" without defining the tested link
- "expert validation" without defining the exact assumption to test

## Stop rule

Stop or postpone when:
- the keystone assumption fails
- the decision would not change after more light research
- the remaining uncertainty is not decision-dominant
- the next method costs more than the decision value justifies
- the work would improve narrative completeness but not conclusion quality
