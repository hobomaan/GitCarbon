<p align="center">
  <img src="assets/gitcarbon-banner.png" alt="GitCarbon – Deterministic Git Workflow" width="720" />
</p>

<h1 align="center">GitCarbon</h1>

<p align="center">
  <strong>A deterministic Git workflow — built natively into VS Code.</strong><br />
  Plastic-style branch explorer &middot; One-press check-ins &middot; Single source of truth
</p>

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=CPR.gitcarbon-vscode">
    <img src="https://img.shields.io/visual-studio-marketplace/v/CPR.gitcarbon-vscode?label=Marketplace&color=007ACC" alt="VS Marketplace Version" />
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=CPR.gitcarbon-vscode">
    <img src="https://img.shields.io/visual-studio-marketplace/i/CPR.gitcarbon-vscode?label=Installs&color=007ACC" alt="Installs" />
  </a>
  <a href="https://github.com/hobomaan/GitCarbon/issues">
    <img src="https://img.shields.io/github/issues/hobomaan/GitCarbon?label=Issues" alt="Open Issues" />
  </a>
  <a href="LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-green.svg" alt="License: MIT" />
  </a>
</p>

---

## The GitCarbon Philosophy

GitCarbon is built around four principles.

### 1️⃣ One Source of Truth  
Your repository history should reflect what actually happened.  
No ambiguity. No hidden structure.

### 2️⃣ No History Rewriting  
Rebase-heavy workflows introduce structural ambiguity and non-determinism.  
GitCarbon encourages merge-based clarity and preserved lineage.

### 3️⃣ Deterministic Workflows  
The same inputs should produce the same visible structure.  
No silent rewrites. No invisible rebases. No surprises.

### 4️⃣ Simplified Interaction  
Git should not require four commands to perform one action.  
GitCarbon reduces commit → push → pull complexity into intentional, unified operations.

Git is powerful — but by default, it is complex and non-deterministic.  
**GitCarbon makes it visual, simplified, and predictable.**

---

## Why GitCarbon?

Most Git tools give you either a terminal or a cluttered UI that hides what matters.  
GitCarbon brings the clarity of Plastic SCM’s branch explorer into VS Code — while simplifying how you interact with Git itself.

- **See the big picture** — interactive commit graph with colour-coded branch lanes and merge edges.
- **Act in context** — perform operations directly from the graph.
- **Check in with intention** — simplified, unified workflows.
- **Stay deterministic** — history remains consistent and trustworthy.
- **Stay in your editor** — everything lives in the VS Code sidebar.

---

### What Makes GitCarbon Different?

- **True left → right branch layout** — no spaghetti graphs  
- **Merge origin clarity** — always know where a branch came from  
- **One-press check-ins** — reduced multi-step Git flows  
- **Deterministic-first design** — preserved, predictable history  

---

## Core Workflow Simplification

Traditional Git often looks like this:

```
git add
git commit
git push
git pull
resolve conflicts
repeat
```

GitCarbon turns that into structured, visible actions:

- **Check In** — stage, commit, and synchronise in a single intentional action  
- **Update** — controlled pull with visible merge context  
- **Merge from the graph** — drag-to-merge with explicit lineage  

Fewer steps.  
More visibility.  
No hidden state.

---

## Features

### Branch Explorer (Commit Graph)

| Capability | Details |
|---|---|
| Interactive graph | Pan, zoom, colour-coded branch lanes, merge edges |
| Context menus | Checkout, merge, cherry-pick, revert, reset, rename, delete, compare |
| Drag-to-merge | Trigger merges visually from branch to branch |
| Merge origin tracking | Clear visual lineage of branch ancestry |
| MiniMap | Bird's-eye navigation overlay |
| Commit search | Find commits by keyword from the header bar |
| Diff preview | Inline diff viewer for comparing commits |

### Simplified Source Control

| Capability | Details |
|---|---|
| One-press Check In | Stage, commit, and sync in a unified action |
| Pending Changes | Tree view with inline diff and discard options |
| Update (Pull) | Controlled pull from sidebar |
| Conflict resolution | Clear conflict file lists with abort options |

### Shelving (Stash)

| Capability | Details |
|---|---|
| Shelve Changes | Stash working tree (including untracked files) |
| Unshelve / Apply / Drop | Full stash management from sidebar |
| Diff preview | Browse shelved file diffs before applying |

### History & Annotations

| Capability | Details |
|---|---|
| File History | Full commit history for any file with inline diffs |
| Blame Annotations | Toggle line-by-line blame annotations in the editor gutter |

### Pull Requests

| Capability | Details |
|---|---|
| Create PR | Open GitHub / GitLab / Azure DevOps pull request from context menu |

---

## Installation

1. Open VS Code  
2. Press `Ctrl+Shift+X`  
3. Search for **GitCarbon**  
4. Click **Install**

Or:

```
ext install CPR.gitcarbon-vscode
```

**Requirements**

- VS Code **1.60** or later  
- Git installed and available on `PATH`

---

## Quick Start

1. Open a Git repository.  
2. Click the **GitCarbon** icon in the Activity Bar.  
3. Explore your repository structure visually.  
4. Use **Check In** to commit and sync with a single action.

---

## Screenshots

| Branch Explorer | Pending Changes | Shelves |
|---|---|---|
| ![Branch Explorer](assets/screenshot-graph.png) | ![Pending Changes](assets/screenshot-pending.png) | ![Shelves](assets/screenshot-shelves.png) |

---

## Roadmap

- [ ] Commit templates  
- [ ] Timeline view  
- [ ] Pull request review workflow  
- [ ] Team policies for deterministic workflows  
- [ ] Profiles & workspaces  

See `CONTRIBUTING.md` for guidelines.

---

## License

This repository (documentation, issue templates, and assets) is licensed under the **MIT License**.

The GitCarbon VS Code extension itself is distributed under its own license via the VS Code Marketplace.

---

<p align="center">
  History is the source of truth.<br />
  <strong>GitCarbon protects it.</strong><br />
  <em>History should not be rewritten.</em>
</p>
---

<p align="center">
  History is the source of truth.<br />
  <strong>GitCarbon protects it.</strong>
</p>