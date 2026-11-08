# Method Families

Use this reference after routing the question type. Method families are not research modes; they are ways to reduce uncertainty.

For each method family, specify fit, output, evidence boundary, common bias, AI role, and when to escalate.

## 1. AI-assisted scoping and prompt-based exploration

Best for:
- turning a broad topic into subquestions
- generating hypotheses and rival hypotheses
- identifying source categories and search queries
- designing extraction fields
- preparing prompts for ChatGPT, Claude, DeepSeek, Perplexity, Deep Research, or internal tools

Typical output:
- narrowed research objective
- hypothesis map
- source map
- prompt set
- extraction schema
- adversarial critique checklist

Evidence quality:
- weak directional evidence unless grounded in cited, checkable, independent sources

Common bias:
- hallucinated claims
- overgeneralized priors
- model agreement mistaken for independent evidence
- false precision in synthesis

AI role:
- scoping, query expansion, extraction draft, clustering, critique, synthesis audit

Human role:
- verify sources, judge relevance, check omissions, decide escalation

## 2. Desk research and source scan

Best for:
- fast orientation using public sources, official documents, filings, articles, policy releases, papers, company pages, reviews, or databases

Typical output:
- source list
- claim table
- timeline
- key actors and controversies
- open evidence gaps

Evidence quality:
- weak to moderate, depending on source credibility, independence, and auditability

Common bias:
- using visible sources only
- relying on secondary summaries
- stale information
- search-result ranking bias

AI role:
- generate source categories, queries, search strings, source extraction tables, and contradiction checks

## 3. Structured case sampling

Best for:
- empirical comparison of companies, products, creators, campaigns, users, markets, or operators

Typical output:
- sample buckets
- extraction fields
- coded case table
- pattern and counterexample map

Evidence quality:
- weak to moderate; strong only when sample logic is robust and observations are rich

Common bias:
- winner-only bias
- convenience samples
- survivorship bias
- comparing non-comparable cases

AI role:
- propose sample buckets, design extraction fields, normalize case notes, identify anomalies

## 4. Artifact deep dive

Best for:
- understanding the operating system behind visible outcomes through documents, release notes, product surfaces, reviews, hiring pages, pricing, changelogs, community posts, transcripts, or sales materials

Typical output:
- artifact inventory
- process reconstruction
- timeline
- operating-system hypotheses

Evidence quality:
- moderate when artifacts are rich, recent, and directly tied to behavior

Common bias:
- treating polished marketing artifacts as operational truth
- missing private process
- overinterpreting surface features

AI role:
- extract structured fields, cluster themes, compare artifacts, identify missing process evidence

## 5. Expert or operator interviews

Best for:
- validating whether observed patterns reflect real mechanisms, constraints, incentives, or hidden workflows

Typical output:
- interview guide
- evidence table by respondent
- confirmed and rejected hypotheses
- mechanism updates

Evidence quality:
- moderate, sometimes strong, depending on respondent quality, independence, specificity, and triangulation

Common bias:
- expert overconfidence
- retrospective rationalization
- small-N bias
- incentives to present a narrative

AI role:
- draft interview guides, generate probes, code transcripts, identify contradictions

## 6. User or customer research

Best for:
- understanding needs, alternatives, behavior, buying criteria, pain intensity, workflows, and willingness to change

Typical output:
- user segments
- job-to-be-done map
- pain and alternative table
- adoption barrier map

Evidence quality:
- moderate when interviews are specific and behavior-grounded; weaker when users speculate about future behavior

Common bias:
- stated preference bias
- leading questions
- recruiting biased users
- confusing enthusiasm with willingness to pay

AI role:
- interview script, transcript coding, segment comparison, quote extraction, bias check

## 7. Survey, panel, or quantitative study

Best for:
- estimating distributions, prevalence, segment differences, or directional correlations across a defined population

Typical output:
- survey instrument
- sample plan
- response table
- segment analysis

Evidence quality:
- weak to strong depending on sampling, question wording, response quality, and analysis design

Common bias:
- bad sampling frame
- leading questions
- non-response bias
- confusing stated preference with behavior

AI role:
- draft survey questions, identify leading wording, create analysis plan, summarize open text

## 8. Experiment or field test

Best for:
- causal questions in products, pricing, growth, messaging, conversion, workflows, or behavior change

Typical output:
- experiment design
- success metric
- test plan
- analysis plan
- decision rule

Evidence quality:
- potentially strong decision-grade evidence when well-designed and sufficiently powered

Common bias:
- underpowered test
- wrong metric
- interference effects
- novelty effects
- poor randomization

AI role:
- draft test variants, identify confounds, design measurement plan, prepare analysis checklist

## 9. Database or quantitative analysis

Best for:
- market, company, usage, financing, hiring, pricing, traffic, transaction, or operational data questions

Typical output:
- data source map
- variable definition
- query or analysis plan
- charts or tables
- sensitivity checks

Evidence quality:
- moderate to strong depending on data provenance, completeness, and measurement validity

Common bias:
- proxy variable mismatch
- missing data
- stale data
- aggregation hiding segment variation

AI role:
- propose variables, write query drafts, design tables, identify proxy risks

## 10. Literature review or academic scan

Best for:
- questions with established research literature, known constructs, empirical studies, or causal models

Typical output:
- paper map
- theory and evidence summary
- study quality table
- unresolved debate map

Evidence quality:
- weak to strong depending on study quality, replication, external validity, and recency

Common bias:
- cherry-picking papers
- ignoring publication bias
- overgeneralizing lab findings
- relying on abstracts only

AI role:
- search query design, paper triage, extraction table, finding contradiction checks

## 11. Adversarial review or red team

Best for:
- high-stakes decisions, fragile causal chains, investment memos, strategy choices, or abstract future scenarios

Typical output:
- fragile assumptions
- counterexamples
- rival explanations
- falsification tests
- escalation recommendation

Evidence quality:
- improves robustness but is not direct evidence unless paired with source checks

Common bias:
- performative skepticism
- inventing objections without discriminating evidence
- confusing uncertainty with falsity

AI role:
- act as independent critic, rival model, assumption auditor, or synthesis auditor

## 12. Monitoring system

Best for:
- future-oriented, policy, market, technology, regulation, or competitive questions where a one-time answer will decay

Typical output:
- leading indicators
- trigger thresholds
- source cadence
- revisit schedule
- update rules

Evidence quality:
- moderate to strong for decision support when indicators are valid and review cadence is realistic

Common bias:
- tracking easy indicators instead of causal indicators
- thresholds that are too vague
- no owner or update cadence

AI role:
- propose indicators, source feeds, trigger logic, and update templates

## Selection rule

Choose the smallest combination of method families that can reduce uncertainty for the decision. Do not stack methods for sophistication. Add heavier methods only when the current phase cannot resolve the decision-relevant uncertainty.
