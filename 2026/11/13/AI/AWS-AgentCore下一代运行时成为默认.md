# Amazon Bedrock AgentCore 下一代运行时在多地成为默认，官方称会话启动显著加快

- **栏目**：AI
- **来源**：[AWS What's New](https://aws.amazon.com/about-aws/whats-new/2026/11/new-agentcore-runtime-default/)、[AWS 机器学习博客](https://aws.amazon.com/blogs/machine-learning/run-agents-securely-and-efficiently-with-the-next-generation-agentcore-runtime/)
- **原始发布时间**：2026-11-12
- **时间说明**：What's New 与机器学习博客均只标注 2026-11-12，未给出时分。

AWS 于 11 月 12 日宣布，Amazon Bedrock AgentCore 的新建运行时在多个区域默认改用下一代（V2）运行时。官方介绍，新运行时仍为每个会话提供独立的 Firecracker 微虚拟机隔离，但会从已初始化智能体的快照恢复会话，并按工作负载伸缩计算和内存，空闲时可缩减至零。会话最高可使用 8 个 vCPU 和 32 GB 内存，容器镜像最大 10 GB。

AWS 称，在 2 GB 镜像上，会话启动时间的 P75 从 29.7 秒降至 2 秒以内；空闲智能体可在释放内存后数分钟内回收资源，多轮会话最多可减少 68% 的计费内存。已有运行时不会自动迁移，需将 platformVersion 设为 V2；若要继续使用旧版，新建时可将该参数设为 V1。该默认变更已在美国东部（弗吉尼亚北部、俄亥俄）、美国西部（俄勒冈）以及欧洲、亚太等多个区域生效。上述启动时延和内存节省数字均为 AWS 官方说明。

**为何值得关注：** 这是 Bedrock 上智能体托管层的默认基础设施升级，直接影响在 AWS 上部署需要隔离执行环境的编码和浏览器类智能体。

[返回当日日报](../日报.md) · [返回首页](../../../../README.md)
