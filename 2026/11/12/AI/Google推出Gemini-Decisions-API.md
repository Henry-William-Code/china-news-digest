# Google 推出 Gemini Decisions API，用于快速多模态封闭式决策

- **栏目**：AI
- **来源**：[Google 官方博客](https://blog.google/innovation-and-ai/technology/developers-tools/gemini-decisions-api/)
- **原始发布时间**：2026-11-11
- **时间说明**：官方博客只标注 Nov 11, 2026，未给出时分，不臆造具体钟点。
- **时效**：页面写明即日起可通过 Gemini API 在 Google AI Studio 使用

Google 宣布推出 Gemini Decisions API，由新模型 Gemini Decision 1（gemini-decision-1）驱动，通过 Gemini API 在 Google AI Studio 提供。该接口面向是非判断、多选和量表打分等封闭式决策，可在一次请求中对同一段多模态输入并行评估最多 1,000 个问题。官方说明支持文本、图片、音频、视频和 PDF，共享输入最长 256K tokens。

页面写明，模型以单次前向传播为候选选项打分并返回概率与置信度，端到端时延约为 150–250 毫秒；定价为每百万输入 tokens 0.10 美元，输出 tokens 不计费。文中举例可用于工具选择、策略检查、模型路由和上下文评分。Google 称内部已用于 Gemini Notebook 的实时路由、Stitch 的快速画布实验、Labs 产品 CC 的表情选择，以及 Search 中 MCP 工具的安全层。文档、演示与 Python、JavaScript、REST 指南现已开放；生态集成正在向 OpenRouter、LangChain、Vercel、LiteLLM 等推进，Google Cloud 上的 Gemini 支持则写明即将推出。上述性能、时延和比价表述来自官方披露。

**为何值得关注：** 这是面向低时延控制面的专用决策接口，而不是再发一条通用对话模型，并同时给出了延迟、计费和接入路径。

[返回当日日报](../日报.md) · [返回首页](../../../../README.md)
