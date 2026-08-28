<div align="center">
  <img src="./bloom.svg" width="720" alt="hey-Chloe blooming banner" />
</div>

<h1 align="center">寇依 · hey-Chloe</h1>

<p align="center">
  <strong>2028 届 · LLM 算法 / 检索排序 / 评测</strong><br/>
  Retrieval, Ranking & Evaluation · Agent Runtime and AI Backend as supporting engineering evidence
</p>

我关注可验证的检索、排序与评测方法，也会把 Agent Runtime 和 AI 后端做成可运行、可测试、可审计的系统。这里的公开仓库用于展示实现与实验过程，不代表生产采用或开源影响力。

## Focus

- **Retrieval & Ranking** — candidate retrieval, learning-to-rank, calibration, debiasing and offline evaluation
- **LLM / RAG Evaluation** — data provenance, split discipline, leakage checks and reproducible artifacts
- **Agent Systems** — bounded loops, tool execution, permission gates, persistence and failure recovery

## Selected Work

- **[MiniClaudeCode](https://github.com/hey-Chloe/MiniClaudeCode)**
  一个小型、可测试的 Coding Agent Runtime：bounded agent loop、schema 校验工具、`ALLOW / ASK / DENY` 权限策略、可插拔运行时、会话恢复与离线 / repo-level evaluation。

- **[KAI-Offline-RecSys-Lab](https://github.com/hey-Chloe/KAI-Offline-RecSys-Lab)**
  基于公开数据的离线推荐实验室，覆盖召回、统一排序、CTR / CVR、去偏、校准与 bootstrap evaluation；不把离线结果写成在线 CTR、转化率或收入提升。

- **[enterprise-agentic-rag](https://github.com/hey-Chloe/enterprise-agentic-rag)**
  面向合成企业语料的 Agentic RAG 试验台，覆盖层级切块、混合检索、重排、LangGraph 编排、工具安全门与评测管线。结果属于 synthetic / offline evidence，不等同于生产验证。

- **[ReminderCat](https://github.com/hey-Chloe/ReminderCat)**
  企业微信提醒 Agent：自然语言意图解析、工具执行、PostgreSQL 持久化、定时推送、幂等去重、重试与超时恢复。端到端手机提醒验收为仓库记录，未写成外部采用证明。

- **[RuleForge-SAST](https://github.com/hey-Chloe/RuleForge-SAST)**
  基于 Semgrep 的多语言 SAST 工具，提供漏洞解释、AI 辅助修复建议与 patch 二次扫描验证，并保留演示视频和界面证据。

- **[Portfolio — Chloe’s Archive](https://hey-chloe.github.io/)** · [source](https://github.com/hey-Chloe/hey-Chloe.github.io)
  已公开部署的中文数字作品集，按 Work / Lab / Notes 组织产品、系统、实验与证据边界。

## Evidence Policy

- `synthetic`、`offline`、`prototype`、`not_executed` 等状态会明确保留。
- 指标只有在数据、划分、baseline、配置、产物与代码版本能够追溯时才进入对外表述。
- Public code is implementation evidence — not automatic proof of production use, user adoption or open-source impact.

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="garden-footer-night.svg" />
    <img src="garden-footer.svg" width="900" alt="garden footer" />
  </picture>
</div>
