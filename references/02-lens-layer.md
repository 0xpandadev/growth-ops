# Lens Layer

The lens layer answers: which public methods should shape the analysis?

Do not use every lens. Select only what changes the decision.

## Lens Library

| Lens family | Use for | Reference files |
|---|---|---|
| VC / startup | PMF, why now, wedge, first customer, defensibility | `radar/vc-startup-lenses.md` |
| Market intelligence | market maps, category momentum, competitor landscape, private-company signals | `radar/market-intelligence.md` |
| Signal scoring systems | Mosaic, private-company health, buying stage, custom enrichment scoring | `radar/signal-and-scoring-systems.md` |
| AI-native discovery | semantic search, similar-company discovery, structured datasets | `radar/exa-style-discovery.md` |
| Customer value | JTBD, value elements, willingness to pay, PLG fit | `radar/customer-value-jtbd.md` |
| China scale ops | fast iteration, ecosystem leverage, recommendation/commerce loops, data middle platform | `radar/china-scale-signals.md` |
| SME operator | small-company reality, old businesses, cash, operations, owner dependency | `operator/sme-operator.md` |
| Turnaround | distressed company, cash crisis, debt pressure, survival plan | `operator/turnaround-cash-control.md` |
| Succession / SME M&A | business succession, search fund, acquisition, inherited company | `operator/succession-and-sme-ma.md` |
| Finance / IB | unit economics, valuation, margin bridge, sensitivity, comps | `operator/finance-and-unit-economics.md` |
| Ops ontology | business objects, workflow states, AI operations architecture | `operator/ops-ontology.md` |
| AI agent ops | agent/workflow fit, evals, guardrails, human handoff | `operator/ai-agent-ops.md` |
| Assets | articles, proposals, decks, skills, dashboards | `references/assets/*` |

## Method Sources To Remember

Use public patterns, not claims of proprietary access.

- YC: RFS, essential startup advice, tarpit ideas, manual-first validation.
- Sequoia: PMF archetypes, company-building narratives, business-plan clarity.
- a16z: market maps, AI Canon, marketplace/growth logic.
- NFX: network effects and explicit defensibility mechanisms.
- First Round / Reforge / Lenny: PMF, growth loops, retention, product growth.
- Bain / JTBD / OpenView: customer value, jobs, PLG fit, time-to-value, willingness to pay.
- CB Insights / PitchBook / Dealroom / Crunchbase: market maps, private-company signals, funding/M&A/category momentum.
- CB Insights Mosaic / private-company health: money, market, momentum, management, finance, industry, HR, competition, investor, and product-awareness signals.
- 6sense / Clay: ICP fit, buying stage, intent, custom data enrichment, next action, and dynamic account score design.
- SignalFire / Harmonic: hiring, headcount, funding, founder/team, web traction, category, and breakout-company signals.
- Gartner / Forrester / IDC: maturity, buyer criteria, adoption barriers.
- McKinsey / BCG / Bain: issue trees, transformation office rhythm, roadmap, operating model.
- Damodaran / CFI / Wall Street Prep: valuation, DCF, comps, sensitivity, finance logic.
- Palantir: ontology, operational data objects, actions, permissions, workflow.
- OpenAI / Anthropic / Glean: agent workflows, retrieval, tools, evals, guardrails, knowledge graph.
- Alibaba / Tencent / ByteDance: data middle platform, ecosystem touchpoints, recommendation/experiment-driven growth.
- 中小企業庁 / 中小企業活性化協議会 / SCORE / SBA / Stanford Search Fund: succession, SME M&A, turnaround, practical small-business operation.

## Selection Rule

If the answer becomes longer but not sharper, remove lenses.

Always ask:

- Does this lens change what the user should do?
- Does it reveal a mechanism or hidden constraint?
- Does it make the next action more testable?
