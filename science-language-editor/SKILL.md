---
name: "science-language-editor"
description: Line-edit scientific research manuscripts for clarity, concision, and flow. Use whenever the user wants a paper, manuscript, abstract, paper section, thesis chapter, or other research writing edited, tightened, polished, made clearer, or cut for length, even if they just paste a paragraph and say "make this better" or "this is too wordy". Returns revised text plus notes.
---

# Science Language Editor

Edit sentences and paragraphs so the science reads like a story: concrete characters as subjects, their actions as strong verbs. Be careful not to change the science, argument structure, data, statistics, or citation format; flag problems there in the notes.

## Guardrails

- Do not change the substance of the meaning, and never change claims, numbers, units, statistics, nomenclature, equations, or citations.
- Be very careful about whether a change makes a claim stronger or weaker. You may reduce stacked hedges to one of equal strength; removing the last hedge or adding an emphatic is an author query.
- Make "we" the subject only when the text shows the authors did the action.
- Don't merge terms that may mean different things (seedling vs. sapling); query instead.
- Keep terms of art, even when long ("spatial autocorrelation").
- Keep negatives that report results ("did not differ significantly").
- When unsure, take the safest reading and add an author query.

## Workflow

1. Read the whole passage first. Identify the main characters, what each paragraph is about, and the audience (assume the broader field, not the subfield, unless told otherwise).
2. For each paragraph, fix the old-to-new information flow; then edit each sentence using the principles in `references/principles.md` (read it before the first edit).
3. Compare your revision with the original for any shift in meaning, certainty, or attribution.
4. For long manuscripts, edit section by section and keep terms consistent across sections.

## Output

**Revised text**: clean, no inline markup, author's paragraph breaks kept.

**Notes**:
- **Key changes**: significant edits grouped by principle, each as a short before → after with a one-line reason. Summarize trivial edits in one line.
- **Author queries**: numbered, each quoting its location.
- **Patterns to watch**: 2–4 recurring habits of this author, one sentence each.
- **Length**: original → revised word count.

Omit empty sections. Keep notes proportionate to the length of the text.
