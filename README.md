# WangXiang AI Journey

> Building a personal AI assistant in public — learning logs, workflows, case studies, and practical guides by 王相.

## 项目是什么

这是一个公开记录 **王相构建、使用、维护个人 AI 助手全过程** 的项目。

它不是单纯的代码仓库，也不只是笔记仓库，而是三者混合：

- **使用记录**：真实怎么用，解决了什么问题
- **经验复盘**：踩了哪些坑，做了什么取舍
- **教程/案例展示**：把能复用的方法整理出来，帮助后来的人少走弯路

这个项目也会作为 **王相个人作品集 / 简历的一部分**，展示长期学习能力、执行力、项目维护能力，以及把 AI 工具真正落到工作流里的过程。

## 这个项目适合谁

- 对 AI 助手、自动化工作流感兴趣的新手
- 想从零开始搭自己的个人助手的人
- 想看真实踩坑过程，而不只是“成功学总结”的人
- 想了解 OpenClaw / agent / 工作流设计思路的人

## 你能在这里看到什么

### 1. Learning Log
记录真实学习过程：
- 今天做了什么
- 遇到了什么问题
- 怎么定位和解决
- 下一步准备做什么

### 2. Workflows
整理已经验证过的工作流：
- 文档处理
- 提醒和任务管理
- 知识归档
- 浏览器自动化
- GitHub 项目维护

### 3. Case Studies
沉淀具体案例：
- 某次自动化是怎么搭成的
- 某次失败是怎么复盘的
- 某个流程为什么这样设计

### 4. Guides
面向新手的实用指南：
- 从零开始
- 常见报错与排查
- 配置思路
- 最小可行方案

## 项目原则

### 公开，但不裸奔
这个项目会尽量公开真实细节，展示完整过程和诚意；
但所有涉及隐私、安全、密钥、账户、基础设施敏感信息的内容，都会做脱敏处理。

详见：[`docs/desensitization-policy.md`](docs/desensitization-policy.md)

### 记录真实过程，而不是事后美化
这里会保留尝试、失败、修改方向、推翻重来这些过程。

因为真正有价值的，不只是“最后成功了”，而是：
**为什么这么做、哪里踩坑、后来如何变得更好。**

### 新手友好
尽量减少只对老手有意义的黑话。
如果必须使用术语，会尽量配上背景解释。

## 当前仓库结构

```text
.
├─ README.md
├─ ROADMAP.md
├─ CONTRIBUTING.md
├─ CHANGELOG.md
├─ SECURITY.md
├─ docs/
│  ├─ desensitization-policy.md
│  ├─ learning-log/
│  ├─ case-studies/
│  ├─ workflows/
│  └─ guides/
├─ showcase/
│  ├─ screenshots/
│  ├─ demos/
│  └─ outcomes/
├─ templates/
└─ .github/
   └─ ISSUE_TEMPLATE/
```

## 从哪里开始看

如果你是第一次来，建议按这个顺序看：

1. `README.md` —— 先理解这个项目想做什么
2. `ROADMAP.md` —— 看当前阶段和后续方向
3. `docs/guides/` —— 看适合新手的说明
4. `docs/learning-log/` —— 看真实推进过程
5. `docs/case-studies/` —— 看具体案例

## 维护状态

当前处于：**项目初始化阶段**

第一阶段重点：
- 搭建公开仓库骨架
- 建立内容分类
- 明确公开边界与脱敏规则
- 开始持续记录学习与实践过程

## 参与方式

如果你有建议、发现问题、或者想交流类似实践，欢迎：
- 提 Issue
- 发起 Discussion（后续会逐步完善）
- 提交改进建议

详见：[`CONTRIBUTING.md`](CONTRIBUTING.md)

## License

暂定使用 MIT，后续如果有更合适的许可策略会再调整。
