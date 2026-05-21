# Ops Ontology

Use this when turning messy operations into an AI-ready business system.

Inspired by public Palantir ontology concepts: business objects, relationships, actions, permissions, and workflows.

Public reference:

- Palantir Ontology overview: https://www.palantir.com/docs/foundry/ontology/overview/

## Ontology Components

Objects:

- customer
- lead
- account
- product
- order
- project
- invoice
- payment
- supplier
- employee
- ticket
- asset
- document

States:

- lead: new / qualified / proposed / won / lost
- order: requested / quoted / confirmed / fulfilled / invoiced / paid
- ticket: open / triaged / in progress / blocked / resolved
- cash: expected / received / delayed / at risk

Actions:

- qualify
- quote
- approve
- assign
- fulfill
- invoice
- collect
- escalate
- renew
- close

Permissions:

- owner
- manager
- operator
- sales
- finance
- external partner

## AI Use Cases

AI becomes useful after the workflow is represented:

- draft quotes
- summarize customer history
- detect margin risk
- flag delayed receivables
- route tickets
- generate weekly operator brief
- update proposal or deck assets

## Output

Use `templates/ops-ontology.md`.

Always include:

- objects
- states
- actions
- data sources
- exceptions
- AI opportunities
- first dashboard
