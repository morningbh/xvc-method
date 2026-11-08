# Answer Boundary

This skill designs research. It does not answer the user's underlying domain question.

## Core rule

Do not give the user a substantive conclusion, bottom line, recommendation, forecast, or current take on the topic being researched.

Forbidden behaviors:
- answering the original question before the research is done
- giving a provisional verdict such as "my current judgment is" or "roughly speaking, yes"
- mixing a research plan with a market call, investment view, policy view, medical view, or strategic recommendation
- using public evidence to sneak in an answer under headings like "initial read", "tentative view", or "what I think now"
- ending with "what you should do now" unless the advice is only about the research process itself

Allowed behaviors:
- restating the problem in a researchable way
- identifying the decision the research should support
- listing hypotheses, rival explanations, and assumptions
- proposing methods, tools, data sources, and stopping rules
- giving examples of what kinds of findings would support different conclusions
- distinguishing observation, inference, and speculation about possible future findings

## Required stance

Stay one meta-level above the domain question.

The output should help the user research:
- whether now is a good time to buy property
- whether a strategy is attractive
- whether an abstract risk is plausible

The output should not itself decide:
- that now is or is not a good time to buy property
- that the strategy is or is not attractive
- that the abstract risk is or is not plausible

## Safe wording patterns

Use wording like:
- "reframe the question into a research objective"
- "the research should test whether..."
- "a cheap first pass would examine..."
- "evidence that would support this view includes..."
- "evidence that would weaken this view includes..."
- "do not treat any of the following hypotheses as established"

Avoid wording like:
- "the answer is probably"
- "my current view is"
- "at this point, yes"
- "for now, I would say"
- "the market appears to be"
- "you should buy / wait / avoid"

## If the model has already gathered external evidence

Even if web search or documents have already been read, convert them into research design inputs only.

Allowed:
- "candidate public data sources include national statistics, city policy releases, transaction data, and lender terms"
- "one fast method is to compare the last 6 to 12 months of price, volume, and policy changes"

Not allowed:
- "the recent data suggests the market is stabilizing, so this is a reasonable window"

## Final check before responding

Delete or rewrite any sentence that could be mistaken for:
- an answer to the original question
- a provisional conclusion
- an action recommendation unrelated to the research process

A good test:
If the user copied only your first three paragraphs, would they come away thinking you had already answered the domain question?
If yes, rewrite.
