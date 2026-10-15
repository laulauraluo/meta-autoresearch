# meta-autoresearch

**Auto research skills and AI research agents, organized around the work.**

English · [简体中文](README.zh-CN.md)

Find a starting point for literature reviews, experiments, figures, academic writing, citations, peer review, and publication. This pointer catalog links to original projects and records what was actually tried: **30 entries across 10 categories**.

[Browse the catalog](CATALOG.md) · [Experience notes](TRIALS.md) · [JSON index](catalog.json)

## Contents

- [Category overview](#categories)
- [Start with your task](#quickstart)
- [Read the experience labels](#experience)
- [How this catalog works](#how-it-works)
- [For agents and tool builders](#for-agents)
- [Repository guide](#repository-guide)
- [Suggest an entry](#contributing)

<a id="categories"></a>

## Category overview

| Category | Start here when you need to… | Examples |
| --- | --- | --- |
| [End-to-end research pipelines](CATALOG.md#research-pipelines) | Coordinate ideas, experiments, and manuscripts | AutoResearchClaw; The AI Scientist |
| [Research skill suites](CATALOG.md#skill-suites) | Find a collection spanning several research tasks | Academic Research Skills; AI Research Skills; Scientific Agent Skills |
| [Literature discovery and reading](CATALOG.md#literature) | Find, screen, compare, and synthesize papers | ARS deep-research; sr-screener |
| [Experiments and evaluation](CATALOG.md#experiments) | Iterate on experiments or review evaluation design | karpathy/autoresearch; acl-experiments |
| [Figures and diagrams](CATALOG.md#figures) | Plot measured results or explain a method | academic-plotting; scientific-visualization; scientific-schematics |
| [Writing and polishing](CATALOG.md#writing) | Improve argument, prose, and disciplinary style | ml-paper-writing; research-paper-writing; writing-clearly-and-concisely |
| [Citations and references](CATALOG.md#citations) | Manage references and check citation consistency | ARS citation-check; citation-management |
| [Review, revision, and rebuttal](CATALOG.md#review) | Review a manuscript and address reviewer concerns | academic-paper-reviewer; pre-submission-reviewer; academic-rebuttal |
| [Submission and reproducibility](CATALOG.md#submission) | Prepare submission materials and reusable evidence | acl-submission; acl-reproducibility |
| [Talks and presentations](CATALOG.md#presentations) | Turn a paper into slides and speaker notes | presenting-conference-talks |

<a id="quickstart"></a>

## Start with your task

1. **Choose the work.** Open a category above, then compare the exact components in the catalog.
2. **Read the evidence.** Check the experience label and its scope. A tested parser is not a tested research pipeline.
3. **Go upstream.** Follow the original documentation for installation, versions, models, API access, hardware, and costs. This repository does not install or run the tools.

| Your task | A useful route through the catalog |
| --- | --- |
| Revise a paper | [Structure and argument](CATALOG.md#writing-structure) → [disciplinary conventions](CATALOG.md#writing-discipline) → [language editing](CATALOG.md#writing-language) |
| Prepare paper figures | Choose [data plots or schematics](CATALOG.md#figures); check figures against the underlying results |
| Check a literature review | [Discover and screen papers](CATALOG.md#literature), then [check references](CATALOG.md#citations) against source texts |
| Respond to reviewers | [Review and rebuttal](CATALOG.md#review), followed by the venue's current response rules |
| Explore autonomous research | Compare [research pipelines](CATALOG.md#research-pipelines) with [bounded experiment loops](CATALOG.md#experiments), then read the [trial gaps](TRIALS.md) |

These are reading routes, not a requirement to run every skill in sequence.

<a id="experience"></a>

## Read the experience labels

| Label | What the evidence supports |
| --- | --- |
| **Used** | The named component or stated subset was applied to a real task. Read the scope note. |
| **Code-tested** | Specific code was investigated and tested. Research output quality may remain unevaluated. |
| **Inspected** | Documentation or source was inspected; personal execution is unconfirmed. |

Labels describe experience, not scores or blanket endorsements. Installing a skill does not count as using it. A suite entry does not mark every included skill as used. The [experience notes](TRIALS.md) keep the gaps visible.

<a id="how-it-works"></a>

## How this catalog works

An **auto research skill** provides a compatible agent with instructions, references, and sometimes scripts for a research task. A **skill suite** groups these components. A **research pipeline** also provides orchestration or execution machinery. Broad task coverage alone does not mean a tool can run experiments independently.

Entries identify a project, exact component, or mode within a skill. Different components from one repository count separately; components assigned to two categories still count once. Three locally used skills have unresolved public origins and no installation links. Their contents are not redistributed.

<a id="for-agents"></a>

## For agents and tool builders

Use [catalog.json](catalog.json) for stable entry IDs, category IDs, upstream URLs, component types, and scoped experience notes. Use the [English catalog](CATALOG.md) or [Chinese catalog](CATALOG.zh-CN.md) for task-based reading. [llms.txt](llms.txt) links both language editions.

Treat a null URL as unresolved provenance, not as an invitation to guess an installation source. Prefer upstream documentation for current behavior. The catalog contains no upstream source code, private manuscripts, or unpublished review outputs. Machine-readable navigation helps readers locate information; it does not guarantee indexing, search ranking, or agent recommendations.

<a id="repository-guide"></a>

## Repository guide

| Document | English | Simplified Chinese |
| --- | --- | --- |
| Overview and task routes | [README.md](README.md) | [README.zh-CN.md](README.zh-CN.md) |
| All entries and their scope | [CATALOG.md](CATALOG.md) | [CATALOG.zh-CN.md](CATALOG.zh-CN.md) |
| Experience and open questions | [TRIALS.md](TRIALS.md) | [TRIALS.zh-CN.md](TRIALS.zh-CN.md) |
| Proposed entry format | [ENTRY_TEMPLATE.md](ENTRY_TEMPLATE.md) | [ENTRY_TEMPLATE.zh-CN.md](ENTRY_TEMPLATE.zh-CN.md) |

The shared [catalog.json](catalog.json) is the canonical structured index; [llms.txt](llms.txt) is an optional reading map. Both Markdown editions are maintained together with that index.

<a id="contributing"></a>

## Suggest an entry

Use the [entry template](ENTRY_TEMPLATE.md). Link the exact upstream component, describe a concrete task, and state what was tried and what remains untested. Keep both language editions and the JSON index consistent. Popularity alone is not evidence of research quality.
