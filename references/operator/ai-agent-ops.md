# AI Agent Ops

Use this when the user asks how to skill-ize work, automate operations, build dashboards, use AI agents, or copy enterprise AI workflows in a small-company way.

## Public Reference Sources

- Anthropic Building Effective Agents: https://www.anthropic.com/engineering/building-effective-agents
- OpenAI practical guide to building agents: https://openai.com/business/guides-and-resources/a-practical-guide-to-building-ai-agents/
- OpenAI evaluation best practices: https://platform.openai.com/docs/guides/evaluation-best-practices
- OpenAI skills overview: https://openai.com/academy/skills/
- Glean work AI / enterprise graph concept: https://docs.glean.com/user-guide/about/what-is-glean

## Agent Or Workflow Decision

Do not call everything an agent.

| Pattern | Use when | Example |
|---|---|---|
| Prompt/template | one-shot output with stable format | draft article outline |
| Workflow | fixed sequence of steps with checks | research -> score -> memo |
| Routed workflow | distinct input categories need different handling | radar vs operator vs assets |
| Agent | ambiguous multi-step work needs tool use, judgment, recovery, and stopping conditions | investigate accounts and build a scored dataset |
| Multi-agent | genuinely separable specialist work needs handoff or parallel review | research + finance + deck QA |

Start with the simplest pattern that can pass quality checks.

## Agent Fit Criteria

Good fit:

- complex decision-making
- difficult-to-maintain rules
- heavy unstructured data
- tool use or external context required
- clear success criteria
- feedback loop or eval possible
- human handoff for uncertainty or risk

Bad fit:

- deterministic calculation
- simple data entry
- high-stakes action without approval
- no way to verify output
- vague "assistant for everything"

## Operating Design

For each AI workflow define:

- input
- tools / data
- state
- guardrails
- output schema
- exit condition
- human handoff trigger
- eval cases
- log / memory
- owner

## Eval Discipline

Create a small eval set before expanding:

- typical cases
- edge cases
- adversarial cases
- bad input
- missing data
- source contradiction
- user asks for unsupported advice

Score against:

- task success
- evidence correctness
- context recall
- source precision
- practical usefulness
- safety / boundary adherence

Use pairwise comparison, classification, or rubric scoring when possible.

## Small-Business Translation

For a solo operator or small business, build:

1. a repeatable prompt/workflow
2. a shared folder/table of source data
3. a quality checklist
4. a few examples of good outputs
5. a weekly review cadence
6. only then, a more autonomous agent

## Output

Return:

- agent/workflow fit decision
- workflow diagram
- tools/data needed
- guardrails
- eval plan
- smallest useful version
- what not to automate yet
