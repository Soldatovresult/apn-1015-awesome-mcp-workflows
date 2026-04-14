# Contributing

## English

This repo accepts three kinds of contributions:

- server patterns
- workflow patterns
- recipe-style combinations of servers and workflows

### Submission Rules

- Be concrete. Name one primary user and one primary job to be done.
- Be honest about evidence. If your entry is only a reusable idea, label it `Pattern seed`.
- Do not claim "best", "widely used", "production-ready", or "actively maintained" without a source.
- Call out trust boundaries for local files, shell access, secrets, browsers, internal docs, and destructive SaaS actions.
- Prefer compact, structured entries over essay-style writeups.
- If your entry depends on a human approval step, say so explicitly.

### Required Fields

Every entry should include most of the following:

- title
- type
- status
- summary
- target user
- problem solved
- inputs
- outputs
- server mix or capability mix
- trust boundary
- why it matters
- evidence note

### Quality Bar

Strong submissions usually score well on the rubric in [`docs/evaluation-rubric.md`](./docs/evaluation-rubric.md):

- problem clarity
- believable user pull
- operational realism
- safety and trust clarity
- composability
- demoability

### PR Checklist

Before opening a PR, check these:

- the entry fits one of the repository content types
- the status label matches the evidence level
- claims are sourced or clearly marked as pattern-level
- internal links work
- the writing is easy to scan

### Template

Use [`docs/submission-template.md`](./docs/submission-template.md) for new entries.

## 中文

这个仓库接受三类内容：

- server 模式
- workflow 模式
- server 与 workflow 的组合方案

### 投稿规则

- 要具体。请写清一个主要用户和一个主要任务。
- 要诚实。如果只是一个可复用思路，请标记为 `Pattern seed`。
- 如果没有来源，不要声称“最佳”“广泛使用”“生产可用”或“持续维护”。
- 涉及本地文件、shell、密钥、浏览器、内部文档或破坏性写操作时，要明确写出信任边界。
- 优先提交结构化、便于扫读的条目，不要写成长篇散文。
- 如果流程需要人工审批或人工确认，也请明确写出来。

### 推荐字段

每个条目最好覆盖这些字段中的大部分：

- 标题
- 类型
- 状态
- 简述
- 目标用户
- 解决的问题
- 输入
- 输出
- 所需 server 或能力组合
- 信任边界
- 为什么重要
- 证据说明

### 质量标准

高质量投稿通常会在 [`docs/evaluation-rubric.md`](./docs/evaluation-rubric.md) 的这些维度上表现较好：

- 问题是否清晰
- 用户需求是否可信
- 落地是否现实
- 安全与信任边界是否清楚
- 是否容易组合
- 是否容易解释和演示

### PR 自检

提交前请确认：

- 条目确实属于本仓库定义的内容类型
- 状态标签与证据强度一致
- 所有宣称要么有来源，要么明确说明只是模式层建议
- 内部链接可用
- 文案便于快速扫读

### 模板

新条目建议直接从 [`docs/submission-template.md`](./docs/submission-template.md) 开始。
