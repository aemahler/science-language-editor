# Science Language Editor

A skill (and plain prompt) that line-edits scientific research manuscripts for clarity, concision, and flow. It returns the revised text plus notes: key changes, author queries, recurring patterns, and word counts.

## Credit

The editing principles are adapted from Anne E. Greene, *Writing Science in Plain English* (University of Chicago Press). The principles are restated in my own words and the examples are original. For the full explanations, examples, and exercises, read the book.

## Install in Claude (claude.ai, desktop, or mobile)

1. Download `science-language-editor.zip` from the latest release. Don't unzip it.
2. In Claude, go to **Customize > Skills**.
3. Click **+**, then **Create skill**, then **Upload a skill**, and choose the zip file.
4. Make sure the skill is toggled on.
5. Paste some manuscript text and ask Claude to edit it.

## Install in Claude Code

Copy the `science-language-editor` folder into `~/.claude/skills/`.

## Use with any other AI chatbot

Open `science-language-editor-prompt.md`, paste its contents into a new chat (or into a project's or custom assistant's instructions), and then paste your text.
