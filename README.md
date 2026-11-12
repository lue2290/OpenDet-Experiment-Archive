# OpenDet 实验归档

本仓库归档 OpenDet / CoRef 的实验脚本、配置与运行结果。实验分卷在 Releases 发布。

| 分卷前缀 | 内容 |
| --- | --- |
| 01-code-and-config | 实验入口、源码、工具、配置、依赖、文档和划分索引 |
| 02-results | 指标、预测 JSON、校准、运行锁、评估日志和逐目标诊断 |
| 03-candidates | 候选框、候选 ID、分数和 logits。混合缓存仅保留候选输出字段 |
| 04-coref-seed42-images | CoRef seed 42 的实际预测可视化（有可核验的产物时提供） |

历史归档内保留的条目位于对应的 .zip.contents 目录。数据集、权重、原始图片、磁盘清理审计与凭据不属于公开归档。

下载 Release 的分卷、MANIFEST.json 和 SHA256SUMS 至同一目录。使用 sha256sum -c SHA256SUMS 校验，再将所有分卷解压到同一目标目录。MANIFEST.json 可按原实验路径查询所属分卷和文件哈希。