# Signal And Scoring Systems

Use this when the user asks to judge companies, leads, accounts, markets, acquisition targets, partners, investors, or themes using external signals.

The goal is not to recreate paid databases such as CB Insights, 6sense, Clay, SignalFire, Harmonic, PitchBook, or Dealroom. The goal is to steal the operating logic: use multiple signal families, separate fit from timing, and turn the score into an action.

## Reference Models

- CB Insights Mosaic: money, market, momentum, management.
- CB Insights Private Company Health: financial, industry, HR, competition, investor, and product-awareness signals.
- 6sense scoring: ICP fit, intent, predictive buying stage, and next-best action.
- Clay account scoring: custom enrichment fields, arbitrary data points, formulas, routing, and workflow triggers.
- SignalFire / Harmonic / PitchBook / Dealroom: startup/private-company signals such as hiring, funding, founder/team, growth, category, traction, and investor activity.

## Universal Signal Stack

| Layer | Question | Example signals | Output field |
|---|---|---|---|
| Fit | Is this the right kind of company/account/theme? | industry, size, geography, buyer, tech stack, business model | ICP / thesis fit |
| Pain | Is there evidence of a real problem? | job posts, reviews, complaints, process gaps, regulation, migration | pain evidence |
| Timing | Why now? | funding, hiring, leadership change, new regulation, market shock, product launch | trigger |
| Intent | Are they researching or moving? | content engagement, search/social signal, website activity, community posts, tool comparisons | intent proxy |
| Money | Can they pay or survive? | funding, revenue proxy, budget owner, cash pressure, investor quality | money signal |
| Market | Is the category healthy? | buyer urgency, growth, analyst category, adoption stage, competitor density | market signal |
| Momentum | Is trajectory improving? | launches, hiring velocity, traffic, partnerships, customer wins | momentum signal |
| Management | Can the team execute? | founder background, senior hires, domain expertise, leadership churn | management signal |
| Reachability | Can the user act on it? | known contact, warm path, public email, community overlap, channel access | next contact |
| Risk | What could make it false? | PR without customers, funding without revenue, vague hiring, old data | confidence / caveat |

## Scoring Formula Pattern

Do not use one universal formula. Choose weights based on the job.

### Sales / Account Scoring

```text
Score = 25% ICP fit + 20% pain + 20% timing + 15% intent + 10% reachability + 10% offer fit
```

### Partner Scoring

```text
Score = 25% audience overlap + 20% trust + 20% complementarity + 15% reachability + 10% operational ease + 10% upside
```

### Acquisition Target Scoring

```text
Score = 20% business quality + 20% owner/succession fit + 20% cash stability + 15% modernization upside + 15% deal feasibility + 10% downside risk
```

### Market / Theme Scoring

```text
Score = 20% buyer urgency + 20% why-now + 20% market momentum + 15% defensibility + 15% monetization path + 10% evidence quality
```

## Stage-To-Action Map

| Stage | Meaning | Action |
|---|---|---|
| Watch | interesting but weak evidence | monitor signals |
| Research | fit is plausible, timing unclear | enrich missing fields |
| Engage | fit and trigger are present | contact / interview / outreach |
| Propose | pain, buyer, and timing are clear | make a concrete offer |
| Defer | weak timing or poor access | revisit later |
| Reject | no fit, no buyer, or bad economics | stop spending time |

## Output Requirements

When this reference is used, output:

- scoring purpose
- signal table
- scoring formula
- ranked list
- top 3 reasons per item
- missing data
- confidence level
- next action
- what would change the score

## Limitations

Say clearly when paid/private databases are unavailable. Use public web evidence, user-provided data, and local files. Do not pretend to know proprietary CB Insights, 6sense, Clay, SignalFire, Harmonic, PitchBook, or Dealroom data.
