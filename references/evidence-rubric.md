# Evidence Rubric

Rate method quality and evidence quality separately. A method can be fast and useful while still producing weak evidence. A slow method does not automatically produce strong evidence.

## Output bands

Use one final band for each proposed method:
- weak directional evidence
- moderate evidence
- strong decision-grade evidence

## Method quality dimensions

Score each as low, medium, or high.

### 1. decision relevance
Does the method directly reduce uncertainty for the decision the research is meant to support?

### 2. speed-to-insight
How quickly will the method produce useful learning?

### 3. feasibility
Can the user realistically execute this method with available time, access, tools, budget, and expertise?

### 4. information gain
How much could the method change the user's beliefs, research direction, or decision threshold?

### 5. escalation value
Will this method clearly indicate whether deeper research is needed?

## Evidence quality dimensions

Score each as low, medium, or high.

### 1. source credibility
Are sources primary, authoritative, expert, first-party, or otherwise reliable for the claim being tested?

### 2. evidence richness
Are the observations, documents, data points, interviews, or artifacts detailed enough to support analysis beyond superficial labels?

### 3. independence and triangulation
Do multiple sources provide independent support, or are they echoing the same original source, narrative, or dataset?

### 4. recency and temporal fit
Does the evidence match the relevant time window? Recent evidence is not always better; it must fit the decision horizon.

### 5. sample or case quality
For empirical comparison, does the sample include enough variation and avoid obvious selection, survivorship, winner-only, or convenience bias?

### 6. bias and confounding risk
Could the observed pattern be explained by incentives, selection effects, omitted variables, strategic disclosure, reporting bias, measurement error, or confounding factors?

### 7. causal strength
For mechanism questions, does the method test links in the causal chain, distinguish rival mechanisms, or only show correlation?

### 8. assumption transparency
For abstract, future, and decision-framing questions, are critical assumptions explicit, prioritized, and challengeable?

### 9. auditability
Can another researcher inspect the sources, extraction fields, prompts, calculations, and reasoning trail?

## AI-assisted evidence boundary

AI-generated synthesis, even if fluent and plausible, is not evidence by itself.

Default rating rules:
- AI used only for brainstorming, hypothesis generation, prompt writing, or query expansion: weak directional evidence at most.
- AI used to summarize provided sources without citations or a source log: weak directional evidence.
- AI used to extract, compare, or critique cited and checkable sources: evidence quality depends on the underlying sources and audit trail.
- AI-generated claims with no verifiable source should be tagged as hypotheses or leads, not findings.
- Multi-model agreement is not triangulation unless models rely on independent, checkable sources.

## Interpretation guidance

### weak directional evidence
Use when the method is fast and useful for orientation, but the sample is thin, sources are weak, assumptions are fragile, AI output is not source-grounded, or major causal links remain unresolved.

### moderate evidence
Use when the method has reasonable comparison logic or causal structure, credible and checkable sources, clearly labeled assumptions, meaningful counterexample search, and enough grounding to narrow plausible conclusions.

### strong decision-grade evidence
Use when the method directly supports the decision, has high-quality primary or independently triangulated evidence, serious counterargument coverage, low unresolved confounding risk, and an auditable trail.

## Stopping rule guidance

A phase can stop when all of the following are true:
- the leading hypotheses, mechanisms, or scenarios are narrower than before
- the remaining uncertainty is known and acceptable for the decision cost
- the recommendation in the eventual research deliverable would likely not reverse after one more light pass
- speculative, AI-generated, and evidence-backed parts are clearly separated
- the source and prompt trail is auditable enough for the decision context

Escalate when any of the following are true:
- multiple explanations or scenario paths fit equally well
- the sample is obviously biased or too small
- the argument depends on one or two fragile hidden assumptions
- the recommendation would change under plausible counterexamples
- the decision is high stakes, costly, or hard to reverse
- the evidence relies mainly on AI synthesis rather than primary or independently checkable sources
