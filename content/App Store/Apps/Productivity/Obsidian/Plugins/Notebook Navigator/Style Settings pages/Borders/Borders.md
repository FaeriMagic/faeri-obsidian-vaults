---
summary: Border colors and border widths on navigation and file items.
tags:
  - style-settings/style/border
---
> [!important] These settings require the [[App Store/Apps/Productivity/Obsidian/Plugins/Style Settings/Style Settings|Style Settings]] plugin.

← Go back to [[2011]]
# Borders
Border colors and border widths on navigation and file items.
## Navigation borders
### Navigation item border width
Border width on navigation item backgrounds, hover state, and selection.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
>The slider ranges from 0 to 4. Only values set through the slider are accepted; manually editing the JSON file will have no effect.
>
>Requires at least one of the following properties to be set in order to be displayed:
>- [[#Custom background border color]]
>- [[#Hover border color]]
>- [[#Selection border color (navitem )]]
>- [[#Selection border color (inactive) (navitem)]]
> 
> Required for:
> - [[Notebook Navigator - Style Settings (Item border radius)|Item border radius]]
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-navitem-border-width": 0
> ```
> If `⟲` is clicked once, the JSON property is reset to the default value.
> If `⟲` is clicked a second time, the JSON property will be removed from `data.json`.
### Custom background border color
Border color on folders and tags with custom backgrounds.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
>Requires the following property to be set in order to be displayed:
> - [[#Navigation item border width]]
>   
> Required for:
> - [[Notebook Navigator - Style Settings (File count border radius)|File count border radius]]
> - [[Notebook Navigator - Style Settings (Item border radius)|Item border radius]]
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-navitem-custom-border-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-navitem-custom-border-color@@dark": "#" 
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Hover border color (navitem)
Border color on hovered navigation items.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
>Requires the following property to be set in order to be displayed:
> - [[#Navigation item border width]]
>   
> Required for:
> - [[Notebook Navigator - Style Settings (File count border radius)|File count border radius]]
> - [[Notebook Navigator - Style Settings (Item border radius)|Item border radius]]
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-navitem-hover-border-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-navitem-hover-border-color@@dark": "#" 
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Selection border color (navitem)
Border color on selected navigation items.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
>Requires the following property to be set in order to be displayed:
> - [[#Navigation item border width]]
>
> Required for:
> - [[Notebook Navigator - Style Settings (Item border radius)|Item border radius]]
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-navitem-selected-border-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-navitem-selected-border-color@@dark": "#" 
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Selection border color (inactive) (navitem)
Border color on selected navigation items when pane is inactive.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
>Requires the following property to be set in order to be displayed:
> - [[#Navigation item border width]]
>   
> Required for:
> - [[Notebook Navigator - Style Settings (Item border radius)|Item border radius]]  
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-navitem-selected-inactive-border-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-navitem-selected-inactive-border-color@@dark": "#" 
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### File count border width
Border width on navigation file count badges.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
>The slider ranges from 0 to 4. Only values set through the slider are accepted; manually editing the JSON file will have no effect.
>
>Requires at least one of the following properties to be set in order to be displayed:
>- [[#File count border color]]
>- [[#Selected file count border color]]
>- [[#Selected file count border color (inactive)]]
>  
>  Required for:
>- [[Notebook Navigator - Style Settings (File count border radius)|File count border radius]]
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-navitem-count-border-width": 0
> ```
> If `⟲` is clicked once, the JSON property is reset to the default value.
> If `⟲` is clicked a second time, the JSON property will be removed from `data.json`.
### File count border color
Border color on navigation file count badges.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
>Requires the following property to be set in order to be displayed:
> - [[#File count border width]]
>
> Required for:
> - [[Notebook Navigator - Style Settings (File count border radius)|File count border radius]]
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-navitem-count-border-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-navitem-count-border-color@@dark": "#" 
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Selected file count border color
Border color on file count badges when selected.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
>Requires the following property to be set in order to be displayed:
> - [[#File count border width]]
>   
> Required for:
> - [[Notebook Navigator - Style Settings (File count border radius)|File count border radius]]
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-navitem-selected-count-border-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-navitem-selected-count-border-color@@dark": "#" 
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Selected file count border color (inactive)
Border color on file count badges when selected and pane is inactive.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> This style is displayed only while the selection is inactive.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
>Requires the following property to be set in order to be displayed:
> - [[#File count border width]]
>   
>  Required for:
>  - [[Notebook Navigator - Style Settings (File count border radius)|File count border radius]]
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-navitem-selected-inactive-count-border-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-navitem-selected-inactive-count-border-color@@dark": "#" 
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
## File item borders
### Selection border width
Border width on selected file items.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
>
>The slider ranges from 0 to 4. Only values set through the slider are accepted; manually editing the JSON file will have no effect.
>
>Requires at least one of the following properties to be set in order to be displayed:
>- [[#Selection border color (file)]]
>- [[#Selection border color (inactive) (file)]]
>- [[Hover border color (file)]]
>
>Required for:
>- [[File item border radius]]
>
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-file-border-width": 0
> ```
> If `⟲` is clicked once, the JSON property is reset to the default value.
> If `⟲` is clicked a second time, the JSON property will be removed from `data.json`.
### Selection border color (file)
Border color on selected file items.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> This style is displayed only while the selection is active.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
>Requires the following property to be set in order to be displayed:
> - [[#Selection border width]]
> 
> Required for:
> - [[Notebook Navigator - Style Settings (File item border radius)|File item border radius]]
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-file-selected-border-color@@light": "#"
>   "notebook-navigator-style-settings@@nn-theme-file-selected-border-color@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Selection border color (inactive) (file)
Border color on selected file items when pane is inactive.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> This style is displayed only while the selection is inactive.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
>Requires the following property to be set in order to be displayed:
> - [[#Selection border width]]
>   
> Required for:
> - [[Notebook Navigator - Style Settings (File item border radius)|File item border radius]]
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-file-selected-inactive-border-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-file-selected-inactive-border-color@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
## Pill borders
### Pill border width
Border width on tag and custom property pills.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
>The slider ranges from 0 to 4. Only values set through the slider are accepted; manually editing the JSON file will have no effect.
>
> Required for:
>- [[#Tag pill border color]]
>- [[#Custom property pill border color]]
>- [[#Selected tag pill border color]]
>- [[#Selected custom property pill border color]]
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-file-pill-border-width" : 1
> ```
> If `⟲` is clicked once, the JSON property is reset to the default value.
> If `⟲` is clicked a second time, the JSON property will be removed from `data.json`.
### Tag pill border color
Border color on tag pills without custom colors.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
>Requires the following property to be set in order to be displayed:
> - [[#Pill border width]]
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-file-tag-border-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-file-tag-border-color@@dark": "#" 
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Custom property pill border color
Border color on custom property pills without custom colors.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
>Requires the following property to be set in order to be displayed:
> - [[#Pill border width]]
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-file-property-border-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-file-property-border-color@@dark": "#" 
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Selected tag pill border color
Border color on tag pills without custom colors in selected files.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
>Requires the following property to be set in order to be displayed:
> - [[#Pill border width]]
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-file-selected-tag-border-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-file-selected-tag-border-color@@dark": "#" 
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Selected custom property pill border color
Border color on custom property pills without custom colors in selected files.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
>Requires the following property to be set in order to be displayed:
> - [[#Pill border width]]
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-file-selected-property-border-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-file-selected-property-border-color@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
