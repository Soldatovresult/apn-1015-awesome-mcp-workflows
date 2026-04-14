[English](./README.md) | [中文](./README.zh-CN.md)

# awesome-mcp-workflows

一个中英双语、以“模式”优先的 MCP 内容仓库，用来整理可复用的工作流、服务形态和可发布的组合方向。

这个仓库刻意保持诚实：

- 它是策展型目录，不是假装实时更新的排行榜
- 它收录的是可复用模式，不是空泛的宣传 demo
- 它服务于产品选题和内部工具设计，不制造不存在的市场结论

大多数条目会先以 `Pattern seed` 的形式存在。只有当贡献者补充了明确来源、实现说明或公开案例时，才应该把条目标成更具体的 `Documented example`。

## 快速导航

- 看内容目录：[lists/servers.md](./lists/servers.md)、[lists/workflows.md](./lists/workflows.md)、[lists/recipes.md](./lists/recipes.md)
- 看编辑规则：[docs/evaluation-rubric.md](./docs/evaluation-rubric.md)、[docs/taxonomy.md](./docs/taxonomy.md)、[docs/submission-template.md](./docs/submission-template.md)
- 看协作与治理：[CONTRIBUTING.md](./CONTRIBUTING.md)、[CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md)、[SECURITY.md](./SECURITY.md)、[docs/releases/v0.1.0.md](./docs/releases/v0.1.0.md)

## 这里收什么

- 有明确用户、触发条件和输出结果的工作流
- 信任边界清晰的 MCP server 模式
- 能组合成产品或内部工具的 server + workflow 套路
- 能帮助后续投稿保持一致性的策展规则

## 这里不收什么

- “agent 什么都能做”的空泛想法
- 无法验证的 adoption、维护状态或性能宣称
- 没有工作流细节的供应商文案搬运
- 只追求新奇、不关心实用性的列表

## 仓库结构

内容目录：
- [lists/servers.md](./lists/servers.md)：可复用的 MCP server 模式
- [lists/workflows.md](./lists/workflows.md)：面向真实工作的工作流模式
- [lists/recipes.md](./lists/recipes.md)：可组合的方案包与发布方向

编辑文档：
- [docs/evaluation-rubric.md](./docs/evaluation-rubric.md)：策展评分维度
- [docs/taxonomy.md](./docs/taxonomy.md)：统一使用的标签与分类
- [docs/submission-template.md](./docs/submission-template.md)：投稿模板

协作与治理：
- [CONTRIBUTING.md](./CONTRIBUTING.md)：投稿规则与 PR 检查项
- [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md)：参与规范与处理方式
- [SECURITY.md](./SECURITY.md)：仓库内容与工具链的安全报告说明
- [docs/releases/v0.1.0.md](./docs/releases/v0.1.0.md)：首个公开版本的 release notes 草稿

## 条目应该回答什么

高质量条目通常会用简洁方式回答这些问题：

- 解决了什么问题？
- 主要用户是谁？
- 输入和输出是什么？
- 需要哪些 server 或能力？
- 信任边界在哪里？
- 为什么它不只是一个 demo？
- 哪些内容是明确已知，哪些只是模式层面的建议？

## 编辑标签

- `Pattern seed`：描述的是一种可复用模式，还没有绑定具体公开实现
- `Documented example`：绑定了明确来源、实现说明或公开案例

标签必须和证据强度匹配，不能因为“听起来像生产可用”就擅自升级。

## 评价维度

仓库会从这些务实角度判断条目质量：

- 任务是否具体
- 用户需求是否可信
- 信任与安全边界是否清楚
- 落地成本是否现实
- 是否容易和其他 server 组合
- 是否便于理解、讲解和演示

完整说明见 [docs/evaluation-rubric.md](./docs/evaluation-rubric.md)。

## 从哪里开始看

- 想找 server 方向：看 [lists/servers.md](./lists/servers.md)
- 想找工作流：看 [lists/workflows.md](./lists/workflows.md)
- 想找更像产品的组合：看 [lists/recipes.md](./lists/recipes.md)
- 想投稿：先读 [CONTRIBUTING.md](./CONTRIBUTING.md) 和 [docs/submission-template.md](./docs/submission-template.md)

## 语言说明

- 列表内容以英文结构为主
- 中文用户可以先阅读本文件理解仓库目的和使用方式
- 辅助文档可以保持英文优先，但会尽量短且机械化

## 参与贡献

欢迎投稿，但门槛不是“有意思的链接”这么低：

- 优先提交边界清晰的工作流
- 诚实标注证据强度
- 说明为什么构建者会关心
- 把信任边界写清楚

具体规则见 [CONTRIBUTING.md](./CONTRIBUTING.md)。
