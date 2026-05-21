# Dashboard And Information Design

Use this when Growth Ops produces an HTML dashboard, operator screen, market radar page, scorecard, or decision console.

The goal is not a pretty screen. The goal is a screen that helps the user decide or act.

## Screen Purpose

Every dashboard must answer:

- Who uses it?
- What decision or action happens here?
- What data changes the decision?
- What threshold creates urgency?
- What should the user do next?

## Information Architecture

Structure screens as:

1. `Status`: what matters now
2. `Drivers`: why it is happening
3. `Details`: evidence rows or underlying entities
4. `Action`: next step, owner, due date
5. `Watch`: falsifiers, alerts, open questions

## Visual Encoding Rules

- Use tables for entity comparison.
- Use scorecards for prioritization.
- Use timelines for plan/cadence.
- Use funnel/loop charts only when stages are real.
- Use line charts for time series.
- Use bar charts for comparisons.
- Use icons only when they replace or clarify a concept.
- Do not use decorative-only visuals.

## Decision Dashboard Fields

Include:

- entity
- score
- reason
- evidence
- owner
- next action
- deadline
- status
- risk
- last updated

## Design Review Checks

- Does the first screen communicate the current state in 5 seconds?
- Are thresholds clear enough to act on?
- Are low-confidence items visually marked?
- Is the dashboard usable without reading a long explanation?
- Is every chart tied to a decision?
- Is every icon meaning-bearing?
- Is the mobile view still understandable?

## Output

Return:

- dashboard purpose
- user
- views
- data model
- components
- metrics
- thresholds
- empty/error states
- export/share needs
