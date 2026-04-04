---
title: Selection border width
aliases:
  - Selection border width
summary: Border width on selected file items.
tags:
  - style-settings/element/list-pane/files
  - style-settings/status/active
  - style-settings/style/border/width
---
← Go back to [[Borders#Selection border width|Notebook Navigator/Style Settings/Borders]]
## Selection border width
Border width on selected file items.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
>
>The slider ranges from 0 to 4. Only values set through the slider are accepted; manually editing the JSON file will have no effect.
>
>Requires at least one of the following properties to be set in order to be displayed:
>- [[Notebook Navigator - Style Settings (Selection border color (file))|Selection border color (file)]]
>- [[Notebook Navigator - Style Settings (Selection border color (inactive) (file))|Selection border color (inactive) (file)]]
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