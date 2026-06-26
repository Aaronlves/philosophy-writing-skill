# Philosophy Writing Skill

`philosophy-writing` is a general Codex skill for drafting, reviewing, revising, outlining, and analyzing philosophical prose.

The skill is project-neutral. It does not contain private research context, personal project files, or project-specific structure.

## What It Does

- Sharpens thesis statements.
- Builds argument outlines and section plans.
- Reconstructs arguments in premise-conclusion form.
- Reviews drafts for thesis clarity, structure, definitions, objections, source use, and prose.
- Tests definitions against central cases, edge cases, and counterexamples.
- Turns literature review into argument-driven prose.
- Strengthens objections and replies.
- Cuts exposition that does not serve the main argument.
- Preserves the difference between stable commitments and exploratory material.
- Gives concrete revision advice instead of generic praise.

## Install

Clone this repository into your Codex skills folder:

```bash
git clone https://github.com/Aaronlves/philosophy-writing-skill.git ~/.codex/skills/philosophy-writing
```

If you already have a local copy, update it with:

```bash
cd ~/.codex/skills/philosophy-writing
git pull
```

## Usage Examples

```text
Use philosophy-writing to review this draft for thesis clarity, argument structure, objections, and prose.
```

```text
Use philosophy-writing to turn this idea into a modest, defensible philosophy paper thesis and outline.
```

```text
Use philosophy-writing to test this definition against central cases, edge cases, and possible counterexamples.
```

```text
Use philosophy-writing to turn this literature review into an argument-driven section that classifies each source by its role.
```

```text
Use philosophy-writing to revise this paragraph so it is clearer, more precise, and more directly connected to the thesis.
```

## Output Pattern

The skill can produce:

1. outlines;
2. draft prose;
3. draft reviews;
4. revised prose;
5. argument repairs;
6. objection-and-reply sections;
7. literature review prose.

It defaults to advisory output unless the user explicitly authorizes file edits.

## Public Boundary

This repository is intentionally general. Keep private project context, file paths, unpublished arguments, feedback, and local workflow rules in a separate private extension or workspace instruction file.

A minimal private extension can use this structure:

```text
project-philosophy-writing/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── project-context.md
    ├── writing-templates.md
    └── workspace-policy.md
```

Use this prompt to create one:

```text
Build a private project-specific extension for the installed
`philosophy-writing` skill. Do not copy or rewrite the general philosophy
writing standards. The extension must use `philosophy-writing` for thesis-first
drafting, argument repair, definition testing, objection/reply development,
literature review prose, and revision standards, then add only my local project
context and workflow rules.

Create the extension as a separate skill named `[project-name]-philosophy-writing`
in `[private skill directory]`. Keep it outside any public repository.

Include:

- the project question, thesis, and stable commitments;
- tentative hypotheses and open questions, clearly separated from stable claims;
- preferred terms, definitions, and distinctions;
- section or part functions, if relevant;
- writing templates and output formats;
- citation style and evidence rules;
- paths and naming conventions for private files;
- rules for when Codex may read, create, or update project files;
- privacy boundaries and material that must not be exported, searched, or published.

Design requirements:

1. Keep general philosophy-writing standards in `philosophy-writing`; do not
   duplicate them.
2. Make the extension trigger only when prose is being drafted, reviewed, or
   revised for this specific project.
3. Tell the agent to use both skills together: the extension supplies local
   project context, and `philosophy-writing` supplies the general method.
4. Treat project notes as context, not as independent scholarly evidence.
5. Preserve existing project files and conventions.
6. Do not create or update shared files unless the write policy authorizes it.
7. Put long project context in clearly named reference files and keep `SKILL.md`
   concise, with explicit instructions about when each reference must be read.
8. Include `agents/openai.yaml`, validate the finished skill, and report its
   private installation path and file structure.
9. Review the completed extension for personal or sensitive information before
   any publication. Default to keeping the entire extension private.

After creating it, show me a brief boundary audit: what remains in the general
skill, what lives in the private extension, and whether project-specific or
personal information appears outside the private directory.
```

## Repository Contents

```text
SKILL.md
agents/openai.yaml
README.md
```

## Repository

GitHub: <https://github.com/Aaronlves/philosophy-writing-skill>
