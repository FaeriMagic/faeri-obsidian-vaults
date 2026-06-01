---
created: 2026-01-12T11:58:53Z
icon: tag
tags:
  - plugins/obsidian/_release
---
[\[Github\]](https://github.com/chrishoward-projects/sourcemode-styling/releases/tag/0.2.26) · [\[Wayback\]](http://web.archive.org/web/20260420123509/https://github.com/chrishoward-projects/sourcemode-styling/releases/tag/0.2.26)
## [0.2.26] - 2026-01-12
### Fixed
- Fixed styling persistence bug where plugin styling would revert to Obsidian's default when clicking side panels (file explorer, search, etc.)
- Fixed issue where styling was incorrectly applied to all visible notes regardless of their mode
- Changed architecture from global container-based styling to per-editor styling
- Each editor now has styling applied individually based on its own source mode state
- Properly supports split panes and multiple notes with different modes simultaneously
- CSS selector changed from `.source-mode-raw .markdown-source-view.mod-cm6` to `.markdown-source-view.mod-cm6.source-mode-raw` for per-editor targeting