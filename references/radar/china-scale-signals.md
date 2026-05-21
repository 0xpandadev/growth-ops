# China Scale Signals

Use this when the user wants operational logic from Alibaba, Tencent, ByteDance, or other fast-scaling Chinese companies.

Do not imitate brands or claim proprietary methods. Translate public patterns into practical operating lenses.

## Public Reference Sources

- Alibaba data middle platform: https://www.alibabacloud.com/blog/theintelligent-evolution-of-the-data-middle-platform-12-years-of-development-from-alibabas-data-platform_598097
- Alibaba New Retail case: https://www.cgap.org/research/publication/new-retail-revolution
- Tencent Mini Programs: https://www.tencent.net.cn/wechat-mini-programs-showcases-new-capabilities-to-celebrate-its-third-anniversary/
- Tencent corporate overview: https://static.www.tencent.com/uploads/2023/08/16/0afb0b7e48d32a1dc663e893e59bfa6d.pdf
- BytePlus A/B testing docs: https://docs.byteplus.com/ko/docs/data-intelligence/Learn_about_A-B_test_products
- ByteDance AI-powered startup case: https://www.mdpi.com/1911-8074/14/5/203/htm

## Lenses

### Alibaba Lens

Business operating system, commerce infrastructure, logistics, payments, cloud, data middle platform.

Small-business translation:

- create one customer/order/product/inventory table
- connect inquiry -> quote -> order -> delivery -> payment -> repeat purchase
- manage margin by product and customer
- build operational dashboards before advanced AI
- treat data as an operating asset: ownership, quality, security, utilization, and cost must be visible
- reduce data islands before asking AI to analyze the business

### Tencent Lens

Social graph, super-app ecosystem, mini programs, messaging, payments, community, customer touchpoints.

Small-business translation:

- build a customer touchpoint OS: LINE, email, community, booking, membership, referral
- treat communication history as operating data
- convert community into repeat purchase and support reduction
- design around transactions and service moments, not only content impressions

### ByteDance Lens

Recommendation, content/product experimentation, A/B testing, rapid iteration, algorithmic distribution.

Small-business translation:

- run weekly offer/title/landing-page/content tests
- track CTR, completion, save, share, inquiry, conversion
- use data to refine positioning, not just content volume
- define experiment owner, hypothesis, success metric, rollout rule, and kill rule

### Optional Lenses

- PDD: price, social commerce, group-buying, subsidy efficiency.
- Meituan: local operations, delivery density, merchant network, SLA.
- Xiaomi: hardware/community/supply chain feedback loops.

## KPI Families

- Product/content: CTR, completion, saves, shares, comments, revisit.
- Growth: DAU/MAU, activation, D1/D7/D30 retention, referral.
- Commerce: GMV, CVR, AOV, purchase frequency, gross margin, subsidy efficiency, return rate.
- Merchant/account: active merchants, repeat merchants, merchant GMV, take rate.
- Ecosystem: cross-service conversion, payment/logistics/cloud attachment.
- Experimentation: experiment count, win rate, cycle time, rollout speed.
- Operations: SLA, inventory turnover, stockout rate, support rate, operating cost.
- AI/data: recommendation lift, personalization uplift, data freshness, iteration speed.

## Output

Return:

- which China-scale lens applies
- what the small-business version is
- data needed
- data ownership / quality risk
- weekly experiment cadence
- KPI dashboard
- risk of overbuilding
