# Experience notes and open questions

English · [简体中文](TRIALS.zh-CN.md)

[Overview](README.md) · [Full catalog](CATALOG.md) · [JSON index](catalog.json)

Inclusion and experience are separate decisions. The curator has selected the four projects below for the catalog. A mention, installation, or targeted code contribution does not establish the quality of a complete research workflow.

## Research projects under evaluation

| Project | Experience and evidence | Still unverified |
| --- | --- | --- |
| [AutoResearchClaw](https://github.com/aiming-lab/AutoResearchClaw) | **Code-tested.** Investigated and tested a literature-cache bug; submitted [PR #334](https://github.com/aiming-lab/AutoResearchClaw/pull/334). | End-to-end research output quality, provenance, costs, and reproducibility. Offline regression tests do not establish these. |
| [karpathy/autoresearch](https://github.com/karpathy/autoresearch) | **Inspected.** Investigated as an open-source contribution candidate. | Actual experiment-loop use and an assessment of the results. |
| [The AI Scientist](https://github.com/SakanaAI/AI-Scientist) | **Inspected.** Investigated the repository and contribution requirements. | An actual research run, its costs, and independent checks of generated claims. |
| [Scientific Agent Skills](https://github.com/K-Dense-AI/scientific-agent-skills) | **Code-tested.** Tested and fixed short PubMed ID extraction in the research-lookup manuscript parser; submitted [PR #312](https://github.com/K-Dense-AI/scientific-agent-skills/pull/312). | Full-suite or end-to-end scientific workflow quality. Provider-backed lookup and paid scanning were not run. |

The linked PRs document targeted contributions; they are not claims of maintainer acceptance or validation of scientific results. Status labels apply only to the stated scope. In particular, this suite-level code test does not mark the individual Scientific Agent Skills entries as used.

## Components used on real tasks

| Source or component | Recorded use | Limit |
| --- | --- | --- |
| Academic Research Skills | Paper-writing review and the full reviewer mode | The complete research pipeline was not run; simulated review is not a venue decision. |
| AI Research Skills / ml-paper-writing | Manuscript review | Claims, numbers, and citations still require independent checks. |
| AI Research Skills / academic-plotting | Figure inspection | Paid diagram generation was not tested. |
| Awesome Journal Skills / selected ACL skills | Experiment design, writing, response strategy, reproducibility, and PDF-level submission review | No claim to have evaluated every venue pack, independently reproduced experiments, or verified the full submission package. |
| Supervisor Skills / pre-submission-reviewer | Manuscript readiness review, with findings checked against the paper | Local records identify the upstream; the installed copy may differ from its current version. Other suite components were not evaluated. |

The [catalog](CATALOG.md) records the experience of each exact component. These are scoped usage records, not a comparative benchmark or an endorsement of every output.

## Unresolved local provenance

| Component | Recorded use | Public source |
| --- | --- | --- |
| research-paper-writing | Manuscript review and revision | Unresolved; URL remains null. |
| writing-clearly-and-concisely | Prose editing | Unresolved for the installed copy; URL remains null. |
| academic-rebuttal | Response strategy and scaffolding | Unresolved; URL remains null. No verified final submitted rebuttal. |

No installation links or skill contents are supplied for these local copies. Unpublished manuscripts, private review text, local paths, and chat logs are excluded from this catalog.

## Adjacent tooling

[Reverse Engineer Anything](https://github.com/morluto/rea) is being tried for inspecting a public website and reconstructing its interface. This is software investigation, not evidence of an autonomous scientific workflow. It is outside the 30-entry core catalog.

## Updating a record

Record the exact component, task, version or commit when known, what was observed, and what remains untested. Use the [entry template](ENTRY_TEMPLATE.md). Update both language editions and catalog.json together; a new code test should not silently upgrade unrelated components.
