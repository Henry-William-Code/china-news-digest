# Kimi Code 发布稳定版 2.5.3，支持中断后在同一轮继续

- **栏目**：AI
- **来源**：[Kimi Code GitHub 发布页](https://github.com/MoonshotAI/kimi-code/releases/tag/%40moonshot-ai%2Fkimi-code%402.5.3) · [Kimi Code 官方变更记录](https://moonshotai.github.io/kimi-code/zh/release-notes/changelog.html)
- **原始发布时间**：2026-11-10 21:06
- **时间说明**：GitHub 发布时间为 2026-11-10T13:06:22Z，换算为上海时间 21:06。
- **时效**：最近约 24 小时

月之暗面发布 Kimi Code 稳定版 2.5.3。官方中文变更记录将主要更新概括为：优化 steer 插话逻辑；改进 Web 交互并修复已知问题；修复 Windows 上把 stdio MCP 服务器配置为 `npx` 等脚本命令时无法启动的问题。

GitHub 发布说明写得更具体：steering 可中断正在进行的模型请求，并在同一轮中继续；同时新增 `POST /api/v1/sessions/{session_id}/steer`，用于一次请求完成消息插话。该版本为正式稳定版，不是 canary。
**为何值得关注：** 这是可核对的官方小版本，核心改进集中在插话中断与 Windows 上 MCP 脚本启动修复。

[返回当日日报](../日报.md) · [返回首页](../../../../README.md)
