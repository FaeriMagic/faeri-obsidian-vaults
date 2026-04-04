---
title: Item border radius
aliases:
  - Item border radius
summary: Corner radius for folder and tag items.
tags:
  - style-settings/element/navigation-pane/folders
  - style-settings/element/navigation-pane/tags
  - style-settings/mode/dark
  - style-settings/mode/light
  - style-settings/style/border/radius
---
← Go back to [[Navigation pane (folders, tags, shortcuts)#Item border radius|Notebook Navigator/Style Settings/Navigation pane (folders, tags, shortcuts)]]
## Item border radius
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