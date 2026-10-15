# 科研工具与技能目录

[English](CATALOG.md) · 简体中文

按任务浏览 30 个独立条目、10 个分类。同一组件可能出现在多个分类；使用状态说明试过什么，不是质量排名。套件中的某个组件被用过，不代表整套都经过评估。

[概览](README.zh-CN.md) · [JSON 索引](catalog.json) · [使用记录](TRIALS.zh-CN.md)

## 目录

- [完整科研流程](#research-pipelines)
- [综合技能套件](#skill-suites)
- [文献检索与阅读](#literature)
- [实验与评测](#experiments)
- [绘图与可视化](#figures)
- [论文写作与润色](#writing)
- [引用核验与管理](#citations)
- [审稿、修改与审稿回复](#review)
- [投稿规范与复现](#submission)
- [报告与演讲](#presentations)

## 使用状态

- **已使用（Used）：** 该组件或明确说明的部分已用于真实任务。
- **已测试代码（Code-tested）：** 调查并测试过局部代码；未必评估过完整科研产出。
- **已查阅（Inspected）：** 查阅过文档或源码；个人执行情况未确认。

本地来源尚未核实的 skill 不提供安装链接。目录仅记录用途和使用范围，不再分发其内容。

<a id="research-pipelines"></a>

## 完整科研流程

编排选题、文献、实验、分析与论文写作。

| 条目 | 适合的任务 | 使用范围与局限 |
| --- | --- | --- |
| <a id="entry-autoresearchclaw"></a>[AutoResearchClaw](https://github.com/aiming-lab/AutoResearchClaw) | 编排文献检索、假设、实验、分析、论文起草与审稿。 | **已测试代码（Code-tested）** — 调查并测试过文献缓存缺陷；尚未评估完整科研流程的产出质量。 |
| <a id="entry-ai-scientist"></a>[The AI Scientist](https://github.com/SakanaAI/AI-Scientist) | 以模板为基础，串联选题、实验、图表、论文写作和自动审稿。 | **已查阅（Inspected）** — 此处指原版 AI Scientist 仓库；尚未亲自完成端到端运行。使用前检查运行要求及论文披露政策。 |

<a id="skill-suites"></a>

## 综合技能套件

跨多项科研任务的技能集合；覆盖面广不代表能够自主执行实验。

| 条目 | 适合的任务 | 使用范围与局限 |
| --- | --- | --- |
| <a id="entry-ars"></a>[Academic Research Skills](https://github.com/Imbad0202/academic-research-skills) | 在研究者引导下进行科研、写作、引用核验、审稿和发表准备。 | **已使用（Used）** — 用过论文写作与审稿组件，尚未运行完整流程。ARS 记录在外部完成的实验，本身不执行实验。 |
| <a id="entry-ai-research-skills"></a>[AI Research Skills](https://github.com/Orchestra-Research/AI-Research-SKILLs) | 覆盖机器学习研究工具和论文准备的模块化技能集合。 | **已使用（Used）** — 用过 ml-paper-writing 和 academic-plotting；这不能代表用过其余技能。 |
| <a id="entry-scientific-agent-skills"></a>[Scientific Agent Skills](https://github.com/K-Dense-AI/scientific-agent-skills) | 面向科学软件、数据源、分析和科研表达的模块化技能。 | **已测试代码（Code-tested）** — 测试并修复过 research-lookup 论文材料解析器提取短 PubMed ID 的问题；已提交 [PR #312](https://github.com/K-Dense-AI/scientific-agent-skills/pull/312)。未评估整套技能或端到端科研流程。所需科学软件与访问凭据仍须另行提供。 |
| <a id="entry-journal-skills"></a>[Awesome Journal Skills](https://github.com/brycewang-stanford/Awesome-Journal-Skills) | 按投稿方向组织研究准备、写作、审稿与投稿技能。 | **已使用（Used）** — 用过部分 ACL 技能；未评估全部会议与期刊技能包。 |
| <a id="entry-supervisor-skills"></a>[Supervisor Skills](https://github.com/HKUSTDial/Supervisor-Skills) | 覆盖选题、论文、图表和投稿前审查的研究辅助技能。 | **已使用（Used）** — 用过 pre-submission-reviewer。本地记录指向此上游，但不能证明所用版本与当前上游完全一致。 |

<a id="literature"></a>

## 文献检索与阅读

发现、筛选、比较并综合相关研究。

| 条目 | 适合的任务 | 使用范围与局限 |
| --- | --- | --- |
| <a id="entry-ars-deep-research"></a>[ARS / deep-research](https://github.com/Imbad0202/academic-research-skills/tree/main/deep-research) | 文献研究与综合分析流程。 | **已查阅（Inspected）** — 已确认上游提供该组件；没有核实到此组件的实际执行记录。 |
| <a id="entry-ars-screener"></a>[ARS / sr-screener](https://github.com/Imbad0202/academic-research-skills/tree/main/sr-screener) | 按预设方案筛选系统综述、范围综述和快速综述的文献。 | **已查阅（Inspected）** — 依据上游文档收录；筛选决定仍需研究团队复核。 |

<a id="experiments"></a>

## 实验与评测

运行有边界的实验循环，设计评测并审查证据。

| 条目 | 适合的任务 | 使用范围与局限 |
| --- | --- | --- |
| <a id="entry-autoresearch"></a>[karpathy/autoresearch](https://github.com/karpathy/autoresearch) | 让编码 agent 在固定实验预算内迭代小模型训练，并评估结果。 | **已查阅（Inspected）** — 这是有预算边界的训练优化循环；未覆盖从文献到论文的自动化。上游要求 NVIDIA GPU 支持。 |
| <a id="entry-acl-experiments"></a>[ACL / acl-experiments](https://github.com/brycewang-stanford/Awesome-Journal-Skills/tree/main/ACL-Skills/skills/acl-experiments) | 审查 ACL 系列论文的实验设计、基线、消融与证据。 | **已使用（Used）** — 用作实验审查视角；不承担 benchmark 的实际执行。 |

<a id="figures"></a>

## 绘图与可视化

区分数据图、架构图与说明性图像，按任务选择。

| 条目 | 适合的任务 | 使用范围与局限 |
| --- | --- | --- |
| <a id="entry-academic-plotting"></a>[AI Research Skills / academic-plotting](https://github.com/Orchestra-Research/AI-Research-SKILLs/tree/main/20-ml-paper-writing/academic-plotting) | 使用 matplotlib/seaborn 绘制数据图，并提供独立的模型辅助示意图流程。 | **已使用（Used）** — 实际用于审图；未测试付费图像生成流程。 |
| <a id="entry-scientific-visualization"></a>[Scientific Agent Skills / scientific-visualization](https://github.com/K-Dense-AI/scientific-agent-skills/tree/main/skills/scientific-visualization) | 科学可视化指导与面向论文的数据图表。 | **已查阅（Inspected）** — 已找到上游组件；没有确认的个人试用记录。 |
| <a id="entry-scientific-schematics"></a>[Scientific Agent Skills / scientific-schematics](https://github.com/K-Dense-AI/scientific-agent-skills/tree/main/skills/scientific-schematics) | 科学示意图与解释性图解。 | **已查阅（Inspected）** — 已找到上游组件；具体生成条件取决于其当前流程。 |

<a id="writing"></a>

## 论文写作与润色

组织论证、起草章节、编辑语言并遵循领域规范。

<a id="writing-structure"></a>

### 结构与论证

| 条目 | 适合的任务 | 使用范围与局限 |
| --- | --- | --- |
| <a id="entry-ml-paper-writing"></a>[AI Research Skills / ml-paper-writing](https://github.com/Orchestra-Research/AI-Research-SKILLs/tree/main/20-ml-paper-writing/ml-paper-writing) | 组织机器学习论文叙事、对齐论断与证据，并起草章节。 | **已使用（Used）** — 实际用于论文审查；引用和数值论断仍需独立核验。 |
| <a id="entry-ars-academic-paper"></a>[ARS / academic-paper](https://github.com/Imbad0202/academic-research-skills/tree/main/academic-paper) | 规划、起草和修改论文，组织研究证据的表达。 | **已使用（Used）** — 实际用于写作审查；不代表完成过从科研到论文的完整流程。 |
| <a id="entry-research-paper-writing"></a>research-paper-writing — 本地来源待核实 | 改善段落衔接，通过反向提纲梳理章节，并对齐论断与支撑材料。 | **已使用（Used）** — 实际用于论文审查与修改。公开来源尚未核实，因此不提供安装链接或技能全文。 |
| <a id="entry-scientific-writing"></a>[Scientific Agent Skills / scientific-writing](https://github.com/K-Dense-AI/scientific-agent-skills/tree/main/skills/scientific-writing) | 起草和修改科学论文。 | **已查阅（Inspected）** — 已找到上游组件；未确认使用过此来源的确切版本。 |

<a id="writing-language"></a>

### 语言润色

| 条目 | 适合的任务 | 使用范围与局限 |
| --- | --- | --- |
| <a id="entry-writing-clearly"></a>writing-clearly-and-concisely — 本地来源待核实 | 使句子清楚、措辞具体、段落简洁，删去浮夸表达。 | **已使用（Used）** — 实际用于文字编辑；所安装副本的公开来源尚未核实。 |

<a id="writing-discipline"></a>

### 领域写作规范

| 条目 | 适合的任务 | 使用范围与局限 |
| --- | --- | --- |
| <a id="entry-acl-writing"></a>[ACL / acl-writing-style](https://github.com/brycewang-stanford/Awesome-Journal-Skills/tree/main/ACL-Skills/skills/acl-writing-style) | 面向 ACL 系列会议的 NLP 论文写作与表达。 | **已使用（Used）** — 实际用于论文审查；投稿前仍需检查当期官方规则。 |
| <a id="entry-systems-writing"></a>[AI Research Skills / systems-paper-writing](https://github.com/Orchestra-Research/AI-Research-SKILLs/tree/main/20-ml-paper-writing/systems-paper-writing) | 组织系统论文的结构和证据表达。 | **已查阅（Inspected）** — 已安装此组件；没有核实到个人执行记录。 |

<a id="writing-revision"></a>

### 修改与审稿回复

| 条目 | 适合的任务 | 使用范围与局限 |
| --- | --- | --- |
| <a id="entry-academic-rebuttal"></a>academic-rebuttal — 本地来源待核实 | 梳理审稿意见，准备有证据支撑的回复材料和修改计划。 | **已使用（Used）** — 用于策略制定和回复框架；未验证最终提交的审稿回复。公开来源仍未核实。 |
| <a id="entry-acl-response"></a>[ACL / acl-author-response](https://github.com/brycewang-stanford/Awesome-Journal-Skills/tree/main/ACL-Skills/skills/acl-author-response) | 指导 ACL 系列审稿流程中的作者回复。 | **已使用（Used）** — 实际用于审稿回复策略；作者仍需核实目标会议的规则并完成最终回复。 |

<a id="citations"></a>

## 引用核验与管理

获取书目元数据，管理参考文献，核查引用一致性与支撑关系。

| 条目 | 适合的任务 | 使用范围与局限 |
| --- | --- | --- |
| <a id="entry-ars-citations"></a>[ARS / citation-check](https://github.com/Imbad0202/academic-research-skills/blob/main/commands/ars-citation-check.md) | 检查参考文献缺漏、文内引用不匹配与格式错误。 | **已查阅（Inspected）** — 这是 academic-paper 的一个模式，并非独立安装的 skill；尚未试用此模式。 |
| <a id="entry-citation-management"></a>[Scientific Agent Skills / citation-management](https://github.com/K-Dense-AI/scientific-agent-skills/tree/main/skills/citation-management) | 获取引用元数据，管理参考文献并进行核验。 | **已查阅（Inspected）** — 没有确认的个人试用记录；除书目元数据外，还应核对原文。 |

<a id="review"></a>

## 审稿、修改与审稿回复

发现薄弱环节、安排修改优先级，并准备有证据支撑的审稿回复。

| 条目 | 适合的任务 | 使用范围与局限 |
| --- | --- | --- |
| <a id="entry-ars-reviewer"></a>[ARS / academic-paper-reviewer](https://github.com/Imbad0202/academic-research-skills/tree/main/academic-paper-reviewer) | 从不同角色视角审查方法、论证、研究定位与表达。 | **已使用（Used）** — 用过完整审稿模式。模拟判断不代表会议决定，也不构成经过校准的录用概率。 |
| <a id="entry-submission-reviewer"></a>[Supervisor Skills / pre-submission-reviewer](https://github.com/HKUSTDial/Supervisor-Skills/tree/main/skills/pre-submission-reviewer) | 在投稿前系统检查论文准备程度。 | **已使用（Used）** — 已将发现的问题与论文核对；这不代表评估过 Supervisor Skills 的其他组件。 |
| academic-rebuttal — 本地来源待核实 | 梳理审稿意见，准备有证据支撑的回复材料和修改计划。 | **已使用（Used）** — 用于策略制定和回复框架；未验证最终提交的审稿回复。公开来源仍未核实。 |
| [ACL / acl-author-response](https://github.com/brycewang-stanford/Awesome-Journal-Skills/tree/main/ACL-Skills/skills/acl-author-response) | 指导 ACL 系列审稿流程中的作者回复。 | **已使用（Used）** — 实际用于审稿回复策略；作者仍需核实目标会议的规则并完成最终回复。 |

<a id="submission"></a>

## 投稿规范与复现

准备投稿材料、补充证据与可复用的成果材料。

| 条目 | 适合的任务 | 使用范围与局限 |
| --- | --- | --- |
| <a id="entry-acl-reproducibility"></a>[ACL / acl-reproducibility](https://github.com/brycewang-stanford/Awesome-Journal-Skills/tree/main/ACL-Skills/skills/acl-reproducibility) | 审查实验报告与发布材料是否支持复现。 | **已使用（Used）** — 用作审查视角；完成审查并不代表已成功独立复现实验。 |
| <a id="entry-acl-submission"></a>[ACL / acl-submission](https://github.com/brycewang-stanford/Awesome-Journal-Skills/tree/main/ACL-Skills/skills/acl-submission) | 检查 ACL 系列会议论文与投稿材料的准备程度。 | **已使用（Used）** — 实际用于 PDF 层面的审查；未验证完整投稿表单与成果材料包。 |

<a id="presentations"></a>

## 报告与演讲

将论文转化为幻灯片与讲者备注。

| 条目 | 适合的任务 | 使用范围与局限 |
| --- | --- | --- |
| <a id="entry-conference-talks"></a>[AI Research Skills / presenting-conference-talks](https://github.com/Orchestra-Research/AI-Research-SKILLs/tree/main/20-ml-paper-writing/presenting-conference-talks) | 将论文转化为 Beamer/PPTX 幻灯片、讲者备注和演讲稿。 | **已查阅（Inspected）** — 已安装此组件；没有核实到个人执行记录。 |

## 如何选择组件

修改论文时，可以先处理论证与结构，再应用领域规范，最后做句子层面的编辑。引用核验和审图各自独立。这是建议的顺序，无需把每个 skill 都用一遍。

实测结果应使用定量绘图流程；关系与架构可用示意图。区分实验执行、评测设计与证据审查，避免把审查意见当成实验结果。

上游来源与组件路径的记录核查日期：2026-10-14。功能简介依据上游文档，使用状态依据限定范围的本地记录。Scientific Agent Skills 的状态已按 PR #312 的代码测试证据更新。未公开论文或私有评审输出不包含在目录中。
