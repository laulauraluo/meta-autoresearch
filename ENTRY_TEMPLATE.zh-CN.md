# 条目模板

[English](ENTRY_TEMPLATE.md) · 简体中文

[概览](README.zh-CN.md) · [目录](CATALOG.zh-CN.md) · [使用记录](TRIALS.zh-CN.md)

每个条目描述一个项目或具体组件。链接到原始来源，不复制 skill 全文。按下列字段整理后交给整理者审核。

## 项目或具体组件

- **ID：** 稳定的小写标识符；更新记录时沿用已有 ID。
- **名称：** 上游项目或组件的名称。
- **上游：** 项目或组件的规范链接；本地来源未核实时使用 null。
- **类型：** 科研流程系统 / 技能套件 / 实验循环 / 技能 / 技能模式 / 本地技能。
- **分类：** 使用 catalog.json 中的分类 ID；允许多个分类。
- **适合任务：** 该组件解决的具体任务。
- **使用状态：** used / code-tested / inspected，含义遵循目录定义。
- **实际尝试范围：** 在哪个组件上做过什么；不公开未发表研究细节。
- **有帮助之处：** 实际观察到的收益，或明确写“尚未评估”。
- **局限：** 已观察到的失败、必要的人工检查与未测试功能。
- **使用要求：** 相关运行环境、模型/API、硬件或费用要求；尽可能附上游依据。
- **上次来源核查：** 日期；已知时记录版本或 commit。
- **整理者决定：** 收录 / 修改 / 暂缓。

## 对应结构化索引

沿用 [catalog.json](catalog.json) 的记录结构，包括 `id`、`name`、`url`、`kind`、`categories`、`description`、`experience`、`experience_notes`、`writing_group` 和 `source_status`。

`kind` 可取 `research-pipeline`、`skill-suite`、`experiment-loop`、`skill`、`skill-mode` 和 `local-skill`。写作条目的 `writing_group` 可取 `structure`、`language`、`discipline` 或 `revision`；其他条目使用 null。准确填写 `source_status`：`verified-upstream` 只表示已确认上游来源，不代表验证过工具产出；`unresolved-local-origin` 对应尚未核实的本地来源及 null URL。

在 `description` 中写具体任务，在 `experience_notes` 中写证据支持的使用范围和局限。有用的补充审核细节可放入使用记录页；无需为了填满表格而杜撰 JSON 字段。

## 提交条目前检查

- 检查是否已有相同 ID 或组件；增加第二个分类无需复制条目。
- 核实具体上游 URL，或保留 null。不要根据相似名称猜测公开来源。
- 区分已使用、已测试代码和已查阅的证据。收录套件不代表其中每个 skill 都用过。
- 同步更新中英文目录、相关使用记录及结构化索引。两种语言保留相同链接与范围。
- 检查文档内部链接和锚点。不包含私有论文、评审原文、凭据或本机路径。

收录是编辑选择，不保证质量，也不代表已成功完成端到端科研。
