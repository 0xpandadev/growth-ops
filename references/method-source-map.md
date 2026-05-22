# Method Source Map

Use this file to prevent "name-only" references. Each external method must change the output.

## Rule

For every method source used, translate it into:

```text
source -> essence -> diagnostic question -> output effect -> misuse warning
```

## Source Map

| Source family | Essence | Diagnostic question | Output effect | Misuse warning |
|---|---|---|---|---|
| Exa Docs / Contents API | AI-native discovery should retrieve, extract, and structure source content, not just list links | What exact fields must be extracted from each source? | Add search query, accepted sources, extracted fields, and evidence URL | Treating search results as verified facts |
| Exa Websets / Websets API | Build verified, enriched, monitorable datasets of entities | What entity set, criteria, enrichments, and update cadence are needed? | Add candidate dataset, verification criteria, enrichments, monitor cadence, and export shape | One-off browsing with no repeatable dataset |
| YC Essential Startup Advice | Launch, talk to users, do things that do not scale, find users who love it, avoid fake work | What can be tested manually with real users this week? | Add manual-first validation and narrow first-customer test | Using YC language to justify vague startup hype |
| YC Requests for Startups | RFS identifies fertile problem spaces and "why now" shifts | Which RFS-like change makes this opportunity timely? | Add why-now thesis, problem owner, first wedge, and validation path | Copying a hot theme without a buyer |
| Sequoia PMF | Different PMF paths require different operating priorities | Is this Hair on Fire, Hard Fact, or Future Vision? | Add PMF archetype and matching GTM/education/pit-stop plan | Treating every idea as urgent pain |
| a16z AI / marketplace | Category maps, systems of intelligence, AI market structure, network/marketplace dynamics | What is the control point or system-of-intelligence wedge? | Add market map, control point, and category thesis | Name-dropping AI without workflow or data advantage |
| NFX Network Effects Manual | Network effects are a mechanism, not a slogan | Does product value increase as participants/data/services join? | Add defensibility mechanism, network type, and cold-start risk | Calling any community or marketplace a network effect |
| Reforge Growth Loops | Growth loops compound; funnels create silos | What output from one cycle feeds the next cycle? | Add loop input/action/output/reinvestment metric | Linear acquisition funnel with no retention or reinvestment |
| OpenView PLG | Product usage drives acquisition, conversion, expansion when conditions fit | Can users experience value before sales intervention? | Add PLG fit check, activation, time-to-value, product-qualified signal | Applying PLG when buyer/user or product value path does not support it |
| Bain Elements of Value | Customers buy objective and subjective value, not only features/price | Which value elements matter most to this buyer? | Add value proposition and willingness-to-pay logic | Competing only on price/performance |
| JTBD / ODI | Customers hire solutions to make progress in specific circumstances | What job, trigger, workaround, and desired outcome are present? | Add customer job, alternatives, and outcome metric | Confusing persona demographics with actual demand |
| CB Insights Mosaic | Private-company health can be scored across money, market, momentum, and management | Which of the 4M signals are strong, weak, or missing? | Add 4M scorecard and confidence level | Treating a single score as truth |
| CB Insights Private Company Health | Non-traditional signals reveal financial, industry, HR, competitive, investor, and product-awareness strength | Which non-traditional signal changes the view? | Add health signal table and contradiction notes | Funding or PR treated as demand proof |
| 6sense Scores | Account priority should separate fit, intent, buying stage, and action | Is the account in-market, a fit, both, or neither? | Add ICP fit, intent, stage, trigger, and next action | Contacting high-fit accounts with no timing signal |
| Clay Account Scoring | Custom scores should combine arbitrary first/third-party data points and trigger workflows | Which custom fields actually predict actionability? | Add custom scoring formula, enrichment fields, routing action | Generic firmographic score with no workflow |
| SignalFire / Harmonic / PitchBook / Dealroom | Private-market signals include hiring, funding, team, growth, category, web traction, and investor activity | Which signal is leading vs lagging? | Add signal stack, source table, and breakout/watchlist status | Mistaking database availability for ground truth |
| Gartner Hype Cycle | Trend analysis needs maturity, expectation, and adoption-stage discipline | Is this trigger, peak, trough, slope, or plateau? | Add maturity stage, adoption risk, and timing implication | Buying hype at the peak |
| PESTEL | External context changes demand, cost, risk, compliance, or timing | Which macro factor changes the decision? | Add external factor, business impact, time horizon, watch signal, hedge | Listing macro trends without action |
| Porter Five Forces | Market attractiveness depends on suppliers, buyers, substitutes, entrants, and rivalry | Which force compresses profit? | Add industry structure and profit-pool pressure | Market size analysis with no competitive economics |
| Value Chain | Strategy must locate where value is created, lost, delayed, or duplicated | Which activity creates customer value or avoidable cost? | Add activity map, cost/value leak, bottleneck, improvement owner, KPI | Drawing process boxes without cost/value logic |
| VRIO / Resource-Based View | Durable advantage requires valuable, rare, hard-to-imitate resources organized for capture | Is this real capability or just an asset? | Add capability score, proof, moat risk, investment needed | Calling data, brand, or community a moat without evidence |
| Porter Generic Strategy / Strategic Groups | Positioning requires tradeoffs and a clear competitor set | Is the company competing on cost, differentiation, focus, or an unstable mixture? | Add basis of competition, strategic group, tradeoff, white-space segment | Recommending everything to everyone |
| BCG Growth-Share / GE-McKinsey Matrix | Portfolio choices should allocate resources by market attractiveness, competitive strength, and cash role | Which unit should invest, hold, harvest, fix, or exit? | Add portfolio action, cash role, resource allocation, exit/scale logic | Labeling "stars/cows/dogs" without a resource decision |
| McKinsey Three Horizons | Growth portfolio should separate core improvement, adjacent growth, and future options | Is this H1, H2, or H3 and what governance fits it? | Add horizon portfolio and resource allocation logic | Treating speculative bets like core operations |
| McKinsey 7S | Execution failure often comes from misalignment across strategy, structure, systems, skills, staff, style, and shared values | Which S blocks execution? | Add alignment gap, required state, action, owner, adoption risk | Assuming strategy wording changes behavior |
| Balanced Scorecard | Strategy execution needs financial, customer, internal-process, learning/innovation, people, and ESG measures | Which KPI proves the strategy is working? | Add objective, perspective, KPI, baseline, target, owner, cadence | Too many KPIs with no decision rights |
| Customer Segmentation / Journey Analysis | Customers experience episodes, not internal org silos | Which segment and journey step changes conversion, retention, satisfaction, or cost-to-serve? | Add segment, episode, pain/waste, metric affected, fix | Persona labels without behavior or economics |
| Scenario Analysis / Contingency Planning | Plans need plausible futures, no-regret moves, hedges, options, and trigger points | Which uncertainty should change the plan? | Add scenario table, assumptions, no-regret moves, hedges, signposts | Generic base/upside/downside with no trigger |
| Change Management | Execution requires behavior change, risk mitigation, communication, training, incentives, and adoption metrics | Who must change behavior and why might resistance be rational? | Add stakeholder, required behavior, friction, enablement, adoption metric | Confusing approval with adoption |
| Gartner / Forrester / IDC | Categories, maturity curves, and buyer criteria shape budgets | Is this emerging, mainstreaming, or declining? | Add adoption stage, buyer criteria, and maturity risk | Treating analyst category labels as customer pain |
| McKinsey / BCG / Bain | Issue trees, operating model, transformation cadence, value tracking | What decision and value-at-stake does the work affect? | Add issue tree, roadmap, owner, KPI, value tracking | Pretty framework with no owner or measurable result |
| KKR Capstone | Value creation starts in diligence, becomes a plan, and is driven on the ground through specific levers | Which lever creates measurable value and who owns it? | Add value thesis, lever stack, owner/KPI/deadline table, 100-day cadence | "PE-style" plan without baseline, owner, or KPI |
| Vista Value Creation | Software businesses improve through disciplined operating excellence, best practices, AI capacity, talent, and governance | Which software operating metric or AI/workflow lever should improve? | Add GTM/product/CS/process metrics, AI readiness, talent/governance gaps | Applying generic PE levers to software without software metrics |
| Thoma Bravo | Software specialization plus operational expertise should tighten profitability, focus, packaging, retention, and add-on integration | Which software performance lever improves durable value? | Add retention, pricing, product focus, support efficiency, integration checks | Cutting cost without protecting product/customer quality |
| CD&R | Operating partners and partnership orientation help improve owner-led or legacy businesses without destroying trust | Which stakeholder alignment or operating partner role is needed? | Add management partnership, owner transition, industry-specific workstream | Treating founder/family businesses like anonymous assets |
| EQT Motherbrain | AI and data augment human judgment across sourcing, diligence, and value creation | What entity dataset, signal, and human review loop improves the decision? | Add dataset, signal score, monitoring cadence, human review, value loop | Treating AI scores as decisions |
| Apollo APPS | Generalist operating partners plus deep functional expertise can unlock cross-functional transformation | Which generalist owner and functional specialist lanes are needed? | Add workstreams, specialist needs, transformation opportunities, governance | One narrow fix when the bottleneck is cross-functional |
| Bain PE Value Creation | Investor/management alignment and delivery assurance turn thesis into measurable value | Are management and owner aligned on what value is being delivered? | Add value alignment, delivery assurance, workstream governance, benefits tracking | Strategy without execution assurance |
| CFI Valuation Methods / Damodaran / IB | Value depends on cash flows, risk, comps, assumptions, and sensitivity | Which valuation method and driver are appropriate? | Add DCF/comps/precedent/asset lens, sensitivity, and downside | Precise valuation from weak inputs |
| Alibaba | Data middle platform links business domains, governance, quality, security, and utilization | Are data islands blocking operation or AI? | Add business data map, ownership, quality, and operating dashboard | Building AI before data and process readiness |
| Tencent | Customer touchpoints, identity, messaging, payments, and mini-program ecosystems create operating leverage | Where does the customer relationship live? | Add customer touchpoint OS and repeat-purchase loop | Treating social/community as pure content |
| ByteDance | Recommendation, experimentation, and rapid product/content feedback loops drive iteration | What is the weekly hypothesis, metric, rollout rule, and kill rule? | Add experiment cadence and metric dashboard | More content volume without learning loop |
| Palantir Ontology | Business objects, states, links, actions, permissions, and functions turn data into operations | What are the objects, states, actions, and decisions? | Add ops ontology and action model | Dashboard without operational action |
| OpenAI / Anthropic agents | Use agents for complex judgment, unstructured data, tools, guardrails, and evals; start simple | Is this deterministic automation, workflow, or agent? | Add agent/workflow fit, guardrails, evals, human handoff | Multi-agent overbuild before simple workflow proves value |
| 中小企業庁 / 活性化協議会 | SME succession and regeneration require practical cash, debt, profit, and support logic | Is the core business viable and financially constrained, or structurally broken? | Add succession/regeneration checks and specialist escalation | Growth plan before survival and creditor reality |

## Review Checklist

When using an external method, confirm:

- Does the method change the conclusion?
- Does it produce a concrete field in the output?
- Does it introduce a test, metric, or falsifier?
- Is the method appropriate for a small company or solo operator?
- Did we avoid claiming private or proprietary access?
