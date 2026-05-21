# Account Scoring

Use this for lead scoring, partner scoring, investor targeting, acquisition target screening, or "who should I contact first?"

## Account Types

- sales leads
- strategic partners
- investors
- acquisition targets
- pilot customers
- media/community partners
- vendors

## Scoring Dimensions

Score 1-5 and explain evidence:

- ICP fit
- visible pain
- timing trigger
- intent / research activity
- buying stage
- budget proxy
- reachability
- offer fit
- urgency
- strategic value
- downside / friction

## 6sense-Style Separation

Do not collapse account quality into one vague score. Separate:

- `Fit`: firmographic / technographic / segment match.
- `Intent`: research activity, website activity, third-party interest, category movement.
- `Stage`: target, awareness, consideration, decision, purchase-like urgency.
- `Trigger`: funding, hiring, regulation, migration, tool replacement, leadership change, pain event.
- `Action`: nurture, research more, warm intro, outbound, proposal, partner route, defer.

Use this especially when the user gives a CSV, CRM export, company list, lead list, investor list, acquisition-target list, or partner list.

## Clay-Style Custom Scoring

Use custom fields rather than generic scoring when the target motion is specific.

Examples:

- If selling AI ops consulting: score workflow pain, public AI hiring, legacy process signals, budget owner, and case-study fit.
- If looking for acquisition targets: score owner dependency, succession likelihood, cash stability, customer concentration, and modernization potential.
- If finding partners: score audience overlap, trust surface, product complementarity, and reachability.

Score formula format:

```text
Total = 30% ICP + 20% Pain + 20% Timing + 15% Reachability + 15% Offer Fit
```

Always explain:

- which data points were used
- which data points were missing
- why the weight matters
- what workflow the score triggers

## Evidence Examples

Strong evidence:

- job posts for the exact workflow
- recent funding, hiring, expansion, migration, regulation, product launch
- public complaints or reviews
- visible outdated process
- explicit budget owner
- known network path

Weak evidence:

- company is large
- vague "AI interest"
- single blog post
- no contact path

## Output

Use `templates/account-scorecard.md`.

Also include:

- top 5 first contacts
- 1-sentence offer angle per account
- outreach trigger
- what to verify before contacting
- next action by stage
- score confidence
