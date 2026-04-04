← Go back to [[Tabs]]
# Settings
### Separator
The symbols to split each tab

> [!info] In `data.json`
> If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "split": "tab: "
> ```
### Default tab title
Default title of new tab

> [!info] In `data.json`
> If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "defaultTabNavItem": "New tab"
> ```
### Default tabs content
Default content of new content

> [!info] In `data.json`
> If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "defaultTabContent": "New tab content"
> ```
### Action button
Function of the top right button. Select 'None' if you don't need it.
- None (*"action-none"*)
- Add new tab (*"action-add"*)
- Edit tab (*"action-edit"*)

> [!info] In `data.json`
> If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "actionButtonType": "action-add"
> ```

> [!bug] 
> No Oxford comma.

### Ignore notice
Ignore notice when adding, deleting tabs and so on.

> [!info] In `data.json`
> If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "ignoreNotice": false
> ```
### Autofresh Markdown view
When enabled, after you modify the settings of the tabs, all markdown files that opened will automatically refresh when you close the settings panel. If disabled, the changes will not take effect immediately on the Tabs in opened Markdown file, and you will need to re-render them matually.

> [!info] In `data.json`
> If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "autorefreshMarkdownView": true
> ```

> [!bug] 
> "file" needs to be pluralized to "files". Also "matually" is incorrect.
### Drag and drop
You can drag and drop tabs to reorder them in the same file.

> [!info] In `data.json`
> If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "dragAndDrop": false
> ```

> [!important] My settings
> I set this to `true`.
## Editor
### Double click to edit
Double click tab content to edit

> [!info] In `data.json`
> If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "doubleClickToEdit": false
> ```

> [!important] My settings
> I set this to `true`.
### Show toolbar
Show toolbar in tabs editor

> [!info] In `data.json`
> If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "showToolbar": true
> ```
### Tab size
Tab size in tab editor

> [!info] In `data.json`
> If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "tabSize": 4
> ```
> The slider ranges from 1 to 8.

> [!bug] 
> This setting doesn't seem to affect anything. The reset button also doesn't work.
### Auto save interval
Set the duration of inactivity after which the editor will automatically save your work. (default: 5000ms, 0 means only save on exit)

> [!info] In `data.json`
> If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "editorAutoSaveInterval": 5000
> ```

> [!important] My settings
> I set this to `0`.
## Appearance

```tabs

tab:Tabs
### Tabs border
Show tabs border when hover or always.
- None (*"border-none"*)
- Hover (*"border-hover"*)
- Always (*"border-always"*)

<div style="text-align: center;">· · ·</div>

 
> [!info] In `data.json`
> If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "defaultTabsBorder": "border-hover"
> ```
<div style="text-align: center;">· · ·</div>

> [!important] My settings
> I set this to `"border-always"`.
<div style="text-align: center;">· · ·</div>

### Tabs border color
Takes effect when "Tabs border" set 'Hover' or 'Always
<div style="text-align: center;">· · ·</div>

> [!info] In `data.json`
> If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "defaultTabsBorderColor": "#e0e0e0"
> ```
<div style="text-align: center;">· · ·</div>

> [!important] My settings
> I set this to `"#282c34"`.
<div style="text-align: center;">· · ·</div>

> [!bug] 
> Description is missing a word and punctuation.
<div style="text-align: center;">· · ·</div>

### Hide tabs code block edit block button
It's just a decorative setting. If you turn on it, you can still control the cursor into tabs to edit the source code.
<div style="text-align: center;">· · ·</div>

> [!info] In `data.json`
> If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "hideTabsEditBlockButton": true
> ```
<div style="text-align: center;">· · ·</div>

> [!important] My settings
> I set this to `false`.
<div style="text-align: center;">· · ·</div>

> [!bug] 
> Description phrasing.
tab:Tabs nav
### Tabs nav default posi tion
Show tabs nav at the top, bottom, left or right.
- Top (*"top"*)
- Bottom (*"bottom"*)
- Left (*"left"*)
- Right (*"right"*)

<div style="text-align: center;">· · ·</div>

> [!info] In `data.json`
> If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "defaultTitlePosition": "top"
> ```
<div style="text-align: center;">· · ·</div>

> [!bug] 
> Description typo spacing and missing Oxford comma.
<div style="text-align: center;">· · ·</div>

### Tabs nav line clamp
Show tabs nav in one line or multiple lines. Only works when the position is 'top' or 'bottom'
- One line (*"one"*)
- Multiple lines (*"multi"*)
  
<div style="text-align: center;">· · ·</div>

> [!info] In `data.json`
> If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "defaultTitleLineClamp": "one"
> ```
<div style="text-align: center;">· · ·</div>

> [!important] My settings
> I set this to `"multi"`.
<div style="text-align: center;">· · ·</div>

> [!bug] 
> Description is missing period.
<div style="text-align: center;">· · ·</div>

### Limit tab title width
If set true, tab title will be limited to the width of the tab. Otherwise, the tab title will be displayed the full width.

<div style="text-align: center;">· · ·</div>

> [!info] In `data.json`
> If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "defaultTitleLimited": false
> ```
tab:Tabs content
### Tabs contents padding
The padding of tabs contents. You can set one to four values(same as css padding.) For example, "0" means no padding. "10px" means 10 pixels on all sides. "10px 20px" means 10 pixels on top and bottom, 20 pixels on left and right.Not only "px" but also "em", "rem" and other units are supported.

<div style="text-align: center;">· · ·</div>

> [!info] In `data.json`
> If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "defaultTabsContentsPadding": "1em 2em"
> ```
<div style="text-align: center;">· · ·</div>

> [!bug] 
> Description has incorrect spacing.
<div style="text-align: center;">· · ·</div>

### Tabs contents max height
If a feasible CSS size is set (for example, 250px, 15em, 50vh, etc.), then when the height of the tabs reaches this size, the excess part can be scrolled. Note that the value should not be set too small, otherwise the tabs will not display properly.
<div style="text-align: center;">· · ·</div>

> [!info] In `data.json`
> If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "defaultTabsContentsMaxHeight": "none"
> ```
```