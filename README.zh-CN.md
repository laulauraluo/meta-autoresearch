# meta-autoresearch

**按科研任务查找 auto research skills 与 AI research agents。**

[English](README.md) · 简体中文

从文献、实验、图表到论文写作、引用、审稿和投稿，找到适合当前任务的入口。这个索引链接到原项目，并说明实际用过什么：**30 个条目，10 个分类**。

[浏览完整目录](CATALOG.zh-CN.md) · [使用与试用记录](TRIALS.zh-CN.md) · [JSON 索引](catalog.json)

## 目录

- [分类总览](#categories)
- [从当前任务开始](#quickstart)
- [读懂使用状态](#experience)
- [目录如何组织](#how-it-works)
- [供 agent 与工具读取](#for-agents)
- [仓库文档导航](#repository-guide)
- [建议收录条目](#contributing)

<a id="categories"></a>

## 分类总览

| 分类 | 适合这样的任务 | 示例 |
| --- | --- | --- |
| [完整科研流程](CATALOG.zh-CN.md#research-pipelines) | 编排选题、实验与论文写作 | AutoResearchClaw；The AI Scientist |
| [综合技能套件](CATALOG.zh-CN.md#skill-suites) | 查找覆盖多项科研任务的技能集合 | Academic Research Skills；AI Research Skills；Scientific Agent Skills |
| [文献检索与阅读](CATALOG.zh-CN.md#literature) | 发现、筛选、比较并综合论文 | ARS deep-research；sr-screener |
| [实验与评测](CATALOG.zh-CN.md#experiments) | 迭代实验或检查评测设计 | karpathy/autoresearch；acl-experiments |
| [绘图与可视化](CATALOG.zh-CN.md#figures) | 绘制实测结果或解释方法 | academic-plotting；scientific-visualization；scientific-schematics |
| [论文写作与润色](CATALOG.zh-CN.md#writing) | 改善论证、文字与领域表达 | ml-paper-writing；research-paper-writing；writing-clearly-and-concisely |
| [引用核验与管理](CATALOG.zh-CN.md#citations) | 管理参考文献并检查引用一致性 | ARS citation-check；citation-management |
| [审稿、修改与审稿回复](CATALOG.zh-CN.md#review) | 审查论文并回应审稿意见 | academic-paper-reviewer；pre-submission-reviewer；academic-rebuttal |
| [投稿规范与复现](CATALOG.zh-CN.md#submission) | 准备投稿材料与可复用证据 | acl-submission；acl-reproducibility |
| [报告与演讲](CATALOG.zh-CN.md#presentations) | 将论文转化为幻灯片和讲者备注 | presenting-conference-talks |

<a id="quickstart"></a>

## 从当前任务开始

1. **选任务。** 打开上方分类，比较目录中的具体组件。
2. **看证据。** 阅读使用状态和范围说明。测过一个解析器，不等于跑通过整套科研流程。
3. **去上游。** 按原项目文档检查安装方式、版本、模型、API、硬件与费用。本仓库不安装或执行这些工具。

| 当前任务 | 建议阅读路线 |
| --- | --- |
| 修改论文 | [结构与论证](CATALOG.zh-CN.md#writing-structure) → [领域规范](CATALOG.zh-CN.md#writing-discipline) → [语言润色](CATALOG.zh-CN.md#writing-language) |
| 准备论文配图 | 选择[数据图或示意图](CATALOG.zh-CN.md#figures)，再与原始结果核对 |
| 检查文献综述 | [检索与筛选论文](CATALOG.zh-CN.md#literature)，再对照原文[核验引用](CATALOG.zh-CN.md#citations) |
| 回复审稿意见 | 阅读[审稿与回复](CATALOG.zh-CN.md#review)，再检查目标会议的回复规则 |
| 探索自动化科研 | 比较[完整科研流程](CATALOG.zh-CN.md#research-pipelines)与[有边界的实验循环](CATALOG.zh-CN.md#experiments)，再查看[尚未验证的部分](TRIALS.zh-CN.md) |

这些是阅读路线，无需按顺序把所有 skill 都跑一遍。

<a id="experience"></a>

## 读懂使用状态

| 状态 | 现有证据支持什么 |
| --- | --- |
| **已使用（Used）** | 该组件或明确说明的部分已用于真实任务；具体范围见条目说明。 |
| **已测试代码（Code-tested）** | 调查并测试过局部代码；科研产出质量可能尚未评估。 |
| **已查阅（Inspected）** | 查阅过文档或源码；没有确认的个人执行记录。 |

状态描述使用深度，不是评分或对整个项目的背书。安装过不等于用过；收录套件不等于其中每个 skill 都用过。[使用记录](TRIALS.zh-CN.md)保留了这些边界。

<a id="how-it-works"></a>

## 目录如何组织

**Auto research skill** 为兼容的 agent 提供科研任务所需的指令、参考资料，有时也包含脚本。**技能套件**汇集多个组件。**科研流程系统**还提供编排或执行机制。覆盖任务多，并不代表能独立完成实验。

条目可以是项目、具体组件或 skill 内的一个模式。同一仓库下不同组件分别计数；跨两个分类的同一组件只计一次。三个实际用过的本地 skill 尚未核实公开来源，因此没有安装链接，也不再分发其内容。

<a id="for-agents"></a>

## 供 agent 与工具读取

[catalog.json](catalog.json) 提供稳定的条目 ID、分类 ID、上游链接、组件类型和使用范围说明。按任务阅读可选择[英文目录](CATALOG.md)或[中文目录](CATALOG.zh-CN.md)；[llms.txt](llms.txt) 提供两个语言版本的入口。

URL 为 null 表示来源尚未核实，不应猜测安装地址。当前行为以上游文档为准。目录不包含上游源码、私有论文或未公开的评审输出。机器可读导航方便读者定位内容，但不能保证被索引、获得搜索排名或被 agent 优先推荐。

<a id="repository-guide"></a>

## 仓库文档导航

| 文档 | 英文 | 简体中文 |
| --- | --- | --- |
| 概览与任务路线 | [README.md](README.md) | [README.zh-CN.md](README.zh-CN.md) |
| 全部条目及使用范围 | [CATALOG.md](CATALOG.md) | [CATALOG.zh-CN.md](CATALOG.zh-CN.md) |
| 使用记录与待验证问题 | [TRIALS.md](TRIALS.md) | [TRIALS.zh-CN.md](TRIALS.zh-CN.md) |
| 新条目填写格式 | [ENTRY_TEMPLATE.md](ENTRY_TEMPLATE.md) | [ENTRY_TEMPLATE.zh-CN.md](ENTRY_TEMPLATE.zh-CN.md) |

共用的 [catalog.json](catalog.json) 是结构化索引的准本；[llms.txt](llms.txt) 是可选阅读导航。两种语言的 Markdown 文档与索引一起维护。

<a id="contributing"></a>

## 建议收录条目

使用[条目模板](ENTRY_TEMPLATE.zh-CN.md)，链接到具体上游组件，说明对应任务、实际尝试和未验证部分。同步更新两个语言版本及 JSON 索引。流行程度本身不能证明科研质量。
