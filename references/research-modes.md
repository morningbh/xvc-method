# Research Modes

Use this router before designing methods.

## Mode vs method boundary

Research modes classify the type of uncertainty in the user's question. Research methods are ways to reduce that uncertainty.

Do not treat the following as research modes:
- AI-assisted scoping or synthesis
- desk scan
- literature review
- expert interviews
- survey
- experiment
- case sampling
- database analysis
- source triangulation
- adversarial critique
- monitoring system

These are method families that can be used under different modes. Use `method-families.md` after the mode is selected.

## Pre-mode: landscape mapping

Use before selecting a primary mode when the user's question is too broad, such as "research this market", "understand this field", "map this opportunity", or "study AI agents".

Purpose:
- define the space
- identify major segments, actors, variables, and controversies
- separate descriptive, causal, future, and decision subquestions
- convert a broad topic into 2 to 5 answerable research questions

Do not let landscape mapping become the final research mode. After the map is built, route each subquestion into empirical comparison, mechanism explanation, scenario inquiry, or normative decision framing.

## 1. Empirical comparison

Use when the question can be studied through observable cases, outputs, entities, documents, cohorts, or user behavior.

Best for:
- creator, product, company, campaign, operator, user, or market comparisons
- recurring pattern detection
- performance differences
- structured sample analysis
- artifact or behavioral comparison

Typical outputs:
- sample buckets
- extraction fields
- cross-case comparison
- ranked hypotheses
- counterexamples and anomalies

Default methods:
- AI-assisted source mapping and extraction schema design
- structured case sampling
- within-entity comparison
- artifact deep dive
- database or quantitative analysis
- user/customer research
- interviews or experiments if needed

## 2. Mechanism explanation

Use when the question asks how or why something happens.

Best for:
- causal chain design
- explanation of system behavior
- decomposition of an observed pattern into links and dependencies
- generation of rival mechanisms
- distinguishing correlation from mechanism

Typical outputs:
- causal chain
- rival mechanism table
- evidence needed per link
- discriminating tests

Default methods:
- AI-assisted causal-chain and rival-chain generation
- mechanism decomposition
- targeted evidence checks on key links
- artifact deep dive
- expert or operator challenge
- adversarial review

## 3. Scenario and future inquiry

Use when the question involves futures, long horizons, uncertain worlds, existential risk, technology transition, regulation change, or states that do not fully exist yet.

Best for:
- conditional forecasting
- future strategic questions
- technology-transition questions
- philosophical problems with partial empirical hooks
- monitoring plans and trigger conditions

Typical outputs:
- assumption map
- scenario branches
- locally testable claims vs untestable claims
- leading indicators and revisit cadence
- conditional confidence, not absolute prediction

Default methods:
- AI-assisted assumption and scenario generation
- causal and rival-chain mapping
- partial validation through proxies, analogies, and adjacent domains
- expert challenge
- monitoring system design

## 4. Normative or decision framing

Use when the question is about what should be done or which option is preferable under objectives, values, and constraints.

Best for:
- strategy choice
- investment focus
- resource allocation
- prioritization under uncertainty
- tradeoff and objective clarification

Typical outputs:
- objective function
- constraint set
- tradeoff matrix
- reversibility assessment
- robust recommendation criteria for the eventual research deliverable

Default methods:
- AI-assisted option and tradeoff generation
- objective and constraint clarification
- robustness analysis
- scenario stress test
- decision-cost and reversibility analysis
- adversarial review before high-cost choices

## Hybrid rule

Many good research questions are hybrid. Example:
- "will AI tutors improve learning outcomes" can be empirical comparison plus mechanism explanation
- "could post-ASI human decline destabilize civilization" can be scenario inquiry plus mechanism explanation
- "should our fund focus on model infrastructure or application-layer AI" can be normative decision framing plus empirical comparison and scenario inquiry

When hybrid, state:
- primary mode: where the pack spends most of its effort
- secondary mode: what supports the primary mode
- which subquestions belong to each mode

## Fast routing tests

Ask these questions internally:
1. Can I observe enough real cases now to compare them directly?
2. Is the core challenge understanding a causal chain rather than a sample?
3. Is the main uncertainty about futures or states that do not yet exist?
4. Is the user really trying to make a choice under values and constraints?
5. Is the topic still too broad and therefore needs landscape mapping first?

If the answer to 1 is no, do not default to sampling. If the answer to 3 is yes, scenario inquiry is probably primary. If the answer to 4 is yes, do not hide the objective function.
