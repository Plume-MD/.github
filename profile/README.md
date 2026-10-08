<h1 align="center">Plume</h1>

<p align="center">
  <b>Markdown, beautifully set.</b><br>
  Double-click a <code>.md</code> file and it opens straight into a clean reading view —
  no vault to import, no project to set up, no editor chrome.
</p>

<p align="center">
  <a href="https://plume-md.com">plume-md.com</a> ·
  <a href="https://plume-md.com/download.html">Download</a> ·
  <a href="https://plume-md.com/docs.html">Documentation</a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Plume-MD/.github/master/assets/reading.png" width="820" alt="A document open in Plume, with the folder tree in the sidebar, a callout, and a table rendering wiki links, highlights, tags and inline maths">
</p>

---

## What this is

Most good Markdown apps assume you are starting a project: import a vault, choose
a workspace, configure a theme. That is the right shape for **writing**. It is the
wrong shape for **reading**, which is what most people do most of the time.

Plume is the other half. A file you double-click, a window, the text set properly,
and nothing else in the way.

- **Reads the Obsidian dialect** — wiki links, callouts, transclusion, highlights,
  tags, block ids, front matter as a properties panel
- **Full GitHub-flavoured Markdown** — tables, task lists, footnotes, definition
  lists, syntax highlighting, KaTeX maths, Mermaid diagrams
- **Edits when you ask it to** — `Ctrl+E` for the raw Markdown in a plain editor
- **Git sync** — keep a folder in a repository; it drives the git already on your
  machine, so no token is ever asked for or stored
- **Plume Vault** — 100 MB, free and optional, for the same notes on another machine

Free software under the MIT licence, for Windows, macOS and Linux.

---

## Five palettes, light and dark

A palette recolours whichever of light or dark is in force rather than replacing
that choice — so Auto keeps following your system inside any of them.

<p align="center">
  <img src="https://raw.githubusercontent.com/Plume-MD/.github/master/assets/palettes.gif" width="760" alt="Plume switching between the Greenwood, Commit, Lapis and Starless palettes, then into dark mode">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Plume-MD/.github/master/assets/palettes-grid.png" width="860" alt="All five Plume palettes shown in both light and dark: Plume, Starless, Greenwood, Commit and Lapis">
</p>

## The graph

Every document in your vault, joined by the links between them.

<p align="center">
  <img src="https://raw.githubusercontent.com/Plume-MD/.github/master/assets/graph.gif" width="720" alt="The Plume vault graph settling, then being fitted and re-arranged">
</p>

## Git sync

Pull what changed elsewhere, commit what changed here, push. Plume drives the
`git` already on your machine, so your credentials stay in your credential helper
or SSH agent — Plume never sees a token, never stores one and never asks for one.

<p align="center">
  <img src="https://raw.githubusercontent.com/Plume-MD/.github/master/assets/git-sync.png" width="820" alt="The Git sync panel in Plume, showing a folder, its GitHub remote, the branch and the last commit">
</p>

## The full tour

<video src="https://raw.githubusercontent.com/Plume-MD/.github/master/assets/tour.mp4" controls muted loop width="820"></video>

If the player above does not appear, the same film is on
[plume-md.com](https://plume-md.com) — or download it
[here](https://raw.githubusercontent.com/Plume-MD/.github/master/assets/tour.mp4).

---

## Repositories

| | |
|---|---|
| **plume** | The desktop application and the website |
| **plume-vault** | The sync service behind Plume Vault |

## Principles

**Your files stay yours.** Plain text on your disk, in folders you chose. The vault
is opt-in, and turning it off leaves every file exactly where it was.

**Nothing happens without you asking.** No telemetry. Nothing is downloaded or
installed until you say so, and every update is checked against a published
checksum before it is allowed to run.

**Say what is true.** Plume is not code-signed yet, so Windows and macOS warn on
first launch — that is written in the release notes rather than hidden. Security
audits are published with their findings, not just their conclusions.

---

<p align="center"><sub>
  Built by <a href="https://github.com/Ishan-Nim">Ishan Nim</a>.
  Not affiliated with Obsidian.
</sub></p>
