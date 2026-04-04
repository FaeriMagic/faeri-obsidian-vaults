---
summary: Style Settings for Things.
created:
modified:
tags:
  - bugs
  - style-settings
---
> [!important] These settings require the [[App Store/Apps/Productivity/Obsidian/Plugins/Style Settings/Style Settings|Style Settings]] plugin.

← Go back to [[Things]]

> [!bug] 
> When reopening the Things Style Settings, previews colors are not properly displayed in the color swatch.
# Features
## Black mobile background
Change mobile editor background to default theme black

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> The toggle must be used in order to be accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@mobile-black-background": false
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
## Disable mobile floating-action button
Revert placement of edit/preview button to default in header (mobile)

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> The toggle must be used in order to be accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@floating-button-off": false
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
## Highlight active line
Change background color of the current working file

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> The toggle must be used in order to be accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@active-line": false
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
## Fancy code blocks
Enable fancy numbered code blocks

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> The toggle must be used in order to be accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@fancy-code": false
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
## Fancy highlighting
Enable fancy highlighting styles with highlight underlines

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> The toggle must be used in order to be accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@fancy-highlight": false
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
## Disable Kanban board styles
Remove minimalist styling to the Kanban plugin

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> The toggle must be used in order to be accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@no-kanban-styles": false
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
## Underline internal links
Show underlines on internal links
- Underline (*"Underline"*)
- None (*"None"*)

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values selected from the dropdown are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@link-decoration": "Underline"
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
## Underline external links
Show underlines on external links
- Underline (*"Underline"*)
- None (*"None"*)

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values selected from the dropdown are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@link-external-decoration": "Underline"
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
# Typography
## Default font colors
Use the default font color styling for bold, italics, and quotes

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> The toggle must be used in order to be accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@default-font-color": false
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
## Highlight color (light)

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@text-highlight-bg-l": "#FFD000"
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.

> [!warning] 
> The **Highlight color (light)** settings only take effect when [[#Fancy highlighting]] is turned off. If Fancy highlighting is enabled, it will override your custom highlight colors.
## Highlight color (dark)

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@text-highlight-bg-d": "#FFD000"
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.

> [!warning] 
> The **Highlight color (dark)** settings only take effect when [[#Fancy highlighting]] is turned off. If Fancy highlighting is enabled, it will override your custom highlight colors.
## Bold font color

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@strong-color": "#FF82B2"
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.

> [!warning] 
> For text that is both ***bold and italicized***, the italic color takes precedent.
## Italics font color

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@em-color": "#FF82B2"
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.

> [!warning] 
> For text that is both ***bold and italicized***, the italic color takes precedent.
## Blockquotes font color

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@quote-color": "#3EB4BF"
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
## Inline code blocks font color (Light mode)

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@code-normal": "#BEC6CF"
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.

> [!warning] 
> This property actually changes the inline code blocks font color in **both light and dark mode**.
## Inline code blocks font color (Dark mode)

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@code-color-d": "#555E68"
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.

> [!bug] 
> This property currently **doesn't work**. See [[#Inline code blocks font color (Light mode)]].
## Tag background color (Light mode)

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@tag-background-color-l": "#BDE1D3"
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
## Tag font color (Light mode)

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@tag-font-color-l": "#1D694B"
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
## Tag background color (Dark mode)

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@tag-background-color-d": "#1D694B"
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
## Tag font color (Dark mode)

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@tag-font-color-d": "#FFFFFF"
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
## Progress colorful mode switcher
Toggle progress color scheme

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> The toggle must be used in order to be accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@progress-color": false
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.

> [!question] 
> This setting may be related to the [[Kanban]] plugin's progress indicators. Untested.
## progress 2-39% color

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@progress-color-1": "#AD5758"
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.

> [!question] 
> This setting may be related to the [[Kanban]] plugin's progress indicators. Untested.
## progress 40-59% color

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@progress-color-2": "#B87F4C"
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.

> [!question] 
> This setting may be related to the [[Kanban]] plugin's progress indicators. Untested.
## progress 60-79% color

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@progress-color-3": "#D2B874"
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.

> [!question] 
> This setting may be related to the [[Kanban]] plugin's progress indicators. Untested.
## progress 80-99% color

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@progress-color-4": "#B0C07E"
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.

> [!question] 
> This setting may be related to the [[Kanban]] plugin's progress indicators. Untested.
## progress 1,100% color

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@progress-color-5": "#768399"
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.

> [!question] 
> This setting may be related to the [[Kanban]] plugin's progress indicators. Untested.
# Headings
## Level 1 Headings
### H1 font size
Accepts any CSS font-size value

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values typed in the field are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@h1-size": "1.7em"
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
### H1 font weight
Accepts numbers representing the CSS font-weight

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values typed in the field are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@h1-weight": 700
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
### H1 color

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@h1-color": "#"
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
## Level 2 Headings
### H2 font size
Accepts any CSS font-size value

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values typed in the field are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@h2-size": "1.5em"
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
### H2 font weight
Accepts numbers representing the CSS font-weight

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values typed in the field are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@h2-weight": 700
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
### H2 color

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@h2-color": "#2E80F2"
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
> 
> **Note:** You **must** input the hex code into the color picker in order for the default property to be applied. Otherwise, Obsidian's default h2 color style will override it.
### H2 underline

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> The toggle must be used in order to be accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@h2-underline": true
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
## Level 3 Headings
### H3 font size
Accepts any CSS font-size value

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values typed in the field are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@h3-size": "1.2em"
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
### H3 font weight
Accepts numbers representing the CSS font-weight

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values typed in the field are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@h3-weight": 600
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
### H3 color

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@h3-color": "#2E80F2"
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
## Level 4 Headings
### H4 font size
Accepts any CSS font-size value

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values typed in the field are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@h4-size": "1.1em"
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
### H4 font weight
Accepts numbers representing the CSS font-weight

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values typed in the field are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@h4-weight": 500
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
### H4 font color

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@h4-color": "#E5B567"
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
### H4 transform
Transform the H4 heading text
- Uppercase (*"uppercase"*)
- None (*"none"*)

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values selected from the dropdown are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@h4-transform": "uppercase"
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.

> [!bug] 
> This property doesn't work.
## Level 5 Headings
### H5 font size
Accepts any CSS font-size value

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values typed in the field are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@h5-size": "1em"
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
### H5 font weight
Accepts numbers representing the CSS font-weight

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values typed in the field are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@h5-weight": 500
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
### H5 color

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@h5-color": "#E83E3E"
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
## Level 6 Headings
### H6 font size
Accepts any CSS font-size value

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values typed in the field are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@h6-size": "0.9em"
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
### H6 font weight
Accepts numbers representing the CSS font-weight

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values typed in the field are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@h6-weight": 400
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.
### H6 color

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "things-style@@h5-color": "#"
> ```
> If `⟲` is clicked, this JSON property will be removed from `data.json`.

---
**Credits**
Created with ❤ by @colineckert. Support @colineckert at buymeacoffee.com/colineckert