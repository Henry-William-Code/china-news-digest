# DeepSeek-V4 系列模型上架 Amazon SageMaker JumpStart

- **栏目**：AI
- **来源**：[AWS What's New](https://aws.amazon.com/about-aws/whats-new/2026/01/deepseek-v4-pro-v4-flash-v4.1-flash-on-sagemaker-jumpstart/)
- **原始发布时间**：2026-11-11
- **时间说明**：页面正文标注 Posted on: Nov 11, 2026。URL 路径含 /2026/01/，发稿日期以页面标注为准。这是现有开源权重模型在 AWS 上的上架，不是 DeepSeek 发布新模型。
- **时效**：公告称现已可在 SageMaker JumpStart 部署

AWS 宣布 DeepSeek-V4-Pro、DeepSeek-V4-Flash 和 DeepSeek-V4.1-Flash 已可在 Amazon SageMaker JumpStart 部署。公告称这三款均为采用 MIT 许可的开源权重混合专家（MoE）语言模型，面向推理、编程和智能体工作负载。AWS 转述的规格为：V4-Pro 总参数 1.6T、每 token 激活 49B，支持 1M 上下文；V4-Flash 总参数 284B、每 token 激活 13B，同样支持 1M 上下文；V4.1-Flash 采用 Causal Encoder-Decoder 架构，主干 552B 参数，预填充激活 8B、解码激活 16B，支持 1M 上下文和最多 384K 输出 tokens，并称其 Compressed Sparse Attention 2 与 FP4 KV 缓存把全局 KV 缓存占用降至约 V4-Flash 的四分之一。

用户可在 SageMaker 控制台的 JumpStart 目录中点击部署，或通过 SageMaker Python SDK 在自己的账户中部署。上述参数、架构和性能表述来自 AWS 公告对模型规格的转述。

**为何值得关注：** DeepSeek 在窗口内没有新的官方模型发布，但这是其 V4 系列在主流云平台上的一次正式开通。

[返回当日日报](../日报.md) · [返回首页](../../../../README.md)
