# RLAgent

自研轻量 Agent 框架（Python）：以「设计级复刻 OpenCode」为主线，对照 Pi、DeepSeek Harness、kimi-code 等开源 Agent 与 LangGraph 框架的实现取舍，融合出自己的版本。

> 本仓库为代码仓库。拆解笔记、组件地图、演化图谱、设计文档与路线图在父目录的学习仓库（`../docs/`）。

## 路线图（摘要）

方法论：**拆解（A）→ 演化比较（B）→ 自主设计（C）→ 实现（D）**，拆解先于编码。

实现阶段（D）按需求驱动扩张，每阶段产出一个能跑的东西：

- **P0 本体核心**：S0 单轮对话 → S1 多轮 → S2 流式 → S3 工具循环 → S4 工具集 → S5 Provider 抽象 → S6 System Context → S7 CLI → S8 会话持久化 → S9 权限审批
- **P1 差异化能力**：S10 沙箱隔离 → S11 事件溯源 → S12 上下文压缩/记忆 → S13 RAG → S14 Subagent → S15 MCP
- **P2 产品化与收口**：S16 FastAPI + React 全链路 → S17 优化/eval/开源/简历
