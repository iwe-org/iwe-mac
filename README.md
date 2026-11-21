<h1><img src="https://iwe.md/images/app/iwe-app-icon.png" alt="" width="40" align="top"> iWe for Mac</h1>

**A native Mac app where you and your AI agent work on the same Markdown notes.**

Open a folder of Markdown files, the same kind of vault Obsidian uses, and you get a keyboard-driven space to write, find and connect notes. **Claude Code** or **Codex** edits them in front of you: what the agent produces lands in your documents, not in a chat log, so the next task starts from everything you already worked out.

iWe is native SwiftUI, no Electron, built on the same Rust engine as the open-source [IWE](https://github.com/iwe-org/iwe) CLI, language server and MCP server.

**[Download iWe.dmg →](https://github.com/iwe-org/iwe-mac/releases/latest/download/iWe.dmg)** · free · macOS 15 or later · no account

[![Latest release](https://img.shields.io/github/v/release/iwe-org/iwe-mac?label=release)](https://github.com/iwe-org/iwe-mac/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/iwe-org/iwe-mac/total)](https://github.com/iwe-org/iwe-mac/releases)
[![macOS 15+](https://img.shields.io/badge/macOS-15%2B-blue)](https://iwe.md/app/?ref=mac-readme-badge)

[Videos](#watch-iwe-in-two-minutes) · [Features](#features) · [Install](#install) · [Main repository](https://github.com/iwe-org/iwe) · [iwe.md/app](https://iwe.md/app/?ref=mac-readme-header)

<a href="https://iwe.md/app/?ref=mac-readme-shot"><img src="https://iwe.md/images/app/GH-screen-1.1.png" alt="iWe for Mac showing project plans and connected documents" width="820"></a>

## Watch iWe in two minutes

**Your agent, writing in the page** (2 min) — Claude Code tightens a paragraph, writes a new section, then adds a chart of the open bugs that redraws as each bug changes stage.

https://github.com/user-attachments/assets/e57763df-46c9-4aea-92a2-ddd0d1010091

**Vim keys for your notes** (2 min) — Move block by block, follow links, search, cut and paste bullets, undo and redo, all without leaving the keyboard.

https://github.com/user-attachments/assets/c3edd2cb-4b7c-4f68-9eda-58aa740c1b23

Both videos with captions are on [iwe.md/app](https://iwe.md/app/?ref=mac-readme-video#videos).

## Why iWe

- **The agent you already have.** iWe runs Claude Code or Codex inside the app with your existing login, skills and hooks. There is no second subscription and no model bundled in.
- **Edits, not chat answers.** You ask in plain words and the answer is a change to your note, written block by block while you watch. One ⌘Z undoes the whole run, even when it touched several notes.
- **Your notes stay a folder of Markdown.** Nothing to import, no database, no lock-in. Any editor opens the files, git versions them, and deleting the app leaves them exactly where they were.
- **Native and keyboard first.** SwiftUI over a Rust engine, with optional Vim keys and every note a few keystrokes away.
- **Private by default.** No account, and your notes never pass through a server of ours.

## Features

### Work with your agent, in the document

- **It sees what you see.** The agent knows the open document, where your cursor is and what you selected, so "tighten this" and "add a chart below this" mean what you expect.
- **Watch it write.** Edits appear block by block as the agent writes them.
- **Keep working while it works.** Your cursor stays where you left it. Esc takes you back to your place, and ⌘↵ follows the agent again.
- **One conversation per tab.** Two tasks can run side by side in two tabs.
- **A browser you share with the agent.** When a task needs the web, the agent opens pages in a browser built into the app. It asks before visiting a site for the first time, and it never types a password.

### Charts that follow your notes

<img src="https://iwe.md/images/app/GH-screen-2.png" alt="A bugs note with a live chart of bugs filed and fixed per week" width="820">

- **Built from your notes.** A chart block reads the properties of your notes, such as the stage of every bug, or a CSV or JSON file in the folder.
- **Always current.** Change a property on one note and the bars move right away.
- **The agent draws it.** Ask for "a chart of where the bugs stand" and the agent writes the chart block. The block is plain text in your Markdown file, so you can edit it too.

### Move through your notes from the keyboard

- **Links you can walk.** A link on its own line nests a note under the current one; an inline link is a cross-reference. Follow either, and go back and forward through everything you opened.
- **Vim mode.** `j` and `k` move a whole block at a time, counts and `gg`/`G` jump, `dd` and `p` move blocks, `/` searches the page, and `?` lists every key. Prefer a conventional cursor? Choose Standard editing in Settings.
- **⌘K opens anything.** Any note by name, or a web address.
- **Tabs, windows and a graph view** that shows how a note connects to the rest of the folder.

### Write in blocks

<img src="https://iwe.md/images/app/GH-screen-3.png" alt="A technical note with a syntax-highlighted Rust code block" width="820">

- **Tables, code and images** edit in place.
- **Diagrams in the page.** Mermaid and SVG blocks draw as pictures.
- **Live pages.** An HTML block renders as a live page, for a dashboard of your own.
- **Themes.** Standard, Book, Compact, Typewriter, Gruvbox, Solarized, or one of your own.

### Search and query

<img src="https://iwe.md/images/app/GH-screen-4.png" alt="A release note with its version, status and date shown as property chips under the title" width="820">

- **Full-text search** across every note, with no setup and no import.
- **Properties as chips.** Frontmatter shows as chips under the title, each with its own control, checked against the schemas you define.
- **A hub note is a table.** Next to each nested link, iWe shows that note's properties, so a list of bugs reads as a table of their stages and owners.
- **Search pages** filter notes by their properties and links, and group the results.
- **A sidebar where every row is a query.** Folders, tags and schemas each open as a live list you can pin.

### See every change

- **One timeline** for your edits and your agent's, with block-level diffs.
- **Undo across notes.** An agent run that touched several notes is still one undo step.
- **Pick up where you left off.** Relaunching brings back every window, tab, cursor and conversation.

## Install

1. Download [iWe.dmg](https://github.com/iwe-org/iwe-mac/releases/latest/download/iWe.dmg) and drag iWe to Applications. The app is signed and notarized, and updates itself.
2. Open a folder of Markdown files, such as an existing Obsidian vault, or start from a [workspace template](https://iwe.md/templates/?ref=mac-readme) with File ▸ New Workspace from Template….
3. To work with an agent, have [Claude Code](https://claude.com/claude-code) or [Codex](https://developers.openai.com/codex/cli) installed and signed in. iWe uses the login you already have.

Requires macOS 15 or later. Every version is on the [releases page](https://github.com/iwe-org/iwe-mac/releases).

## What iWe does not do yet

There is no iPhone, Windows or Linux version, and no built-in sync between devices. Because the notes are plain files, you can sync the folder with git or any file-sync tool you already use.

## Privacy

Your notes stay on your Mac. The app sends crash diagnostics and optional anonymous usage statistics, never the content of your notes. Details are in the [privacy notice](https://iwe.md/privacy.html?ref=mac-readme).

## Part of IWE

iWe for Mac is one way into an IWE knowledge base. The same folder of notes works with:

- **[IWE](https://github.com/iwe-org/iwe)**, the main repository: the open-source Rust engine, the `iwe` CLI, the language server and the MCP server for AI agents.
- **Your editor**: [VS Code](https://github.com/iwe-org/vscode-iwe), [Neovim](https://github.com/iwe-org/iwe.nvim), [Zed](https://github.com/iwe-org/zed-iwe) and Helix through the language server.
- **Workspace templates**: ready-made knowledge bases from the [template registry](https://github.com/iwe-org/templates).

Use the app, your editor, or both.

## Feedback

This repository hosts the app's releases and its issue tracker. Report a bug or ask for a feature in [Issues](https://github.com/iwe-org/iwe-mac/issues); questions and ideas are welcome in [Discussions](https://github.com/iwe-org/iwe/discussions) on the main repository.

**Community:** [Twitter/X](https://x.com/iwe_md) · [Reddit](https://www.reddit.com/r/iwe/) · [iwe.md](https://iwe.md/?ref=mac-readme-footer)
