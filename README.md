# paper-polish

A Claude Code skill that makes AI-drafted research papers read as if their authors wrote them, and keeps every claim checkable.

AI drafts of papers share the same tells. Sentences chain clauses with "and", define things by what they are not, end on punchy fragments, stack hedges and set up colon reveals. Claims sound right but rest on no record. As a paper evolves, the draft also drifts: an "every" stops being true, a number no longer recomputes, and details pile up that no conclusion needs. paper-polish gives Claude 39 one-line rules that catch these problems, so it drafts and edits like a careful co-author.

What it covers:

- **Sentences:** "and"-chains, negation framing, vague pointers, stacked hedges, rhetorical tails.
- **Paragraphs and sections:** purpose first, context before claims, every result followed by what it shows.
- **Terms:** names by function, one scheme for parallel items, each term defined once.
- **Content and accuracy:** scope words checked per experiment, statistics with their populations, effects credited only where measured, no over-disclosure.
- **Tables and figures:** units in headers, one counting unit, derived numbers that recompute.
- **Proposing edits:** raise only what a reviewer would notice; use same-length rewrites at the page limit.

## Install

Copy `paper-polish/` into `~/.claude/skills/` to use it in all projects, or into `<project>/.claude/skills/` to use it in one project.

## Use

Claude loads the skill when you draft, edit, polish or audit paper text. You can also ask for it by name, for example: "polish this paragraph with paper-polish".
