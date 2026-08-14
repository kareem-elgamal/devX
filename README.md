<div align="center">

<img src="https://dev-nexus.pages.dev/logo.png" width="96" alt="DevX" />

# DevX

**One orb, your whole workspace.**

A floating launcher for developers — search your projects, open them in the
right IDE and the right shell, and keep notes, requests, git, meetings and
reminders one keystroke away.

[![Download](https://img.shields.io/badge/download-v0.2.11-0b6fc4?style=for-the-badge)](https://github.com/kareem-elgamal/devX/releases/latest)
[![Documentation](https://img.shields.io/badge/docs-dev--nexus.pages.dev-6b3fb0?style=for-the-badge)](https://dev-nexus.pages.dev)
[![Windows](https://img.shields.io/badge/Windows-10%20%2F%2011-555?style=for-the-badge)](https://dev-nexus.pages.dev/guide/download)

[العربية](README.ar.md) · [Documentation](https://dev-nexus.pages.dev) · [Download](https://github.com/kareem-elgamal/devX/releases/latest)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://dev-nexus.pages.dev/shots/panel-en-dark.png">
  <img src="https://dev-nexus.pages.dev/shots/panel-en-light.png" width="620" alt="The DevX panel: collections, projects and the service icons.">
</picture>

</div>

## Download

**[⭳ Download DevX →](https://github.com/kareem-elgamal/devX/releases/latest)**

| File | What it is |
| --- | --- |
| **`DevX Setup <version>.exe`** | The installer. Adds a Start-menu entry, a desktop shortcut, and an uninstaller. Take this one. |
| **`DevX-portable-<version>.exe`** | A single file that runs as-is. Good for a USB stick or a machine you cannot install on. |

Both are the same application. Neither needs Node.js or anything else installed
first.

> [!WARNING]
> The app is not code-signed, so Windows SmartScreen says the publisher is
> unknown. Choose **More info → Run anyway**.

DevX is a **Windows** application. It opens your IDE, drives Windows Terminal
and WSL, and needs a Windows desktop session for the tray icon and the
always-on-top orb.

## After it starts

DevX does not open a window of its own — it goes to the **tray**, and puts a
small floating orb on your desktop. Press <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>Space</kbd>,
click the orb, or click the tray icon to open the panel — with the search box
already focused.

Carry on with **[Getting started →](https://dev-nexus.pages.dev/guide/getting-started)**

## What is inside

| | |
| --- | --- |
| **[Projects, found by any name](https://dev-nexus.pages.dev/services/panel)** | Collections, aliases and fuzzy search. `Enter` opens the IDE, `Shift+Enter` opens a terminal — in Windows or in WSL, whichever the project uses. |
| **[Quick commands in a real terminal](https://dev-nexus.pages.dev/services/commands-terminal)** | Per-project, per-collection and global commands, run in a tabbed pty session that keeps its scrollback. |
| **[An API tester that knows your project](https://dev-nexus.pages.dev/services/api)** | The base URL comes from the project's own `.env`, saved requests live in the repo, and `Ctrl+Shift+A` opens a scratch tab from your clipboard. |
| **[Meetings, transcribed locally](https://dev-nexus.pages.dev/services/meetings)** | Microphone plus system audio, transcribed on your own machine by Whisper, then summarised into decisions and action items. |
| **[Markdown notes on disk](https://dev-nexus.pages.dev/services/notes)** | A global notebook plus per-project notes, stored as `.md` files you can commit, sync or grep. |
| **[Git info](https://dev-nexus.pages.dev/services/git)** | Branch, ahead/behind, working-tree status, branch switching and the commit graph, per project. |
| **[Prayer times and أذكار](https://dev-nexus.pages.dev/services/islamic)** | Alerts a few minutes after the adhan, a snooze button that runs away from your pointer, and the morning and evening أذكار with counters. |
| **[Reminders](https://dev-nexus.pages.dev/services/reminders)** | One-off or repeating, with snooze — and they survive the app being closed. |
| **[Backup & restore](https://dev-nexus.pages.dev/services/backup)** | One-click or scheduled `.zip` backups of everything, to any folder — including a cloud-synced one. |
| **[Startup projects](https://dev-nexus.pages.dev/services/startup)** | Projects that open themselves, in the IDE or a terminal, when the app launches. |

Arabic and English throughout, English by default, RTL when Arabic is on.

## Documentation

Everything lives on **[dev-nexus.pages.dev](https://dev-nexus.pages.dev)**, in
English and Arabic:

- [Getting started](https://dev-nexus.pages.dev/guide/getting-started) — the first ten minutes
- [Keyboard shortcuts](https://dev-nexus.pages.dev/guide/shortcuts) — every one of them
- [Settings](https://dev-nexus.pages.dev/reference/settings) · [Where data lives](https://dev-nexus.pages.dev/reference/data)
- [Troubleshooting](https://dev-nexus.pages.dev/reference/troubleshooting)

## About this repository

This repository is the **download and documentation home** for DevX. The
application source is not published here.

Found a bug or want a feature? Open an
[issue](https://github.com/kareem-elgamal/devX/issues).

---

<div align="center">

Made by [Karim Sayed](https://github.com/kareem-elgamal)

</div>
