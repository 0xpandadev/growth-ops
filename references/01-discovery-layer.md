# Discovery Layer

The discovery layer answers: what should be collected, from where, and how should it become usable evidence?

## Search Is Not Enough

Do not stop at keyword search. Build a small evidence dataset:

- entities: companies, people, products, accounts, markets, technologies
- attributes: size, segment, buyer, geography, maturity, momentum, budget owner
- signals: hiring, funding, launches, integrations, regulation, pricing, customer complaints
- evidence: URLs, dates, excerpts, pages, source type, confidence
- interpretation: why it matters, what changed, what to verify

## Exa-Style Semantic Discovery

Use Exa as a reference model for AI-native discovery even if the Exa API is not available. Exa's public docs emphasize semantic/neural search, content extraction, similar result discovery, and Websets-style dataset creation:

- Exa docs: https://docs.exa.ai/
- Contents API guide: https://exa.ai/docs/reference/contents-api-guide
- Websets overview: https://docs.exa.ai/websets/overview

Translate this into a workflow:

1. Start with a natural-language concept, not only keywords.
2. Find initial examples.
3. Use "similar to these" thinking to expand the universe.
4. Extract structured fields from each source.
5. Enrich missing fields.
6. Score and cluster results.
7. Keep evidence rows inspectable.

## Source Families

Use the relevant source families:

- Official: company pages, filings, product docs, API docs, government data, earnings materials.
- Market data: CB Insights, PitchBook, Dealroom, Crunchbase, funding databases, analyst reports.
- Buyer reality: job posts, reviews, forums, social posts, procurement pages, app reviews, sales pages.
- Technology: GitHub, docs, changelogs, SDKs, benchmarks, developer forums.
- SME/local: local directories, registries, tax/insolvency guidance, association materials, reviews.
- China scale ops: corporate docs, case studies, product ecosystem pages, cloud docs, operating papers.

## Evidence Table Fields

Use this schema when doing research:

| Field | Meaning |
|---|---|
| Source | URL or document |
| Date | publication or access date |
| Entity | company, person, market, product, account |
| Evidence | short fact or excerpt |
| Signal type | demand, supply, funding, hiring, regulation, product, customer pain |
| Relevance | direct / supporting / weak / contradiction |
| Confidence | high / medium / low |
| Implication | why it matters |
| Next check | what to verify |

## Weak Signal Rules

Treat weak signals as prompts for investigation, not conclusions.

Good weak signals:

- repeated buyer complaints
- new budget language
- job postings that imply workflow pain
- technical docs showing platform shift
- regulatory deadlines
- new integrations or ecosystem hooks
- repeated founder/customer language across sources

Bad weak signals:

- one viral post
- a vague trend name
- funding alone
- "AI for X" without workflow, budget, or adoption path
