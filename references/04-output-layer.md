# Output Layer

The output layer makes work usable.

## Output Families

| Output | Use when | Template |
|---|---|---|
| Opportunity card | judging a theme, idea, product, market | `templates/opportunity-card.md` |
| Market radar | tracking themes, competitors, technologies | `templates/market-radar.md` |
| Account scorecard | ranking leads, partners, investors, targets | `templates/account-scorecard.md` |
| SME operator memo | diagnosing a small business | `templates/sme-operator-memo.md` |
| Turnaround plan | distressed business or cash crisis | `templates/turnaround-plan.md` |
| Value creation plan | acquisition, succession, PE-style improvement, operational value creation, 100-day plan | `templates/value-creation-plan.md` |
| Ops ontology | turning messy operations into AI-ready workflow | `templates/ops-ontology.md` |
| Content asset plan | article, X, newsletter, deck, source pack | `templates/content-asset-plan.md` |
| Skill blueprint | repeatable work to skill design | `templates/skill-blueprint.md` |
| Growth Board | GUI / board / command surface for decision-ready visual operation | `templates/growth-board-spec.md`, `templates/growth-board-html-brief.md` |

## Deck And HTML Handoff

When the user asks for slides, do not jump straight to design.

First create:

- audience
- decision / purpose
- storyline
- slide-by-slide action titles
- exhibit plan
- data and sources
- visual meaning of icons/charts
- QA risks

Then hand off to `smart-decks`.

## Dashboard Handoff

When the user asks for an HTML dashboard, specify:

- decision or action the screen supports
- user and use case
- source data
- core entities
- views
- filters
- score logic
- confidence labels
- update cadence
- red/yellow/green thresholds
- owner / next action fields
- export or sharing need

For detailed screen logic, load `references/assets/dashboard-and-information-design.md`.

For Growth Board or Command Surface requests, load `references/assets/growth-board.md`.

Default rule:

- If the user explicitly asks for GUI, board, dashboard, command surface, screen, or visual console, produce a Growth Board spec or HTML brief.
- If the user only asks for analysis, produce text first and optionally recommend a Growth Board when it would clarify the decision.
- If the user provides messy data and asks for GUI without a clear purpose, use Auto Board to discover the decision candidates.

## Article / Content Handoff

When the user asks for content:

- define the reader
- state the angle
- keep the claim falsifiable
- preserve source links
- add "how to copy this" if the article is practical
- generate derivative assets only when useful
