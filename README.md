![meta-autoresearch — research tools, organized around the work](assets/research-map-banner.svg)

# meta-autoresearch

### Research tools, organized around the work.

English · [简体中文](README.zh-CN.md)

A task-based catalog of auto research skills, AI research agents, and scientific workflows. **30 unique entries · 10 categories**, with exact components, original sources, and scoped experience notes.

[Browse all entries](CATALOG.md) · [Experience & gaps](TRIALS.md) · [JSON](catalog.json)

<a id="categories"></a>

## The research map

Enter at any task. These four groups organize reading, not a required execution sequence.

| Start with the work | Explore |
| --- | --- |
| **Frame the work** | [Research pipelines](CATALOG.md#research-pipelines) · [Skill suites](CATALOG.md#skill-suites) |
| **Find & test** | [Literature](CATALOG.md#literature) · [Experiments & evaluation](CATALOG.md#experiments) · [Figures](CATALOG.md#figures) |
| **Write & check** | [Writing](CATALOG.md#writing) · [Citations](CATALOG.md#citations) · [Review & revision](CATALOG.md#review) |
| **Share the research** | [Submission & reproducibility](CATALOG.md#submission) · [Talks & presentations](CATALOG.md#presentations) |

<a id="quickstart"></a>

## Find a starting point

1. **Choose the task.** Open a category and compare exact components.
2. **Read the scope.** Check the experience label and notes; a tested parser is not a tested research pipeline.
3. **Go upstream.** Check the original installation, model, API, hardware, and cost requirements.

For a manuscript revision, start with [structure & argument](CATALOG.md#writing-structure) → [disciplinary conventions](CATALOG.md#writing-discipline) → [language editing](CATALOG.md#writing-language). For autonomous research, compare [research pipelines](CATALOG.md#research-pipelines) with [bounded experiment loops](CATALOG.md#experiments), then read the trial gaps.

<a id="coverage"></a>

## Coverage at a glance

| Category | Entries | One component & its experience scope |
| --- | ---: | --- |
| [End-to-end research pipelines](CATALOG.md#research-pipelines) | 2 | [AutoResearchClaw](CATALOG.md#entry-autoresearchclaw) · **Code-tested** — Literature-cache code tested; full research output unevaluated. |
| [Research skill suites](CATALOG.md#skill-suites) | 5 | [Scientific Agent Skills](CATALOG.md#entry-scientific-agent-skills) · **Code-tested** — research-lookup PMID parser tested; full suite unevaluated. |
| [Literature discovery and reading](CATALOG.md#literature) | 2 | [ARS / deep-research](CATALOG.md#entry-ars-deep-research) · **Inspected** — Documentation inspected; this component has not been trialed. |
| [Experiments and evaluation](CATALOG.md#experiments) | 2 | [ACL / acl-experiments](CATALOG.md#entry-acl-experiments) · **Used** — Used to review experiment design; not a benchmark runner. |
| [Figures and diagrams](CATALOG.md#figures) | 3 | [AI Research Skills / academic-plotting](CATALOG.md#entry-academic-plotting) · **Used** — Used for figure inspection; paid generation untested. |
| [Writing and polishing](CATALOG.md#writing) | 9 | [AI Research Skills / ml-paper-writing](CATALOG.md#entry-ml-paper-writing) · **Used** — Used for manuscript review; claims still need checks. |
| [Citations and references](CATALOG.md#citations) | 2 | [ARS / citation-check](CATALOG.md#entry-ars-citations) · **Inspected** — Mode inspected; no trial of this mode confirmed. |
| [Review, revision, and rebuttal](CATALOG.md#review) | 4 | [ARS / academic-paper-reviewer](CATALOG.md#entry-ars-reviewer) · **Used** — Full review mode used; simulated judgments are not venue decisions. |
| [Submission and reproducibility](CATALOG.md#submission) | 2 | [ACL / acl-reproducibility](CATALOG.md#entry-acl-reproducibility) · **Used** — Used as a review lens; independent reproduction not established. |
| [Talks and presentations](CATALOG.md#presentations) | 1 | [AI Research Skills / presenting-conference-talks](CATALOG.md#entry-conference-talks) · **Inspected** — Installed; no verified execution record. |

**30 unique entries, 32 category memberships.** Cross-category entries appear in both categories and count once in the catalog. The components above are browsing examples, not rankings.

<a id="experience"></a>

## What the experience labels support

| Label | Scope |
| --- | --- |
| **Used (17)** | The exact component or a stated subset was applied to a real task; read its scope note. |
| **Code-tested (2)** | Specific code was investigated and tested; research output quality remains unevaluated. |
| **Inspected (11)** | Documentation or source was inspected; personal execution is unconfirmed. |

Labels describe experience, not reliability scores. Installation does not count as use, and a suite label does not transfer to every included skill. [Experience notes](TRIALS.md) keep the gaps visible.

<a id="how-it-works"></a>

## Components, suites, and pipelines

A **skill** provides task instructions, references, and sometimes scripts. A **skill suite** groups components. A **research pipeline** also supplies orchestration or execution machinery. Broad coverage does not establish autonomous experiment execution. This repository provides navigation and notes; follow upstream documentation to install and run a tool.

Different components from one repository have separate entries. Three used local skills have unresolved public origins: their experience notes remain, without guessed installation URLs or redistributed contents.

<a id="for-agents"></a>
<a id="repository-guide"></a>

## Documents & machine-readable access

| Document | English | 简体中文 |
| --- | --- | --- |
| All entries & scope | [CATALOG.md](CATALOG.md) | [CATALOG.zh-CN.md](CATALOG.zh-CN.md) |
| Experience & gaps | [TRIALS.md](TRIALS.md) | [TRIALS.zh-CN.md](TRIALS.zh-CN.md) |
| Entry template | [ENTRY_TEMPLATE.md](ENTRY_TEMPLATE.md) | [ENTRY_TEMPLATE.zh-CN.md](ENTRY_TEMPLATE.zh-CN.md) |

[catalog.json](catalog.json) is the shared structured index: stable IDs, categories, upstream URLs, component types, and scoped experience notes. [llms.txt](llms.txt) maps both language editions. A null URL means unresolved provenance. Machine readability does not guarantee indexing, ranking, or agent recommendations.

The catalog contains no upstream source code, private manuscripts, or unpublished review outputs.

<a id="contributing"></a>

## Suggest an entry

Use the [entry template](ENTRY_TEMPLATE.md): identify the exact component, task, original URL, what was tried, and what remains untested. Keep both languages and JSON consistent. Popularity alone is not evidence of research quality.

Source-check date: **2026-10-14** · See individual entries and experience notes for scope and evidence.
