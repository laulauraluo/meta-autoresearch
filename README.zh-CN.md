![meta-autoresearch — research tools, organized around the work](assets/research-map-banner.svg)

# meta-autoresearch

### 把研究任务放到同一张地图上。

[English](README.md) · 简体中文

Auto research skills、AI research agents 与科学工作流的任务目录。**30 个唯一条目 · 10 个分类**。每项保留具体组件、原始来源与有范围的使用记录。

[浏览完整目录](CATALOG.zh-CN.md) · [使用记录与缺口](TRIALS.zh-CN.md) · [JSON](catalog.json)

<a id="categories"></a>

## 研究任务地图

从任何任务进入；四组仅为阅读导航，不规定执行顺序。

| 从哪类工作进入 | 目录入口 |
| --- | --- |
| **组织研究** | [完整科研流程](CATALOG.zh-CN.md#research-pipelines) · [综合技能套件](CATALOG.zh-CN.md#skill-suites) |
| **查证与实验** | [文献检索与阅读](CATALOG.zh-CN.md#literature) · [实验与评测](CATALOG.zh-CN.md#experiments) · [绘图与可视化](CATALOG.zh-CN.md#figures) |
| **表达与核查** | [论文写作与润色](CATALOG.zh-CN.md#writing) · [引用核验与管理](CATALOG.zh-CN.md#citations) · [审稿、修改与回复](CATALOG.zh-CN.md#review) |
| **交付研究** | [投稿规范与复现](CATALOG.zh-CN.md#submission) · [报告与演讲](CATALOG.zh-CN.md#presentations) |

<a id="quickstart"></a>

## 找到一个能开始的入口

1. **选任务。** 打开地图中的分类，比较具体组件。
2. **看范围。** 读使用标签与条目说明；测过解析器，不等于跑通过科研流程。
3. **去上游。** 检查原项目的安装、模型、API、硬件与费用要求。

修改论文可以从 [结构与论证](CATALOG.zh-CN.md#writing-structure) → [领域规范](CATALOG.zh-CN.md#writing-discipline) → [语言润色](CATALOG.zh-CN.md#writing-language) 开始。探索自动化科研时，先比较 [科研流程](CATALOG.zh-CN.md#research-pipelines) 与 [有边界的实验循环](CATALOG.zh-CN.md#experiments)，再看试用缺口。

<a id="coverage"></a>

## 十类覆盖

| 分类 | 条目归属数 | 代表组件与经历范围 |
| --- | ---: | --- |
| [完整科研流程](CATALOG.zh-CN.md#research-pipelines) | 2 | [AutoResearchClaw](CATALOG.zh-CN.md#entry-autoresearchclaw) · **Code-tested** — 验证过文献缓存代码；未评估完整科研产出。 |
| [综合技能套件](CATALOG.zh-CN.md#skill-suites) | 5 | [Scientific Agent Skills](CATALOG.zh-CN.md#entry-scientific-agent-skills) · **Code-tested** — 验证过 research-lookup 的 PMID 解析器；未评估整套技能。 |
| [文献检索与阅读](CATALOG.zh-CN.md#literature) | 2 | [ARS / deep-research](CATALOG.zh-CN.md#entry-ars-deep-research) · **Inspected** — 查阅过文档；尚未试用这个具体组件。 |
| [实验与评测](CATALOG.zh-CN.md#experiments) | 2 | [ACL / acl-experiments](CATALOG.zh-CN.md#entry-acl-experiments) · **Used** — 用于实验设计审查；不承担 benchmark 执行。 |
| [绘图与可视化](CATALOG.zh-CN.md#figures) | 3 | [AI Research Skills / academic-plotting](CATALOG.zh-CN.md#entry-academic-plotting) · **Used** — 用于审图；未测试付费生成流程。 |
| [论文写作与润色](CATALOG.zh-CN.md#writing) | 9 | [AI Research Skills / ml-paper-writing](CATALOG.zh-CN.md#entry-ml-paper-writing) · **Used** — 用于论文审查；论断仍需核验。 |
| [引用核验与管理](CATALOG.zh-CN.md#citations) | 2 | [ARS / citation-check](CATALOG.zh-CN.md#entry-ars-citations) · **Inspected** — 查阅过该模式；尚未确认试用。 |
| [审稿、修改与审稿回复](CATALOG.zh-CN.md#review) | 4 | [ARS / academic-paper-reviewer](CATALOG.zh-CN.md#entry-ars-reviewer) · **Used** — 用过完整审稿模式；模拟判断不代表会议决定。 |
| [投稿规范与复现](CATALOG.zh-CN.md#submission) | 2 | [ACL / acl-reproducibility](CATALOG.zh-CN.md#entry-acl-reproducibility) · **Used** — 用作审查视角；不代表成功独立复现。 |
| [报告与演讲](CATALOG.zh-CN.md#presentations) | 1 | [AI Research Skills / presenting-conference-talks](CATALOG.zh-CN.md#entry-conference-talks) · **Inspected** — 已安装；没有核实到执行记录。 |

共 **30 个唯一条目、32 次分类归属**；跨类条目会在两类中出现，但只计一个条目。表中组件是阅读入口，不是排名。

<a id="experience"></a>

## 使用记录说到哪里

| 标签 | 范围 |
| --- | --- |
| **Used · 已使用（17）** | 具体组件或明确的子集用于真实任务；以条目说明为准。 |
| **Code-tested · 已测试代码（2）** | 调查和测试过局部代码；尚不能判断科研产出质量。 |
| **Inspected · 已查阅（11）** | 查阅过文档或源码；没有确认的个人执行记录。 |

标签描述经历，不是可靠性分数。安装不等于使用；套件的标签不会传递给所有子技能。[使用记录](TRIALS.zh-CN.md)保留了未验证部分。

<a id="how-it-works"></a>

## 组件、套件与流程

**Skill** 提供任务指令、参考资料，有时附带脚本。**技能套件**汇集组件。**科研流程系统**还提供编排或执行机制。任务覆盖广，不代表能自主完成实验。本仓库提供目录与记录，安装和运行按原项目文档进行。

同一仓库的不同组件分别收录。3 项已使用的本地技能尚未核实公开来源：保留经历说明，不提供猜测的安装地址，也不再分发其内容。

<a id="for-agents"></a>
<a id="repository-guide"></a>

## 文档与机器入口

| 内容 | English | 简体中文 |
| --- | --- | --- |
| 完整条目与范围 | [CATALOG.md](CATALOG.md) | [CATALOG.zh-CN.md](CATALOG.zh-CN.md) |
| 使用记录与缺口 | [TRIALS.md](TRIALS.md) | [TRIALS.zh-CN.md](TRIALS.zh-CN.md) |
| 条目模板 | [ENTRY_TEMPLATE.md](ENTRY_TEMPLATE.md) | [ENTRY_TEMPLATE.zh-CN.md](ENTRY_TEMPLATE.zh-CN.md) |

[catalog.json](catalog.json) 是共用结构化索引，提供稳定 ID、分类、上游 URL、组件类型与有范围的经历说明。[llms.txt](llms.txt) 是双语阅读地图。URL 为 null 表示来源未定。机器可读不保证搜索收录、排名或 agent 推荐。

目录不包含上游源码、私有论文或未公开的评审输出。

<a id="contributing"></a>

## 补充一个条目

使用[条目模板](ENTRY_TEMPLATE.zh-CN.md)，给出具体组件、任务、原始链接、实际尝试与尚未验证的部分。同步维护两个语言版本和 JSON。流行程度不能证明科研质量。

来源检查日期: **2026-10-14** · 范围与具体证据见条目及使用记录。
