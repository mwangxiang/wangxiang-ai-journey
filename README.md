# WangXiang AI Journey

> Building a personal AI assistant in public — learning logs, workflows, case studies, and practical guides by 王相.

一个公开记录 **王相从零开始构建、使用、维护个人 AI 助手全过程** 的项目。

这个仓库既是：
- **学习日志**
- **实践复盘**
- **教程与案例库**
- **王相的公开作品集 / 简历项目**

---

## 项目亮点

- **Build in public**：公开展示真实推进过程，而不是只展示结果
- **新手友好**：尽量少黑话，强调从 0 到 1 的真实路径
- **强调细节**：保留踩坑、调整、推翻、重做这些过程信息
- **重视安全**：尽可能公开，但严格做脱敏处理
- **长期维护**：不是一次性文章，而是持续更新的公开项目

---

## 这个项目在做什么

这是一个公开记录 **个人 AI 助手如何真正落地到日常工作流里** 的项目。

它不只是“配个机器人”，而是围绕下面这些问题持续实践：

- AI 助手到底能帮人做什么？
- 怎么让它真的融入日常使用，而不是摆设？
- 遇到问题时，怎么排查、修正、复盘？
- 怎么把使用经验整理成别人也能参考的方法？
- 怎么把这个过程做成一个对外可展示、可持续维护的项目？

---

## 适合谁看

这个项目主要写给：

- 想从零开始搭个人 AI 助手的新手
- 想看真实实践过程，而不是只看结论的人
- 想了解 agent / OpenClaw / 自动化工作流思路的人
- 想把 AI 实践做成公开项目或作品集的人

---

## 仓库内容结构

### 1. Learning Log
记录真实推进过程：
- 今天做了什么
- 遇到了什么问题
- 怎么定位
- 怎么解决
- 下一步做什么

### 2. Workflows
整理可复用工作流：
- 文档处理
- 提醒与任务管理
- 知识归档
- 浏览器自动化
- GitHub 项目维护

### 3. Case Studies
沉淀完整案例：
- 某次自动化怎么搭起来的
- 某次失败如何复盘
- 某个流程为什么这样设计

### 4. Guides
写给新手的实用指南：
- 从零开始
- 常见问题排查
- 配置思路
- 最小可行方案

---

## 精选内容入口

如果你想快速理解这个项目，建议先看这几篇：

- [`docs/learning-log/2026-03-09-project-init.md`](docs/learning-log/2026-03-09-project-init.md) —— 项目是怎么开始的
- [`docs/case-studies/2026-03-09-github-cli-login-and-repo-bootstrap.md`](docs/case-studies/2026-03-09-github-cli-login-and-repo-bootstrap.md) —— 用手机远程协助完成 GitHub CLI 登录与项目初始化
- [`docs/case-studies/2026-03-09-why-build-this-in-public.md`](docs/case-studies/2026-03-09-why-build-this-in-public.md) —— 为什么要把 AI 助手实践做成公开项目
- [`docs/workflows/openclaw-github-maintenance.md`](docs/workflows/openclaw-github-maintenance.md) —— 如何用 OpenClaw 持续运维一个公开 GitHub 项目
- [`docs/workflows/openclaw-research-and-file-delivery.md`](docs/workflows/openclaw-research-and-file-delivery.md) —— 如何用 OpenClaw 快速、准确地查资料并把结果发送给用户
- [`docs/workflows/external-signal-daily-briefing-method.md`](docs/workflows/external-signal-daily-briefing-method.md) —— 如何做可复刻的“外部发现日报”，并自动产出 Markdown 文档
- [`docs/workflows/external-signal-daily-briefing-template.md`](docs/workflows/external-signal-daily-briefing-template.md) —— 外部发现日报的 Markdown 输出模板
- [`docs/workflows/external-signal-daily-briefing-prompt-template.md`](docs/workflows/external-signal-daily-briefing-prompt-template.md) —— 外部发现日报的执行提示词模板
- [`docs/workflows/github-project-maintenance.md`](docs/workflows/github-project-maintenance.md) —— 如何持续维护一个公开 GitHub 项目
- [`docs/case-studies/2026-03-09-finding-and-delivering-a-paper-from-shit-journal.md`](docs/case-studies/2026-03-09-finding-and-delivering-a-paper-from-shit-journal.md) —— 如何从 S.H.I.T Journal 精准找到目标论文并直接交付文件
- [`docs/guides/how-to-read-this-project.md`](docs/guides/how-to-read-this-project.md) —— 第一次看这个项目，应该怎么读

## 先看哪里

如果你第一次来到这个仓库，建议按下面顺序看：

1. [`ROADMAP.md`](ROADMAP.md) —— 看项目现在在哪个阶段
2. [`docs/guides/getting-started.md`](docs/guides/getting-started.md) —— 看新手入口
3. [`docs/guides/how-to-read-this-project.md`](docs/guides/how-to-read-this-project.md) —— 看阅读路线
4. [`docs/learning-log/2026-03-09-project-init.md`](docs/learning-log/2026-03-09-project-init.md) —— 看项目是怎么开始的
5. [`docs/case-studies/`](docs/case-studies/) —— 看完整案例
6. [`docs/workflows/`](docs/workflows/) —— 看可复用工作流

---

## 项目原则

### 1. 公开，但不裸奔
尽量公开真实细节，展示诚意和过程感；
但所有涉及隐私、安全、密钥、账户、基础设施敏感信息的内容，都会做脱敏处理。

详见：[`docs/desensitization-policy.md`](docs/desensitization-policy.md)

### 2. 记录真实过程，而不是事后美化
这里会保留：
- 失败
- 重试
- 改方向
- 推翻重来
- 选择与取舍

因为真正有价值的，不只是“成功了”，而是：
**为什么这么做、哪里踩坑、最后如何变得更好。**

### 3. 新手友好优先
会尽量减少只对老手有意义的表达。
如果必须使用术语，会尽量补背景。

---

## 当前状态

当前阶段：**项目初始化 + 第一版公开骨架已建立**

已经完成：
- GitHub 仓库创建
- 第一版 README / ROADMAP / CONTRIBUTING / CHANGELOG / SECURITY
- 脱敏公开规范
- 第一篇 learning log
- 基础目录结构与 issue / PR 模板

下一步重点：
- 补第一批真实案例
- 强化 README 的作品集展示感
- 沉淀更多 workflow 与 guide
- 建立持续更新节奏

---

## 为什么它值得关注

很多 AI 项目喜欢展示“最终很厉害的结果”，但不展示：
- 一开始有多乱
- 中间踩过什么坑
- 哪些方法实际没用
- 为什么最后选了这一套工作流

而这个项目，想公开的正是这些最有参考价值的部分。

---

## 参与方式

如果你有建议、发现问题、或者也在做类似项目，欢迎：

- 提 Issue
- 提改进建议
- 分享你的实践经验

详见：[`CONTRIBUTING.md`](CONTRIBUTING.md)

---

## License

当前默认按 MIT 方向处理，后续如有必要再补正式 LICENSE。
