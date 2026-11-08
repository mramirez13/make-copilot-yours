# Make Copilot Yours

A guided HR AI in Practice workshop on Microsoft 365 Copilot personalization. This is a self-contained static site.

## Run locally

Open `index.html` in a browser.

## Prompt workshop

`coseb-prompt-builder.html` hosts **Make Your Prompt Work**, the companion HR prompting activity. The filename is retained so existing links, including `https://aka.ms/cosebpromptbuilder`, continue to work; the participant-facing framework is **Context, Goal, Source, Expectations**.

The builder follows the personalization site's one-screen-at-a-time pattern: setup, framework, task selection, four prompt fields, and an editable prompt canvas to copy into Copilot. The canvas is the final screen, with controls to edit the four parts, copy repeatedly, choose another task, or clear drafts. There are no response-analysis steps, checkboxes, partner-debrief screens, or toolkit gates.

Seven HR starters include fictional source material: communications, meeting preparation, process changes, role descriptions, learning plans, aggregate feedback, and draft-plan review. A custom task can start blank. Source naming does not grant Copilot access to a file; participants must supply or attach actual approved material inside Copilot.

Drafts and final prompt edits live only in memory in the current tab and are preserved separately for each task. There is no sign-in, tracking, storage, or network submission. Refresh clears the activity. Changing fields protects manually edited final prompts with a keep-or-rebuild choice. Clipboard failures open a manual-copy dialog. Empty prompts produce an explicit copy message without preventing navigation to another task.

## Host with GitHub Pages

This repository is configured to publish from the `main` branch at the repository root.
