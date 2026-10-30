---
name: paper-polish
description: Concise writing and accuracy rules for research papers (systems and ML venues). Use before drafting or editing any paper paragraph, abstract, caption or table, and when polishing or auditing a draft before submission.
---

# Paper polish

Goal: clear, direct, verifiable prose that reads as written by its authors.

## Before writing
- Read two or three recent papers from the target venue. Match their structure and register.
- Read the surrounding draft. Keep its terms and order.
- Check every number and causal claim against the source records. A plausible claim is not a verified one.

## Sentences
- One idea per sentence. Split clauses chained with "and" or semicolons.
- Say what something does, not what it is not. Use "X, not Y" only with a reason.
- Give numbers, not adjectives or fractions. Give the test when significance matters.
- One qualifier per claim.
- Name the referent, the object and the metric. Avoid "it", "this" and "that" across sentences.
- Vary sentence openings. Avoid runs of fronted phrases.
- No rhetorical tails, punchy fragments, editorial labels, meta narration or emphatic adverbs.
- Use colons for lists and explanations, not for dramatic reveals.
- No bold for emphasis. Italicize a term only at its first definition.
- Use plain words. Replace coined phrases and wordplay with what they mean.
- Don't give code or checks human verbs ("knows", "decides", "says"); name the mechanism.
- Check an unusual word against the venue's papers before using it.
- Don't repeat a verb across adjacent clauses or sentences ("depends ... depends"). Vary it or merge the sentences.
- Before calling another tool's setting "common" or "standard", check its defaults and docs.

## Paragraphs and sections
- Open each section with its purpose. Give context before the claim.
- Bridge from setup to results: say what is compared and where it is shown.
- Follow each result with what it shows.
- Prefer a verified mechanism to an anecdote. Drop any mechanism you cannot verify.
- Use one heading style per section.
- Use run-in headings only for parallel items a reader scans. Drop them on single paragraphs.
- Keep each list item self-contained.
- Cut asides the reader already knows.
- In a design section, present the core idea first and give each headline component its own subsection. Put protocol details after the parts they serve.
- Keep the contribution list near the venue's norm; measure a few published lists first.
- In the opening paragraph, state scale and stakes precisely, separate what the system must choose from what is given, show why the choices are hard with one or two concrete trade-offs, then current practice and its cost. Keep citations out of it; cite where a concept is named.
- Model an opening or related-tools paragraph on the closest papers' structure, but never reuse their sentences.
- When surveying existing tools, open with the problem, credit each category before its limitation, and make the limitations cover every gap your system addresses.
- Support a motivating observation with evidence from where it was observed, not from an ablation of your own system. Give the evidence before the conclusion.
- Leave ablations out of the introduction.
- In a design section, describe the system's defaults. Put protocol used only for the evaluation in the evaluation setup, and check the released code rather than an old copy.

## Terms
- Name things by function, not by internal labels.
- Name and order parallel items the same way everywhere.
- Define a term once, at first use. Skip definitions the text never needs.
- Give each quantity one name. After defining it, use only that name.
- Name a cited system at its first citation, not only inside a citation group.
- Describe a capability rather than one vendor's tool when the design works with any; name a tool as an example only where a mechanism depends on it.

## Content and accuracy
- Report the final system and what supports the argument. Leave development history out. Move supporting detail to the appendix.
- Include a detail only if a conclusion depends on it. Fix a false claim by narrowing it, not by adding an explanation.
- Describe the version of the system that produced the results.
- Check every "all", "every", "each" and "no" against each experimental setting.
- State a statistic's population, period and counting rule.
- Attribute an effect only to what you measured.
- In the abstract, use one number per distinct claim.
- Across the main text, give each claim one number, the one its figure or table shows. Put alternative baselines in the appendix.
- Give each quantity one format throughout (percent or multiple).
- Before cutting a sentence, check what it supports elsewhere in the paper.
- Write each contribution as what it is, what is new against prior work, then the evidence. Keep limitations out of the contribution list. For an industry track, name the deployment.
- State a fairness condition (same budget, same gate) where it matters: abstract, contributions, setup and each comparison, not in every sentence.
- Verify every claim about another system against its source. A contrast must hold for every system it covers.
- Check references with a script against arXiv and Crossref, then check the rest by hand. List every author unless a team byline is the authors' own citation form, cite the peer-reviewed version, and drop access dates once a version is pinned.

## Tables and figures
- Put units in headers. Group related columns under one header.
- Each table supports one claim. Keep only the rows and columns that support it.
- Keep cells to numbers or short labels. Move lists and sentences to an appendix table the caption points to.
- One row per item. Group rows with section-label rows, the same way in every table.
- A column keeps one meaning and format in every table. When you change one, update its definition and every table that refers to it.
- No cell splits a number or leaves one word on a line. Split compound cells into columns and check the rendered PDF.
- Place each table or figure right after the paragraph that first cites it.
- Use one counting unit consistently in the table, caption and text.
- Every derived number must recompute from the printed inputs and the stated formula.
- A column means the same thing in every row. Report outcomes as "x of n" rather than counts whose meaning changes by row, and drop group rows that only state the obvious.
- Plot the statistic the text and tests use, or mark it in the figure.
- When comparing means of a few runs, report mean ± standard deviation.
- Don't define in a caption a term only one cell uses; make the cell self-contained.
- An architecture figure shows inputs and outputs; its labels are names, with details in the caption and text.
- Give the system one color in every figure, and check the palette for color-blind readers.
- Render each figure at its printed width so font sizes match across figures. Keep figure text at least 6 pt in print and lines at least 0.5 pt.
- Use the same spacing between every figure and its caption.
- A caption says what the figure shows and how to read it.
- Don't repeat table rows in prose. State the result and its mechanism.
- Cite each table, figure, section or appendix once per section, where it backs a claim. Don't point back to text the reader just read, and check that each target holds what the sentence says.

## Proposing edits
- When the author asks about wording, answer and propose a rewrite; change the text only when asked.
- Show the full rewritten text, then one line per change saying why.
- Raise only issues a reviewer would notice or that hurt credibility. Say when an item barely matters.
- Before calling a word inflated, check whether the venue's papers use it.
- Never write to a length: propose the best sentence, then trim in a separate pass by removing details no conclusion depends on. To save a line, cut a few words from a paragraph whose last line holds only one or two words.
- Fix readability first and trim for space afterwards, by cutting repetition rather than compressing sentences again.
- Don't leave a paragraph's last line alone at the top of a page or column; trim a few words.
- Verify each reported issue against the source before raising it.
