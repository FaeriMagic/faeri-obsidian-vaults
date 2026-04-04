---
title: Custom color file name weight
aliases:
  - Custom color file name weight
summary: Font weight for file names with custom colors (overrides default file weight).
tags:
  - bugs
  - style-settings/element/list-pane/files
  - style-settings/style/font/font-weight
---
← Go back to [[Navigation pane (folders, tags, shortcuts)#Custom color file name weight|Notebook Navigator/Style Settings/Navigation pane (folders, tags, shortcuts)]]
## Custom color file name weight
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
## See also
- [[Notebook Navigator - Style Settings (Custom color folder-tag weight)|Custom color folder/tag weight]]