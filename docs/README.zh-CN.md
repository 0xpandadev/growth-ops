# Growth Ops

**Growth Ops 是一个面向业务增长、经营判断和资产化输出的 operating intelligence Skill。**

[English](../README.md) | [日本語](./README.ja.md) | [中文](./README.zh-CN.md)

它适合创始人、一人公司、小型企业、咨询顾问、投资研究者、新业务负责人，以及正在思考如何把 AI 用到真实业务流程中的操作者。

Growth Ops 不只是总结信息。它可以把零散的笔记、URL、公司名单、市场主题、客户线索、业务问题、老企业改造、现金压力、AI 工作流想法，转化成真正可以使用的业务输出：

- 市场雷达
- 机会判断卡
- 线索 / 客户 / 合作伙伴评分
- 中小企业经营诊断
- 业务再生 / turnaround 计划
- 提案 brief
- HTML dashboard 规格
- 内容计划
- slide deck brief
- 可复用的 Skill blueprint

它的核心思路是：

```text
不要只总结信息。
要理解业务处境，提取真正的信号，判断什么重要，并把下一步行动变得清楚。
```

## 它和普通 AI 总结有什么不同

很多 AI 输出看起来很整齐，但实际不一定能用。

- 只是列趋势
- 只是套框架
- 只是总结文章
- 只是做一个好看的表
- 只是说「AI 可以提升效率」

Growth Ops 试图往下多走一层：

- 真正需要做的决策是什么？
- 哪些是事实，哪些是推断，哪些是假设，哪些还不知道？
- 哪些信号真的有意义？
- 机会或问题背后的机制是什么？
- 本周可以验证什么？
- 什么情况出现时，应该承认判断错了？
- 最终应该产出什么，才能让人真的行动？

它的目标不是显得聪明，而是让输出变得可执行。

## 三个内部方向

你不需要记住模式名。直接自然提问即可，Skill 会自动判断该走哪条路径。

```text
growth-ops
  radar    = 看外部: 市场、趋势、竞争、目标客户、合作伙伴、弱信号
  operator = 看内部: 商业模式、现金、运营、继承、再生、现代化
  assets   = 做成资产: memo、brief、proposal、slides、HTML、content、skill blueprint
```

## Radar: 看外部机会和信号

适合这些问题：

- 这个市场主题是真的机会，还是只是 hype？
- 哪些公司、客户、合作伙伴、收购对象值得关注？
- 哪些信号代表 momentum、timing、budget 或真实痛点？
- 这个领域处在早期、过热期、落地期，还是已经成熟？
- 这个机会有什么陷阱？

Radar 会借鉴这些公开方法的思路：

- Exa 风格的 semantic discovery / Websets
- YC Essential Startup Advice / Requests for Startups
- Sequoia PMF
- a16z 的 category map / AI / marketplace 视角
- NFX Network Effects
- Reforge Growth Loops
- Gartner Hype Cycle
- Porter Five Forces
- CB Insights Mosaic / Private Company Health
- 6sense 的 fit / intent / buying stage
- Clay 的 custom account scoring
- SignalFire / Harmonic / PitchBook / Dealroom 风格的 private-market signals

它不会假装拥有付费数据库。它使用的是这些系统背后的判断逻辑：多维信号、验证标准、fit 和 timing 的分离、评分到行动的转换。

## Operator: 看业务内部和经营现实

适合这些问题：

- 一个传统小企业该如何现代化？
- 接手一家老公司，应该先修哪里？
- 现金紧张、负债压力、利润下滑时如何判断？
- 哪些客户、产品、流程真正赚钱？
- AI 应该加在哪里？哪里不该加？
- 这个业务应该先救命、再优化，还是可以直接增长？

Operator 会把抽象战略翻译成经营现实：

- 谁负责？
- 什么时候做？
- 用什么数据判断？
- 对现金、客户、流程、风险有什么影响？
- 本周可以测试什么？

## Assets: 把分析变成能用的东西

适合这些输出：

- 决策 memo
- 市场 radar
- account scorecard
- proposal brief
- 内容大纲
- slide deck brief
- HTML dashboard spec
- Skill blueprint

Growth Ops 不希望分析停留在聊天窗口里。它更关心：这份分析能不能被拿去使用、展示、销售、管理或继续迭代。

## Growth Board: 面向业务判断的 GUI

Growth Ops 也可以把分析结果变成 **Growth Board**，也就是一个面向决策的 GUI / knowledge UI。

它不是普通 KPI dashboard。它要展示的是信息如何变成判断：

```text
signal -> interpretation -> decision -> action
```

用户不需要记住具体界面名称。只要这样说：

```text
[$growth-ops]
把这些信息变成 Growth Board。
<笔记、公司列表、市场主题、杂乱数据、业务流程>
```

Growth Ops 会自动判断适合哪种 board：

- **Auto Board**: 目标还不清楚的杂乱输入
- **Signal Board**: 市场主题、弱信号、新闻、公司动态
- **Score Board**: 线索、客户、合作伙伴、投资/收购对象、想法排序
- **Map Board**: 公司、客户、产品、流程、人物、资金、资料之间的关系
- **Scenario Board**: 定价、AI 导入、业务再生、招聘、现金流等假设模拟
- **Action Board**: 谁在什么时候、什么条件下、做什么动作

视觉方向不是普通 SaaS dashboard，而是参考 Palantir 的 object/state/action、CB Insights 的 signal stack、6sense/Clay 的 account scoring、Neo4j 的 entity graph、Runway/Pigment 的 scenario planning、incident.io/PagerDuty 的 action workflow，以及 Tufte/Few 的信息密度和清晰度，做成更像高级业务操作台的界面。

## 如何使用

在 Codex 中可以这样调用：

```text
[$growth-ops](C:\Users\sheng\.codex\skills\growth-ops\SKILL.md)
把下面内容整理成可以做业务决策的形式。
<URL / 笔记 / 公司列表 / 市场主题 / 业务问题>
```

也可以更简单：

```text
[$growth-ops]
让这个内容变得 decision-ready。
```

## 使用场景示例

### 1. 判断市场主题

```text
[$growth-ops]
分析这个主题是不是真机会。
请给出 why now、买方痛点、市场地图、玩家分类、风险、验证方法和下一步监控项。
```

### 2. 公司 / 线索 / 合作伙伴评分

```text
[$growth-ops]
对这个公司列表排序。
请按 ICP fit、pain、timing、intent、budget proxy、reachability 和 next action 来评分。
```

### 3. 中小企业经营诊断

```text
[$growth-ops]
假设我要接手这家传统小企业。
请从现金、利润、客户、流程、人员、AI 现代化和 90 天计划角度诊断。
```

### 4. AI 工作流设计

```text
[$growth-ops]
这个业务流程适合做 AI agent 吗？
还是简单 workflow 就够了？请设计数据、工具、guardrails、eval 和人工确认点。
```

### 5. 内容 / 提案 / Slides

```text
[$growth-ops]
把这个 URL 和笔记变成文章选题、提案 brief、slide 结构和 dashboard 概念。
```

## 默认输出结构

通常会输出：

1. 结论
2. 真正要判断的问题
3. 事实 / 推断 / 假设 / 未知
4. 背后的机制
5. 选项或评分
6. 推荐下一步
7. 反证点 / 监控点

## 适合谁

- 一人公司，需要同时做研究、销售、内容、提案和业务开发的人
- 小企业经营者，需要现实可执行的判断和计划
- 正在接手、收购、改造或再生传统企业的人
- 想把 AI 放进真实业务流程的人
- 想更系统地看市场、公司、趋势和投资主题的人
- 需要把研究变成文章、提案、dashboard 或 slides 的人

## 它不会假装做什么

Growth Ops 不会假装自己拥有 CB Insights、PitchBook、Dealroom、6sense、Clay、SignalFire、Harmonic、Gartner、McKinsey、BCG、Bain、Palantir、YC、Sequoia 等机构的付费或私有数据。

它使用的是公开方法、用户提供的数据、本地文件和可用的研究工具。

换句话说，它不是秘密数据库，而是一个用于 **观察、拆解、判断、评分和输出业务资产** 的 Skill。

## 为什么需要它

小团队和一人公司通常不缺信息。真正缺的是：如何从信息里看出关键点，如何决定下一步，如何把判断变成可以行动的成果物。

```text
零散信息 -> 结构化判断 -> 下一步行动 -> 可复用业务资产
```

Growth Ops 就是为了把这条链路变成一个可调用的 Skill。
