# RLAgent

自研轻量 Agent 框架（Python）：以「设计级复刻 OpenCode」为主线，对照 Pi、DeepSeek Harness 等开源 Agent 的实现取舍，融合出自己的版本。

> 本仓库为代码仓库。学习笔记、路线图、JD 能力矩阵与模块讲稿在父目录的学习仓库（`../docs/`）。

## 路线图（摘要）

- M1 核心 agentic loop + tool calling（裸 SDK 自研）
- M2 工具系统 + 权限/审批流 + 沙箱隔离
- M3 会话持久化 + 事件溯源 + 上下文/记忆管理
- M4 RAG（embedding + 向量库）
- M5 多 Agent / subagent + MCP（client + 自实现 server）
- M6 产品化全链路（FastAPI + Web 前端）
- M7 Prompt/速度优化 + eval + 开源发布
