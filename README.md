# Growth Ops

**Growth Ops is an operating intelligence skill for people who need to find opportunities, make business decisions, and turn messy information into usable business assets.**

[English](./README.md) | [日本語](./docs/README.ja.md) | [中文](./docs/README.zh-CN.md)

Growth Ops is built for solo operators, founders, small companies, consultants, investors, and new-business builders who need more than a generic summary. It helps turn rough notes, URLs, company lists, market questions, customer signals, business problems, and AI workflow ideas into decision-ready outputs: market radars, opportunity cards, account scorecards, operating memos, turnaround plans, proposal briefs, dashboard specs, content plans, and skill blueprints.

It is designed around one simple idea:

```text
Do not just summarize information.
Understand the business situation, extract the signal, decide what matters, and make the next action obvious.
```

## Visual Examples

Growth Ops can produce **Growth Board** interfaces: compact knowledge UIs that make the path from signal to judgment visible. These examples are anonymized and rendered from the actual HTML examples in this repository.

<a href="./examples/growth-board-en-signal.html">
  <img src="./examples/screenshots/growth-board-en-signal.png" alt="Growth Board Signal Board example" width="100%">
</a>

<table>
  <tr>
    <td width="50%">
      <a href="./examples/growth-board-ja-score.html">
        <img src="./examples/screenshots/growth-board-ja-score.png" alt="Growth Board Japanese Score Board example" width="100%">
      </a>
    </td>
    <td width="50%">
      <a href="./examples/growth-board-zh-scenario.html">
        <img src="./examples/screenshots/growth-board-zh-scenario.png" alt="Growth Board Chinese Scenario Board example" width="100%">
      </a>
    </td>
  </tr>
</table>

## What Makes It Different

Most AI workflows stop too early. They summarize an article, list some trends, or produce a nice-looking framework. Growth Ops tries to go one layer deeper:

- What is the actual decision?
- What is fact, inference, assumption, or unknown?
- Which signals are meaningful and which are noise?
- What mechanism explains the opportunity or bottleneck?
- What should be tested this week?
- What would prove the idea wrong?
- What output would actually help someone operate, sell, invest, build, or decide?

Growth Ops is intentionally practical. It is not a "strategy theater" skill. It should produce something you can use: a ranked list, a decision memo, a scorecard, a 90-day plan, a dashboard spec, a deck brief, a proposal angle, or a repeatable workflow.

## The Three Internal Lanes

You do not need to remember modes. Ask naturally, and the skill routes internally.

```text
growth-ops
  radar    = look outside: markets, themes, competitors, accounts, partners, weak signals
  operator = look inside: business model, cash, operations, succession, turnaround, modernization
  assets   = make it usable: memos, briefs, proposals, decks, HTML, content, skill blueprints
```

### Radar

Use Radar when you want to look outside the business:

- Is this market theme real or just hype?
- Which companies, accounts, partners, or acquisition targets should I watch?
- What signals suggest momentum, timing, urgency, or budget?
- Which category is emerging, maturing, crowded, or structurally unattractive?
- What would make this opportunity a trap?

Radar borrows public-method logic from Exa-style discovery, YC, Sequoia, a16z, NFX, Reforge, Gartner Hype Cycle, Porter Five Forces, CB Insights-style market maps, PitchBook/Dealroom-style private-market signals, 6sense-style buying-stage thinking, Clay-style custom scoring, and more.

It does not pretend to have access to paid databases. Instead, it uses their operating logic: build a signal stack, verify sources, separate fit from timing, and turn scoring into action.

### Operator

Use Operator when you need to understand and improve a business from the inside:

- How should a small or old company be modernized?
- Is this business viable, cash-constrained, or structurally broken?
- What should be fixed first: sales, margin, operations, debt, workflow, or ownership?
- How should a turnaround or succession plan be structured?
- Where can AI automation help, and where would it only create complexity?

Operator is especially useful for small businesses, local businesses, legacy companies, solo businesses, distressed companies, business succession, and AI-enabled operations. It translates abstract strategy into operational reality:

- who does it
- by when
- using what data
- with what cash impact
- with what workflow change
- with what risk or fallback

### Assets

Use Assets when you need to turn analysis into something other people can read, use, or act on:

- a decision memo
- a market radar
- an account scorecard
- a proposal brief
- a note/article outline
- a slide deck brief for `smart-decks`
- an HTML dashboard spec
- a reusable skill blueprint

Assets is where Growth Ops becomes useful outside the chat window. It packages thinking into practical business artifacts.

## Growth Board: GUI For Business Judgment

Growth Ops can also turn analysis into a **Growth Board**: a decision-oriented GUI / knowledge UI. This is not a generic KPI dashboard. It is a visual surface that shows how information becomes judgment.

```text
signal -> interpretation -> decision -> action
```

You do not need to choose a board type. Ask naturally:

```text
[$growth-ops]
Turn this into a Growth Board.
<notes, company list, market theme, messy data, or workflow>
```

Growth Ops will infer the right board:

- **Auto Board**: messy input with unclear objective.
- **Signal Board**: market themes, weak signals, news, company movement.
- **Score Board**: accounts, leads, partners, investors, targets, ideas.
- **Map Board**: entities, relationships, workflows, operations.
- **Scenario Board**: pricing, AI adoption, turnaround, investment, hiring, cash.
- **Action Board**: execution, follow-up, operating cadence.

The visual grammar borrows from Palantir-style object/state/action thinking, CB Insights-style signal stacks, 6sense/Clay-style account scoring, Neo4j-style entity graphs, Runway/Pigment-style scenarios, incident.io/PagerDuty-style action workflows, and Tufte/Few-style information clarity. It should feel like a high-end operating console, not another empty SaaS dashboard.

### Growth Board Examples

Open the example HTML files locally after cloning, or serve the repository with GitHub Pages / any static server:

- [Examples index](./examples/index.html)
- [English Signal Board](./examples/growth-board-en-signal.html): market/theme signals into decision and action.
- [Japanese Score Board](./examples/growth-board-ja-score.html): anonymized account/partner scoring.
- [Chinese Scenario Board](./examples/growth-board-zh-scenario.html): small-business AI modernization scenarios.

## What You Can Ask It To Do

### 1. Market Radar

```text
[$growth-ops]
Analyze this theme. Is it a real opportunity or just hype?
Give me the market map, why-now thesis, buyer urgency, key players, weak signals,
risks, and what I should monitor next.
```

Best for:

- market research
- new-business ideas
- AI trend evaluation
- category watching
- investment themes
- "what should I build/write/watch next?"

Output:

- category definition
- market map
- signal table
- maturity stage
- opportunity thesis
- watchlist
- falsifiers
- next research actions

### 2. Account / Lead / Partner Scoring

```text
[$growth-ops]
Score this company list. Separate ICP fit, pain, timing, intent, budget proxy,
reachability, and next action. Tell me who to contact first and why.
```

Best for:

- sales targeting
- partner research
- investor targeting
- acquisition target screening
- pilot customer selection
- consulting outreach

Output:

- ranked account list
- scoring formula
- top reasons
- missing data
- confidence level
- next action by stage

### 3. Small Business Operator Memo

```text
[$growth-ops]
Assume I am taking over this old small business.
Diagnose the business and give me a practical 90-day operating plan.
```

Best for:

- small-business management
- business succession
- local/legacy company modernization
- distressed company review
- cash and margin diagnosis

Output:

- business diagnosis
- cash / margin / customer / workflow risks
- first 30/60/90-day actions
- owner dependency
- modernization opportunities
- specialist escalation points

### 4. AI Operations Blueprint

```text
[$growth-ops]
Can this workflow become an AI agent or should it stay a simpler workflow?
Design the process, tools, guardrails, evals, and human handoff.
```

Best for:

- AI workflow design
- agent readiness review
- internal operations automation
- skill creation
- business process modernization

Output:

- workflow vs agent decision
- data requirements
- tool boundaries
- guardrails
- evaluation plan
- human handoff
- implementation sequence

### 5. Content-To-Assets

```text
[$growth-ops]
Turn this URL and notes into a note article idea, an executive brief,
a slide outline, and a dashboard concept.
```

Best for:

- thought leadership
- research-to-content
- proposal creation
- deck planning
- business storytelling

Output:

- narrative angle
- article structure
- executive summary
- slide/deck brief
- visual/dashboard idea
- source list

## Method Sources It Uses

Growth Ops uses public patterns and abstracted methods from business, startup, market intelligence, finance, and AI operations. These references are not used as name-dropping. Each method must change the output.

Examples:

- **Exa Docs / Contents API / Websets**: search, verify, enrich, monitor, and export structured datasets.
- **YC Essential Startup Advice / Requests for Startups**: launch manually, talk to users, avoid fake work, identify timely problem spaces.
- **Sequoia PMF**: separate Hair on Fire, Hard Fact, and Future Vision products.
- **NFX Network Effects Manual**: name the actual defensibility mechanism and cold-start problem.
- **Reforge Growth Loops**: replace linear funnels with compounding loops.
- **Gartner Hype Cycle**: separate hype from adoption maturity.
- **Porter Five Forces**: analyze market structure and profit pressure, not only TAM.
- **McKinsey Three Horizons**: separate core improvement, adjacent growth, and future options.
- **CB Insights Mosaic / Private Company Health**: look at money, market, momentum, management, HR, competition, investors, and product awareness.
- **6sense / Clay**: separate fit, intent, buying stage, custom scoring, and next action.
- **SignalFire / Harmonic / PitchBook / Dealroom-style signals**: track hiring, funding, founders, web traction, category shifts, and investor activity.
- **Palantir Ontology**: turn business operations into objects, states, actions, permissions, and workflows.
- **CFI / Damodaran / investment banking logic**: select valuation methods, drivers, sensitivities, and downside cases.
- **OpenAI / Anthropic agent guidance**: distinguish workflows from agents, define evals, guardrails, and human handoff.
- **Japan SME / turnaround references**: handle succession, cash crisis, debt pressure, and practical small-business operation.

## Default Output Shape

Growth Ops usually answers in this structure:

1. Bottom line
2. Decision / job to be done
3. Facts, inferences, assumptions, unknowns
4. Mechanism
5. Options or score
6. Recommended next action
7. Falsifier / watchpoint

This is meant to keep the output useful, not just impressive.

## Quick Start

In Codex, call the skill like this:

```text
[$growth-ops](C:\Users\sheng\.codex\skills\growth-ops\SKILL.md)
Turn this into a business decision memo.
<paste notes, URL, company list, idea, or situation>
```

Or simply:

```text
[$growth-ops]
Make this decision-ready.
```

## Good Inputs

Growth Ops works well with:

- rough notes
- URLs
- market themes
- company lists
- customer lists
- CSV exports
- business ideas
- consulting notes
- investment themes
- small-business situations
- messy operational workflows
- AI automation ideas
- article drafts
- proposal requirements

The messier the input, the more important the skill becomes: it turns scattered material into a structured business view.

## What It Will Not Pretend To Do

Growth Ops does not claim proprietary access to CB Insights, PitchBook, Dealroom, 6sense, Clay, SignalFire, Harmonic, Gartner, McKinsey, BCG, Bain, Palantir, YC, Sequoia, or any other organization.

It uses public patterns, user-provided data, local files, and available research tools. If a paid or private data source is unavailable, it should say so clearly and use the best available evidence.

## Why This Exists

Small teams and solo operators often do not need another dashboard, another generic strategy template, or another AI summary. They need help seeing what matters, deciding what to do, and turning that decision into an artifact they can use immediately.

Growth Ops is designed to be that layer:

```text
messy information -> structured judgment -> practical next action -> usable business asset
```

If you are exploring a market, evaluating a company, trying to revive an old business, designing an AI workflow, preparing a proposal, or turning research into assets, Growth Ops gives you a sharper operating surface.
