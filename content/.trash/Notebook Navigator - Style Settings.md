---
color:
background:
title: Notebook Navigator/Style Settings
summary: Style Settings for Notebook Navigator.
created:
modified:
tags:
  - documentation/style-settings
---
> [!important] These settings require the [[App Store/Apps/Productivity/Obsidian/Plugins/Style Settings/Style Settings|Style Settings]] plugin.

← Go back to [[Notebook Navigator]]
# Borders
Border colors and border widths on navigation and file items.
## File item borders
##### Hover border color (file)
Border color on hovered file names.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
>Requires the following property to be set in order to be displayed:
> - [[#File item border width]]
> 
> Required for:
> - [[#File item border radius]]
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-file-hover-border-color@@light" : "#"
>   "notebook-navigator-style-settings@@nn-theme-file-hover-border-color@@dark" : "#" 
> ```
> If reset, the JSON property will be removed from the file.
