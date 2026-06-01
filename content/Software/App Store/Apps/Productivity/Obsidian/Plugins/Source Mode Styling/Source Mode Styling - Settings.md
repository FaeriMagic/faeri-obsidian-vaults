---
tags:
  - documentation/settings
---
#### Monospace font
Select a monospace font for source mode
- Use theme font (*"theme"*)
- Cascadia Code (*"Cascadia Code"*)
- Cascadia Mono (*"Cascadia Mono"*)
- Courier New (*"Courier New"*)
- Consolas (*"Consolas"*)
- Source Code Pro (*"Source Code Pro"*)
- monospace (*"monospace"*)

> [!info] In [[Source Mode Styling - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "fontFamily": "Source Code Pro"
> ```
##### Release log
- [[Source Mode Styling (0.2.25)|0.2.25]]: Added "Refresh Fonts" button for manual re-detection
#### Font weight
Set the font weight for source/raw mode
- Theme default (*"theme"*)
- Light (*"light"*)
- Normal (*"normal"*)
- Semi-bold (*"semibold"*)
- Bold (*"bold"*)
- Custom (*""*) (selecting this option will create a field for number input)

> [!info] In [[Source Mode Styling - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "fontWeight": "theme"
> ```
##### Release log
- [[Source Mode Styling (0.2.13)|0.2.13]]: Fixed: Order of font weights in settings dropdown
#### Font size
Set the font size for source mode (px)
- Theme default (*"theme"*)
- Custom (*null*) (selecting this option will create a field for number input)

> [!info] In [[Source Mode Styling - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "fontSize": "theme"
> ```
#### Font color
Set the text color for source mode
- Theme default (*"theme"*)
- Custom (*#333333*) (selecting this option will create a hex color picker for input)

> [!info] In [[Source Mode Styling - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "fontSize": "theme"
> ```
#### Line height
Set the line height for source mode (e.g. 1.0-2.5)
- Theme default (*"theme"*)
- Custom (selecting this option will create a field for number input)

> [!info] In [[Source Mode Styling - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "lineHeight": 1.75
> ```
#### Heading color
Set the color for headings in source mode
- Theme default (*"theme"*)
- Custom (selecting this option will create a hex color picker for input)

> [!info] In [[Source Mode Styling - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "headingColor": "#2d5b8c"
> ```
#### Background color
Set the background color for source mode
- Theme default (*"theme"*)
- Custom (selecting this option will create a hex color picker for input) (*default: "\#fbfaf6"*)

> [!info] In [[Source Mode Styling - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "backgroundColor": "theme"
> ```