# Auto research skills catalog

English · [简体中文](CATALOG.zh-CN.md)

Browse 30 unique entries across 10 task categories. A component can appear in more than one category. Experience labels describe what was tried, not a ranking; using one component does not establish experience with its entire suite.

[Overview](README.md) · [JSON index](catalog.json) · [Experience notes](TRIALS.md)

## Contents

- [End-to-end research pipelines](#research-pipelines)
- [Research skill suites](#skill-suites)
- [Literature discovery and reading](#literature)
- [Experiments and evaluation](#experiments)
- [Figures and diagrams](#figures)
- [Writing and polishing](#writing)
- [Citations and references](#citations)
- [Review, revision, and rebuttal](#review)
- [Submission and reproducibility](#submission)
- [Talks and presentations](#presentations)

## Experience labels

- **Used:** applied the named component or stated subset to a real task.
- **Code-tested:** investigated and tested specific code; full research output may remain unevaluated.
- **Inspected:** read documentation or source; personal execution is unconfirmed.

Local skills with unresolved origin have no installation link. Their summaries document use; their contents are not redistributed.

<a id="research-pipelines"></a>

## End-to-end research pipelines

Idea, literature, experiments, analysis, and manuscript orchestration.

| Entry | Best fit | Experience and limits |
| --- | --- | --- |
| <a id="entry-autoresearchclaw"></a>[AutoResearchClaw](https://github.com/aiming-lab/AutoResearchClaw) | Orchestrates literature, hypotheses, experiments, analysis, manuscript drafting, and review. | **Code-tested** — Investigated and tested a literature-cache bug; full research output quality has not been evaluated. |
| <a id="entry-ai-scientist"></a>[The AI Scientist](https://github.com/SakanaAI/AI-Scientist) | Template-based idea generation, experiments, figures, paper writing, and automated review. | **Inspected** — Original AI Scientist repository; no personal end-to-end run. Check its runtime requirements and manuscript disclosure policy. |

<a id="skill-suites"></a>

## Research skill suites

Collections spanning multiple tasks; workflow coverage does not imply autonomous experiment execution.

| Entry | Best fit | Experience and limits |
| --- | --- | --- |
| <a id="entry-ars"></a>[Academic Research Skills](https://github.com/Imbad0202/academic-research-skills) | Human-guided research, writing, citation checks, review, and publication workflows. | **Used** — Used paper-writing and reviewer components; the full pipeline has not been run. ARS records externally run experiments rather than executing them. |
| <a id="entry-ai-research-skills"></a>[AI Research Skills](https://github.com/Orchestra-Research/AI-Research-SKILLs) | A modular collection covering ML research tooling and paper preparation. | **Used** — Used ml-paper-writing and academic-plotting; this does not establish experience with the rest of the library. |
| <a id="entry-scientific-agent-skills"></a>[Scientific Agent Skills](https://github.com/K-Dense-AI/scientific-agent-skills) | Modular skills for scientific packages, data sources, analysis, and research communication. | **Code-tested** — Tested and fixed short PubMed ID extraction in the research-lookup manuscript parser; submitted [PR #312](https://github.com/K-Dense-AI/scientific-agent-skills/pull/312). No full-suite or end-to-end scientific workflow evaluation. Selected scientific software and credentials must be supplied separately. |
| <a id="entry-journal-skills"></a>[Awesome Journal Skills](https://github.com/brycewang-stanford/Awesome-Journal-Skills) | Venue-oriented skills for research preparation, writing, review, and submission. | **Used** — Used selected ACL skills; no claim to have evaluated all venue packs. |
| <a id="entry-supervisor-skills"></a>[Supervisor Skills](https://github.com/HKUSTDial/Supervisor-Skills) | Research-assistance skills spanning ideas, papers, figures, and submission review. | **Used** — Used pre-submission-reviewer. Local records identify this upstream, but do not prove exact identity with its current version. |

<a id="literature"></a>

## Literature discovery and reading

Find, screen, compare, and synthesize relevant studies.

| Entry | Best fit | Experience and limits |
| --- | --- | --- |
| <a id="entry-ars-deep-research"></a>[ARS / deep-research](https://github.com/Imbad0202/academic-research-skills/tree/main/deep-research) | Literature research and synthesis workflows. | **Inspected** — Available upstream; no verified execution record for this specific component. |
| <a id="entry-ars-screener"></a>[ARS / sr-screener](https://github.com/Imbad0202/academic-research-skills/tree/main/sr-screener) | Protocol-driven screening for systematic, scoping, and rapid reviews. | **Inspected** — Listed from upstream documentation; screening decisions still require research-team checks. |

<a id="experiments"></a>

## Experiments and evaluation

Run bounded experiment loops, design evaluations, and assess evidence.

| Entry | Best fit | Experience and limits |
| --- | --- | --- |
| <a id="entry-autoresearch"></a>[karpathy/autoresearch](https://github.com/karpathy/autoresearch) | A coding agent iterates on small-model training under a fixed experiment budget and evaluates the result. | **Inspected** — A bounded training optimization loop, not literature-to-paper automation. Upstream expects NVIDIA GPU support. |
| <a id="entry-acl-experiments"></a>[ACL / acl-experiments](https://github.com/brycewang-stanford/Awesome-Journal-Skills/tree/main/ACL-Skills/skills/acl-experiments) | Review experiment design, baselines, ablations, and evidence for ACL-family papers. | **Used** — Applied as an experiment-review lens; it is not a benchmark execution engine. |

<a id="figures"></a>

## Figures and diagrams

Distinguish data plots, architecture diagrams, and illustrative images.

| Entry | Best fit | Experience and limits |
| --- | --- | --- |
| <a id="entry-academic-plotting"></a>[AI Research Skills / academic-plotting](https://github.com/Orchestra-Research/AI-Research-SKILLs/tree/main/20-ml-paper-writing/academic-plotting) | Data plots with matplotlib/seaborn; a separate model-assisted diagram workflow. | **Used** — Used for figure inspection. Paid diagram generation was not tested. |
| <a id="entry-scientific-visualization"></a>[Scientific Agent Skills / scientific-visualization](https://github.com/K-Dense-AI/scientific-agent-skills/tree/main/skills/scientific-visualization) | Scientific visualization guidance and publication-oriented data figures. | **Inspected** — Component located upstream; no confirmed personal trial. |
| <a id="entry-scientific-schematics"></a>[Scientific Agent Skills / scientific-schematics](https://github.com/K-Dense-AI/scientific-agent-skills/tree/main/skills/scientific-schematics) | Scientific schematics and explanatory diagrams. | **Inspected** — Component located upstream; generation requirements depend on its current workflow. |

<a id="writing"></a>

## Writing and polishing

Structure arguments, draft sections, edit language, and apply disciplinary conventions.

<a id="writing-structure"></a>

### Structure and argument

| Entry | Best fit | Experience and limits |
| --- | --- | --- |
| <a id="entry-ml-paper-writing"></a>[AI Research Skills / ml-paper-writing](https://github.com/Orchestra-Research/AI-Research-SKILLs/tree/main/20-ml-paper-writing/ml-paper-writing) | ML-paper narrative, claim-to-evidence alignment, and section drafting. | **Used** — Applied to manuscript review; citation and numerical claims still need independent checks. |
| <a id="entry-ars-academic-paper"></a>[ARS / academic-paper](https://github.com/Imbad0202/academic-research-skills/tree/main/academic-paper) | Paper planning, drafting, revision, and presentation of research evidence. | **Used** — Used in writing review; not evidence of completing the whole research-to-paper pipeline. |
| <a id="entry-research-paper-writing"></a>research-paper-writing — local origin unresolved | Paragraph flow, reverse outlining, section structure, and claim-support alignment. | **Used** — Used in manuscript review and revision. Public origin is unresolved; no install link or skill contents are supplied. |
| <a id="entry-scientific-writing"></a>[Scientific Agent Skills / scientific-writing](https://github.com/K-Dense-AI/scientific-agent-skills/tree/main/skills/scientific-writing) | Scientific manuscript drafting and revision. | **Inspected** — Upstream component located; no confirmed use of this exact source version. |

<a id="writing-language"></a>

### Language and concision

| Entry | Best fit | Experience and limits |
| --- | --- | --- |
| <a id="entry-writing-clearly"></a>writing-clearly-and-concisely — local origin unresolved | Sentence clarity, concrete wording, concise paragraphs, and removal of inflated prose. | **Used** — Used for prose editing. Public origin of the installed copy is unresolved. |

<a id="writing-discipline"></a>

### Disciplinary writing

| Entry | Best fit | Experience and limits |
| --- | --- | --- |
| <a id="entry-acl-writing"></a>[ACL / acl-writing-style](https://github.com/brycewang-stanford/Awesome-Journal-Skills/tree/main/ACL-Skills/skills/acl-writing-style) | NLP-paper writing and presentation for ACL-family venues. | **Used** — Applied to manuscript review. Check current official venue rules before submission. |
| <a id="entry-systems-writing"></a>[AI Research Skills / systems-paper-writing](https://github.com/Orchestra-Research/AI-Research-SKILLs/tree/main/20-ml-paper-writing/systems-paper-writing) | Systems-paper structure and evidence presentation. | **Inspected** — Installed component; no verified personal execution record. |

<a id="writing-revision"></a>

### Revision and responses

| Entry | Best fit | Experience and limits |
| --- | --- | --- |
| <a id="entry-academic-rebuttal"></a>academic-rebuttal — local origin unresolved | Triage reviewer concerns and prepare evidence-grounded response material and revision plans. | **Used** — Used for strategy and response scaffolding, not a verified final submitted rebuttal. Public origin remains unresolved. |
| <a id="entry-acl-response"></a>[ACL / acl-author-response](https://github.com/brycewang-stanford/Awesome-Journal-Skills/tree/main/ACL-Skills/skills/acl-author-response) | Author-response guidance for ACL-family review processes. | **Used** — Used for rebuttal strategy; the author must verify venue-specific rules and finalize the response. |

<a id="citations"></a>

## Citations and references

Retrieve metadata, manage references, and check citation consistency and support.

| Entry | Best fit | Experience and limits |
| --- | --- | --- |
| <a id="entry-ars-citations"></a>[ARS / citation-check](https://github.com/Imbad0202/academic-research-skills/blob/main/commands/ars-citation-check.md) | Check missing references, mismatched in-text citations, and formatting errors. | **Inspected** — An academic-paper mode, not a separate installed skill; this specific mode has not been trialed. |
| <a id="entry-citation-management"></a>[Scientific Agent Skills / citation-management](https://github.com/K-Dense-AI/scientific-agent-skills/tree/main/skills/citation-management) | Citation metadata retrieval, reference management, and verification workflows. | **Inspected** — No confirmed personal trial; inspect the source text as well as bibliographic metadata. |

<a id="review"></a>

## Review, revision, and rebuttal

Find weaknesses, prioritize revisions, and prepare evidence-grounded responses.

| Entry | Best fit | Experience and limits |
| --- | --- | --- |
| <a id="entry-ars-reviewer"></a>[ARS / academic-paper-reviewer](https://github.com/Imbad0202/academic-research-skills/tree/main/academic-paper-reviewer) | Review methodology, argument, positioning, and presentation through distinct roles. | **Used** — Used full review mode. Simulated judgments are not conference decisions or calibrated acceptance probabilities. |
| <a id="entry-submission-reviewer"></a>[Supervisor Skills / pre-submission-reviewer](https://github.com/HKUSTDial/Supervisor-Skills/tree/main/skills/pre-submission-reviewer) | A structured manuscript readiness review before submission. | **Used** — Findings checked against the manuscript; other Supervisor Skills components were not thereby evaluated. |
| academic-rebuttal — local origin unresolved | Triage reviewer concerns and prepare evidence-grounded response material and revision plans. | **Used** — Used for strategy and response scaffolding, not a verified final submitted rebuttal. Public origin remains unresolved. |
| [ACL / acl-author-response](https://github.com/brycewang-stanford/Awesome-Journal-Skills/tree/main/ACL-Skills/skills/acl-author-response) | Author-response guidance for ACL-family review processes. | **Used** — Used for rebuttal strategy; the author must verify venue-specific rules and finalize the response. |

<a id="submission"></a>

## Submission and reproducibility

Prepare submission materials, supplementary evidence, and reusable artifacts.

| Entry | Best fit | Experience and limits |
| --- | --- | --- |
| <a id="entry-acl-reproducibility"></a>[ACL / acl-reproducibility](https://github.com/brycewang-stanford/Awesome-Journal-Skills/tree/main/ACL-Skills/skills/acl-reproducibility) | Review whether experiment reporting and release materials support reproducibility. | **Used** — Applied as a review lens; a review does not establish successful independent reproduction. |
| <a id="entry-acl-submission"></a>[ACL / acl-submission](https://github.com/brycewang-stanford/Awesome-Journal-Skills/tree/main/ACL-Skills/skills/acl-submission) | Check manuscript and submission readiness for an ACL-family venue. | **Used** — Used for PDF-level review; the complete submission form and artifact package were not verified. |

<a id="presentations"></a>

## Talks and presentations

Turn a paper into slides and speaker notes.

| Entry | Best fit | Experience and limits |
| --- | --- | --- |
| <a id="entry-conference-talks"></a>[AI Research Skills / presenting-conference-talks](https://github.com/Orchestra-Research/AI-Research-SKILLs/tree/main/20-ml-paper-writing/presenting-conference-talks) | Turn a paper into Beamer/PPTX slides, speaker notes, and a talk script. | **Inspected** — Installed component; no verified personal execution record. |

## Choosing a component

For manuscript revision, start with argument and structure, apply relevant disciplinary conventions, then edit sentence-level wording. Treat citation checks and figure checks as separate tasks. This is a suggested sequence, not a requirement to run every skill.

Use quantitative plotting for measured results and schematics for relationships and architecture. Keep experiment execution, evaluation design, and evidence review distinct.

Recorded source and component-path check: 2026-10-14. Capabilities summarize upstream documentation; experience comes from scoped local usage records. Scientific Agent Skills was updated with the code-test evidence for PR #312. No unpublished manuscripts or private review outputs are included.
