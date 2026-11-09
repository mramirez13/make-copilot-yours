# Make Copilot Yours

A guided HR AI in Practice workshop on Microsoft 365 Copilot personalization. This is a self-contained static site.

## Run locally

Open `index.html` in a browser.

## Prompt workshop

`coseb-prompt-builder.html` hosts **Prompting Essentials for HR**, available at `https://aka.ms/buildyourprompt`. The filename is retained so existing links, including `https://aka.ms/cosebpromptbuilder`, continue to work; the participant-facing framework is **Context, Goal, Source, Expectations**.

The page combines the original Prompting Essentials' friendly reading flow with the **Make Copilot Yours visual family**: warm off-white backgrounds, rose accents, Segoe UI typography, charcoal dark mode, 650-weight headings, restrained borders, and 16px cards. It does not import the original Prompting Essentials blue/navy palette, purple accents, gradients, or elevated card shadows.

The open layout includes a welcoming hero, four ingredient cards, a simple-to-strong example, an editable prompt canvas, reusable patterns, and a closing takeaway. Section links provide direct access without wizard screens or completion gates. There are no response-analysis steps, checkboxes, partner-debrief screens, or assessments.

Seven HR starters include fictional source material: communications, meeting preparation, process changes, role descriptions, learning plans, aggregate feedback, and draft-plan review. A custom task can start blank. Source naming does not grant Copilot access to a file; participants must supply or attach actual approved material inside Copilot.

All four ingredient fields and the editable output are available together. Ingredient changes update the prompt automatically until it is edited directly; after that, a visible notice and explicit keep-or-rebuild confirmation protect manual edits. Blank ingredients produce clear placeholders, not navigation errors. Pattern buttons load the corresponding task and preserve any existing draft.

Drafts and final prompt edits live only in memory in the current tab and are preserved separately for each task. There is no sign-in, tracking, storage, or network submission. Refresh clears the activity. Clipboard failures open a manual-copy dialog. Empty prompts produce an explicit copy message without preventing task switching.

## Companion exercises

The shared rose-star header identifies each site as **Make Copilot Yours**, **Prompting Essentials**, **Cowork Delegation**, or **Your First Agent**, respectively. Every header uses the same subheader: **HR AI IN PRACTICE**. These header identities do not change navigation labels or exercise copy.

Headers contain no top-right theme switches or exercise shortcut buttons. Light/dark styling is selected on page load from the browser preference (or the explicit `scoutTheme` query parameter). The shared workshop navigation and in-content exercise actions remain available.

All pages reserve a stable scrollbar gutter so the centered header, star, and content do not shift when navigating between shorter and longer activities.

All four pages use one cohesive top-level workshop navigation: identical exercise names, order, rose button styling, 44px touch targets, and a filled current-page indicator. Its surface and borders span the viewport; the header, navigation buttons, and content share a 1040px maximum content width with 40px gutters, reducing to 16px at 680px and below. Links wrap on narrow screens instead of hiding exercises in a horizontally scrolling strip, and the navigation scrolls away with the page. Build Your Prompt has no additional section-navigation row, and Guidelines Guide has no separate underlined-link family navigation or duplicate footer site tree. The personalization journey remains an activity progress indicator, not another site menu. Preserve this shared navigation treatment across future changes; matching colors alone is not enough to make the experiences familial. The two additional pages use the same visual family and open, editable-copy interaction.

Accessibility support includes keyboard-visible focus, focusable skip-link destinations, labeled inputs and native dialogs, live copy/status messages, reduced-motion support, stronger dark-theme control boundaries, and rose links with improved contrast. The personalization visual guide is optional and stopped/hidden by default; its button starts and stops it, and equivalent numbered text instructions remain available. Automated axe checks and keyboard/reflow checks support these improvements but are not a claim of full WCAG conformance or a substitute for assistive-technology user testing.

### Delegate the Work

`delegate-the-work.html` supports a 6-8 minute manager-enablement exercise. It includes a fictional source pack, editable outcome, deliverables, and working agreement, plus a copy-ready assignment. Copilot Chat is the default route: propose a plan, then draft deliverables one at a time when asked. Participants with Cowork access can instead commission connected work with a plan-first pause and human checkpoint. The page does not imply Chat performs background execution, and it does not require Cowork access.

### Build Your Guidelines Guide

`build-your-guidelines-guide.html` supports an introductory Agent Builder exercise inside Microsoft 365 Copilot, not the standalone Copilot Studio authoring experience. Participants use the same fictional workshop handbook, available to read and download as a plain-text knowledge file. The page supplies an editable build description, configuration references, and copyable prompts for the Agent Builder preview.

Participants must actually add the handbook in Agent Builder's Knowledge configuration and wait for it to be ready; mentioning a filename in instructions does not attach it. Maker and knowledge-source availability depend on account licensing and tenant policy. This is a personal learning prototype, not an instruction to share or publish an HR policy service. Workplace follow-through should begin with an existing approved agent and a content owner, using a maintained source rather than separate handbook copies. Prompt instructions are not a technical guarantee of source-only answers.

Both companions keep drafts only in memory. Refresh clears changes. Clipboard failures provide manual copying, and changes to ingredients cannot silently overwrite a manually edited output. The guidelines download is an explicit user-triggered file download; neither page uploads or collects participant inputs.

## Host with GitHub Pages

This repository is configured to publish from the `main` branch at the repository root.
