---
created: 2025-06-21T12:29:15Z
last checked: 2026-06-01T00:00:00
last updated: 2026-01-25T06:41:11Z
author: "[[Howard, Chris|Chris Howard]]"
icon: x
obsidian stats plugin category: Customization & UI
platforms:
  - "[[Github]]"
  - "[[Obsidian|Obsidian Community]]"
programming languages:
  - "[[TypeScript]]"
  - "[[JavaScript]]"
  - "[[Shell programs|Shell]]"
status: Not installed
version: 0.2.31
tags:
  - plugins/obsidian/markdown
  - plugins/obsidian-stats/editor
  - plugins/obsidian-stats/font
  - plugins/obsidian-stats/source-mode
  - plugins/obsidian-stats/styling
---
> Provides a customizable raw look in source mode using a monospace font to clearly differentiate from Live Preview.

| [Obsidian Community](https://community.obsidian.md/plugins/sourcemode-styling) | [Obsidian Stats](https://www.obsidianstats.com/plugins/sourcemode-styling) |
| :----------------------------------------------------------------------------: | :------------------------------------------------------------------------: |
The Source Mode Styling plugin transforms source mode into a genuine raw text editor with monospace fonts and customizable styling options. It creates clear visual separation from Live Preview by applying developer friendly aesthetics. The plugin automatically detects monospace fonts installed on your system (Source Code Pro, Fira Code, JetBrains Mono, etc.) and lets you control font weight, size, color, line height and background.

> [!abstract] [Github](https://github.com/chrishoward-projects/sourcemode-styling)
> > [!info]- README
> > - [[Source Mode Styling - Github README#Overview|Overview]]
> > - [[Source Mode Styling - Github README#Installation|Installation]]
> >	- [[Source Mode Styling - Github README#From Community Plugins (Recommended)|From Community Plugins (Recommended)]]
> >	- [[Source Mode Styling - Github README#Manual Installation|Manual Installation]]
> > - [[Source Mode Styling - Github README#Usage|Usage]]
> >	- [[Source Mode Styling - Github README#Quick Start|Quick Start]]
> >	- [[Source Mode Styling - Github README#Configuration Options|Configuration Options]]
> >	- [[Source Mode Styling - Github README#Font Detection|Font Detection]]
> > - [[Source Mode Styling - Github README#Examples|Examples]]
> > 	- [[Source Mode Styling - Github README#Before vs After|Before vs After]]
> > - [[Source Mode Styling - Github README#Advanced Usage|Advanced Usage]]
> > 	- [[Source Mode Styling - Github README#Theme Integration|Theme Integration]]
> > 	- [[Source Mode Styling - Github README#CSS Customization|CSS Customization]]
> > - [[Source Mode Styling - Github README#Compatibility|Compatibility]]
> > - [[Source Mode Styling - Github README#Troubleshooting|Troubleshooting]]
> > 	- [[Source Mode Styling - Github README#Font Not Appearing?|Font Not Appearing?]]
> > 	- [[Source Mode Styling - Github README#Settings Not Applying?|Settings Not Applying?]]
> > 	- [[Source Mode Styling - Github README#Mobile Issues?|Mobile Issues?]]
> > - [[Source Mode Styling - Github README#Contributing|Contributing]]
> > 	- [[Source Mode Styling - Github README#Development Setup|Development Setup]]
> > - [[Source Mode Styling - Github README#Changelog|Changelog]]
> > - [[Source Mode Styling - Github README#Requirements|Requirements]]
> > - [[Source Mode Styling - Github README#License|License]]
> 
> > [!info]- [[App Store/Apps/Productivity/Obsidian/Plugins/Source Mode Styling/Release history/Release history.canvas|Release history]]
> > ### 2025
> > | Date   | Release                                                 | Commit message                        |
> > | ------ | ------------------------------------------ | ---------------------------------------------------------------- |
> > | Jun 21 | [[Source Mode Styling (0.2.10)\|0.2.10]]   | fix release script not including styles                        |  
> > | Jun 22 | [[Source Mode Styling (0.2.13)\|0.2.13]]   | fix casting to any v.0.2.13<br><br>- Order of font weights in settings dropdown<br>- Fix missed obsidian-mode-raw rename<br>- Fix casting to any as requested by Obsidian validator             |
> > | Jul 14 | [[Source Mode Styling (0.2.14)\|0.2.14]]   | fix in code styling                                            |
> > | Aug 17 | [[Source Mode Styling (0.2.16)\|0.2.16]]   | fix manifest version                                            |
> > | Aug 18 | [[Source Mode Styling (0.2.18)\|0.2.18]]   | Fix version management issues<br><br>- Update manifest.json to correct version 0.2.18<br>- Remove duplicate and empty 0.2.16 changelog entries<br>- Ensure version consistency across all files<br><br>🤖 Generated with [Claude Code]([https://claude.ai/code](https://claude.ai/code))<br><br>Co-Authored-By: Claude <noreply@anthropic.com> |
> > | Nov 12 | [[Source Mode Styling (v0.2.21)\|v0.2.21]] | Fix event registration to comply with Obsidian guidelines<br><br>- Wrap all workspace event handlers in plugin.registerEvent()<br>- Remove manual event cleanup code (Obsidian handles this automatically)<br>- Update StylingManager to accept Plugin instance for proper event registration<br>- Fix memory leak potential from unregistered event handlers<br><br>Generated with [Claude Code]([https://claude.com/claude-code](https://claude.com/claude-code))<br><br>Co-Authored-By: Claude <noreply@anthropic.com>                    |
> > | Nov 12 | [[Source Mode Styling (v0.2.22)\|v0.2.22]] | Remove Enable Source Mode Styling setting references from documentation<br><br>- Remove setting from Quick Start instructions<br>- Remove setting from Configuration Options table<br>- Setting was already removed from the plugin code<br><br>Generated with [Claude Code]([https://claude.com/claude-code](https://claude.com/claude-code))<br><br>Co-Authored-By: Claude <noreply@anthropic.com>                    |
> > ### 2026
> > | Date   | Release                                             | Commit message                        |
> > | ------ | --------------------------------------- | ------------------------------------- |
> > | Jan 12 | [[Source Mode Styling (0.2.25)\|0.2.25]] | Bump version to 0.2.25<br><br>Co-Authored-By: Claude Sonnet 4.5 <noreply@anthropic.com>                                        |
> > | Jan 12 | [[Source Mode Styling (0.2.26)\|0.2.26]] | Fix styling persistence with per-editor architecture<br>Fixed critical bug where plugin styling would disappear when clicking side panels or incorrectly apply to all visible notes.<br><br>Changes:<br>- Architectural shift from container-based to per-editor styling<br>- CSS class now applied directly to individual .markdown-source-view.mod-cm6 elements<br>- Each editor evaluated independently based on its own source mode state<br>- CSS selector changed from descendant (.source-mode-raw .markdown-source-view) to direct class (.markdown-source-view.mod-cm6.source-mode-raw)<br>- Rewrote updateViewModeClass() to iterate through all markdown leaves and apply styling per-editor<br>- Added Setting import for debug mode toggle<br>- Removed unused WorkspaceLeaf import and isInSourceMode() method<br><br>Fixes:<br>- Styling now persists when clicking side panels<br>- Split panes with different modes each styled correctly<br>- No global styling applied when one note is in source mode<br><br>Co-Authored-By: Claude Sonnet 4.5 <noreply@anthropic.com>                                          |
> > | Jan 18 | [[Source Mode Styling (0.2.27)\|0.2.27]] | Obsidian compliance fixes<br><br>- Change console.log to console.debug<br>- Fix settings not using sentence case<br>- Fix styles being set directly, not by CSS                     |
> > | Jan 19 | [[Source Mode Styling (0.2.28)\|0.2.28]] | bump version 0.2.28                                   |
> > | Jan 25 | [[Source Mode Styling (0.2.30)\|0.2.30]] | chore: bump version to 0.2.30<br><br>Obsidian compliance improvements:<br>- Security: replace innerHTML with safe empty() method<br>- Memory: add hide() method for proper event cleanup<br>- Style: remove broad CSS selector overriding core styles<br>- Refactor: use Obsidian DOM helpers and CSS variables<br>- A11y: add aria-label and tooltip position to button<br><br>Co-Authored-By: Claude Opus 4.5 <noreply@anthropic.com>                              |
> > | Jan 25 | [[Source Mode Styling (0.2.31)\|0.2.31]] | bump version to fix release mismatch                     |

> [!abstract] Plugin
> > [!info]- Settings
> > - [[Source Mode Styling - Settings#Monospace font|Monospace font]]
> > - [[Source Mode Styling - Settings#Font weight|Font weight]]
> > - [[Source Mode Styling - Settings#Font size|Font size]]
> > - [[Source Mode Styling - Settings#Font color|Font color]]
> > - [[Source Mode Styling - Settings#Line height|Line height]]
> > - [[Source Mode Styling - Settings#Heading color|Heading color]]
> > - [[Source Mode Styling - Settings#Background color|Background color]]

