# DeepMind 发布 AlphaGenome 2，用于预测 DNA 变异在特定细胞类型中的影响

- **栏目**：AI
- **来源**：[Google DeepMind 官方博客](https://deepmind.google/blog/alphagenome-2-deciphering-how-cells-read-dna-to-better-understand-disease/)
- **原始发布时间**：2026-11-11
- **时间说明**：官方博客标注 November 11, 2026，未给出时分。文中写 Today, we are announcing AlphaGenome 2。
- **时效**：即日起向非商业研究开放 API，商业研究为私人预览；官方明确仅供研究使用

Google DeepMind 发布新一代 DNA 序列模型 AlphaGenome 2。与上一版同时预测多种组织不同，新模型改为按单一生物学条件（组织、细胞类型或细胞状态）做条件预测，并可用研究者自己的单细胞实验经细胞编码器生成条件，而无需重新训练。官方称模型在人类和小鼠的批量及单细胞数据上训练，包含超过 1.07 亿个细胞图谱、覆盖 68 种组织，可预测基因表达、组蛋白修饰、染色质可及性，并新增了甲基化输出。

DeepMind 写道，在 TenK10K 的 28 种原代免疫细胞数据上，它识别到的因果变异比例约为 30%，方向性基因效应约为 43%，高于经单细胞数据微调的原版 AlphaGenome 及其他专用工具给出的 16% 和 23%。该模型即日起通过 AlphaGenome API 向非商业研究开放，商业研究为私人预览。页面明确说明仅供研究使用，尚未针对临床或诊断用途完成验证或批准。文中还提到，后续计划在 Google Antigravity 中发布 AlphaGenome 2 Skills。上述评测数字来自官方披露。

**为何值得关注：** 这是 DeepMind 在基因组序列模型上的一次正式迭代，把预测从组织平均推进到细胞类型，并同步开放研究接口。

[返回当日日报](../日报.md) · [返回首页](../../../../README.md)
