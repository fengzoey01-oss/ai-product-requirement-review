# ai-product-requirement-review

一个用于评审 AI 产品需求的 Codex skill。

它适合处理这类任务：

- 审 AI 产品 PRD
- 评估 AI Agent 需求是否合理
- 判断模型选型、数据方案、评测指标、兜底设计是否完整
- 找出需求中的风险点、缺项和伪需求

## 它解决什么问题

很多 AI 产品需求文档看起来很完整，但真正推进时会暴露这些问题：

- 需求是在写功能，不是在定义问题
- AI 能力边界没有说清楚
- 模型选型只是拍脑袋，没有技术可行性判断
- 数据、评测、成本、延迟、兜底没有写
- 产品说“能做”，但没有交代“怎么验收”

这个 skill 的作用，就是把这些问题系统化地审出来。

## 适合谁

- AI 产品经理
- Agent 产品设计者
- 需求评审参与方
- 想把 AI PRD 写得更像真实可落地方案的人

## 最短用法

```text
用 $ai-product-requirement-review 评审这个 AI 产品 PRD
```

也可以直接说：

```text
用 $ai-product-requirement-review 看看这个 AI Agent 需求有没有问题
用 $ai-product-requirement-review 帮我补模型、数据、评测和兜底方案
```

## 仓库结构

```text
.
├── SKILL.md
└── agents/
    └── openai.yaml
```

## 安装方式

复制到你的 Codex skills 目录：

```text
~/.codex/skills/ai-product-requirement-review
```

然后重启 Codex。
