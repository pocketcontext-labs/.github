<a href="https://www.pocketcontext.com/"><img src="https://raw.githubusercontent.com/pocketcontext-labs/.github/main/profile/assets/social-card.png" alt="PocketContext. Give your agent a second brain. Your knowledge. Connected. Under your control." width="1200" /></a>

Give your agent a second brain. PocketContext is a local knowledge base in one program — a server, a browser reader and a command-line client for macOS, Linux and Windows. Your agent brings in your notes as sources, connects them into pages that cite their evidence, and answers from what you already know. You choose the machine: your own computer, or alongside an always-on agent.

## Projects

| Project | What it provides |
| --- | --- |
| [PocketContext](https://github.com/pocketcontext-labs/pocketcontext) | The knowledge base: immutable sources (text notes, and PDFs, images or audio your agent converts to text), Markdown pages with structured properties and citations, full revision history, authenticated search and SQL reads, and an installable skill for Claude Code, Codex and Antigravity. |

## What it does

- **Answers with sources.** Pages keep their citations and revision history, so you can see how a page developed and what supports it.
- **Works with the tools you already use.** Your agent brings text from Notion, Obsidian, Gmail, Jira and others through its own authorized tools. PocketContext has no built-in connectors.
- **Explore your knowledge.** Browse published pages and searchable original sources, follow citations to highlighted passages, and organize topics and catalogs through page properties.
- **Organize with spaces.** A project belongs to one person, and spaces simply partition that knowledge. New projects start with one space, Default; you or your agent can create, rename, archive and restore spaces and choose the default. Archiving preserves evidence and history.
- **Use it from another computer.** A built-in private tunnel connects your computer to the server on an agent computer, exposing only the project's port; you still sign in to the project's one account.
- **Stays yours.** One person, one server with authenticated clients, and a project folder you can back up: a SQLite database, a storage folder and a configuration file, with the program that opens them beside them.

Version 0.12.1 stores any file but extracts only UTF-8 text itself: your agent converts PDFs, images and audio, and PocketContext marks that text as derived evidence. PocketContext is not an AI model: your agent supplies the reasoning, scheduling and access to other services. Since 0.12.0 an optional helper in the repository imports an existing Obsidian collection as pages, keeping the original files as sources. The program lives in the project folder, and its installers ask you to name that folder. Like every release since 0.11.0, it does not open databases created by 0.10.0 or earlier and has no upgrade path: export what you need with the earlier release and start a new project.

## Get started

The [PocketContext website](https://www.pocketcontext.com/) has copyable setup prompts for your own computer or an always-on agent computer, and a short guide. Or ask an agent that can run commands to follow the [0.12.1 README](https://github.com/pocketcontext-labs/pocketcontext/blob/v0.12.1/README.md): it installs the binary into the project folder you name, creates a project and installs the skill. Downloads and release notes are on the [0.12.1 release page](https://github.com/pocketcontext-labs/pocketcontext/releases/tag/v0.12.1); the [data model](https://github.com/pocketcontext-labs/pocketcontext/blob/v0.12.1/docs/data-model.md) covers the details. For questions and contributions, use the [issue tracker](https://github.com/pocketcontext-labs/pocketcontext/issues).

[Website](https://www.pocketcontext.com/) · [PocketContext for business](https://business.pocketcontext.com/) · [LinkedIn](https://www.linkedin.com/company/pocketcontext)
