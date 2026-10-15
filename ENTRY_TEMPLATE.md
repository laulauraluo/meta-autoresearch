# Entry template

English · [简体中文](ENTRY_TEMPLATE.zh-CN.md)

[Overview](README.md) · [Catalog](CATALOG.md) · [Experience notes](TRIALS.md)

Describe one project or exact component. Link to its original source instead of copying skill contents. Use the fields below to prepare an entry for curator review.

## Project or exact component

- **ID:** a stable lowercase identifier, reusing the existing ID when updating a record.
- **Name:** the upstream project or component name.
- **Upstream:** the canonical project or component URL; use null when local provenance is unresolved.
- **Type:** research pipeline / skill suite / experiment loop / skill / skill mode / local skill.
- **Categories:** choose IDs from catalog.json; more than one is allowed.
- **Best fit:** the concrete task this component addresses.
- **Experience:** used / code-tested / inspected, following the catalog definitions.
- **Scope tried:** what was actually done, on which component; keep unpublished research details private.
- **What helped:** an observed benefit, or explicitly mark it as not yet evaluated.
- **Limitations:** observed failures, required manual checks, and untested functionality.
- **Requirements:** relevant runtime, model/API, hardware, or cost requirements, with an upstream source when possible.
- **Last source check:** date; record a version or commit when known.
- **Curator decision:** include / revise / defer.

## Mapping to the structured index

Use the existing record shape in [catalog.json](catalog.json). Its keys include `id`, `name`, `url`, `kind`, `categories`, `description`, `experience`, `experience_notes`, `writing_group`, and `source_status`.

The `kind` values are `research-pipeline`, `skill-suite`, `experiment-loop`, `skill`, `skill-mode`, and `local-skill`. A writing entry may use `structure`, `language`, `discipline`, or `revision` for `writing_group`; other entries use null. Keep `source_status` accurate: `verified-upstream` means the upstream source was identified, not that the tool's outputs were validated; `unresolved-local-origin` accompanies an unresolved local source and null URL.

Put the task description in `description` and the supported usage scope and limitations in `experience_notes`. Additional review details belong in the experience notes page when useful; do not invent JSON fields merely to fill this form.

## Before proposing the entry

- Check for an existing ID or component; a second category does not require a duplicate entry.
- Verify the exact upstream URL or retain null. Do not guess a public origin from a similar name.
- Keep Used, Code-tested, and Inspected evidence distinct. Adding a suite does not mark every skill inside it as used.
- Update the English and Chinese catalogs, related trial notes, and the structured index together. Preserve the same links and scope across languages.
- Check local document links and anchors. Exclude private manuscripts, review text, credentials, and local paths.

Inclusion is an editorial decision, not a guarantee of quality or a claim of successful end-to-end research.
