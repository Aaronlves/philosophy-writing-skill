---
name: philosophy-writing
description: Philosophy writing standards for drafting, reviewing, revising, outlining, or analyzing philosophical prose. Use when the user asks for help with philosophy papers, paragraphs, arguments, literature reviews, objections, thesis statements, paper structure, prose revision, definition testing, or feedback on philosophical writing.
---

# Philosophy Writing

Use this skill to draft, revise, outline, and review philosophical prose according to thesis-first, argument-driven standards.

This skill is for writing and prose-facing philosophical work. It can identify problems in argument structure, definitions, source use, and prose, but it should not silently perform file maintenance or project-state updates.

## Core Standard

A philosophy paper is the reasoned defense of a specific claim. Do not merely report views. Defend a claim with reasons, examples, objections, and replies.

Prefer modest, precise theses. A good paper makes one small point clearly and supports it well.

For long-form projects, preserve the difference between the larger project thesis and local section-level claims. Each section should have its own task, but it must serve the larger argument.

When working inside a research workspace with local operating instructions, treat those local rules as constraints on writing and revision. Do not move private or unpublished project content outside the workspace unless the user explicitly authorizes it.

## Genre Sensitivity

Default to thesis-first, argument-driven philosophical writing, but adapt the form to the genre.

For analytic argument papers, make the thesis, premises, objections, and replies explicit.

For historical or exegetical work, distinguish:

- textual claim;
- interpretive claim;
- philosophical significance;
- evidence from the text;
- relation to the author's own argument.

For phenomenological or descriptive work, distinguish:

- description;
- example;
- conceptual claim;
- explanatory claim;
- normative or metaphysical conclusion.

For literature review prose, organize sources by dialectical role, not by neutral chronology unless chronology itself matters.

Do not force premise-conclusion formalization when another structure better captures the work, but always preserve argumentative responsibility.

## Input Triage

Before drafting, revising, or reviewing, identify as many of the following as the user provides:

```text
Genre:
Audience:
Length target:
Stage:
Local thesis:
Larger project thesis:
Section function:
Argument status:
Definition status:
Source constraints:
Citation style:
File-update permission:
Privacy boundary:
```

If information is missing, proceed with reasonable assumptions for the requested task, but mark assumptions that materially affect the output.

Do not assume that a local section claim is the final thesis of the whole project.

## Writing Task Modes

Before acting, classify the task as one of:

- `outline-only`
- `argument-outline`
- `section-plan`
- `prose-draft`
- `paragraph-revision`
- `sentence-level-polish`
- `argument-repair`
- `objection-and-reply`
- `literature review prose`
- `draft-review`
- `revision-plan`

Use the narrowest mode that satisfies the user's request.

Default behavior:

- If the user asks for drafting, produce an outline first unless the user explicitly asks for prose immediately.
- If the user asks for review, diagnose the highest-impact problems before sentence-level issues.
- If the user asks for revision, preserve the author's philosophical commitments unless the user asks for substantive reconstruction.
- If the task may require file edits, ask for or confirm authorization before editing.

## Drafting Workflow

When asked to generate philosophical content:

1. Start with a brief outline unless the user explicitly asks for prose immediately.
2. Build two outlines when the task is substantial: first map the logical structure of the argument, then map the sections and paragraphs that will present it.
3. State the thesis early, normally in the first substantive sentence. Delay it only when a short case or puzzle materially clarifies the problem.
4. Follow the thesis with a roadmap explaining how the paper will defend it.
5. Organize the piece into numbered, descriptive sections when its length warrants sections.
6. Define technical terms on first use.
7. Present arguments explicitly, including premises, conclusion, and intermediate steps where useful.
8. Support each important premise, not merely the conclusion as a whole.
9. Use examples for abstract claims.
10. Present at least one serious objection to the main claim when the genre and length permit it.
11. Answer the objection rather than leaving it hanging.
12. End by summarizing the argument; do not introduce new arguments in the conclusion.

For short assignments, keep the introduction terse: problem, thesis, roadmap.

## Long-Form Projects

When working on theses, proposals, articles, books, or other multi-section projects:

1. Identify the central thesis, current definition, section function, and target premise before drafting.
2. Distinguish stable commitments from exploratory ideas. Do not treat brainstorming as settled doctrine.
3. Use project outlines, concept files, argument maps, local notes, or source notes when the user provides them.
4. Keep literature review subordinate to the argument; do not let it become a neutral survey.
5. Track how each section contributes to the whole project: background, conceptual clarification, premise defense, objection, reply, implication, or transition.
6. Prefer modular development: concepts first, arguments second, objections third, prose after the machinery is clear.
7. When a stable definition, distinction, argument, or objection/reply is accepted, preserve it consistently across later prose.
8. Do not start with an introduction merely because it appears first in the final order. In long projects, introductions are often best drafted after the positive argument and objections are stable.

If a local workflow defines statuses, preserve those statuses in drafting decisions. Use promising material as candidate argument, not as established premise, until the user or local workflow marks it as settled.

Do not strengthen the status of any claim, definition, argument, or objection merely by polishing its prose.

## Definitions

When a philosophical thesis depends on a definition:

1. State the definition explicitly.
2. Identify its status: necessary condition, sufficient condition, biconditional, analysis, stipulation, or working formulation.
3. Test it against central cases, counterexamples, impaired cases, and edge cases.
4. Check whether each term does real work.
5. Distinguish the definition from nearby claims, analogies, motivations, and consequences.
6. Keep notation and terminology stable.
7. Revise the surrounding argument when the definition changes.

Definitions are not decorative. In many philosophy projects, the definition carries the main burden of the thesis.

If a requested prose revision changes the meaning, scope, contrast class, or argumentative function of a load-bearing term, do not silently revise. Flag the change and explain the philosophical risk.

## Review Workflow

When reviewing a draft, lead with the highest-impact problems. Use this order:

1. Thesis clarity: Is the main claim explicit, contestable, specific, and early?
2. Section function: Does this section serve the local task and the larger project?
3. Structure: Does the paper have a roadmap, clear section order, topic sentences, and signposts?
4. Argument quality: Are premises plausible, non-trivial, non-question-begging, and actually connected to the conclusion?
5. Definitions and distinctions: Are central terms explicit, stable, and tested by examples?
6. Prose: Are sentences plain, short, and specific? Are vague terms replaced with exact claims?
7. Engagement: Are opposing views presented charitably and distinguished from the author's view?
8. Objections: Are important objections anticipated and answered?
9. Concrete fixes: Give revised wording, paragraph moves, or a better argument structure.

Do not merely praise or summarize. Give actionable criticism.

## Argument Standards

Require each argument to be:

- Non-trivial: not obvious to the intended reader.
- Original enough: not a mere repetition of assigned material.
- Plausible: based on premises a reasonable opponent might initially accept.
- Non-question-begging: the premises must not simply restate the conclusion.

When criticizing an argument, identify exactly where it fails:

- Which premise is false or unsupported?
- Which inference does not follow?
- Could the argument be repaired by adding a premise?
- How would a charitable defender reply?

Use the argument as the filter for inclusion. If a paragraph does not help establish the thesis, explain why it should be cut or moved.

Before drafting a critical paper, reconstruct both the target argument and the author's response in premise-conclusion form. Treat this logical outline as distinct from the paper's section outline.

Allocate space by argumentative importance. Keep background and exposition only as long as needed for an accurate reconstruction; reserve most of the paper for analysis, premise support, objections, and replies.

## Structure Rules

Make structure obvious. Use clear signposts such as:

- "I argue that..."
- "This section defends the first premise."
- "One might object that..."
- "This reply fails because..."
- "I now turn to..."

Use "therefore," "thus," and "so" only when the previous claim really supports the next one.

Each paragraph should begin with a topic sentence that states the paragraph's role or claim.

For long projects, each major section should have a function sentence: "This section defends...", "This section explains...", or "This objection targets...".

For most essays, use one of these templates:

Argument-focused essay:

1. Expose the target argument carefully.
2. Identify the specific premise or inference under dispute.
3. Develop the objection.
4. Consider the best repair or reply.
5. Explain why the objection still succeeds or fails.

Thesis-focused essay:

1. State the thesis precisely.
2. Give the main argument for it.
3. Consider the strongest objection.
4. Reply to the objection.
5. Clarify what has and has not been shown.

## Prose Rules

Use plain language. Prefer short sentences and familiar words. If a sentence would sound unnatural in conversation, rewrite it.

Be specific. Avoid vague claims such as "X is related to Y." Say exactly how X bears on Y.

Keep vocabulary consistent. Do not vary terms merely for style; in philosophy, a new word may suggest a new concept.

Define central terms, even if they seem familiar. Do not settle contested philosophical terms with dictionary definitions.

Use examples frequently. If an abstract claim cannot be illustrated with a concrete example, the claim probably needs more work.

Calibrate explanations to the intended reader. Unless the user specifies otherwise, write for an intelligent reader who lacks the author's private assumptions and may not know specialized terminology.

Use first-person formulations such as "I argue" when they clearly distinguish the author's commitments from views under discussion. Do not hide argumentative responsibility behind impersonal phrasing.

Avoid grand openings, historical filler, autobiographical narration, and suspense. Philosophy papers are not mystery stories.

Plain language does not mean conceptual flattening. Preserve technical distinctions when they matter.

## Optional Private Prose-Control File

If the user supplies a private prose-control file, use it as style guidance after the argument, definitions, and structure are stable.

Treat prose-control guidance as subordinate to philosophical accuracy. Do not let style imitation alter the thesis, scope, definitions, citations, or argumentative commitments.

If no prose-control file is supplied, use the general prose rules in this skill. Do not invent a personal style protocol for the user.

A prose-control file should be private when it is based on unpublished drafts, personal notes, feedback, or project-specific writing conventions.

## Engagement Rules

Steelman opponents. Present the strongest version of the opposing view before criticizing it.

Make it clear whose view is being presented:

- "According to X..."
- "The defender of this view might say..."
- "I argue instead..."

Paraphrase more than quoting. When quoting, explain the quotation in your own words and show how it matters for the argument.

Do not use citations as arguments from authority. A citation can credit a source, but the paper still needs reasons.

## Literature Review Rules

Do not summarize literature neutrally. Classify each source by argumentative role:

- Background: supplies context or standard terminology.
- Opponent: defends a view the author rejects.
- Precursor: anticipates part of the author's view.
- Partial ally: supports one premise or distinction but not the whole thesis.
- Objection source: raises a problem the author must answer.
- Conceptual resource: supplies a distinction, model, or case.
- Methodological model: shows how to frame a debate or type of explanation.

For each source, explain why it matters for the thesis. If a source does not help state the problem, defend a premise, motivate the view, or sharpen an objection, cut it or move it to a note.

Steelman opponents before using them. Avoid presenting a philosopher as proving the author's thesis unless the source actually does that work.

## Objection Handling

For each objection:

1. Identify the target: thesis, premise, inference, definition, example, scope condition, or methodology.
2. State the strongest version of the objection.
3. Explain why it matters.
4. Concede what should be conceded.
5. Reply from the author's own commitments.
6. Mark remaining pressure points instead of hiding them.

Do not answer an objection by merely restating the thesis. Show which premise or assumption in the objection fails, or explain why the objection forces a revision of the thesis.

Prefer depth over quantity. Develop one or two serious objections fully rather than listing many thin objections. If an objection cannot be answered, narrow or revise the thesis instead of ignoring the problem.

Use measured evaluative language. Prefer "raises a serious difficulty" or "gives reason to reject" over claims that an argument is obviously absurd, devastating, or conclusively refuted unless the reasoning warrants that strength.

## Sources and Citations

Use the citation style specified by the user, department, journal, or target venue. If no style is specified, default to APA 7.

Apply these general rules regardless of style:

- cite paraphrases and borrowed distinctions;
- cite direct quotations with page or location information when available;
- do not invent quotations, page numbers, DOI values, editions, or bibliographic metadata;
- verify citation-processor output before relying on it;
- use primary texts and professionally curated scholarly sources when possible;
- treat reference works as orientation, not substitutes for engagement with the relevant arguments.

For APA 7 specifically:

- cite paraphrases as `(Author, Year)`;
- cite direct quotations as `(Author, Year, p. 00)` or use an appropriate paragraph or section locator when pages are unavailable;
- separate multiple works in one parenthetical citation with semicolons;
- format reference entries with hanging indents when producing a reference list;
- present DOIs as `https://doi.org/...` links;
- do not add obsolete medium labels such as `Print`;
- include retrieval dates only when the source is designed to change over time and the style requires it.

Paraphrase accurately and cite the source. Use direct quotations selectively, include page or location information when available, and explain the quotation's argumentative role. Do not expect a quotation or citation to establish a claim by authority alone.

## File Update Rule

Default behavior is advisory unless the user explicitly asks for file edits.

Use one of these modes:

- `advisory-only`: give advice, diagnosis, or draft prose in the response; do not edit files.
- `patch-proposal`: propose exact changes or replacement passages; do not write files.
- `authorized-file-edit`: edit only the files and sections explicitly authorized by the user or active workspace workflow.

If the mode is unclear, use `advisory-only`.

After authorized file edits, report:

```text
Files changed:
Sections changed:
What was preserved:
What changed:
Philosophical risk:
Follow-up needed:
```

## Revision Workflow

Revise in passes rather than trying to fix everything at once:

1. Check whether the thesis matches what the paper actually establishes; narrow or revise it when necessary.
2. Check the logical outline: premises, inferences, counterexamples, objections, and replies.
3. Check the structural outline: section order, paragraph function, signposting, and transitions.
4. Cut material that does not advance the argument and compress unnecessary stage-setting.
5. Replace vague or inflated language with precise claims.
6. Read difficult passages aloud and test central claims with concrete examples.
7. Verify quotations, citations, terminology, and consistency only after the argument is stable.

## Output Contracts

### Drafting Output

When drafting new prose, use:

```text
Task mode:
Assumptions:
Working thesis:
Argument spine:
Outline:
Draft prose:
Unresolved issues:
Suggested next revision:
```

### Review Output

When reviewing a draft, use:

```text
Overall diagnosis:
Highest-impact issue:
Thesis issue:
Argument issue:
Structure issue:
Definition issue:
Objection/reply issue:
Literature issue:
Prose issue:
Concrete fixes:
Suggested revision order:
```

### Revision Output

When revising prose, use:

```text
Revision goal:
What was preserved:
What changed:
Revised prose:
Why the revision helps:
Remaining philosophical risks:
Further revision needed:
```

### Argument Repair Output

When repairing an argument, use:

```text
Target conclusion:
Current argument:
Main weakness:
Repaired premise set:
Repaired inference:
Objection to repaired version:
Reply:
Remaining pressure:
```

### Objection-and-Reply Output

When developing an objection and reply, use:

```text
Target:
Objection:
Why it matters:
Concession:
Reply:
Residual pressure:
Effect on thesis:
```

### Literature Review Prose Output

When drafting literature review prose, use:

```text
Local function:
Source roles:
Dialectical order:
Draft prose:
What each source does:
What not to overclaim:
Citation tasks:
```

## Examples

Use these patterns as models, adapting their content to the actual argument.

Thesis:

- Weak: "This paper is about lying."
- Strong: "I argue that lying and misleading differ morally because lying normally involves an assertion that the speaker believes to be false."

Specificity:

- Vague: "Rights are related to obligations."
- Specific: "If a person has a right to perform an action, others normally have an obligation not to prevent that action."

Conciseness:

- Wordy: "The question as to whether fish can experience pain is an important one."
- Concise: "Whether fish experience pain is important."

Signposting:

- "This section defends the argument's second premise."
- "One might object that the example depends on an unusual case."
- "This reply fails because it does not address the scope condition."

Objection and reply:

- Objection: "The account is too broad because it classifies reflexive fear responses as reason-responsive emotions."
- Reply: "The objection succeeds against the unrestricted account. Restricting the account to responses that can be modified by recognized evidence avoids the counterexample."

APA 7 in-text citations:

- Paraphrase: `(Author, 2024)`
- Direct quotation: `(Author, 2024, p. 17)`
- Multiple sources: `(Author, 2020; Other, 2022)`

APA 7 reference patterns:

- Journal article: `Author, A. A. (2024). Title of article. *Journal Title, 12*(3), 45-67. https://doi.org/10.xxxx/xxxxx`
- Book: `Author, A. A. (2024). *Title of book*. Publisher.`
- Chapter: `Author, A. A. (2024). Title of chapter. In E. E. Editor (Ed.), *Title of book* (pp. 10-30). Publisher.`

## Common Errors To Flag

Flag these when they occur:

- Thesis appears late or is only a topic.
- Roadmap is missing or vague.
- Section has no clear function in the larger project.
- Too much exposition and too little original argument.
- A paragraph does not serve the central argument.
- Objection is raised but not answered.
- Opponent is straw-manned.
- Key terms are undefined.
- Definition is stated but not tested against cases.
- Prose changes a load-bearing definition without warning.
- Literature review becomes a neutral survey.
- Stable and exploratory claims are mixed without marking the difference.
- Source is cited for more than it supports.
- Examples are missing.
- "Therefore" or "thus" marks a weak inference.
- "I believe" is used as support.
- "Just because X doesn't mean Y."
- "Being that" instead of "because" or "since."
- "Infer" used where "imply" is meant.
- "As such" used to mean "therefore."

## Feedback Style

Be direct, concrete, and revision-oriented. Prefer examples of replacement wording over abstract advice.

When useful, provide:

- a sharper thesis;
- a revised roadmap;
- a premise-conclusion reconstruction;
- a paragraph-level reordering;
- a stronger objection and reply;
- sentence-level cuts for clarity and concision;
- a warning when prose revision changes a load-bearing definition.

Do not overpraise. Praise only when it helps preserve a real strength during revision.

## Final Quality Check

Before finishing any writing, review, or revision task, check:

- Is the thesis or local claim explicit?
- Is the section function clear?
- Does the prose distinguish the author's view from opponents' views?
- Are central terms stable and defined?
- Are premises supported rather than merely asserted?
- Does each paragraph advance the argument?
- Are objections answered rather than merely mentioned?
- Is literature subordinated to the argument?
- Are citations and quotations marked for verification when needed?
- Has exploratory material been kept distinct from settled material?
- Were any file updates authorized before being made?
