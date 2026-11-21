# iWe for Mac Changelog

## 1.23.0 - 2026-11-23

In this release HTML written in your notes renders as a page, images and text files open inside the app, and the conversation panel shows what a conversation has used.

**HTML in your notes renders.** HTML written directly in markdown, such as a README's centered hero, images with a set width, tables and collapsible sections, shows as a page instead of its source. Its links open the linked note, or the web page in the in-app browser, and web images such as badges load once you allow them in the new Privacy settings.

**Images and text files open in the app.** Click an image in the sidebar to view it with Zoom to Fit and Actual Size, or a config, source or other text file to read it with find and line wrapping. Links to these files in a note open the same viewers.

**See what a conversation has used.** The icon at the top of the conversation panel shows how full the agent's context is, the tokens it has used, its estimated cost where the agent reports one, and how many turns, tool calls and changed documents it took. The counts stay with the conversation after a restart.

## 1.22.0 - 2026-11-22

In this release you can mark up the PDFs in your workspace and the agent can read and add those marks, and Antigravity joins Claude Code and Codex as an agent you can run on your own account.

**Highlight, underline and annotate your PDFs.** Select text in a workspace PDF and highlight it, underline it or add a note from the PDF bar or the right-click menu. Rest the pointer on a note to read it, click to edit it, drag to move it. The marks are saved into the file, so Preview and other readers show them too.

**The agent works with your PDF marks.** When the agent reads a PDF it sees your highlights, underlines and notes, and it can mark a passage or remove a mark itself. Its marks appear in the open viewer right away.

**Antigravity as your agent.** Pick Antigravity next to Claude Code and Codex in Settings or the conversation panel, and it runs on your own Google login, with the models your account offers, an effort setting, approval cards for its file and shell tools, and edits to your notes applied through the editor like the other agents.

## 1.21.0 - 2026-11-21

In this release the sidebar shows your files as well as your folders and lets you rename them and move them to the Trash, CSV files open as tables, and link autocomplete finds files and web pages.

**Your files are in the sidebar.** With Non-Empty Only off, each folder lists its files under its subfolders: a note opens in the editor, a CSV, PDF or HTML file in its viewer, and anything else in its default app. Rename a folder or a file and every link to it, and to the notes and files inside it, follows; ⌘Z puts it all back, files on disk included. Move to Trash says how many files and notes a folder holds before anything goes.

**CSV files open as tables.** Follow a link to a CSV, TSV or TAB file, or find it in ⌘K, and it opens in the tab as a table you can sort by any column, filter with ⌘F and copy rows from. It reloads when the file changes.

**Links to files and web pages as you type.** Typing `[` offers PDF and HTML files from your workspace and pages from your browsing history next to your notes, and ⌘K keeps a few matching files and pages in view instead of burying them under notes.

## 1.20.0 - 2026-11-18

In this release PDFs open inside the app and the agent can read them, the sidebar takes on the look of a Mac sidebar, and the agent carries only the instructions a task needs.

**PDFs open in iWe.** A link to a PDF in your notes, or a PDF you reach on the web, opens right in the tab, with thumbnails, its table of contents and find with every match highlighted. Back and Forward step through it like any page, and it comes back at the page you left. ⌘K finds PDFs and HTML pages in your workspace by name, and one click opens a PDF in Preview.

**The agent reads your PDFs.** Ask about the PDF on screen, drop one on the prompt, or give it a link: it reads and searches the whole file, quotes a passage with a link straight to its page, and can open the PDF at that page with the passage selected.

**The sidebar looks like a Mac sidebar.** Documents, folders and pinned items sit in sections the way they do in Finder, and the Pinned section folds away. Its text and rows follow the sidebar size you pick in System Settings, the way Finder's do, and a click anywhere in a row's left margin opens or closes it. New filters show only hubs, or only folders that have something in them.

**The agent sends far less with every request.** It loads its how-to for charts, pages, diagrams and data files only when a task first needs it, so each turn carries less.

**More Vim motions.** `d$`, `d0`, `d^`, `c$`, `c0`, `c^`, `y$` and `y0` work, and `C` and `D` act to the end of the block.

## 1.19.0 - 2026-11-15

In this release the agent can work with the data files and web pages in your workspace and check its git history. It also asks before it reaches a site you haven't allowed. The app is now published by iWe Software LLC.

**The agent works with your data files and pages.** It finds and reads the CSV, JSON, HTML and text files in your workspace and answers questions from them. It adds rows to a data file without touching the rows already there, and changes a few lines of a page without rewriting it. It knows which page you have open, so "this page" means that page.

**The agent asks before it visits a site you haven't allowed.** That covers fetching a page as well as browsing. It also asks before it reads a page you opened yourself. Sites you allow are kept for your account, not inside the workspace folder, so a shared or copied workspace can't allow a site for you.

## 1.18.1 - 2026-11-13

This release keeps agent runs going when they should, tells you plainly when an agent is not signed in, and tidies up workspace setup and the Vim keys.

## 1.18.0 - 2026-11-11

This release adds a gallery of workspace templates you can start a new workspace from, and shows you what is new after each update.

**Start a workspace from a template.** File ▸ New Workspace from Template… opens a gallery of community templates. Search it, see what each one gives the agent, and create a workspace that opens on the template's start page.

**See what is new after an update.** A What's New card shows the highlights of every version since the one you last used. Help ▸ What's New in iWe opens it any time.

## 1.17.0 - 2026-11-09

This release lets you choose your agent, or none, the moment you first open the app, and lets you start in a folder of your own.

**Pick your agent on the welcome card, or none at all.** The card lists the agents installed on your Mac and lets you choose a signed-in one. No Agent turns every AI feature off until you choose one in Settings.

**Start in your own folder.** The welcome card ends with Open Your Workspace…, which opens any folder you like, or Open the Default Workspace.

## 1.16.0 - 2026-11-08

This release lets you choose how often Claude Code asks before it runs a command, and keeps the document steady while the block cursor moves past tables and code blocks.

**Claude Code asks only when it matters.** Settings ▸ Agent ▸ Permission mode starts on Auto: Claude Code runs what it judges safe and asks you only about the rest. Ask every time keeps the old behavior, and a third choice follows your own Claude Code settings.

**The document stays put as the block cursor moves.** `j` and `k` past tables, code blocks, diagrams, pages and images no longer throw the view elsewhere, and `zz` centers the row or line you are on.

## 1.15.0 - 2026-11-07

This release adds comments to your notes, a setting that keeps Claude Code to your notes, and html pages that can set a document's fields.

**Comments in your notes.** Write a note to yourself or to the agent on its own line or inside a sentence. It shows as gray text or a small speech bubble, stays in the markdown file, and is hidden everywhere else. ⇧⌘M adds one.

**Keep Claude Code to your notes.** Settings ▸ Agent ▸ Access ▸ Notes only gives Claude Code no shell and no file tools, so it can work with your notes but cannot touch other files, code or GitHub.

## 1.14.1 - 2026-11-03

This release fixes the agent's streamed reply when it calls tools partway through an answer.

**The agent's reply reads in full while it works.** The last word before a tool call no longer goes missing, and what the agent writes after the call starts a new paragraph instead of running into the sentence before it.

## 1.14.0 - 2026-10-31

This release lets several workspaces stay open at once, each in its own windows, makes Return at the start of a block insert a new block above it, and gives lists a menu to change their type.

**Several workspaces at once.** Open a workspace in a new window and keep the current one open; a relaunch reopens every workspace that was open.

**Return at the start of a block adds a block above.** The cursor moves into a new empty block, and the block you were in keeps its heading, its checkbox and its formatting.

## 1.13.0 - 2026-10-30

This release makes tabs open smoothly and on the page you are looking at, lets HTML pages and charts use the whole column and answer the first click, and puts your pinned items one press away.

**Tabs open smoothly.** A new tab opens on what you are looking at, without the window flickering, losing focus or flashing the sidebar, and the tabs restored at launch arrive together.

**HTML pages and charts fill the column.** Pages span the full width without a frame, and their buttons, links and tabs work on the first click.

## 1.12.0 - 2026-10-27

This release lets you split a section into one note per sub-section in a single step, and tidies up Settings.

**Split a section into notes in one step.** Hold Option on a header's context menu and Extract Sub-Sections moves each sub-section into its own note, leaving a link to each in its place.

**Settings behaves.** The Agent tab speaks your language and keeps your MCP servers in view, and the Settings window no longer slips behind the workspace window.

## 1.11.0 - 2026-10-25

This release changes how the agent's writing looks as it lands, makes the Group and Sort menus of search and catalog pages easier to use, and keeps the shortcut bar out of Standard mode.

**The agent writes at a steady pace.** Its text appears word by word in a soft blue that fades to the text's own color. Its cursor is a glowing rail in the gutter instead of a band over the block.

**Group and Sort offer the properties that matter.** The menus list the few properties most documents on the page share. Every other property is one search away under More Properties….

## 1.10.1 - 2026-10-24

This release keeps section anchors on links when a document is renamed. It is the first published build of [1.10.0](1.10.0), which was cut but not published, so it carries that release's changes as well.

**The agent fixes what it breaks.** When something the agent wrote is broken or outdated, such as a chart that does not draw or a link to a document that does not exist, it hears about it right away, and the app has it fix the problem before the turn ends.

**Rendered blocks appear instantly.** Diagrams, SVG images, HTML pages and charts show their last render as soon as a document opens, and update once the new render is ready.

## 1.10.0 - 2026-10-24

This release has the agent fix what it breaks before it stops, makes rendered blocks appear instantly and editable from their context menu, writes charts as plain Vega-Lite, and gives the Keyboard Shortcuts popup a search field.

**The agent fixes what it breaks.** When something the agent wrote is broken or outdated, such as a chart that does not draw or a link to a document that does not exist, it hears about it right away, and the app has it fix the problem before the turn ends.

**Rendered blocks appear instantly.** Diagrams, SVG images, HTML pages and charts show their last render as soon as a document opens, and update once the new render is ready.

## 1.9.3 - 2026-10-22

This release fixes a crash around duplicated documents and smooths how the cursor moves over charts, diagrams and other rendered blocks.

**Stability improvements.**

## 1.9.2 - 2026-10-20

This release puts New Document, New Tab and Close Tab back at the top of the File menu.

**Stability improvements.**

## 1.9.1 - 2026-10-19

This release makes the caret go where you send it: the arrow keys cross paragraphs in Vim mode, the caret stays on its own line where a paragraph wraps, and undo no longer drops you into editing.

**Stability improvements.** The caret goes where you move it, on wrapped lines and across paragraphs in Vim mode, and undo keeps you in the mode you were in.

## 1.9.0 - 2026-10-18

This release brings iWe to nine more languages and tidies the menu bar: conversation and table commands get menus of their own, items that duplicated a toolbar button are gone, and every command carries an icon.

**iWe in your language.** Menus, settings, sheets and messages are now in Spanish, French, German, Japanese, Simplified Chinese, Brazilian Portuguese, Russian, Ukrainian and Danish, following the language chosen in System Settings for the whole Mac or for iWe alone.

**A cleaner menu bar.** Conversation commands have a Conversation menu and table commands a Table menu, items that duplicated a toolbar button are gone, and every command carries an icon.

## 1.8.0 - 2026-10-18

This release adds a workspace statistics popup, moves New Tab to the toolbar, and makes tabs behave as parts of one window: the sidebar is shared across a window's tabs, each tab keeps its own cursor, and restored tabs come back as tabs.

**See your workspace at a glance.** View › Workspace Statistics (⌥⌘I) shows how many documents, words, links, orphans and broken links the workspace has, and which documents are the longest, the most referenced and the most connected.

**Tabs behave like one window.** Hiding the sidebar hides it in every tab of the window, each tab keeps its own cursor on a shared document, and tabs restored at launch come back as tabs instead of a stack of small windows.

## 1.7.1 - 2026-10-17

This release sorts titles the way your language does and makes the agent's task card name every document it touched once, with its own row for property changes.

**Titles sort the way your language does.** An emoji at the start of a title no longer decides where it goes, upper- and lowercase sort together, and `Note 2` comes before `Note 10`.

## 1.7.0 - 2026-10-15

This release makes wiki links that name a note by its file name find it in any folder, and adds a Pin button to the toolbar. Background agents and Codex subagents are now visible and stoppable, the agent's browser work stays on screen, and the agent writes links in your workspace's format.

**Wiki links find notes in any folder.** A link such as `[[Chinese Language Plugins]]` opens the note, lists in its backlinks, and draws its graph edge wherever the note lives.

## 1.6.2 - 2026-10-14

This release polishes the window: popups, menus and panels lift off the page with a native shadow, text scrolled under the toolbar blurs behind it, and switching the theme back to Auto changes the whole window at once. The agent's working glow stays off rendered charts and diagrams, and the Privacy Notice names the analytics processor.

**Visual improvements.** Popups, menus and panels lift off the page, text blurs under the toolbar, and the window follows a theme switch back to Auto.

## 1.6.1 - 2026-10-12

This release keeps changes made outside iWe from being lost when a note is deleted at the same time.

**Changes made outside iWe always arrive.** When another tool deletes a note and edits other notes in the same moment, as `iwe delete` does when it removes a note and the links to it, iWe now takes in every change instead of discarding them all.

## 1.6.0 - 2026-10-11

This release lets a chart draw a data file kept beside your notes, and asks once about usage data where it starts off. Claude Code conversations hold up better: long tool calls and large results get through, a retried edit can no longer be overwritten by a late one, and a turn that hands work to background agents waits for them. The setup screen is redesigned, animations are one switch, and links in table cells work.

**Charts from your own data files.** A chart can draw a CSV, TSV, JSON or JSONL file in the workspace, joined to your notes' fields, and it redraws as soon as the file is saved. When the file cannot be read, the chart says which file and which line.

## 1.5.0 - 2026-10-10

This release is about the first minutes with iWe. A folder that was never set up opens on a setup screen, and the agent turns it into a knowledge base with you, in a conversation of its own. The first launch asks how you edit and opens a welcome note that shows what the agent can draw into a page. The agent panel is tidier: finished turns fold to one row, replies sit on their own card, and the chips beside the prompt stay out of the way while a turn runs. Fixes cover a blank Home, green-on-green diffs, MCP connectors you are already signed in to, and what an error report says.

**Set up any folder with the agent.** Open a folder that was never set up and a screen says what it found, where your notes will live and which agents are connected. *Set Up with Claude Code* (or Codex) starts a conversation in which the agent proposes a structure sized to the folder, asks which parts to build, and creates the index, the hubs and the documents in front of you.

**A better first launch.** One card asks how you want to edit, Standard or Vim, and whether the shortcut bar is shown. The workspace iWe creates opens on a welcome note with three prompts to try and example pages of charts, diagrams and a live dashboard, each a real block you can edit.

**A tidier agent panel.** A finished turn folds to its title with how long it took and *View changes*; a click opens the steps. Replies sit on a faint card, and the agent chip gives way while a turn runs.

## 1.4.0 - 2026-10-09

Claude Code and Codex can now reach the MCP servers you already set up for them, so the tools you rely on outside iWe come along into the conversation. View changes reads better: each document gets its own card that starts at its first heading. The agent picks a reply's form more sensibly, and a long list of fixes covers hosted sessions that could quit or freeze the app, horizontal rules, tables, images and two-window editing.

**Bring your own MCP servers.** Turn on *Use my MCP servers* in Settings ▸ Agent, and Claude Code or Codex gets the servers you already configured for that CLI, next to iWe's own. A checkbox per server says which ones come along.

**Clearer changes.** View changes gives each document its own card that starts at its first heading, with changed blocks tinted and unchanged text greyed, so you see what moved at a glance.

## 1.3.0 - 2026-10-09

The agent can now ask you to choose, and you can answer: Claude Code, Codex and the built-in agent all put their questions in one card you click or key through. What a turn changed moves next to the turn itself: every finished turn ends with a Done row, and View changes opens that turn's diffs in the agent panel, drawn the way the document draws them. Underneath, the window stays responsive while the agent starts, files are written and replies stream, and tall code blocks and tables keep the cursor in view.

**Answer the agent's questions.** When Claude Code, Codex or the built-in agent asks you to choose, the choices appear as a card: click one, press 1–4, pick several when the question allows it, or type your own answer.

**See what each turn changed.** Every finished turn ends with *Done · View changes*, which opens that turn's edits in the agent panel, formatted like the document instead of raw markdown.

## 1.2.0 - 2026-10-07

Tables become something you edit rather than something you route around: rows behave like blocks, cells like words, in both editor modes, with a Table menu and undo that covers it all. Watching the agent work changes too: its text arrives on a steady beat, fades in tinted and cools to its own color, the block it is writing glows, and you can send a prompt in the background and keep reading while it runs. ⌘K now opens on where you just were.

**Edit tables in either mode.** Arrow into a cell and type; rows move, copy, delete and undo like blocks, and a Table menu adds and removes rows and columns.

**Watch the agent write, or let it work in the background.** The agent's text fades in on a steady beat and cools from its accent as you catch up, and ⌥↵ sends a prompt without leaving what you are reading.

## 1.1.0 - 2026-10-04

Pictures come into a document the way they come into any other editor: paste a screenshot or drop an image file, and it lands as a figure. Web pages get a Reload button, file uploads work in the browser, and a set of fixes makes inclusion rows and the arrow keys around them behave.

**Paste and drop images.** Paste a screenshot or drop image files from Finder, and the picture is saved next to the document and shown in place.

**Reload a web page.** A Reload button and ⌘R refresh the page you are looking at, even while you are typing in it.

## 1.0.0 - 2026-10-03

The first major release. Documents get themes, charts draw live from your notes, and the agent answers "show me" with a chart or a table that stays current instead of a paragraph of numbers. Mermaid diagrams are drawn by Mermaid itself, the toolbar's back and forward buttons remember where you have been, and a long list of fixes makes standard editing mode, the cursor and the agent UI behave the way you expect.

**Themes for your documents.** Pick how documents look in Settings ▸ Appearance ▸ Theme: Standard, Book, Compact, Typewriter, Gruvbox or Solarized, or a theme of your own. The editor, previews, diagrams and pages all follow it.

**Live charts from your notes.** A chart block draws a chart from your documents and keeps it current as they change, and the agent builds charts, tables and dashboards when you ask to see something.
