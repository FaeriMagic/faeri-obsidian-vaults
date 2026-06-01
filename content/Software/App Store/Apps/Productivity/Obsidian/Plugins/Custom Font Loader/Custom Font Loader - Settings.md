---
tags:
  - documentation/settings
---
In Order <span style="color: gray;">[sic]</span> to set the font, copy your font into fonts directory that you set
#### Fonts Folder
Folder to look for your custom fonts
> [!info] In [[Custom Font Loader - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "font_folder": ".obsidian/fonts/"
> ```
#### Reload fonts from folder
This button reloades <span style="color: gray;">[sic]</span> from the folder you specified (it also creates the folder for you)
#### Font
Choose font (if you can't see your fonts, make sure your fonts are in the folder you specified and hit reload. Also if you choose multiple fonts, we will load and process all fonts in the folder for you. In that Case, enable Custom CSS Mode)
- None (*"none"*)
- Multiple fonts (*"all"*)

> [!info] In [[Custom Font Loader - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "font": "None"
> ```
#### Force Style
**Only appears if `"font"` is NOT SET to `"None"` or `"none"`.**
This option should only be used if you have installed a community theme and normal mode doesn't work
> [!info] In [[Custom Font Loader - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "force_mode": false
> ```
#### Custom CSS Mode
**Only appears if `font` is NOT SET to `"None"` or `"none"`.**
If you want to apply a custom css style rather than a default style, choose this.
> [!info] In [[Custom Font Loader - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "custom_css_mode": false
> ```
#### Custom CSS Style
**Only appears if [[Custom Font Loader - Settings#Custom CSS Mode]] is enabled.**
> [!info] In [[Custom Font Loader - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "custom_css": ""
> ```

> [!important] #my-settings 
> ```
> /* FOR READING MODE */
> .markdown-reading-view .perfect_dos_vga_437_win * {
>   font-family: 'perfect_dos_vga_437_win' !important;
> }
> 
> /* FOR SOURCE MODE */
> .markdown-source-view.source-code-cascadia-mono:not(.is-live-preview) .cm-content {
>   font-family: 'Cascadia Mono' !important;
> }
> ```
