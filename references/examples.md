# Worked Examples

Use these examples to calibrate v4 output. Do not copy rigidly. Always obey the non-answer boundary: design research, do not answer the underlying question.

## Anti-pattern: complete but unfocused research plan

Bad behavior:
- start with a full landscape map
- list every plausible research method
- distribute effort evenly across subquestions
- give a provisional market or strategy view
- recommend deeper research without a kill criterion

Good behavior:
- identify the keystone uncertainty first
- express what must be true
- design a cheap kill test
- define kill, preserve, and escalate criteria
- postpone non-dominant work

## Example 1: cyclical investment research

### User question
I want to research whether two memory companies are still worth medium-term allocation.

### Good v4 routing
Primary mode: normative or decision framing
Secondary modes: scenario inquiry and mechanism explanation
Special reference: `cyclical-investment-research.md`

### Keystone uncertainty
Whether current stock prices have already priced a long enough high-memory-price cycle, or whether the market is underpricing how long supply-demand tightness can persist.

### Why this dominates
If the required price and margin cycle is already fully priced, strong current demand does not create attractive risk/reward. If the market has underpriced cycle duration, the research should test the supply-demand mechanism that could extend the cycle.

### What-has-to-be-true chain
`current price is attractive`
`-> market-implied duration of high memory prices is too short`
`-> high prices and margins persist longer than consensus expects`
`-> demand remains real consumption rather than mostly inventory build`
`-> supply response is delayed by capacity, technology migration, or bottlenecks`
`-> price, inventory, capex, and customer indicators preserve the thesis`

### Cheapest credible kill test
1. Reverse-engineer the stock price into implied revenue, gross margin, EPS, FCF, and cycle duration.
2. Compare implied cycle duration with past memory price cycles and expansion lead times.
3. Check whether demand evidence indicates consumption or pull-forward inventory.
4. Identify the first 5 to 8 indicators that would show pricing tightness is ending.

### Kill / preserve / escalate
| outcome | evidence pattern |
|---|---|
| Kill | current price already requires an unusually long high-price cycle, and inventory/capex/price indicators show tightening is peaking |
| Preserve | current price implies only a modest cycle duration, while supply response appears slow and demand evidence is consumption-led |
| Escalate | public data cannot distinguish customer consumption from inventory build, or cannot verify true capacity lead time |

### What to postpone
- broad semiconductor taxonomy
- full company history
- management biography
- non-core end-market details
- precise target price
- expert calls before the implied-cycle test is complete

## Example 2: product strategy research

### User question
How should I research whether to build an AI workflow product for finance teams?

### Keystone uncertainty
Whether the target users have a repeated, high-stakes workflow where AI can reduce cycle time without creating unacceptable review risk.

### What-has-to-be-true chain
`product bet is attractive`
`-> users have a frequent painful workflow`
`-> current workaround is slow or expensive`
`-> AI output can be trusted or reviewed efficiently`
`-> user behavior changes from trial to repeated usage`
`-> willingness to pay follows usage`

### Cheapest credible kill test
Run 5 to 8 workflow interviews focused on the last three times the task occurred. Extract frequency, current tool stack, review burden, cost of error, switching barrier, and willingness to pay evidence.

### Kill / preserve / escalate
Kill if the workflow is infrequent, low-stakes, already solved, or requires review effort that cancels AI speed gains. Preserve if the workflow is frequent, painful, reviewable, and currently handled through costly manual work. Escalate to prototype only after behavior evidence survives.

## Example 3: abstract scenario inquiry

### User question
How should I research whether a future AI governance failure could destabilize society?

### Keystone uncertainty
Which causal link most carries the scenario: model capability, deployment incentives, institutional coordination failure, infrastructure dependency, or public trust collapse.

### Cheapest credible kill test
Map 3 to 5 plausible causal chains and identify which link is both most fragile and most testable with present evidence. Use historical analogs and current institutional evidence only for local claims; do not pretend they settle the future scenario.

### Kill / preserve / escalate
Kill a chain if it depends on a speculative link with no present proxy and no plausible monitoring signal. Preserve a chain if several local claims have analog support and clear indicators. Escalate to expert challenge only for chains that remain decision-relevant.

## Example 4: empirical comparison

### User question
How should I research what distinguishes strong technical media accounts from weak ones?

### Keystone uncertainty
Whether performance differences are mainly caused by repeatable operating choices or by pre-existing audience / distribution advantages.

### Cheapest credible kill test
Compare strong, typical, weak, and contradictory accounts using fields that can discriminate operating choices from audience inheritance: topic selection, insight density, cadence, distribution source, author credibility, post format, engagement quality, and repeatability.

### Kill / preserve / escalate
Kill the operating-playbook thesis if high performance mostly tracks inherited audience and does not correlate with observable repeatable choices. Preserve if similar operating patterns recur across independent winners and do not appear in weak cases. Escalate to operator interviews if surface artifacts cannot distinguish process from visible output.

## Example 5: fund allocation decision

### User question
How should our fund research whether to spend more time on frontier model infrastructure instead of application-layer AI?

### Keystone uncertainty
Whether the fund has a credible proprietary edge in one category that is large enough to overcome access, competition, technical evaluation, and timing constraints.

### What-has-to-be-true chain
`resource allocation shift is attractive`
`-> expected return per partner hour is higher`
`-> proprietary sourcing or judgment edge exists`
`-> investable companies are accessible at acceptable prices`
`-> technical and market risks can be evaluated better than competitors`
`-> opportunity cost versus application-layer AI is justified`

### Cheapest credible kill test
Audit the last 12 to 24 months of actual deal flow, missed deals, evaluated companies, access quality, win/loss reasons, and partner time allocation. Compare frontier infrastructure and application-layer opportunities using the same fields.

### Kill / preserve / escalate
Kill if the fund lacks access or judgment edge in frontier infrastructure and the opportunity set is mostly inaccessible. Preserve if deal quality, access, and underwriting edge are visibly better than current allocation reflects. Escalate to deeper thesis work only after internal evidence shows a real edge.
