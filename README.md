# Make Copilot Yours

A guided HR AI in Practice workshop on Microsoft 365 Copilot personalization. This is a self-contained static site.

## Run locally

Open `index.html` in a browser.

## Prompt workshop

`coseb-prompt-builder.html` hosts **Prompting Essentials for HR**, the companion HR prompting page. The filename is retained so existing links, including `https://aka.ms/cosebpromptbuilder`, continue to work; the participant-facing framework is **Context, Goal, Source, Expectations**.

The page adapts the original Prompting Essentials layout, blue/navy theme, and conversational writing for HR: a welcoming hero, four ingredient cards, a simple-to-strong example, an open prompt canvas, reusable patterns, and a closing takeaway. Section links provide direct access without wizard screens or completion gates. There are no response-analysis steps, checkboxes, partner-debrief screens, or assessments.

Seven HR starters include fictional source material: communications, meeting preparation, process changes, role descriptions, learning plans, aggregate feedback, and draft-plan review. A custom task can start blank. Source naming does not grant Copilot access to a file; participants must supply or attach actual approved material inside Copilot.

All four ingredient fields and the editable output are available together. Ingredient changes update the prompt automatically until it is edited directly; after that, a visible notice and explicit keep-or-rebuild confirmation protect manual edits. Blank ingredients produce clear placeholders, not navigation errors. Pattern buttons load the corresponding task and preserve any existing draft.

Drafts and final prompt edits live only in memory in the current tab and are preserved separately for each task. There is no sign-in, tracking, storage, or network submission. Refresh clears the activity. Clipboard failures open a manual-copy dialog. Empty prompts produce an explicit copy message without preventing task switching.

## Host with GitHub Pages

This repository is configured to publish from the `main` branch at the repository root.
