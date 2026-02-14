# Changelog

All notable changes to **GitCarbon – Visual Branch Explorer** will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [0.1.0] — 2025-02-09

### Added

#### Branch Explorer
- Interactive commit graph with pan, zoom, colour-coded branch lanes, and merge edges
- Context menus on commits, branches, segments, and edges — checkout, merge, cherry-pick, revert, reset, rename, delete, compare
- Tag management — create and delete tags from the graph
- Branch hiding — declutter the graph; unhide via context menu or settings
- Commit search — find commits by keyword from the header bar or Command Palette
- MiniMap — bird's-eye navigation overlay
- Drag-to-merge — drag one branch onto another to trigger a merge
- Diff preview — inline diff viewer for comparing commits
- Light and Dark theme support — follows VS Code theme or manual override
- Settings page — theme, diagnostics, MiniMap, detail pane, node size, hidden branches
- Toast notifications — success/error feedback in the webview
- No-repo empty state — friendly message when no Git repo is found

#### Source Control
- Pending Changes sidebar — tree view with inline diff, open file, discard single file, discard all
- Check In view — sidebar webview for committing with a message
- Update command — pull latest changes from the sidebar
- Confirmation dialogs for destructive operations

#### Shelving
- Shelve Changes — stash working tree including untracked files
- Shelves sidebar — browse, apply, pop, and drop stashes
- Shelved file diff preview — browse diffs before applying

#### History & Annotations
- File History — full commit log for any file with inline diffs
- Blame Annotations — toggle line-by-line blame in the editor gutter

#### Pull Requests
- Create PR — open a GitHub / GitLab / Azure DevOps pull request from the context menu

#### Multi-Repo
- Auto-discover Git repos in workspace subfolders
- Repositories sidebar with switch-repo support

#### Info Pages
- About, FAQ, and Feature Comparison webview pages
- PDF export for the Feature Comparison table

---

[0.1.0]: https://marketplace.visualstudio.com/items?itemName=CPR.gitcarbon-vscode
