# Growth Board

Growth Board is the GUI / knowledge UI layer for Growth Ops.

Use this when the user asks for:

- GUI
- dashboard
- board
- command surface
- screen
- visual console
- HTML dashboard
- "見える形"
- "判断できる画面"

The user should not need to remember board names. Infer the decision, then compose the right board.

## Core Idea

Growth Board is not a generic dashboard.

Generic dashboard:

```text
metric -> chart -> passive viewing
```

Growth Board:

```text
signal -> interpretation -> decision -> action
```

The board should show how raw information becomes a business judgment.

## User-Facing Names

Use simple names.

| Board | Use when | Core question |
|---|---|---|
| Auto Board | messy input, unclear objective, mixed data | What can we understand and decide from this input? |
| Signal Board | market themes, weak signals, news, company movement | Which signals matter and what do they imply? |
| Score Board | accounts, leads, partners, investors, targets, ideas | What should be prioritized and why? |
| Map Board | entities, relationships, workflows, operations | How are the important objects connected and changing? |
| Scenario Board | pricing, AI adoption, turnaround, investment, hiring, cash | What happens if assumptions change? |
| Action Board | execution, follow-up, operating cadence | Who should do what next, under what condition? |

Default:

- If the user asks "which GUI fits?", recommend one primary board plus one or two alternatives.
- If the user asks "make it GUI" and the intent is unclear, use Auto Board.
- If the user asks "make it GUI" and the intent is clear, choose the best board automatically.
- If multiple boards are needed, compose them into one Growth Board instead of asking the user to choose modules.

## Reference Models To Borrow From

Use these as conceptual references. Do not claim proprietary access or copy their product UI.

| Reference | What to borrow | Growth Board translation |
|---|---|---|
| Palantir Foundry / Ontology | object, state, action, permission, workflow | Map Board and Action Board |
| CB Insights Mosaic / Private Company Health | money, market, momentum, management, non-traditional signals | Signal Board and Score Board |
| 6sense | fit, intent, buying stage, next action | Score Board |
| Clay | arbitrary enrichment fields, formulas, routing workflows | Score Board and Action Board |
| Dataminr / Recorded Future | event detection, impact, response | Signal Board |
| Neo4j Bloom / Linkurious / Maltego | entity graph and hidden relationships | Map Board |
| Runway / Pigment / Anaplan | scenario planning and assumption comparison | Scenario Board |
| incident.io / PagerDuty / Retool | triggers, actions, owner, workflow | Action Board |
| Tufte / Stephen Few | high-density clarity, no decoration, strong information hierarchy | Visual grammar |
| Rumelt | diagnosis, guiding policy, coherent action | Decision structure |

## Auto Board

Use Auto Board when the user dumps messy data and says "make it visual", "GUI", "dashboard", or "見える形" without a clear objective.

Auto Board should discover:

- entities
- themes
- signals
- numbers
- contradictions
- decisions that could be made
- missing data
- recommended board type

Layout:

```text
top: what this input appears to contain
left: Signal Inbox
center: Decision Candidates
right: Recommended Board / Next Action
bottom: Evidence and Unknowns
```

Output:

- primary recommended board
- 2 alternative board routes if useful
- what the user can decide now
- what cannot be decided yet

## Signal Board

Use for market themes, trend watching, company movement, competitive signals, customer voice, news, hiring, funding, regulation, and weak signals.

Core panels:

- Signal Inbox: each signal with source, date, strength, and confidence.
- Interpretation: what the signal likely means.
- Decision Impact: what decision the signal affects.
- Watchpoints: what would confirm or falsify the interpretation.
- Action: monitor, research, contact, build, avoid, or escalate.

Do not produce a news dashboard. A Signal Board must explain why each signal matters.

## Score Board

Use for company lists, account scoring, partner scoring, acquisition targets, investor targeting, idea selection, and opportunity prioritization.

Core panels:

- Ranked list.
- Scoring formula.
- Signal evidence by item.
- Fit / Pain / Timing / Intent / Upside / Risk / Reachability.
- Confidence and missing data.
- Next action by stage.

Borrow from 6sense and Clay:

- separate fit from timing
- separate intent from evidence
- make weights explicit
- route each score to an action

## Map Board

Use when relationships and states matter more than individual scores.

Core panels:

- Entity graph: company, customer, product, workflow, account, invoice, person, document, system.
- State labels: active, blocked, risky, high-value, delayed, unknown, validated.
- Relationship labels: owns, buys, uses, funds, competes, depends on, blocks, triggers.
- Action affordances: qualify, contact, collect, quote, escalate, test, automate.

Borrow from Palantir / graph tools:

- objects are not just data rows
- objects have states
- states imply possible actions
- permissions and ownership matter

## Scenario Board

Use when assumptions, trade-offs, or future states matter.

Core panels:

- Base case.
- Scenario A / B / C.
- Assumption sliders or switches.
- Impact table.
- Risk and reversibility.
- Decision threshold.

Common scenarios:

- price change
- AI adoption
- hiring
- cost cut
- sales push
- turnaround
- acquisition
- market entry
- product pivot

Borrow from Runway / Pigment / Anaplan:

- keep assumptions visible
- compare scenarios side by side
- show sensitivity, not fake precision

## Action Board

Use when the goal is execution.

Core panels:

- action
- owner
- deadline or cadence
- trigger condition
- input data needed
- expected outcome
- risk
- follow-up

Borrow from incident.io / PagerDuty / Retool:

- actions are first-class objects
- triggers matter
- follow-up matters
- workflow should be visible

## Composition Rules

Most real requests need a composed board.

| Input pattern | Default composition |
|---|---|
| messy pasted data | Auto Board |
| market theme | Signal Board + Score Board + Evidence |
| company list | Score Board + Action Board |
| old company / turnaround | Map Board + Scenario Board + Action Board |
| AI workflow | Map Board + Scenario Board + Action Board |
| acquisition/investment target | Score Board + Map Board + Scenario Board |
| content / proposal / deck planning | Signal Board + Action Board |

Always keep one dominant board. Supporting modules should not create a crowded cockpit.

## Visual Grammar

Aim for a cool, high-end operating console. Apple-level polish is a baseline, not the ceiling; the board should feel more analytical, denser, and more decision-oriented.

Use:

- calm dark or near-white base
- one sharp accent color
- thin dividers
- high-density but readable typography
- compact source chips
- confidence badges
- state tags
- graph lines only when they encode relationships
- panels with clear purpose
- sticky action rail when useful
- evidence drawer instead of noisy footnotes

Avoid:

- generic KPI cards as the main visual
- decorative gradients with no meaning
- random icons
- meaningless maps
- SaaS template look
- dense tables without interpretation
- Apple-like emptiness that hides the decision

## Output Modes

Text-only spec:

- use `templates/growth-board-spec.md`

HTML build brief:

- use `templates/growth-board-html-brief.md`

If actually building HTML, the UI must include:

- title and decision statement
- signal-to-decision chain
- evidence and unknowns
- recommended action
- responsive layout
- no decorative-only visuals
- no overflowing text

## Good Prompts

```text
[$growth-ops]
この情報をGrowth Board化して。目的はまだ曖昧なので、まずAuto Boardで何が見えるか出して。
```

```text
[$growth-ops]
この会社リストをScore Boardで見せて。ICP fit、pain、timing、intent、次アクションを出して。
```

```text
[$growth-ops]
この市場テーマをSignal Boardにして。シグナル、意味、判断、次の検証を見える化して。
```

```text
[$growth-ops]
ここまでの議論をGrowth BoardのHTMLにするためのbriefにして。
```

