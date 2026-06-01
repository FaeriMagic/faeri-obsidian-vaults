---
created: 2025-11-12T11:37:24Z
icon: tag
tags:
  - plugins/obsidian/_release
---
[\[Github\]](https://github.com/chrishoward-projects/sourcemode-styling/releases/tag/0.2.21) · [\[Wayback\]](http://web.archive.org/web/20260420133831/https://github.com/chrishoward-projects/sourcemode-styling/releases/tag/0.2.21)
## [0.2.21] - 2025-11-12
### Fixed
- Event handlers now properly registered using plugin.registerEvent() for correct lifecycle management
- Removed manual event cleanup code as Obsidian handles this automatically with registerEvent()
- All workspace events (active-leaf-change, layout-change, file-open) now comply with Obsidian event guidelines
- Fixed memory leak potential from unregistered event handlers
## [0.2.20] - 2025-11-12
### Changed
- Refactored styling system to use CSS custom properties instead of dynamic style elements
- Font detection now uses CSS variables instead of creating temporary style elements
- StyleInjector rewritten to manage CSS variables via setProperty/removeProperty
- CSSGenerator now returns CSS variable values instead of generating CSS strings
- Improved Obsidian submission compliance by eliminating all dynamic style element creation
## [0.2.19] - 2025-11-12
## Changed
- Added MIT licence
- rename CSS style settings-input-hidden to source-mode-settings-input-hidden to mitigate conflicate with other plugins
- remove enable Source Mode Styling setting
- update minAppVersion to 1.9.14