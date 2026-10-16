# Pulse--AI-mods-and-prompts

**Pick what you need, choose your AI, copy, and get to work.**

Pulse is a free, single-page guide for getting more out of **Claude**, **ChatGPT** and **Gemini**. There is nothing to install and no sign-up. Open the page, choose a category, choose your AI, and copy.

**Live site:** https://Pulse-AImods.surge.sh

## What is inside

| Category | What you get |
| --- | --- |
| **Prompts** | Ready-made prompts for each chatbot (Claude, ChatGPT, Gemini), including *Ultrathink* and *Fan out subagents* for Claude. Fill in the `[BRACKETS]`, then paste. |
| **Skills & add-ons** | Skills, mods, extensions and plugins for Claude, Codex (OpenAI) and Gemini CLI, with copy-ready install lines. Tabs for mods, skills, new repos and trending repos. |
| **Commands** | Slash commands for Claude Code, Codex and Gemini CLI, plus "magic phrases" that work in any chatbot. |

Extras: search on every page, one-tap Copy buttons, light and dark theme, a mobile-friendly layout, and a small pegboard animation that follows your mouse.

## Works offline

Pulse is one self-contained file, `index.html`, with the HTML, CSS and JavaScript together and no external libraries, fonts or images.

- Browsing, searching and copying work with **no internet**.
- You need internet only to open the "See details" links and to install a skill or add-on.

## Run it on your computer

1. Download or clone this repository.
2. Double-click `index.html`. It opens in your browser.

## Publish it with GitHub Pages

1. Create a new repository on GitHub and upload `index.html`, `README.md` and `LICENSE`.
2. Open **Settings**, then **Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*. Pick the `main` branch and the `/ (root)` folder, then press **Save**.
4. After a minute, the site is live at `https://<your-username>.github.io/<repository-name>/`.

## Edit the content

Everything is inside `index.html`, in the `CONTENT` area of the script:

- `PROMPTS` is the list of power prompts, grouped as `claude`, `openai` and `gemini`. Each has a `title`, `icon`, `use` (one plain sentence), `prompt` and `tags`.
- `DATA` is the list of skills, mods, new repos and trending repos.
- `CMDS` is the list of slash commands and magic phrases.

Save the file and refresh the page. There is no build step.

## Good to know

- The star counts and "new / trending" items are a snapshot from October 14, 2026 and may have changed.
- Slash commands change between tool versions. Type `/help` inside the tool to see what yours offers.
- Skills can include scripts. Read a project's page before installing it.

## Credits

Created by **SRIVELTECH**.

The mouse-following pegboard uses the **Hairline** line-drawing engine (`@lucasmarkes/hairline`), embedded in `index.html`. Check that project's license and keep its credit if you publish or redistribute this file.

## Trademarks

Claude, Anthropic, ChatGPT, OpenAI, Codex, Gemini and other names mentioned belong to their respective owners. Pulse is independent and is not affiliated with, endorsed by, or sponsored by them.

## License

Copyright (c) 2026 SRIVELTECH. All rights reserved. See [LICENSE](LICENSE).
