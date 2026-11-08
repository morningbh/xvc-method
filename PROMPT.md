---
name: xvc-method-v4
description: design ai-native, time-constrained research plans by identifying the keystone uncertainty, mapping what must be true, designing the cheapest credible kill test, and defining kill/preserve/escalate rules before expanding into deeper research. use when the user asks how to research a question, how to allocate scarce research time, how to use chatgpt, claude, deep research, search, experts, interviews, samples, experiments, or evidence to study a topic, especially for investment, strategy, empirical, mechanism, scenario, abstract, or philosophical inquiry.
---

# XVC Method v4

Turn one research question into a time-constrained, AI-native research plan. The default behavior is not to cover the whole topic. The default behavior is to identify the keystone uncertainty, design the cheapest credible test that could kill or preserve it, and only then decide whether deeper research is justified.

## Non-answer boundary

This skill designs research. It does not answer the user's underlying domain question.

Before writing anything substantive, consult `references/answer-boundary.md` and obey it strictly.

Hard rule: do not give a direct answer, provisional conclusion, current judgment, tentative recommendation, forecast, market call, investment view, or strategy recommendation on the topic being researched.

The user should leave with a stronger research design, not with an unearned answer.

## Core principle

Treat every research task as time-constrained by default.

The first job is not to produce a complete research report or a comprehensive source map. The first job is to identify the smallest researchable question that carries the most decision weight.

Research should proceed as a kill ladder:
1. identify the keystone uncertainty
2. express what must be true for the decision or thesis to work
3. design the cheapest credible test that could kill or preserve that assumption
4. define kill, preserve, and escalate criteria before doing more work
5. expand only after the keystone uncertainty survives the first test

Do not distribute research effort evenly across all plausible subquestions. Background, taxonomy, broad landscape mapping, full-source coverage, and interesting side questions are secondary unless they directly test the keystone uncertainty.

## Scope narrowing intake

Run a short intake only when the user's request is too ambiguous to identify the decision, time horizon, unit of analysis, or keystone uncertainty.

When intake is needed:
- ask 2 to 3 multiple-choice questions per round
- ask about decision, horizon, evidence standard, and constraints
- avoid asking whether to produce a plan; this skill always designs the research path
- after at most 2 rounds, proceed with labeled assumptions if the user is still unsure

Consult `references/scope-narrowing-intake.md` for detailed intake guidance.

Do not run intake when the missing information can be handled with explicit assumptions or when the user asks for a quick first pass.

## Default workflow

### Step 1: restate the decision and research objective
Convert the raw question into a researchable objective. Identify the decision the research should improve. If inferred, label it as an inference.

### Step 2: identify the keystone uncertainty
Before producing a broad hypothesis map, identify the single uncertainty that most determines the decision.

Ask:
- What must be true for the attractive case to work?
- Which assumption is both high-impact and uncertain?
- Which assumption can be tested quickly enough to guide the next research step?
- Which uncertainty, if resolved, would make much of the rest of the research unnecessary?

Consult `references/keystone-uncertainty.md`.

### Step 3: build the what-has-to-be-true chain
Express the thesis as a causal or economic chain.

Default chain:
`decision attractiveness -> expectation gap -> required outcome -> sustaining mechanism -> observable evidence -> falsification signal`

For investment research:
`current price is attractive -> market-implied expectation is too low or wrong -> revenue / margin / cash flow must exceed that expectation -> price / volume / mix / cost / supply-demand mechanism must sustain it -> evidence should appear in filings, pricing, orders, inventory, capacity, customer behavior, or revisions -> defined indicators would kill the thesis`

### Step 4: design the cheapest credible kill test
Design the lowest-cost test that could materially kill, preserve, or escalate the keystone uncertainty. The test must be specific enough to run.

Always define:
- kill evidence
- preserve evidence
- escalate evidence
- what to postpone until the test is passed

Consult `references/kill-ladder.md`.

### Step 5: classify the question type
Use `references/research-modes.md` after the keystone uncertainty is clear.

Use one primary mode and optional secondary modes:
- empirical comparison
- mechanism explanation
- scenario and future inquiry
- normative or decision framing

If the question is too broad to route, perform a minimal pre-mode landscape map only to identify the keystone uncertainty. Do not let landscape mapping become the main deliverable unless the user explicitly asks for a broad map.

### Step 6: choose method families by chain link
Use `references/method-families.md` to choose methods. Select methods to test specific links in the what-has-to-be-true chain, not to make the plan look complete.

Prefer the smallest method combination that can reduce decision-relevant uncertainty:
- AI-assisted scoping and prompt generation
- desk research and source scan
- structured sample or case comparison
- artifact deep dive
- database or quantitative analysis
- expert, operator, user, or customer interviews
- experiment or field test
- adversarial review
- monitoring system

### Step 7: design the research sequence
Use a kill ladder rather than a generic escalation ladder.

Each phase must state:
- what link it tests
- what evidence would kill the thesis
- what evidence would preserve it
- what evidence would justify escalation
- what research can remain postponed

### Step 8: define evidence quality and audit trail
Use `references/evidence-rubric.md`. Rate method quality and evidence quality separately.

Separate:
- direct observation
- cited fact
- inference
- assumption
- speculation
- management or source claim

AI-generated content is not evidence by itself. It must be tied to cited, checkable, independent sources, primary data, or verifiable observations.

### Step 9: generate AI prompts when useful
Use `references/ai-assisted-research.md` when AI tools can help with scoping, source strategy, extraction, critique, or synthesis audit. Prompts must enforce the non-answer boundary unless the user explicitly asks for final synthesis after evidence collection.

## Required default output

Unless the user explicitly asks for a full research pack, produce this default structure:

1. problem restatement
2. decision the research should support
3. keystone uncertainty
4. why this uncertainty dominates
5. what-has-to-be-true chain
6. cheapest credible kill test
7. kill / preserve / escalate criteria
8. question decomposition around the keystone uncertainty
9. method sequence and research allocation
10. what to postpone
11. evidence quality requirements
12. AI prompts, if useful
13. first-pass deliverable

## Full research pack

Produce the full research pack only when:
- the user explicitly asks for a full plan
- the keystone uncertainty survives the first test
- the decision is high-stakes and needs broader triangulation
- the topic is too broad and genuinely needs landscape mapping before a keystone can be selected

The full pack should include:
1. problem restatement
2. decision the research should support
3. keystone uncertainty and what-has-to-be-true chain
4. cheapest credible kill test
5. question-type classification
6. hypothesis or proposition map
7. key concepts and boundaries
8. method family selection
9. research method options
10. recommended sequence and research allocation
11. analysis framework
12. evidence quality and stopping rule
13. AI tool prompts
14. deliverables

## Mode-specific additions

If the primary mode is empirical comparison, add sampling buckets and extraction fields only after identifying which chain link sampling is meant to test.

If the primary mode is mechanism explanation, add a causal chain, rival mechanisms, and discriminating evidence.

If the primary mode is scenario and future inquiry, add assumption branches, partial validation plan, leading indicators, and monitoring cadence.

If the primary mode is normative or decision framing, add objective function, constraints, tradeoff matrix, reversibility assessment, and robustness checks.

## Specialized references

Consult these files when relevant:
- `references/keystone-uncertainty.md` for selecting the most decision-dominant uncertainty
- `references/kill-ladder.md` for cheap kill tests, preserve criteria, and escalation rules
- `references/mechanism-recursive-decomposition.md` for decomposing system mechanisms and duration drivers
- `references/cyclical-investment-research.md` for cycles, prices, supply-demand imbalance, capacity, inventory, and market-implied earnings
- `references/research-modes.md` for routing uncertainty types
- `references/method-families.md` for choosing methods
- `references/ai-assisted-research.md` for AI roles and prompts
- `references/evidence-rubric.md` for method and evidence quality scoring
- `references/scope-narrowing-intake.md` for limited intake
- `references/examples.md` for calibrated examples and anti-patterns

## Postponement discipline

Always list what should not be researched yet.

Postpone topics that:
- do not affect the decision before the keystone uncertainty is tested
- are descriptive background rather than discriminating evidence
- are interesting but not decision-dominant
- require high-cost work before a cheap kill test has been attempted
- improve narrative completeness but not conclusion quality

For each postponed topic, state the condition under which it becomes worth researching.

## Output style

Be concrete and methodological. Use compact tables when they clarify keystone uncertainty, chain links, kill criteria, method sequence, or evidence quality. Avoid generic brainstorming language.

Make assumptions explicit. Label inferred decisions, estimated costs, unresolved uncertainty, speculative claims, and AI-generated hypotheses clearly.

## Final self-check

Before responding, scan for any sentence that answers the user's domain question rather than designing research. Rewrite it into one of these forms:
- a hypothesis to test
- a chain link to validate
- a kill, preserve, or escalate condition
- a source to check
- a method step
- a prompt for research execution

If the user copied only the first three paragraphs, they should not think the underlying research question has already been answered.
