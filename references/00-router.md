# Router

Use this file first when the request is broad or ambiguous.

## Lane Selection

| User need | Lane | Typical output |
|---|---|---|
| Find themes, markets, companies, competitors, accounts, partners, acquisition targets | `radar` | Market radar, opportunity map, account scorecard, watchlist |
| Judge a business situation, cash pressure, operations, succession, modernization, AI workflow | `operator` | Operating memo, turnaround plan, ops ontology, 90-day plan |
| Turn analysis into article, deck, proposal, dashboard, reusable workflow, skill | `assets` | Content plan, deck brief, proposal, HTML dashboard spec, skill blueprint |
| Research + decide + package | `radar + operator + assets` | Decision-ready business asset |

## Auto-Routing Examples

- "このテーマが有望か見て" -> load `radar/vc-startup-lenses.md`, `radar/market-intelligence.md`, maybe `01-discovery-layer.md`.
- "この顧客/プロダクトの本当の痛みを見て" -> load `input-understanding.md`, `radar/customer-value-jtbd.md`.
- "営業先リストを優先順位付けして" -> load `radar/account-scoring.md`, `radar/signal-and-scoring-systems.md`, `scoring-rubrics.md`.
- "有望企業/市場シグナル/Private company health を見て" -> load `radar/market-intelligence.md`, `radar/signal-and-scoring-systems.md`.
- "古い会社を承継したらどう立て直すか" -> load `operator/sme-operator.md`, `operator/succession-and-sme-ma.md`, `operator/legacy-company-modernization.md`.
- "倒産しそうな会社をどう再生するか" -> load `operator/turnaround-cash-control.md`, `operator/finance-and-unit-economics.md`.
- "これをnote記事とスライドにして" -> load `assets/content-assets.md`, `assets/deck-and-brief.md`.
- "AIエージェント/スキルで業務化したい" -> load `operator/ai-agent-ops.md`, `assets/skill-blueprint.md`.
- "HTMLダッシュボードにしたい" -> load `assets/dashboard-and-information-design.md`.
- "この作業をスキル化したい" -> load `assets/skill-blueprint.md`.

## Do Not Make Users Memorize Modes

If the user says "template", "examples", or "what can this do", show a numbered list of practical use cases. If the user gives only a number later, map it back to the listed use case.

## Default Output Shape

Use this compact form unless the user asks for a different format:

1. Bottom line
2. Decision / job to be done
3. Evidence and assumptions
4. Mechanism
5. Options or score
6. Recommended next action
7. Falsifier / watchpoint
