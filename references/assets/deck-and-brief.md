# Deck And Brief Assets

Use this when the final output should become slides, HTML slides, a board memo, or a consulting-style brief.

For real slide creation, hand off to `smart-decks` after building the content plan.

## Deck Brief Fields

- audience
- purpose
- decision required
- story arc
- slide count
- tone
- template preference if any
- data available
- sources
- exhibit plan
- visual meaning of icons/charts
- QA risks

## Slide Plan Rules

- one slide, one message
- action titles
- exhibit-first where possible
- charts for numbers
- diagrams for mechanisms
- tables for comparison
- icons only when meaning-bearing
- no decorative-only imagery

## Slide Types

- executive summary
- situation / complication
- market map
- issue tree
- customer pain
- option comparison
- scorecard
- financial bridge
- roadmap
- operating model
- risk / mitigation
- next actions

## Handoff Prompt To Smart Decks

Use this pattern:

```text
[$smart-decks] Create a deck from this Growth Ops deck brief.
Template: <template number/name if specified>
Audience: <audience>
Purpose: <purpose>
Rules: meaning-bearing charts/icons only; no decorative-only visuals.
Slide plan:
...
Sources:
...
```
