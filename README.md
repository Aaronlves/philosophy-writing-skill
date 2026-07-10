# Philosophy Writing Skill

`philosophy-writing` is a project-neutral Codex skill for drafting, revising, outlining, explaining, and conducting revision-oriented review of philosophical prose. It is designed around philosophical questions, concepts, interpretations, arguments, objections and replies, thought experiments, and normative burdens—not scientific manuscript structure or data-driven research. It preserves the writer's commitments rather than silently replacing them.

## Quick Workflow

1. Identify genre, audience, stage, local claim, and passage function.
2. State what must be preserved and what the passage must accomplish.
3. Build the logical, interpretive, or dialectical structure before polishing prose.
4. Check scope, force, definitions, objections, and source support.
5. Draft or revise for the actual genre.
6. Keep substantive alternative arguments separate unless requested.
7. Polish transitions and sentences last.

It is acceptable to say “I do not know” or “the available source does not settle this.” Polishing must not promote exploratory claims, strengthen source attributions, or change a load-bearing definition without notice.

## Public Skill vs. Private Extension

This repository contains the reusable writing method. Keep personal prose preferences, unpublished project claims, local statuses, source maps, file paths, and write permissions in a private extension.

```text
project-philosophy-writing/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── project-context.md
    ├── prose-control.md
    └── write-policy.md
```

Apply private prose-control guidance only after the philosophical structure is stable. Style imitation must not alter thesis, scope, definitions, citations, or argumentative commitments.

## Deploying a Personal Philosophy-Writing Skill

Use a personal extension when you want `philosophy-writing` to serve a specific project, thesis, course, article, or long-form manuscript without putting private material in this public repository. The extension should be a thin adapter: it supplies project context, preferred prose-control guidance, templates, and write permissions, while this public skill supplies the general writing method.

Recommended private structure:

```text
my-project-philosophy-writing/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── project-context.md
    ├── prose-control.md
    ├── writing-templates.md
    ├── source-use-policy.md
    └── write-policy.md
```

Deploy it locally:

```bash
mkdir -p ~/.codex/skills/my-project-philosophy-writing/agents
mkdir -p ~/.codex/skills/my-project-philosophy-writing/references
```

Then create the files above. Keep `SKILL.md` concise:

````markdown
---
name: my-project-philosophy-writing
description: "Use only when philosophical prose is being drafted, revised, outlined, or reviewed for [project name]. Pair with philosophy-writing for the general writing method. Do not use for unrelated writing or unauthorized file updates."
---

# My Project Philosophy Writing

Use `philosophy-writing` for thesis-first drafting, argument repair, definition testing, objection and reply handling, literature-review prose, and revision standards. This personal skill supplies only project context, prose-control guidance, templates, source-use rules, and permissions.

Before drafting or revising, record:

```text
Task mode:
Project context:
Text or target section:
What must be preserved:
Read set:
Write set:
Authorized output:
File-update permission:
Stop condition:
```

Read only the needed references:

- `references/project-context.md` for stable commitments, tentative hypotheses, terminology, section functions, and open questions.
- `references/prose-control.md` only after the thesis, argument, definitions, and source responsibilities are stable.
- `references/writing-templates.md` when a project-specific output form is required.
- `references/source-use-policy.md` before making source claims, literature-review claims, or citation-dependent prose.
- `references/write-policy.md` before creating or updating any file.
````

Create `agents/openai.yaml`:

```yaml
interface:
  display_name: "My Project Philosophy Writing"
  short_description: "Draft and revise project prose"
  default_prompt: "Use $my-project-philosophy-writing with $philosophy-writing to draft or revise this project prose while preserving the current thesis, definitions, source boundaries, and permissions."
```

To check deployment, start a new Codex session or reload skills if your environment requires it, then run:

```text
Use $my-project-philosophy-writing with $philosophy-writing to revise this paragraph. Do not update files. State the task mode, what must be preserved, read set, write set, and stop condition first.
```

Before using or sharing the personal skill:

1. Verify that its description triggers only for the intended project.
2. Keep general writing rules in `philosophy-writing`; do not duplicate them.
3. Put long project context in `references/`, not in `SKILL.md`.
4. Separate stable commitments from tentative hypotheses and open questions.
5. Treat notes and drafts as context, not as independent scholarly evidence.
6. Require verification before promoting source claims into polished prose.
7. Keep prose-control subordinate to thesis, argument, definitions, source fidelity, and citation duties.
8. Test with one ordinary revision, one thesis-changing revision request, and one unauthorized file-update request.
9. Scan the folder for personal names, absolute paths, unpublished claims, draft prose, and institution-specific details before publishing anything.

Keep the personal skill private by default. If you later publish a template, replace project facts with placeholders and remove all local paths, identifiers, private claims, and prose samples.

## Installation

Clone the repository into the Codex skills folder:

```bash
git clone https://github.com/Aaronlves/philosophy-writing-skill.git ~/.codex/skills/philosophy-writing
```

The operational bundle is:

```text
philosophy-writing/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── argument-and-definition-standards.md
    ├── literature-and-long-form-prose.md
    ├── output-contracts.md
    └── review-and-revision.md
```

`README.md` is user-facing documentation; Codex follows `SKILL.md` and loads references as needed.

## Use It For

- thesis, roadmap, outline, paragraph, section, article, proposal, or chapter drafting;
- revision that preserves an intended thesis;
- argument repair, definition testing, objections, concessions, and replies;
- historical or exegetical exposition;
- phenomenological or descriptive philosophy;
- debate maps and question-focused exposition;
- literature review organized by philosophical role;
- local review aimed at revising the text;
- sentence-level polish after the philosophy is stable.

Use `paper-analysis` for source-grounded paper analysis. Use a separate source-checking workflow for quotation, page, metadata, or claim-support checks. Use a separate peer review workflow for independent holistic or referee-style assessment.

## Genre Sensitivity

The skill uses analytic-essay conventions as defaults, not universal laws.

- Argumentative work makes claims, grounds, inferences, objections, and replies explicit where useful.
- Historical and exegetical work separates textual evidence, interpretation, rival readings, and present significance.
- Phenomenological and descriptive work separates description, case, concept, explanation, and later metaphysical or normative conclusions.
- Formal work explains assumptions, derivation, interpretation, and limits.
- Literature review and debate exposition organize positions by questions and pressures rather than by author catalogue, unless chronology itself matters.

Topic sentences, short sentences, examples, and first-person signposts are aids. Use them when they clarify the philosophy; do not impose them mechanically.

## File Modes

| Mode | Use |
| --- | --- |
| `advisory-only` | Give advice or prose in chat without editing files. |
| `patch-proposal` | Provide exact replacement text without writing it. |
| `authorized-file-edit` | Edit only the files and sections authorized for the current task. |

## Example Prompts

```text
Use $philosophy-writing to revise this paragraph while preserving its thesis. Flag any change that would alter scope or argumentative burden.
```

```text
Use $philosophy-writing to turn this idea into a modest thesis, argument spine, roadmap, and section outline.
```

```text
Use $philosophy-writing to compare two readings of this passage. Separate textual evidence, interpretation, and philosophical evaluation.
```

```text
Use $philosophy-writing to reorganize this literature review by questions, positions, and residual pressures rather than by author.
```

## Creating a Private Prose-Control File

Build prose control from several model texts and describe reusable patterns in your own words. Track thesis placement, paragraph movement, sentence rhythm, technical vocabulary, examples, objections, source integration, and uncertainty. Do not copy distinctive sentences or import a model author's philosophical commitments.

Keep the file private if it uses unpublished writing, personal feedback, project details, or local paths.

## Validation

After changing the skill, run the current Codex skill validator if one is available.

Also verify named references, `agents/openai.yaml`, trigger boundaries, and public/private markers. Basic structural validation does not detect semantic conflicts, duplicated operational instructions, or privacy leakage.

## Privacy

Before publishing changes, scan for personal names, absolute paths, institutional details, unpublished arguments, draft prose, and domain-specific examples that may have come from private work. Prefer neutral examples in the public skill.
