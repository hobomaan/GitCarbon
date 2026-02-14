<p align="center">
  <img src="assets/gitcarbon-banner.png" alt="GitCarbon – Visual Branch Explorer" width="720" />
</p>

<h1 align="center">GitCarbon – Visual Branch Explorer</h1>

<p align="center">
  <strong>A visual Git client built into VS Code — inspired by Plastic SCM.</strong><br />
  Interactive commit graph &middot; Pending changes sidebar &middot; Shelving &middot; One-click merge & cherry-pick
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

## Why GitCarbon?

Most Git tools give you either a terminal or a cluttered UI that hides what matters.  
**GitCarbon** brings the clarity of **Plastic SCM's branch explorer** into VS Code — so you can *see* your repository, not just manage it.

- **See the big picture** — an interactive commit graph with colour-coded branch lanes, merge edges, and zoom/pan.
- **Act in context** — right-click any commit, branch, or tag for the exact operations you need.
- **Stay in your editor** — no window-switching; everything lives in the VS Code sidebar.

---

## Features

### Branch Explorer (Commit Graph)

| Capability | Details |
|---|---|
| Interactive graph | Pan, zoom, colour-coded branch lanes, merge edges |
| Context menus | Checkout, merge, cherry-pick, revert, reset, rename, delete, compare |
| Tag management | Create / delete tags from any commit node |
| Branch hiding | Declutter the graph — hide and unhide branches |
| Commit search | Find commits by keyword from the header bar |
| MiniMap | Bird's-eye navigation overlay |
| Drag-to-merge | Drag one branch onto another to trigger a merge |
| Diff preview | Inline diff viewer for comparing commits |

### Source Control

| Capability | Details |
|---|---|
| Pending Changes | Tree view with inline diff, open file, discard single / discard all |
| Check In view | Sidebar webview for committing with a message |
| Conflict resolution | Detailed conflict file lists with abort options for merge / cherry-pick / revert |
| Update (Pull) | One-click pull from the sidebar |

### Shelving (Stash)

| Capability | Details |
|---|---|
| Shelve Changes | Stash working tree (including untracked files) |
| Unshelve / Apply / Drop | Full stash management from the Shelves sidebar |
| Diff preview | Browse shelved file diffs before applying |

### History & Annotations

| Capability | Details |
|---|---|
| File History | Full commit history for any file with inline diffs |
| Blame Annotations | Toggle line-by-line blame annotations in the editor gutter |

### Pull Requests

| Capability | Details |
|---|---|
| Create PR | Open a GitHub / GitLab / Azure DevOps pull request from the context menu |

### Additional

- **Multi-repo support** — auto-discovers Git repos in workspace subfolders
- **Light & Dark themes** — follows VS Code theme or manual override
- **Settings page** — theme, diagnostics, MiniMap, detail pane, node size, hidden branches
- **Toast notifications** — success/error feedback in the webview
- **No-repo empty state** — friendly welcome message when no Git repo is found

> **How does GitCarbon compare?** See the full [Feature Comparison (PDF)](assets/GitCarbon%20—%20Feature%20Comparison.pdf) covering GitCarbon, GitLens, Git Graph, GitHub Desktop, and Plastic SCM.

---

## Installation

**From the Marketplace (recommended)**

1. Open VS Code
2. Press `Ctrl+Shift+X` to open Extensions
3. Search for **GitCarbon**
4. Click **Install**

Or install directly:

```
ext install CPR.gitcarbon-vscode
```

**Requirements**

- VS Code **1.60** or later
- Git installed and available on `PATH`

---

## Quick Start

1. Open a folder containing a Git repository.
2. The **GitCarbon** icon appears in the Activity Bar (sidebar).
3. Click it to open the **Branch Explorer** — your interactive commit graph.
4. Use the **Pending Changes** view below to stage, diff, and commit.

---

## Screenshots

> *Screenshots will be added here. Place images in the `assets/` folder.*

| Branch Explorer | Pending Changes | Shelves |
|---|---|---|
| ![Branch Explorer](assets/screenshot-graph.png) | ![Pending Changes](assets/screenshot-pending.png) | ![Shelves](assets/screenshot-shelves.png) |

---

## Commands

All commands are available from the Command Palette (`Ctrl+Shift+P`):

| Command | Description |
|---|---|
| `GitCarbon: Open Branch Explorer` | Open the commit graph |
| `GitCarbon: Check In` | Commit staged/pending changes |
| `GitCarbon: Update` | Pull latest changes |
| `GitCarbon: Shelve Changes` | Stash working tree |
| `GitCarbon: Unshelve Changes` | Pop the latest stash |
| `GitCarbon: Show File History` | View commit log for current file |
| `GitCarbon: Toggle Blame Annotations` | Toggle inline blame in editor |
| `GitCarbon: Discard All Changes` | Revert all pending changes |

---

## Settings

| Setting | Default | Description |
|---|---|---|
| `gitcarbon.themeOverride` | `auto` | Force `light` or `dark` theme for the graph |
| `gitcarbon.showMiniMap` | `true` | Show the MiniMap overlay |
| `gitcarbon.showDetailPane` | `true` | Show the commit detail pane |
| `gitcarbon.nodeSize` | `normal` | Graph node size (`small` / `normal` / `large`) |
| `gitcarbon.hiddenBranches` | `[]` | Branches to hide from the graph |
| `gitcarbon.showDiagnostics` | `false` | Show diagnostic overlay |

---

## Roadmap

We're actively developing GitCarbon. Planned features include:

- [ ] Commit templates
- [ ] Timeline view (VS Code native timeline API)
- [ ] Pull request list & review
- [ ] PR inline comments
- [ ] Issues integration
- [ ] Custom script hooks
- [ ] Profiles & workspaces
- [ ] Tabbed / multi-panel layouts

Have an idea? [Open a feature request →](https://github.com/hobomaan/GitCarbon/issues/new?template=feature_request.md)

---

## Contributing

GitCarbon is currently **closed-source**. This repository exists for:

- **Bug reports** — [report a bug](https://github.com/hobomaan/GitCarbon/issues/new?template=bug_report.md)
- **Feature requests** — [request a feature](https://github.com/hobomaan/GitCarbon/issues/new?template=feature_request.md)
- **Discussions** — share ideas, ask questions, and connect with other users

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## License

This repository (documentation, issue templates, and assets) is licensed under the [MIT License](LICENSE).

The GitCarbon VS Code extension itself is distributed under its own license via the [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=CPR.gitcarbon-vscode).

---

<p align="center">
  Built with care for developers who believe <strong>history should not be rewritten</strong>.
</p>
