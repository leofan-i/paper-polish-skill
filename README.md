# paper-polish

A Claude Code skill that helps research-paper drafts avoid common AI-draft anti-patterns and keep every claim checkable.

AI-drafted papers often share the same problems: sentences chained with "and", claims framed by what something is not, stacked hedges, and claims with no source behind them. As a draft changes, its scope words, numbers and details also fall out of sync with the results. paper-polish gives Claude 39 one-line rules to avoid these problems and to check each claim against its source.

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
