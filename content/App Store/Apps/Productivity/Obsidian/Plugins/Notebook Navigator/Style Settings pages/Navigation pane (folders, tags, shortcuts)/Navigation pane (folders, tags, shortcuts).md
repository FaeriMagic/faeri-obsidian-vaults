---
summary: Customize the background and items within the navigation pane.
tags:
  - style-settings/element/navigation-pane
---
> [!important] These settings require the [[App Store/Apps/Productivity/Obsidian/Plugins/Style Settings/Style Settings|Style Settings]] plugin.

← Go back to [[2011]]
# Navigation pane (folders, tags, shortcuts)
Customize the background and items within the navigation pane.
### Navigation pane background
Background color of the navigation pane (desktop only).

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-nav-bg@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-nav-bg@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Navigation separator color
Line color for separators rendered inside navigation spacers.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-nav-separator-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-nav-separator-color@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
## Folder & tag items
### Expand/collapse arrow color
Color for expand/collapse arrows.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-chevron-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-chevron-color@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Icon color (nav)
Icon color for folders and tags.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-icon-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-icon-color@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Text color
Text color for folder and tag names.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-name-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-name-color@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### File text color
Text color for note shortcuts and recent files. Defaults to folder/tag text color.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-file-name-color@@light": "#"
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-file-name-color@@dark": "#" 
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### File count text color
Text color for file count badges.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-count-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-count-color@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### File count background
Background color for file count badges.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> Required for:
> - [[#File count border radius]]
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-count-bg@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-count-bg@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### File count border radius
Corner radius for file count badges.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> The slider ranges from 0 to 8. Only values set through the slider are accepted; manually editing the JSON file will have no effect.
> 
> Requires at least one of the following properties to be set in order to be displayed:
> - [[#File count background]]
> - [[Notebook Navigator - Style Settings (File count border width)|File count border width]] and at least one of the following properties:
> 	 - [[Notebook Navigator - Style Settings (File count border color)|File count border color]]
> 	 - [[Notebook Navigator - Style Settings (Selected file count border color)|Selected file count border color]]
> 	 - [[Notebook Navigator - Style Settings (Selected file count border color (inactive))|Selected file count border color (inactive)]]
> - [[#Hover background (navitem)]]
> - [[#Selection background]]
> - [[#Selection background (inactive)]]
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-count-border-radius@@light": 8,
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-count-border-radius@@dark": 8
> ```
> If `⟲` is clicked once, the JSON property is reset to the default value.
> If `⟲` is clicked a second time, the JSON property will be removed from `data.json`.
### Item border radius
Corner radius for folder and tag items.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> The slider ranges from 0 to 14. Only values set through the slider are accepted; manually editing the JSON file will have no effect.
> 
> Requires at least one of the following properties to be set in order to be displayed:
> - [[Notebook Navigator - Style Settings (Navigation item border width)|Navigation item border width]] and at least one of the following properties:
> 	 - [[Notebook Navigator - Style Settings (Custom background border color)|Custom background border color]]
> 	 - [[Notebook Navigator - Style Settings (Hover border color)|Hover border color (navitem)]]
> 	 - [[Notebook Navigator - Style Settings (Selection border color (navitem))|Selection border color (navitem)]]
> 	 - [[Notebook Navigator - Style Settings (Selection border color (inactive) (navitem))|Selection border color (inactive) (navitem)]]
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-border-radius@@light": 8,
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-border-radius@@dark": 8
> ```
> If `⟲` is clicked once, the JSON property is reset to the default value.
> If `⟲` is clicked a second time, the JSON property will be removed from `data.json`.
### Hover background (navitem)
Item hover background color.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> Required for:
> - [[#File count border radius]]
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-hover-bg@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-hover-bg@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Selection background (navitem)
Selected item background color.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> This style is displayed only while the selection is active.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> Required for:
> - [[#File count border radius]]
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-selected-bg@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-selected-bg@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Selected chevron color
Expand/collapse arrow color when item is selected.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> This style is displayed only while the selection is active.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-selected-chevron-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-selected-chevron-color@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Selected icon color
Icon color when item is selected.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
>
> This style is displayed only while the selection is active.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-selected-icon-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-selected-icon-color@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Selected name color
Folder/tag name color when selected.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> This style is displayed only while the selection is active.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-selected-name-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-selected-name-color@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Selected count text color
File count text color when item is selected.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> This style is displayed only while the selection is active.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-selected-count-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-selected-count-color@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Selected count background
File count background color when selected.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> This style is displayed only while the selection is active.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-selected-count-bg@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-selected-count-bg@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Selected chevron color (inactive)
Expand/collapse arrow color when item is selected and pane is inactive.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> This style is displayed only while the selection is inactive.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-selected-inactive-chevron-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-selected-inactive-chevron-color@@dark": "#" 
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Selected icon color (inactive)
Icon color when item is selected and pane is inactive.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> This style is displayed only while the selection is inactive.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-selected-inactive-icon-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-selected-inactive-icon-color@@dark": "#" 
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Selected count text color (inactive)
File count text color when item is selected and pane is inactive.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> This style is displayed only while the selection is inactive.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-selected-inactive-count-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-selected-inactive-count-color@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Selected count background (inactive)
File count background color when item is selected and pane is inactive.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> This style is displayed only while the selection is inactive.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-selected-inactive-count-bg@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-selected-inactive-count-bg@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Selection background (inactive) (navitem)
Selected item background color when pane is inactive.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> This style is displayed only while the selection is inactive.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> Required for:
> - [[#File count border radius]]
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-selected-inactive-bg@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-selected-inactive-bg@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Selected name color (inactive)
Folder/tag name color when selected and pane is inactive.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> This style is displayed only while the selection is inactive.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-selected-inactive-name-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-nav-navitem-selected-inactive-name-color@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Tag highlight (include)
Background color for positive tag highlights and tag drop targets.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-tag-positive-bg@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-tag-positive-bg@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Tag highlight (exclude)
Background color for negative tag highlights and the untagged drop target.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-tag-negative-bg@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-tag-negative-bg@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
## Text styling
### Default file name weight
Default font weight for file names in shortcuts and recent notes.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> The slider ranges from 100 to 900. Only values set through the slider are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-navitem-file-name-font-weight": 400
> ```
> If `⟲` is clicked once, the JSON property is reset to the default value.
> If `⟲` is clicked a second time, the JSON property will be removed from `data.json`.
### Default folder/tag weight
Default font weight for folder and tag names.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> The slider ranges from 100 to 900. Only values set through the slider are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-navitem-name-font-weight": 400
> ```
> If `⟲` is clicked once, the JSON property is reset to the default value.
> If `⟲` is clicked a second time, the JSON property will be removed from `data.json`.
### File count font weight
Font weight for file count badges.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> The slider ranges from 100 to 900. Only values set through the slider are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-navitem-count-font-weight": 400
> ```
> If `⟲` is clicked once, the JSON property is reset to the default value.
> If `⟲` is clicked a second time, the JSON property will be removed from `data.json`.
### Custom color file name weight
Font weight for file names with custom colors (overrides default file weight).

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> The slider ranges from 100 to 900. Only values set through the slider are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-navitem-custom-color-file-name-font-weight": 600
> ```
> If `⟲` is clicked once, the JSON property is reset to the default value.
> If `⟲` is clicked a second time, the JSON property will be removed from `data.json`.

> [!bug] 
> Does not work.
### Custom color folder/tag weight
Font weight for folders and tags with custom colors (overrides default folder/tag weight).

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> The slider ranges from 100 to 900. Only values set through the slider are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-navitem-custom-color-name-font-weight": 600
> ```
> If `⟲` is clicked once, the JSON property is reset to the default value.
> If `⟲` is clicked a second time, the JSON property will be removed from `data.json`.
### Folder note weight
Font weight for folders with notes (overrides all others).

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> The slider ranges from 100 to 900. Only values set through the slider are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-navitem-folder-note-name-font-weight": 400
> ```
> If `⟲` is clicked once, the JSON property is reset to the default value.
> If `⟲` is clicked a second time, the JSON property will be removed from `data.json`.
### Folder note decoration
Text decoration for folders with notes.
- None (*"none"*)
- Underline (*"underline"*)
- Dotted underline (*"underline dotted"*)

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the dropdown are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-navitem-folder-note-name-decoration": "underline"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Folder note hover decoration
Text decoration when hovering folders with notes.
- None (*"none"*)
- Underline (*"underline"*)
- Dotted underline (*"underline dotted"*)

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the dropdown are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-navitem-folder-note-name-hover-decoration": "underline"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
## Pinned shortcuts
### Pinned shortcut shadow color
Gradient overlay color rendered beneath pinned shortcuts.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-pinned-shortcut-shadow-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-pinned-shortcut-shadow-color@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.