---
title: File count border width
aliases:
  - File count border width
summary: Border width on navigation file count badges.
tags:
  - style-settings/element/navigation-pane/file-count
  - style-settings/style/border/width
---
← Go back to [[Borders#File count border width|Notebook Navigator/Style Settings/Borders]]
## File count border width
Border width on navigation file count badges.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
>The slider ranges from 0 to 4. Only values set through the slider are accepted; manually editing the JSON file will have no effect.
>
>Requires at least one of the following properties to be set in order to be displayed:
>- [[Notebook Navigator - Style Settings (File count border color)|File count border color]]
>- [[Notebook Navigator - Style Settings (Selected file count border color)|Selected file count border color]]
>- [[Notebook Navigator - Style Settings (Selected file count border color (inactive))|Selected file count border color (inactive)]]
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