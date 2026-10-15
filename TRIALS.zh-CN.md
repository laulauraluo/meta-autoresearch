# 使用记录与待验证问题

[English](TRIALS.md) · 简体中文

[概览](README.zh-CN.md) · [完整目录](CATALOG.zh-CN.md) · [JSON 索引](catalog.json)

是否收录与用到什么程度是两件事。整理者已选择将下列四个项目纳入目录。提到过、安装过或提交过局部代码修复，都不能证明完整科研流程的质量。

## 正在评估的科研项目

| 项目 | 使用状态与证据 | 尚未验证 |
| --- | --- | --- |
| [AutoResearchClaw](https://github.com/aiming-lab/AutoResearchClaw) | **已测试代码（Code-tested）。** 调查并测试过文献缓存缺陷，已提交 [PR #334](https://github.com/aiming-lab/AutoResearchClaw/pull/334)。 | 端到端科研产出的质量、来源可追溯性、成本和可复现性。离线回归测试不能证明这些。 |
| [karpathy/autoresearch](https://github.com/karpathy/autoresearch) | **已查阅（Inspected）。** 作为开源贡献候选做过调查。 | 实际运行实验循环，以及对结果的评估。 |
| [The AI Scientist](https://github.com/SakanaAI/AI-Scientist) | **已查阅（Inspected）。** 调查过仓库与贡献要求。 | 实际科研运行、成本，以及对生成论断的独立核验。 |
| [Scientific Agent Skills](https://github.com/K-Dense-AI/scientific-agent-skills) | **已测试代码（Code-tested）。** 测试并修复过 research-lookup 论文材料解析器提取短 PubMed ID 的问题，已提交 [PR #312](https://github.com/K-Dense-AI/scientific-agent-skills/pull/312)。 | 整套技能或端到端科研流程的质量。未运行依赖服务提供方的检索或付费扫描。 |

PR 链接记录局部贡献，不代表维护者已接受，也不代表科学结论已获验证。状态仅适用于明确说明的范围；特别是，套件中的代码测试不会把单独收录的 Scientific Agent Skills 组件自动标为“已使用”。

## 用于真实任务的组件

| 来源或组件 | 已记录的用途 | 边界 |
| --- | --- | --- |
| Academic Research Skills | 论文写作审查与完整审稿模式 | 未运行完整科研流程；模拟审稿不代表会议录用决定。 |
| AI Research Skills / ml-paper-writing | 论文审查 | 论断、数值与引用仍需独立核验。 |
| AI Research Skills / academic-plotting | 图表检查 | 未测试付费示意图生成。 |
| Awesome Journal Skills / 部分 ACL 技能 | 实验设计、写作、回复策略、复现材料与 PDF 层面的投稿审查 | 未评估每个会议或期刊技能包，未独立复现实验，也未验证完整投稿材料包。 |
| Supervisor Skills / pre-submission-reviewer | 检查论文准备程度，并将问题与原文核对 | 本地记录指向该上游；安装副本可能与当前版本不同。未评估套件其他组件。 |

[完整目录](CATALOG.zh-CN.md)按具体组件记录使用深度。这些是限定范围的使用记录，不是比较基准，也不是对每次输出的背书。

## 来源尚未核实的本地技能

| 组件 | 已记录的用途 | 公开来源 |
| --- | --- | --- |
| research-paper-writing | 论文审查与修改 | 尚未核实；URL 保持 null。 |
| writing-clearly-and-concisely | 文字编辑 | 所安装副本的来源尚未核实；URL 保持 null。 |
| academic-rebuttal | 回复策略与框架 | 尚未核实；URL 保持 null。未验证最终提交的审稿回复。 |

这些本地副本不提供安装链接或技能全文。本目录不包含未发表论文、私有评审原文、本机路径或聊天记录。

## 相邻工具

[Reverse Engineer Anything](https://github.com/morluto/rea) 正在用于检查公开网页并重建界面。这属于软件调查，不能作为自主科研流程的证据，因此不计入核心目录的 30 个条目。

## 如何更新记录

写明具体组件、任务、已知版本或 commit、实际观察，以及尚未测试的内容。可使用[条目模板](ENTRY_TEMPLATE.zh-CN.md)。同步更新两个语言版本及 catalog.json；新的局部代码测试不应悄悄提升无关组件的使用状态。
