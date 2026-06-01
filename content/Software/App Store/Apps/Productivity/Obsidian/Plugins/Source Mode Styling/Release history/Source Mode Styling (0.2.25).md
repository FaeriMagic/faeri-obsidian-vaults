---
created: 2026-01-12T06:19:19Z
icon: tag
tags:
  - plugins/obsidian/_release
---
[\[Github\]](https://github.com/chrishoward-projects/sourcemode-styling/releases/tag/0.2.25) · [\[Wayback\]](http://web.archive.org/web/20260420125602/https://github.com/chrishoward-projects/sourcemode-styling/releases/tag/0.2.25)

0.2.25 (2026-01-12)

Enhanced Style Preview
- Added dedicated StylePreview component at bottom of settings
- Preview now shows heading (always bold) + paragraph with comprehensive sample text
- Real-time updates when any setting changes
- Applies all 7 styling settings dynamically (font family, size, weight, colour, heading colour, background colour, line height)
- Relocated from inline position in FontFamilySetting to dedicated component at bottom

<p>0.2.24 (2026-01-07)</p>

Performance & Font Detection Improvements
- Font detection caching system eliminates 2-3 second delay (now <10ms when cached)
- Lazy, non-blocking async font detection in chunks (first load: 500-1000ms)
- Added font preview sample with real-time visual feedback
- Added [[Source Mode Styling - Settings#Monospace font|"Refresh Fonts" button]] for manual re-detection
- Hash-based cache validation auto-invalidates when font list changes
- Loading state shown while detecting fonts
- Fixed CSS class name typo (.source-mode-source-mode-settings-input-hidden)

<p>0.2.23 (2026-01-04)</p>

Debug System & Code Quality
- Comprehensive debug logging system for troubleshooting styling issues
- Debug mode logs view state detection, class application, CSS variables, and computed styles
- TypeScript improvements: removed redundant type unions, simplified types
- Fixed Promise return warnings in event handlers
- Removed unnecessary type assertions