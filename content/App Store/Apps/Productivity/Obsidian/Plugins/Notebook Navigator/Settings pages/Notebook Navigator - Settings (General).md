---
icon: LiSettings
name: Settings/General
summary: Settings listed under the "General" tab.
---
← Go back to [[2011]]
# General
## %% General %%
### %% ----- %%
#### What's new in Notebook Navigator 2.4.3
See recent updates and improvements
#### Mastering Notebook Navigator ([video](https://www.youtube.com/watch?v=BewIlG8wLAM))
This video covers everything you need to be productive in Notebook Navigator, including hot keys, search, tags, and advanced customization.
### Vault profiles
#### Vault profile
Profiles store file type visibility, hidden files, hidden folders, hidden tags, hidden notes, shortcuts, and navigation banner. Switch profiles from the navigation pane header.

> [!note] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "vaultProfiles": [
>     {
>       "id": "default",
>       "name": "Default",
>       "fileVisibility": "supported",
>       "propertyKeys": [],
>       "hiddenFolders": [],
>       "hiddenTags": [],
>       "hiddenFileNames": [],
>       "hiddenFileTags": [],
>       "hiddenFileProperties": [],
>       "navigationBanner": null,
>       "periodicNotesFolder": "",
>       "shortcuts": []
>     }
>   ],
>   "vaultProfile": "default"
> ```
> **Sync mode:**
> ```JSON
>   "syncModes": {
>     "vaultProfile": "synced"
>   }
> ```
> Disabling sync mode will set `vaultProfile` to `"local"`.
#### Vault title placement
Choose where the vault title is shown.
- Show in header (*"header"*)
- Show in navigation pane (*"navigation"*)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "vaultTitle": "navigation"
> ```

> [!bug]
> Not sure if working.
### Filtering
#### Show file types (vault profile)
Filter which file types are shown in the navigator. File types not supported by Obsidian may open in external applications.
- Documents (.md, .canvas, .base) (*"documents"*)
- Supported (opens in Obsidian) (*"supported"*)
- All (may open externally) (*"all"*)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "fileVisibility": "supported"
> ```
#### Property keys (vault profile)
Frontmatter property keys, with per-key visibility for navigation and file list.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>       "propertyKeys": [
>         {
>           "key": "YOUR-PROPERTY-NAME",
>           "showInNavigation": true,
>           "showInList": false,
>           "showInFileMenu": false
>         },
>       ],
> ```
#### Hide files (vault profile)
Comma-separated list of filename patterns to hide. Supports \* wildcards and / paths (e.g. temp-\*, \*.png, /assets/\*).

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>       "hiddenFileNames": []
> ```

> [!important] My settings
> I set it to `"*Shortcut.lnk"`.
#### Hide folders (vault profile)
Comma-separated list of tag patterns. Name patterns: tag* (starting with), \*tag (ending with). Path patterns: /archive (root archive only), /res* (root folders starting with res), /\*/drafts (mid-segment wildcard).

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>       "hiddenFolders": []
> ```
#### Hide tags (vault profile)
Comma-separated list of tag patterns. Name patterns: tag\* (starting with), \*tag (ending with). Path patterns: archive (tag and descendants), archive/\* (descendants only), projects/\*/drafts (mid-segment wildcard).

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>       "hiddenTags": []
> ```
#### Hide notes with tags (vault profile)
Comma-separated list of tag patterns. Notes containing matching tags are hidden. Name patterns: tag\* (starting with), \*tag (ending with). Path patterns: archive (tag and descendants), archive/\* (descendants only), projects/\*/drafts (mid-segment wildcard).

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>       "hiddenFileTags": []
> ```
#### Hide notes with property rules (vault profile)
Comma-separated list of frontmatter rules. Use \`key\` or \`key=value\` entries (e.g., status=done, published=true, archived).

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>       "hiddenFileProperties": []
> ```
### Templates
#### Template folder location
Template file picker shows notes from this folder.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "calendarTemplateFolder": ""
> ```

> [!bug]
> Potentially a bug.

> [!important] My settings
> I set it to `"Templates"`.
### Behavior
#### Open new notes in new tab
When enabled, the Create new note command opens notes in a new tab. When disabled, notes replace the current tab.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "createNewNotesInNewTab": false
> ```
#### Auto-reveal active note
Automatically reveal notes when opened from Quick Switcher, links, or search.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "autoRevealActiveFile": true
> ```
##### Use shortest path
Enabled: Auto-reveal selects the nearest visible ancestor folder or tag. Disabled: Auto-reveal selects the file's actual folder and exact tag.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "autoRevealShortestPath": true
> ```
##### Ignore events from right sidebar
Do not change active note when clicking or change notes in the right sidebar.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "autoRevealIgnoreRightSidebar": true
> ```
#### Single pane animation
Transition duration when switching panes in single-pane mode (milliseconds)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "paneTransitionDuration": 150
> ```
> **Sync mode:**
> ```JSON
>   "syncModes": {
>     "paneTransitionDuration": "synced"
>   }
> ```
> Disabling sync mode will set `paneTransitionDuration` to `"local"`.
### Keyboard navigation
#### Multi-select modifier
Choose which modifier key toggles multi-selection. When Option/Alt is selected, Cmd/Ctrl click opens notes in a new tab.
- Cmd/Ctrl click (*"cmdCtrl"*)
- Option/Alt click (*"optionAlt"*)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "multiSelectModifier": "cmdCtrl"
> ```
##### Press Enter to open files
Open files only when pressing Enter during list keyboard navigation.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "enterToOpenFiles": false
> ```
### Desktop appearance
#### Dual pane layout
Show navigation pane and list pane side by side on desktop.
> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "dualPane": true
> ```
> **Sync mode:**
> ```JSON
>   "syncModes": {
>     "dualPane": "synced"
>   }
> ```
> Disabling sync mode will set `dualPane` to `"local"`.

> [!important] My settings
> I set this to `false`.
#### Dual pane orientation
Choose horizontal or vertical layout when dual pane is active.
- Horizontal split (*"horizontal"*)
- Vertical split (*"vertical"*)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "dualPaneOrientation": "horizontal"
> ```
> **Sync mode:**
> ```JSON
>   "syncModes": {
>     "dualPaneOrientation": "synced"
>   }
> ```
> Disabling sync mode will set `dualPaneOrientation` to `"local"`.
#### Background color
Choose background colors for navigation and list panes.
- Separate backgrounds (*"separate"*)
- Use list background (*"primary"*)
- Use navigation background (*"secondary"*)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "desktopBackground": "separate"
> ```
#### Show tooltips
Display hover tooltips with additional information for notes and folders.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "showTooltips": false
> ```

> [!important] My settings
> I set this to `true`.
##### Show path
Display folder path in note names in tooltips.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "showTooltipPath": true
> ```

> [!important] My settings
> I set this to `false`.
### Appearance
#### Zoom level
Controls the overall zoom level of Notebook Navigator.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "desktopScale": 1
> ```
> The slider ranges from 75 (0.75) to 150 (1.5). However, values beyond this range can be inputted in `data.json` and will be valid.
> 
> **Sync mode:**
> ```JSON
>   "syncModes": {
>      "uiScale": "synced"
>   }
> ```
> Disabling sync mode will set `uiScale` to `"local"`.
#### Default startup view
Choose which pane to display when opening Notebook Navigator. Navigation pane shows recent notes, and folder tree. List pane shows note list immediately.
- Navigation pane (*"navigation"*)
- List pane (*"files"*)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "startView": "files"
> ```
#### Homepage
Choose the file that Notebook Navigator opens automatically, such as a dashboard.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "homepage": null
> ```
##### Separate mobile homepage
Use a different homepage for mobile devices.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "useMobileHomepage": false
> ```
#### Show info buttons
Display info buttons in the search bar and calendar header.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "showInfoButtons": true
> ```
#### Toolbar buttons
Choose which buttons appear in the toolbar. Hidden buttons remain accessible via commands and menus.
##### Navigation toolbar
- Show dual panes (*"toggleDualPane"*)
- Expand all items (*"expandCollapse"*)
- Show hidden folders, tags, and notes (*"hiddenItems"*)
- Show calendar (*"calendar"*)
- Reorder navigation (*"rootReorder"*)
- New folder (*"newFolder"*)
##### List toolbar
- Show navigation (*"back"*)
- Search (*"search"*)
- Show notes from subfolders / descendants (*"descendants"*)
- Change sort order (*"sort"*)
- Change appearance (*"appearance"*)
- New note (*"newNote"*)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "toolbarVisibility": {
>     "navigation": {
>       "toggleDualPane": true,
>       "expandCOllapse": true,
>       "calendar": true,
>       "hiddenItems": true,
>       "rootReorder": true,
>       "newFolder": true
>     },
>     "list": {
>      "back": true,
>      "search": true,
>      "descendants": true,
>      "sort": true,
>      "appearance": true,
>      "newNote": true
>     }
>   }
> ```
> 
> **Sync mode:**
> ```JSON
>   "syncModes": {
>     "toolbarVisibility": "synced"
>   }
> ```
> Disabling sync mode will set `toolbarVisibility` to `"local"`.

> [!important] My settings
> I set `toggleDualPane`, `newFolder`, and `newNote` to `false`.
### Icons
#### Interface icons
Edit toolbar, folder, tag, pinned, search, and sort icons.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "interfaceIcons": {
>     "nav-show-single-pane":
>     "nav-show-dual-pane":
>     "nav-profile-chevron":
>     "nav-shortcuts":
>     "nav-expand-all":
>     "nav-collapse-all":
>     "nav-calendar":
>     "nav-hidden-items":
>     "nav-root-reorder":
>     "nav-new-folder":
>     "nav-recent-files":
>     "nav-tree-expand":
>     "nav-tree-collapse":
>     "nav-folder-open":
>     "nav-folder-closed":
>     "nav-tags":
>     "nav-tag":
>     "nav-properties":
>     "nav-property":
>     "nav-property-value":
>     "list-search":
>     "list-descendants":
>     "list-sort-ascending":
>     "list-sort-descending":
>     "list-appearance":
>     "list-new-note":
>     "list-pinned":
>     "file-unfinished-task":
>     "file-word-count":
>   }
> ```
> If a property is reset, they are removed from the JSON file.

> [!important] My settings
> I set `file-word-count` to `"LiWholeWord"`.
#### Apply color to icons only
When enabled, custom colors are applied only to icons. When disabled, colors are applied to both icons and text labels.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "colorIconOnly": false
> ```
### Formatting
#### Date format
Format for displaying dates (uses Moment format).
[Moment format](https://momentjs.com/docs/#/displaying/format/)

Common formats:
MMM D, YYYY = May 25, 2022
DD/MM/YYYY = 25/05/2022
YYYY-MM-DD = 2022-05-25

Tokens:
YYYY/YY = year
MMMM/MMM/MM = month
DD/D = day
dddd/ddd = weekday

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "dateFormat": "MMM D, YYYY"
> ```

> [!important] My settings
> I set this to `"dddd, MMM D, YYYY"`.
#### Time format
Format for displaying times (using Moment format).
[Moment format](https://momentjs.com/docs/#/displaying/format/)

Common formats:
h:mm a = 2:30 PM (12-hour)
HH:mm = 14:30 (24-hour)
h:mm:ss a = 2:30:45 PM
HH:mm:ss = 14:30:45

Tokens:
HH/H = 24-hour
hh/h = 12-hour
mm = minutes
ss = seconds
a = AM/PM

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "timeFormat": "h:mm a"
> ```

> [!important] My settings
> I set this to `"h:mm:ss a"`.
## Files
### Confirm before deleting
Show confirmation dialog when deleting notes or folders

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "confirmBeforeDelete": true
> ```
### Delete attachments when deleting files
Automatically remove attachments linked to the deleted file if they're not used elsewhere
- Ask each time (*"ask"*)
- Always (*"always"*)
- Never (*"never"*)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "deleteAttachments": "ask"
> ```
### Move conflicts
When moving a file into a folder where a file with the same name already exists. Ask each time (rename, overwrite, cancel) or always rename.
- Ask each time (*"ask"*)
- Always rename (*"rename"*)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "moveFileConflicts": "ask"
> ```
## Icon packs
#### Bootstrap Icons (version 1.13.1)
https://icons.getbootstrap.com/
#### Font Awesome (version 7.1.0)
https://fontawesome.com/
#### Material Icons (version 145)
https://fonts.google.com/icons
#### Phosphor Icons (version 2.1.2)
https://phosphoricons.com/
#### RPG Awesome (version 0.2.0)
https://nagoshiashumari.github.io/Rpg-Awesome/
#### Simple Icons (version 15.20.0)
https://simpleicons.org/

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> The icons' JSON properties are only added upon being downloaded.
> 
> **Default:**
> ```JSON
>   "externalIconProviders": {
>     "bootstrap-icons": 
>     "fontawesome-solid":
>     "material-icons":
>     "phosphor":
>     "rpg-awesome":
>     "simple-icons":
>   }
> ```
> If an icon pack is removed, the JSON property is set to `false` rather than being removed.

Downloaded icon packs sync installation state across devices. Icon packs stay in the local database on each device; sync only tracks whether to download or remove them. Icon packs downloaded from the Notebook Navigator repository (https:github.com/johansan/notebook-navigator/tree/main/icon-assets).
## Advanced
#### Check for new version on start
Checks for new plugin releases and shows a notification when an update is available. Checks occur at most once per day.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "checkForUpdatesOnStart": true
> ```
#### Reset pane separator position
Reset the draggable separator between navigation pane and list pane to default position.
#### Reset all settings
Reset all Notebook Navigator settings to default values.

Upon clicking "Reset all settings", you will receive this popup:

> [!warning] Reset all settings?
> This will reset all Notebook Navigator settings to their default values. This cannot be undone.
#### Clean up metadata
Removes orphaned metadata left behind when files, folders, or tags are deleted, moved, or renamed outside of Obsidian. This only affects the Notebook Navigator settings file.
#### Rebuild cache
Use this if you experience missing tags, incorrect previews or missing feature images. This can happen after sync conflicts or unexpected closures.