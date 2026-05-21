# Exa-Style Discovery

Use this when the user wants better-than-keyword discovery: themes, companies, accounts, papers, tools, emerging markets, or examples similar to a seed.

## Public Reference Model

Exa positions itself around neural/semantic search, content extraction, similar-link discovery, and Websets-style dataset creation.

Useful public references:

- Exa docs: https://docs.exa.ai/
- Contents API guide: https://exa.ai/docs/reference/contents-api-guide
- Websets overview: https://docs.exa.ai/websets/overview
- Websets API overview: https://docs.exa.ai/websets/api/overview

Do not assume Exa is available as a tool. Use the method even with normal browsing.

## Workflow

1. Define the concept in natural language.
2. Create 3-5 seed examples.
3. Search for semantically similar entities.
4. Define verification criteria before accepting results.
5. Extract structured fields.
6. Enrich missing fields from official sources.
7. Cluster by buyer, workflow, technology, geography, business model, or trigger.
8. Score each cluster.
9. Output a dataset, not just prose.

## Websets Discipline

Exa's Websets pattern is not just "search". The important idea is to create a verified and enriched web dataset.

Translate that into this operating rule:

- `Search`: find candidates from a natural-language description.
- `Verify`: reject results that do not meet explicit criteria.
- `Enrich`: add structured fields such as CEO, funding, pricing, headcount, customer segment, or contact signal.
- `Monitor`: if the theme matters over time, define what should be checked again and how often.
- `Export`: make the result usable as a table, account list, watchlist, or dashboard input.

## Contents API Discipline

Use the Contents API idea when the task needs source extraction:

- fetch the page or document
- extract clean text
- extract highlights relevant to the query
- preserve the source URL
- separate direct evidence from interpretation

Translate this into normal browsing by never scoring an entity from a search-result title alone. Open the source, extract the relevant content, and attach evidence.

## Websets API Discipline

Use the Websets API idea when the task needs a repeatable dataset:

- `Webset`: the collection, such as "AI ops tools for Japanese SMEs".
- `Search`: the query and criteria used to find candidates.
- `Item`: each accepted company/person/paper/article.
- `Verification`: why the item matches.
- `Enrichment`: fields to add, such as founder, pricing, headcount, funding, buyer, customer proof.
- `Monitor`: how the set should be updated over time.

Even without Exa access, output this structure when the user wants market radar, account scoring, sourcing, partner lists, or target-company discovery.

## Good Queries

- "companies helping small manufacturers automate quoting and job costing"
- "AI agents for insurance back-office workflows"
- "tools similar to [seed company] for [buyer]"
- "recent examples of local service businesses using AI for dispatch, pricing, or support"

## Fields To Extract

- entity
- website
- category
- buyer
- pain
- product
- pricing signal
- traction signal
- hiring/funding signal
- competitor / similar entity
- evidence URL
- why it matters

## Output

Return:

- seed logic
- acceptance / rejection criteria
- discovered clusters
- top entities/accounts
- evidence table
- enrichment fields
- recommended next search
- monitor cadence if relevant
- what would prove the theme is real
