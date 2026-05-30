# 发布配套文案

## 朋友圈版

最近把自己常用的一套 AI 产品需求评审框架，封装成了一个 Codex skill：`ai-product-requirement-review`。

它主要解决一个特别常见的问题：
很多 AI PRD 写得很长，但真进评审会的时候，模型可行性、数据方案、评测指标、兜底设计和安全边界都说不清楚。

所以我把这套检查逻辑做成了结构化 skill。

适合直接拿来审：

- AI 产品需求
- AI Agent 方案
- RAG / Copilot / 工作流自动化设计

GitHub：
https://github.com/fengzoey01-oss/ai-product-requirement-review

## 社群版

做了一个 AI 产品需求评审的 Codex skill，叫 `ai-product-requirement-review`。

它不是生成 PRD，而是专门用来“审 PRD”的。

核心会看这些问题：

- 需求是不是从真实问题出发
- 这个场景到底适不适合用 AI
- 模型选型和技术路线是否可行
- 数据、评测、延迟、成本、兜底方案有没有说清楚
- 有没有明显的安全、合规和上线风险

如果你经常做 AI 产品、Agent、RAG、企业智能流程，这个 skill 会很省事：
https://github.com/fengzoey01-oss/ai-product-requirement-review

## 公众号导语版

这段时间我越来越明显地感受到，AI 产品需求里真正难的，往往不是“想一个功能”，而是“判断这个功能到底能不能做、值不值得做、上线后会不会出问题”。

很多 PRD 看起来已经很完整了，但真正进入评审时，常常会卡在一些更底层的判断上：模型选型是不是合理、数据有没有来源、冷启动怎么过、效果怎么验收、延迟和成本能不能承受、AI 出错时怎么兜底，以及安全与合规风险到底有没有被认真考虑。

所以我把自己常用的一套 AI 产品需求评审逻辑，封装成了一个 Codex skill：`ai-product-requirement-review`。

仓库地址：
https://github.com/fengzoey01-oss/ai-product-requirement-review

## 仓库介绍开头版

`ai-product-requirement-review` is a Codex skill for reviewing AI product requirements with a delivery-oriented lens.

It helps teams evaluate whether an AI feature, agent workflow, or LLM-based product spec is actually feasible, measurable, and launch-ready across model choice, data readiness, evaluation, fallback design, latency, cost, and safety.
