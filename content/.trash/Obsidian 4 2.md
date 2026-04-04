---
developer: Dynalist Inc.
seller: Dynalist Inc.
languages:
  - English
  - "[[CSS]]"
  - "[[JavaScript]]"
  - "[[TypeScript]]"
age rating: 4+
copyright: © Dynalist Inc.
website: https://obsidian.md/
email: support@obsidian.md
color: "#8A5CF5"
platforms:
  - App Store
  - "[[Bluesky]]"
  - "[[Discord]]"
  - "[[Github]]"
  - "[[Instagram]]"
  - "[[Mastodon]]"
  - "[[Threads]]"
  - "[[X (Twitter)]]"
  - "[[YouTube]]"
app store: https://apps.apple.com/app/id1557175442
bluesky: https://bsky.app/profile/obsidian.md
bluesky trusted verifier: "[[Bluesky]]"
bluesky verification date: 2026-01-30
discord:
github: https://github.com/obsidianmd
instagram: https://www.instagram.com/obsdmd/
mastodon: https://mas.to/@obsidian
mastodon join date: 2023-02-19
threads: https://www.threads.com/@obsdmd
x (twitter): https://x.com/obsdmd
x (twitter) join date: March 2020
youtube: https://www.youtube.com/channel/UCRP5KXKq8Ytc6IH06VWRmkQ
youtube join date: 2017-01-25
tags:
  - app/productivity
---
<div style="display: flex; gap: 1em; margin: 0 auto; max-width: 840px">
	<div style="align-items: center; display: flex; flex-shrink: 0; position: relative; width: 128px; z-index: 2;">
		<img src="Icon - Obsidian.webp" style="border-radius: 25%;">
	</div>
	<div style="display: flex; flex-direction: column; gap: 2px;">
		  <h1 style="font: 700 17px/1.2307692308 Helvetica, Arial, sans-serif; margin: 0;">Obsidian - Connected Notes</h1>
		  <h2 style="color: rgba(245,245,245,.6); font: 400 14px/1.230769308 Helvetica, Arial, sans-serif; mix-blend-mode: plus-lighter; margin: 0;">Your second brain on the go</h2>
		  <p style="font: 400 13px/1.230769308 Helvetica, Arial, sans-serif; margin: 0; color: rgba(245,245,245,.6); mix-blend-mode: plus-lighter;">Free</p>
	</div>
</div>

Obsidian is a powerful knowledge base that works on top of a local folder of plain text Markdown files.

It is a second brain, for you, forever. Now available on the go for iOS!

Features include:
- Customizable toolbar
- Pull down quick actions
- Graph view
- [[Plugins|Community plugins]]
- Themes
- Sidebar pinning for tablet
- iCloud vaults
# Settings documentation
Upon opening Obsidian for the first time, Obsidian comes with the following .json files in the .obsidian folder:

> [!info] In `app.json`
> **Default:**
> ```JSON
> {}
> ```

> [!info] In `appearance.json`
> **Default:**
> ```JSON
> {}
> ```

> [!info]- In `core-plugins.json`
> **Default:**
> ```JSON
> {
>   "file-explorer": true,
>   "global-search": true,
>   "switcher": true,
>   "graph": true,
>   "backlink": true,
>   "canvas": true,
>   "outgoing-link": true,
>   "tag-pane": true,
>   "footnotes": false,
>   "properties": true,
>   "page-preview": true,
>   "daily-notes": true,
>   "templates": true,
>   "note-composer": true,
>   "command-palette": true,
>   "slash-command": false,
>   "editor-status": true,
>   "bookmarks": true,
>   "markdown-importer": false,
>   "zk-prefixer": false,
>   "random-note": false,
>   "outline": true,
>   "word-count": true,
>   "slides": false,
>   "audio-recorder": false,
>   "workspaces": false,
>   "file-recovery": true,
>   "publish": false,
>   "sync": true,
>   "bases": true,
>   "webviewer": false
> }
> ```

> [!info]- In `workspace.json`
> **Default:**
> ```JSON
> {
>   "main": {
>   "id": "b6880eb90074385c",
>   "type": "split",
>   "children": [
>     {
>       "id": "f2536fe24ce8f8f3",
>       "type": "tabs",
>       "children": [
>         {
>           "id": "8c67c3da817ad3fb",
>           "type": "leaf",
>           "state": {
>             "type": "empty",
>             "state": {},
>             "icon": "lucide-file",
>             "title": "New tab"
>             }
>           }
>         ]
>       }
>     ],
>     "direction": "vertical"
>   },
>   "left": {
>     "id": "cfb42b5c145d9a51",
>     "type": "split",
>     "children": [
>       {
>         "id": "b024ba4d74cf81b9",
>         "type": "tabs",
>         "children": [
>           {
>             "id": "db94200a8bb8b207",
>             "type": "leaf",
>             "state": {
>               "type": "file-explorer",
>               "state": {
>                 "sortOrder": "alphabetical",
>                 "autoReveal": false
>               },
>               "icon": "lucide-folder-closed",
>               "title": "Files"
>             }
>           },
>           {
>             "id": "85f58db3627519a6",
>             "type": "leaf",
>             "state": {
>               "type": "search",
>               "state": {
>                 "query": "",
>                 "matchingCase": false,
>                 "explainSearch": false,
>                 "collapseAll": false,
>                 "extraContext": false,
>                 "sortOrder": "alphabetical"
>               },
>               "icon": "lucide-search",
>               "title": "Search"
>             }
>           },            
>           {
>             "id": "3f0ae3be709c1ade",
>             "type": "leaf",
>             "state": {
>               "type": "bookmarks",
>               "state": {},
>               "icon": "lucide-bookmark",
>               "title": "Bookmarks"
>             }
>           }
>         ]
>       }
>     ],
>     "direction": "horizontal",
>     "width": 300
>   },
>   "right": {
>     "id": "3b69008ddf2e7093",
>     "type": "split",
>     "children": [
>       {
>         "id": "3658c0c4a5f03768",
>         "type": "tabs",
>         "children": [
>           {
>             "id": "a47548cd07b0d49f",
>             "type": "leaf",
>             "state": {
>               "type": "backlink",
>               "state": {
>                 "collapseAll": false,
>                 "extraContext": false,
>                 "sortOrder": "alphabetical",
>                 "showSearch": false,
>                 "searchQuery": "",
>                 "backlinkCollapsed": false,
>                 "unlinkedCollapsed": true
>               },
>               "icon": "links-coming-in",
>               "title": "Backlinks"
>             }
>           },
>           {
>             "id": "298f8d5998711aa7",
>             "type": "leaf",
>             "state": {
>               "type": "outgoing-link",
>               "state": {
>                 "linksCollapsed": false,
>                 "unlinkedCollapsed": true
>               },
>               "icon": "links-going-out",
>               "title": "Outgoing links"
>             }
>           },
>           {
>             "id": "1df0e649195d5836",
>             "type": "leaf",
>             "state": {
>               "type": "tag",
>               "state": {
>                 "sortOrder": "frequency",
>                 "useHierarchy": true,
>                 "showSearch": false,
>                 "searchQuery": ""
>               },
>               "icon": "lucide-tags",
>               "title": "Tags"
>             }
>           },
>           {
>             "id": "a6f2ee98d3cc2ce5",
>             "type": "leaf",
>             "state": {
>               "type": "all-properties",
>               "state": {
>                 "sortOrder": "frequency",
>                 "showSearch": false,
>                 "searchQuery": ""
>               },
>               "icon": "lucide-archive",
>               "title": "All properties"
>             }
>           },
>           {
>             "id": "2d05e9244917516d",
>             "type": "leaf",
>             "state": {
>               "type": "outline",
>               "state": {
>                 "followCursor": false,
>                 "showSearch": false,
>                 "searchQuery": ""
>               },
>               "icon": "lucide-list",
>               "title": "Outline"
>             }
>           }
>         ]
>       }
>     ],
>     "direction": "horizontal",
>     "width": 300,
>     "collapsed": true
>   },
>   "left-ribbon": {
>     "hiddenItems": {
>       "switcher:Open quick switcher": false,
>       "graph:Open graph view": false,
>       "canvas:Create new canvas": false,
>       "daily-notes:Open today's daily note": false,
>       "templates:Insert template": false,
>       "command-palette:Open command palette": false,
>       "bases:Create new base": false
>     }
>   },
>   "active": "8c67c3da817ad3fb",
>   "lastOpenFiles": []
> }
> ```

## Options
### General
##### Automatic updates
Turn this off to prevent the app from checking for updates.

**Default:** `true`
##### Language
Change the display language.
[Learn how to add a new language to Obsidian.](https://help.obsidian.md/translations)

**Default:** `English`

> [!abstract]- Available languages
> | Language code | Language name         | Native name         |
> | ------------- | --------------------- | ------------------- |
> | `am`          | Amharic               | አማርኛ                |
> | `ar`          | Arabic                | العربية             |
> | `be`          | Belarusian            | Беларуская мова     |
> | `bn`          | Catalan               | català              |
> | `cs`          | Czech                 | čeština             |
> | `da`          | Danish                | Dansk               |
> | `de`          | German                | Deutch              |
> | `en`          | English               | English             |
> | `en-GB`       | English (GB)          | English (GB)        |
> | `es`          | Spanish               | Español             |
> | `fa`          | Persian               | فارسی               |
> | `fr`          | French                | Français            |
> | `ga`          | Irish                 | Gaeilge             |
> | `he`          | Hebrew                | עברית 🇮🇱          |
> | `hu`          | Hungarian             | Magyar              |
> | `id`          | Indonesian            | Bahasa Indonesia    |
> | `it`          | Italian               | Italiano            |
> | `ja`          | Japanese              | 日本語                 |
> | `kh`          | Khmer                 | ខ្មែរ               |
> | `ko`          | Korean                | 한국어                 |
> | `lv`          | Latvian               | Latviešu            |
> | `ms`          | Malay                 | Bahasa Melayu       |
> | `ne`          | Nepali                | नेपाली              |
> | `nl`          | Dutch                 | Nederlands          |
> | `no`          | Norwegian             | Norsk               |
> | `pl`          | Polish                | Polski              |
> | `pt`          | Portuguese            | Português           |
> | `pt-BR`       | Brazilian Portuguese  | Português do Brasil |
> | `ro`          | Romanian              | Română              |
> | `ru`          | Russian               | Русский             |
> | `sq`          | Albanian              | Shqip               |
> | `th`          | Thai                  | ไทย                 |
> | `tr`          | Turkey                | Türkçe              |
> | `uk`          | Ukrainian             | Українська          |
> | `uz`          | Uzbek                 | oʻzbekcha           |
> | `vi`          | Vietnamese            | Tiếng Việt          |
> | `zh`          | Chinese (Simplified)  | 简体中文                |
> | `zh-TW`       | Chinese (Traditional) | 繁體中文                |
#### Advanced
##### Notify if startup time takes longer than expected
Diagnose issues with your app by seeing what is causing the app to load slowly.

**Default:** `off`

> [!important] My settings
> I turned this on.
### Editor
#### Always focus new tabs
When you open a link in a new tab, switch to it immediately.

> [!info] In `app.json`
> Only written to `app.json` upon update.
> 
> **Default:**
> ```JSON
>   "focusNewTab": true
> ```
##### Default view for new tabs
The default view that a new markdown tab gets opened in.
- Editing view (`"source"`)
- Reading view (`"preview"`)

> [!info] In `app.json`
> Only written to `app.json` upon update.
> 
> **Default:**
> ```JSON
>   "defaultViewMode": "source"
> ```
##### Default editing mode
The default editing mode a new tab will start with.
- Live Preview
- Source Mode

> [!info] In `app.json`
> Only written to `app.json` upon update.
> 
> **Default:**
> ```JSON
>   "livePreview": true
> ```
##### Show editing mode in status bar
Show the editing mode toggle in the status bar.

**Default:** `true`
#### Display
##### Readable line length
Limit maximum line length. Less content fits onscreen, but long blocks of text are more readable.

> [!info] In `app.json`
> Only written to `app.json` upon update.
> 
> **Default:**
> ```JSON
>   "readableLineLength": true
> ```
##### Strict line breaks
Markdown specs ignore single line breaks in reading view. Turn this off to make single line breaks visible.

> [!info] In `app.json`
> Only written to `app.json` upon update.
> 
> **Default:**
> ```JSON
>   "strictLineBreaks": false
> ```
##### Properties in document
Choose how properties are displayed at the top of notes. Select "source" to show properties as raw YAMAL.
- Visible (`visible`)
- Hidden (`hidden`)
- Source (`source`)

> [!info] In `app.json`
> Only written to `app.json` upon update.
> 
> **Default:**
> ```JSON
>   "propertiesInDocument": "visible"
> ```

> [!important] My settings
> I set this to `hidden`.
##### Fold heading
Lets you fold all content under a heading.

> [!info] In `app.json`
> Only written to `app.json` upon update.
> 
> **Default:**
> ```JSON
>   "foldHeading": true
> ```
> 
> **Note:** Even if set to `false`, the carat will still appear next to the heading upon hover. It just won't be clickable.
##### Fold indent
Lets you fold part of an indentation, such as lists.

> [!info] In `app.json`
> Only written to `app.json` upon update.
> 
> **Default:**
> ```JSON
>   "foldIndent": true
> ```
> 
> **Note:** Even if set to `false`, the carat will still appear next to the heading upon hover. It just won't be clickable.
##### Line numbers
Show line numbers in the gutter.

> [!info] In `app.json`
> Only written to `app.json` upon update.
> 
> **Default:**
> ```JSON
>   "showLineNumber": false
> ```

> [!important] My settings
> I set this to `true`.
##### Indentation guides
Show vertical relationship lines between list items.

> [!info] In `app.json`
> Only written to `app.json` upon update.
> 
> **Default:**
> ```JSON
>   "showIndentGuide": true
> ```
##### Right-to-left (RTL)
Sets the default text direction of notes to right-to-left.

> [!info] In `app.json`
> Only written to `app.json` upon update.
> 
> **Default:**
> ```JSON
>   "rightToLeft": false
> ```
#### Behavior
##### Spellcheck
Turn on the spellchecker.

> [!info] In `app.json`
> Only written to `app.json` upon update.
> 
> **Default:**
> ```JSON
>   "spellcheck": true
> ```
##### Spellcheck languages
Choose the languages for the spellchecker to use.

> [!example]- Available languages
> - Afrikaans
> - Albanian
> - Armenian
> - Bulgarian
> - Catalan
> - Croatian
> - Czech
> - Danish
> - Dutch
> - English
> - English (Australia)
> - English (Canada)
> - English (United Kingdom)
> - English (United Kingdom)(oxendict)
> - English (United States)
> - Estonian
> - Faroese
> - French
> - French (France)
> - German
> - German (Germany)
> - Greek
> - Hebrew
> - Hindi
> - Hungarian
> - Indonesian
> - Italian
> - Italian (Italy)
> - Korean
> - Latvian
> - Lithuanian
> - Norwegian Bokmål
> - Persian
> - Polish
> - Portuguese
> - Portuguese (Brazil)
> - Portuguese (Portugal)
> - Romanian
> - Russian
> - Serbian
> - Serbo-Croatian
> - Slovak
> - Slovenian
> - Spenish
> - Spanish (419)
> - Spanish (Argentina)
> - Spanish (Mexico)
> - Spanish (Spain)
> - Spanish (United States)
> - Swedish
> - Tajik
> - Tamil
> - Turkish
> - Ukrainian
> - Vietnamese
> - Welsh
##### Auto-pair brackets
Pair brackets and quotes automatically. 

> [!info] In `app.json`
> Only written to `app.json` upon update.
> 
> **Default:**
> ```JSON
>   "autoPairBrackets": true
> ```
##### Auto-pair Markdown syntax
Pair symbols automatically for bold, italic, code, and more. 

> [!info] In `app.json`
> Only written to `app.json` upon update.
> 
> **Default:**
> ```JSON
>   "autoPairMarkdown": true
> ```
##### Smart lists
Automatically set indentation and place list items correctly.

> [!info] In `app.json`
> Only written to `app.json` upon update.
> 
> **Default:**
> ```JSON
>   "smartIndentList": true
> ```
##### Indent using tabs
Use tabs to indent by pressing the "Tab" key. Turn this off to indent using 4 spaces.

> [!info] In `app.json`
> Only written to `app.json` upon update.
> 
> **Default:**
> ```JSON
>   "useTab": true
> ```

> [!bug] 
> Setting `useTab` to `false` does **not** disable tab indentation. It only adds the ability to indent with 4 spaces as well. While the description is technically accurate, it does not match what the property name or user expectation implies.
##### Indent visual width
Number of spaces a tab character will render as.

> [!info] In `app.json`
> Only written to `app.json` upon update.
> 
> **Default:**
> ```JSON
>   "tabSize": 4
> ```

> [!note] Changing tab size to a number not supported by the slider
> While the tab size slider only supports values between 2 and 8, you can set the value to a different number in `app.json` directly and it will render correctly.
> Numbers below 0 (such as -1 or -2) will render a tab size of 8 regardless of the number.
#### Advanced
##### Convert pasted HTML to Markdown
Automatically convert HTML to Markdown when pasting and drag-and-drop from web pages. Use Ctrl/Cmd+Shift+V to paste HTML without converting.

> [!info] In `app.json`
> Only written to `app.json` upon update.
> 
> **Default:**
> ```JSON
>   "autoConvertHtml": true
> ```

> [!warning]
> When `autoConvertHtml` is `false`, pressing Ctrl/Cmd+Shift+V will **not** convert pasted HTML to Markdown.
##### Vim key bindings
Use Vim key bindings when editing.

> [!info] In `app.json`
> Only written to `app.json` upon update.
> 
> **Default:**
> ```JSON
>   "vimMode": false
> ```

**When turning vim key bindings on, you will receive this popup:**

> [!warning] Confirm entering Vim mode
> <span style="color: #FB464C;">Vim mode is for efficient text editing but can be quite counter-intuitive. If you're not familiar with Vim, this option might make it look like Obsidian has stopped working.</span>
> 
> To verify that you know your way around Vim, please enter the command to quit Vim without saving below:
### Files and links
##### Default file to open
Choose which file to open when the app starts.
- Last opened (`""`)
- New note (`"new"`)
- Specific file (`"file:"`)
- Daily note (`"daily"`)

> [!info] In `app.json`
> Only written to `app.json` upon update.
> 
> **Default:**
> ```JSON
>   "openBehavior": false
> ```

> [!info] File to open
> Select a specific file to open by default.
> 
> **This setting only appears when `openBehavior` is set to `"file:"`.** The selected file's path is appended to `"file:"` in `app.json`.
##### Default location for new notes
Where newly created notes are placed.
- Vault folder (`"root"`)
- Same folder as current file (`"current"`)
- In the folder specified below (`"folder"`)

> [!info] In `app.json`
> Only written to `app.json` upon update.
> 
> **Default:**
> ```JSON
>   "newFileLocation": "root"
> ```

> [!info] Folder to create new notes in
> Newly created notes will appear in this folder.
> 
> **This setting only appears when `newFileLocation` is set to `"folder"`.** The selected folder is stored in:
> ```JSON
>  "newFileFolderPath": "Your folder name"
> ```
> **Note:** `newFileFolderPath` retains its value even when a different option is selected in the dropdown, but only takes effect when `newFileLocation` is set to `"folder"`.
##### Default location for new attachments
Where newly added attachments are placed.
- Vault folder "`/`"
- Same folder as the current file (`"./"`)
- In subfolder under current folder (`"./your-folder-name"`)
- In the folder specified below (`"your-folder-path"`)

> [!info] In `app.json`
> Only written to `app.json` upon update.
> 
> **Default:**
> ```JSON
>   "attachmentFolderPath": "/"
> ```

> [!info] Subfolder name
> If your file is in "vault/folder", and you set subfolder name to "attachments", attachments will be saved to "vault/folder/attachments".
> 
> **This setting only appears when "In subfolder under current folder" is selected in the dropdown.**
> 
> If no folder is specified, `attachmentFolderPath` will default to `"./attachments"`.

> [!info] Attachment folder path
> Place newly created attachment files, such as images created via drag-and-drop or audio recordings, in this folder.
> 
> **This setting only appears when "In the folder specified below" is selected in the dropdown.**
>  
> If no folder is specified, `attachmentFolderPath` will default to `"attachments"`.

> [!important] My settings
> I selected "Same folder as current file".
#### Links
##### New link format
What links to insert when auto-generating internal links.
- Shortest path when possible (`"shortest"`)
- Path from current file (`"relative"`)
- Path from vault folder (`"absolute"`)

> [!info] In `app.json`
> Only written to `app.json` upon update.
> 
> **Default:**
> ```JSON
>   "newLinkFormat": "shortest"
> ```
##### Automatically update internal links
Turn off to be prompted to update links after renaming a file.

> [!info] In `app.json`
> Only written to `app.json` upon update.
> 
> **Default:**
> ```JSON
>   "alwaysUpdateLinks": false
> ```

**When renaming a link, you will receive this popup:**

> [!warning] Update links
> Do you want to update internal links that link to this file? 
> 
> This will affect \[#] in \[#] file.
> 
> \[Always update] \[Just once] \[Do not update]

If "Always update" is selected, `"alwaysUpdateLinks"` is set to `true`.

> [!bug]
> **Closing** the dialog will proceed with renaming the file, without updating internal links.

> [!important] My settings
> I turned this on.
##### Use \[\[Wikilinks]]
Auto-generate Wikilinks for \[\[links]] and !\[\[images]] instead of Markdown links and images. Disable this option to generate Markdown links instead.

> [!info] In `app.json`
> Only written to `app.json` upon update.
> 
> **Default:**
> ```JSON
>   "useMarkdownLinks": false
> ```
##### Show all file types
Show files with any extension even if Obsidian can't open them natively, so you can link to them and see them in File Explorer and Quick Switcher.

> [!info] In `app.json`
> Only written to `app.json` upon update.
> 
> **Default:**
> ```JSON
>   "showUnsupportedFiles": false
> ```

> [!important] My settings
> I turned this on.
#### Trash
##### Confirm file deletion
Ask before deleting a file.

> [!info] In `app.json`
> Only written to `app.json` upon update.
> 
> **Default:**
> ```JSON
>   "promptDelete": true
> ```

If `"promptDelete"` is `true`, you will receive this popup when you try to delete a file:

> [!warning] Delete file
> Are you sure you want to delete "your-file-name"?
> 
> (Information about happens to the file if deleted is placed here.)
> 
> - [ ] Do not ask again \[Delete] \[Cancel]

Checking "Do not ask again" before clicking "Delete" will cause `"promptDelete"` to be set to `false`.
##### Deleted files
What happens to a file after you delete it.
- Move to system trash (`"system"`)
  The deletion prompt will say:
	  "It will be moved to your system trash."
- Move to Obsidian trash (.trash folder) (`"local"`)
  The deletion prompt will say:
	  "It will be moved to your Obsidian trash, which is located in the ".trash" hidden folder in your vault."
- Permanently delete (`"none"`)
  The deletion prompt will say:
	  "<span style="color: #FB464C;">This file will be permanently deleted.</span>"

> [!info] In `app.json`
> Only written to `app.json` upon update.
> 
> **Default:**
> ```JSON
>   "trashOption": "system"
> ```

> [!warning] Deleting to .trash when it does not exist
> For vaults synced with iCloud, the first deletion may create the `.trash` folder without moving the file. A second deletion is required. This is caused by iCloud intercepting the delete operation, not an Obsidian bug.

> [!important] My settings
> I set this to "Move to Obsidian trash (.trash folder)"
#### Advanced
##### Excluded files
Excluded files will be hidden in Search, Graph View, and Unlinked Mentions, less noticeable in Quick Switcher and link suggestions.

> [!info] In `app.json`
> Only written to `app.json` upon update.
> 
> **Default:**
> ```JSON
>   "userIgnoreFilters": []
> ```

**When clicking "Manage", you will receive this popup:**

> [!warning] Excluded files
> No excluded filter is applied right now. Add one below.

##### Override config folder
Use a different config folder than the default one. Must start with a dot.
##### Allow URI callbacks
Enable the use of x-callback-url through x-success or x-error when handling Obsidian URIs. [Learn more](https://help.obsidian.md/uri#Use+x-callback-url+parameters)

> [!info] In `app.json`
> Only written to `app.json` upon update.
> 
> **Default:**
> ```JSON
>   "uriCallbacks": false
> ```
##### Rebuild vault cache
<span style="color: #FB464C;">Rebuilding the cache could take a few seconds to a few minutes depending on the size of your vault.</span> [Learn more](https://help.obsidian.md/data-storage#Metadata+cache)
### Appearance
##### Base color scheme
Choose Obsidian's default color scheme.
- Dark (`"obsidian"`)
- Light (`"moonstone"`)
- Adapt to system (`"system"`)

> [!info] In `appearance.json`
> Only written to `appearance.json` upon update.
> 
> **Default:**
> ```JSON
>   "theme": "system"
> ```
##### Accent color
Choose the accent color used throughout the app.

> [!info] In `appearance.json`
> Only written to `appearance.json` upon update.
> 
> **Default:**
> ```JSON
>   "accentColor": ""
> ```
> When unspecified, the accent color is <span style="color: #8A5CF5;">\#8A5CF5</span>.

##### Themes
Manage installed themes and browse community themes.

If there is no "themes" folder in Obsidian, either installing a new theme or clicking the folder icon will create one.

> [!info] In `appearance.json`
> Only written to `appearance.json` upon update.
> 
> **Default:**
> ```JSON
>   "cssTheme": ""
> ```

> [!info] About the Default theme
> According to the theme's page in the community themes, the Default theme was made by Obsidian. It cannot be uninstalled, and only has a simple description on the theme page:
> 
> A simple theme designed to feel intuitive across all platforms. Supports light and dark mode.
#### Interface
##### Inline title
Display the filename as an editable title inline with the file contents.

> [!info] In `app.json`
> Only written to `app.json` upon update.
> 
> **Default:**
> ```JSON
>   "showInlineTitle": true
> ```

> [!important] My settings
> I turned this off.
##### Show tab title bar
Display the header at the top of every tab.

> [!info] In `appearance.json`
> Only written to `appearance.json` upon update.
> 
> **Default:**
> ```JSON
>   "showViewHeader": true
> ```
##### Show ribbon
Display vertical toolbar on the side of the window.

> [!info] In `appearance.json`
> Only written to `appearance.json` upon update.
> 
> **Default:**
> ```JSON
>   "showRibbon": true
> ```
##### Ribbon menu configuration
Configure what commands appear in the ribbon menu.

Clicking "Manage" will cause this popup to appear:

> [!warning] Ribbon menu
> Change what items you want to be active in the ribbon. Drag and drop to change the order.

By default, the ribbon items are displayed in the following order:
- Open quick switcher
- Open graph view
- Create a new canvas
- Open today's daily note
- Insert template
- Open command palette
- Create new base
#### Font
##### Interface font
Set base font for all of Obsidian.

> [!info] In `appearance.json`
> Only written to `appearance.json` upon update.
> 
> **Default:**
> ```JSON
>   "interfaceFontFamily": ""
> ```
> When unspecified, the font family is set to Segoe UI.

Clicking "Manage" will cause this popup to appear:

> [!warning] Interface font
> No custom font is applied right now. Add one below.

> [!example] Available fonts
> - <span style="font-family: Inter;">Inter</span>
> - <span style="font-family: Agency FB;">Agency FB</span>
> - <span style="font-family: Algerian;">Algerian</span>
> - <span style="font-family: Arial;">Arial</span>
> - <span style="font-family: Arial Black;">Arial Black</span>
> - <span style="font-family: Arial Narrow;">Arial Narrow</span>
> - <span style="font-family: Arial Rounded MT;">Arial Rounded MT</span>
> - <span style="font-family: BIZ UDGothic;">BIZ UDGothic</span>
> - <span style="font-family: BIZ UDMincho;">BIZ UDMincho</span>
> - <span style="font-family: BIZ UDPGothic;">BIZ UDPGothic</span>
> - <span style="font-family: BIZ UDPMincho;">BIZ UDPMincho</span>
> - <span style="font-family: Bahnschrift;">Bahnschrift</span>
> - <span style="font-family: Baskerville Old Face;">Baskerville Old Face</span>
> - <span style="font-family: Bauhaus 93;">Bauhaus 93</span>
> - <span style="font-family: Bell MT;">Bell MT</span>
> - <span style="font-family: Berlin Sans FB;">Berlin Sans FB</span>
> - <span style="font-family: Bernard MT;">Bernard MT</span>
> - <span style="font-family: Blackadder ITC;">Blackadder ITC</span>
> - <span style="font-family: Bodoni 72 Oldstyle;">Bodoni 72 Oldstyle</span>
> - <span style="font-family: Bodoni 72 Smallcaps;">Bodoni 72 Smallcaps</span>
> - <span style="font-family: Bodoni MT;">Bodoni MT</span>
> - <span style="font-family: Bodoni MT Poster;">Bodoni MT Poster</span>
> - <span style="font-family: Book Antiqua;">Book Antiqua</span>
> - <span style="font-family: Bookman Old Style;">Bookman Old Style</span>
> - <span style="font-family: Bookshelf Symbol 7;">Bookshelf Symbol 7</span>
> - <span style="font-family: Bradley Hand ITC;">Bradley Hand ITC</span>
> - <span style="font-family: Britannic;">Britannic</span>
> - <span style="font-family: Broadway;">Broadway</span>
> - <span style="font-family: Brush Script MT;">Brush Script MT</span>
> - <span style="font-family: Calibri;">Calibri</span>
> - <span style="font-family: Californian FB;">Californian FB</span>
> - <span style="font-family: Calisto MT;">Calisto MT</span>
> - <span style="font-family: Cambria;">Cambria</span>
> - <span style="font-family: Cambria Math;">Cambria Math</span>
> - <span style="font-family: Candara;">Candara</span>
> - <span style="font-family: Cascadia Code;">Cascadia Code</span>
> - <span style="font-family: Cascadia Mono;">Cascadia Mono</span>
> - <span style="font-family: Castellar;">Castellar</span>
> - <span style="font-family: Centaur;">Centaur</span>
> - <span style="font-family: Century;">Century</span>
> - <span style="font-family: Century Gothic;">Century Gothic</span>
> - <span style="font-family: Century Schoolbook;">Century Schoolbook</span>
> - <span style="font-family: Chiller;">Chiller</span>
> - <span style="font-family: Colonna MT;">Colonna MT</span>
> - <span style="font-family: Comic Sans MS;">Comic Sans MS</span>
> - <span style="font-family: Constantia;">Constantia</span>
> - <span style="font-family: Cooper;">Cooper</span>
> - <span style="font-family: Copperplate Gothic;">Copperplate Gothic</span>
> - <span style="font-family: Corbel;">Corbel</span>
> - <span style="font-family: Courier;">Courier</span>
> - <span style="font-family: Courier New;">Courier New</span>
> - <span style="font-family: Curlz MT;">Curlz MT</span>
> - <span style="font-family: Dubai;">Dubai</span>
> - <span style="font-family: Ebrima;">Ebrima</span>
> - <span style="font-family: Edwardian Script ITC;">Edwardian Script ITC</span>
> - <span style="font-family: Elephant;">Elephant</span>
> - <span style="font-family: Engravers MT;">Engravers MT</span>
> - <span style="font-family: Eras ITC;">Eras ITC</span>
> - <span style="font-family: Felix Titling;">Felix Titling</span>
> - <span style="font-family: Footlight MT;">Footlight MT</span>
> - <span style="font-family: Forte;">Forte</span>
> - <span style="font-family: Franklin Gothic;">Franklin Gothic</span>
> - <span style="font-family: Franklin Gothic Medium;">Franklin Gothic Medium</span>
> - <span style="font-family: Freestyle Script;">Freestyle Script</span>
> - <span style="font-family: French Script MT;">French Script MT</span>
> - <span style="font-family: Gabriola;">Gabriola</span>
> - <span style="font-family: Gadugi;">Gadugi</span>
> - <span style="font-family: Garamond;">Garamond</span>
> - <span style="font-family: Georgia;">Georgia</span>
> - <span style="font-family: Gigi;">Gigi</span>
> - <span style="font-family: Gill Sans MT;">Gill Sans MT</span>
> - <span style="font-family: Gloucester MT;">Gloucester MT</span>
> - <span style="font-family: Goudy Old Style;">Goudy Old Style</span>
> - <span style="font-family: Goudy Stout;">Goudy Stout</span>
> - <span style="font-family: HP Simplified;">HP Simplified</span>
> - <span style="font-family: HP Simplified Hans;">HP Simplified Hans</span>
> - <span style="font-family: HP Simplified Jpan;">HP Simplified Jpan</span>
> - <span style="font-family: Haettenschweiler;">Haettenschweiler</span>
> - <span style="font-family: Harlow Solid;">Harlow Solid</span>
> - <span style="font-family: Harrington;">Harrington</span>
> - <span style="font-family: Helvetica;">Helvetica</span>
> - <span style="font-family: High Tower Text;">High Tower Text</span>
> - <span style="font-family: Impact;">Impact</span>
> - <span style="font-family: Imprint MT Shadow;">Imprint MT Shadow</span>
> - <span style="font-family: Informal Roman;">Informal Roman</span>
> - <span style="font-family: Ink Free;">Ink Free</span>
> - <span style="font-family: Inter;">Inter</span>
> - <span style="font-family: Javanese Text;">Javanese Text</span>
> - <span style="font-family: Jokerman;">Jokerman</span>
> - <span style="font-family: Juice ITC;">Juice ITC</span>
> - <span style="font-family: Kristen ITC;">Kristen ITC</span>
> - <span style="font-family: Kunstler Script;">Kunstler Script</span>
> - <span style="font-family: Leelawadee UI;">Leelawadee UI</span>
> - <span style="font-family: Lucida Bright;">Lucida Bright</span>
> - <span style="font-family: Lucida Calligraphy;">Lucida Calligraphy</span>
> - <span style="font-family: Lucida Console;">Lucida Console</span>
> - <span style="font-family: Lucida Fax;">Lucida Fax</span>
> - <span style="font-family: Lucida Handwriting;">Lucida Handwriting</span>
> - <span style="font-family: Lucida Sans;">Lucida Sans</span>
> - <span style="font-family: Lucida Sans Typewriter;">Lucida Sans Typewriter</span>
> - <span style="font-family: Lucida Sans Unicode;">Lucida Sans Unicode</span>
> - <span style="font-family: Magneto;">Magneto</span>
> - <span style="font-family: Maiandra GD;">Maiandra GD</span>
> - <span style="font-family: Malgun Gothic;">Malgun Gothic</span>
> - <span style="font-family: Marlett;">Marlett</span>
> - <span style="font-family: Matura M7 Script Capitals;">Matura M7 Script Capitals</span>
> - <span style="font-family: Meiryo;">Meiryo</span>
> - <span style="font-family: Meiryo UI;">Meiryo UI</span>
> - <span style="font-family: MS Mincho;">MS Mincho</span>
> - <span style="font-family: MS PMincho;">MS PMincho</span>
> - <span style="font-family: Microsoft Himalaya;">Microsoft Himalaya</span>
> - <span style="font-family: Microsoft JhengHei;">Microsoft JhengHei</span>
> - <span style="font-family: Microsoft JhengHei UI;">Microsoft JhengHei UI</span>
> - <span style="font-family: Microsoft New Tai Lue;">Microsoft New Tai Lue</span>
> - <span style="font-family: Microsoft PhagsPa;">Microsoft PhagsPa</span>
> - <span style="font-family: Microsoft Sans Serif;">Microsoft Sans Serif</span>
> - <span style="font-family: Microsoft Tai Le;">Microsoft Tai Le</span>
> - <span style="font-family: Microsoft YaHei;">Microsoft YaHei</span>
> - <span style="font-family: Microsoft YaHei UI;">Microsoft YaHei UI</span>
> - <span style="font-family: Microsoft Yi Baiti;">Microsoft Yu Baiti</span>
> - <span style="font-family: Modern No. 20;">Modern No. 20</span>
> - <span style="font-family: Mongolian Baiti;">Mongolian Baiti</span>
> - <span style="font-family: Monotype Corsiva;">Monotype Corsiva</span>
> - <span style="font-family: MS Reference Specialty;">MS Reference Specialty</span>
> - <span style="font-family: Myanmar Text;">Myanmar Text</span>
> - <span style="font-family: Niagara Engraved;">Niagara Engraved</span>
> - <span style="font-family: Niagara Solid;">Niagara Solid</span>
> - <span style="font-family: Nirmala Text;">Nirmala Text</span>
> - <span style="font-family: Nirmala UI;">Nirmala UI</span>
> - <span style="font-family: Noto Sans JP;">Noto Sans JP</span>
> - <span style="font-family: Noto Serif JP;">Noto Serif JP</span>
> - <span style="font-family: OCR A;">OCR A</span>
> - <span style="font-family: Old English Text MT;">Old English Text MT</span>
> - <span style="font-family: Onyx;">Onyx</span>
> - <span style="font-family: Palace Script MT;">Palace Script MT</span>
> - <span style="font-family: Palatino Linotype;">Palatino Linotype</span>
> - <span style="font-family: Times;">Papyrus</span>
> - <span style="font-family: Parchment;">Parchment</span>
> - <span style="font-family: Perpetua;">Perpetua</span>
> - <span style="font-family: Perpetua Titling ;">Perpetua Titling MT</span>
> - <span style="font-family: Poor Richard;">Poor Richard</span>
> - <span style="font-family: Pristina;">Pristina</span> 
> - <span style="font-family: Rockwell;">Rockwell</span>
> - <span style="font-family: Sans Serif Collection;">Sans Serif Collection</span>
> - <span style="font-family: Segoe Print;">Segoe Print</span>
> - <span style="font-family: Segoe Script;">Segoe Script</span>
> - <span style="font-family: Segoe UI;">Segoe UI</span>
> - <span style="font-family: Segoe UI Emoji;">Segoe UI Emoji</span>
> - <span style="font-family: Segoe UI Historic;">Segoe UI Historic</span>
> - <span style="font-family: Segoe UI Symbol;">Segoe UI Symbol</span>
> - <span style="font-family: Segoe UI Variable Display;">Segoe UI Variable Display</span>
> - <span style="font-family: Segoe UI Variable Small;">Segoe UI Variable Small</span>
> - <span style="font-family: Segoe UI Variable Text;">Segoe UI Variable Text</span>
> - <span style="font-family: Showcard Gothic;">Showcard Gothic</span>
> - <span style="font-family: Sitka Banner;">Sitka Banner</span>
> - <span style="font-family: Snap ITC;">Snap ITC</span>
> - <span style="font-family: Source Code Pro;">Source Code Pro</span>
> - <span style="font-family: Symbol;">Symbol</span>
> - <span style="font-family: Tahoma;">Tahoma</span>
> - <span style="font-family: Times;">Times</span>
> - <span style="font-family: Times New Roman;">Times New Roman</span>
> - <span style="font-family: UD Digi Kyokasho N;">UD Digi Kyokasho N</span>
> - <span style="font-family: UD Digi Kyokasho NK;">UD Digi Kyokasho NK</span>
> - <span style="font-family: UD Digi Kyokasho NP;">UD Digi Kyokasho NP</span>
> - <span style="font-family: Verdana;">Verdana</span>
> - <span style="font-family: Viner Hand ITC;">Viner Hand ITC</span>
> - <span style="font-family: Yu Gothic;">Yu Gothic</span>
> - <span style="font-family: Yu Gothic UI;">Yu Gothic UI</span>

> [!bug] Bugs
> - Inter is listed twice.
> - The scroll wheel stops scrolling after "Lucida Sans".
### Hotkeys
### Core plugins
### Community Plugins

## Core plugins


