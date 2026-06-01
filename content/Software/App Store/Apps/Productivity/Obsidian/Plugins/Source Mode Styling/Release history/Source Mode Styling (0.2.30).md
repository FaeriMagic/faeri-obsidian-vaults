---
created: 2026-01-25T06:30:27Z
icon: tag
tags:
  - plugins/obsidian/_release
---
[\[Github\]](https://github.com/chrishoward-projects/sourcemode-styling/releases/tag/0.2.30) · [\[Wayback\]](http://web.archive.org/web/20260420120815/https://github.com/chrishoward-projects/sourcemode-styling/releases/tag/0.2.30)
## [0.2.30]
### Fixed
- Replace innerHTML with safe empty() method to prevent potential XSS vulnerabilities
- Add hide() method to settings tab for proper event cleanup when tab is closed or plugin disabled
- Remove broad CSS selector that was overriding Obsidian core button styles
### Changed
- Use Obsidian DOM helpers (createEl, createDiv) instead of document.createElement for consistency
- Use Obsidian CSS variables for spacing and border-radius in settings UI
### Added
- Add aria-label and data-tooltip-position to refresh button for accessibility
## [0.2.29]
### Changed
- Upgraded ESLint to v9 with flat config format (eslint.config.mjs)
- Upgraded TypeScript to v5.x
- Added eslint-plugin-obsidianmd for Obsidian-specific linting rules
- Replaced @typescript-eslint/parser and @typescript-eslint/eslint-plugin with unified typescript-eslint package
- Removed deprecated .eslintrc, .eslintrc.json, and .eslintignore files