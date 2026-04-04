---
icon: LiNavigation
color:
background:
name: Settings/Navigation
summary: Settings listed under the "Navigation" tab.
created:
modified:
---
← Go back to [[2011]]
# Navigation
## %% Navigation %%
### Appearance
#### Navigation banner (vault profile)
Displays an image above the navigation pane. Changes with the selected vault profile.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>       "navigationBanner": null
> ```
##### Pin banner
Pin the navigation banner above the navigation tree.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "pinNavigationBanner": true
> ```
> **Sync mode:**
> ```JSON
>   "syncModes": {
>     "pinNavigationBanner": "synced"
>   }
> ```
> Disabling sync mode will set `pinNavigationBanner` to `"local"`.
#### Show note count
Display the number of notes next to each folder and tag.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "showNoteCount": true
> ```
##### Show current and descendant counts separately
Display note counts as "current ▾ descendants" format in folders and tags.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "separateNoteCounts": true
> ```
#### Show indent guides
Display indent guides for nested folders and tags.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "showIndentGuides": false
> ```

> [!important] My settings
> I set this to `true`.
#### Root item spacing
Spacing between root-level folders and tags.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> The slider ranges from 0 to 6, but higher values can be entered manually in the JSON file.
> 
> **Default:**
> ```JSON
>   "rootLevelSpacing": 0
> ```
#### Tree indentation
Adjust the indentation width for nested folders and tags.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> The slider ranges from 10 to 24. Any number not in that range will be ignored in favor of the default value, 16.
> 
> **Default:**
> ```JSON
>   "navIndent": 16
> ```
> **Sync mode:**
> ```JSON
>   "syncModes": {
>     "navIndent": "synced"
>   }
> ```
> Disabling sync mode will set `navIndent` to `"local"`.

> [!important] My settings
> I set this to `10`.
#### Item height
Adjust the height of folders and tags in the navigation pane.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> The slider ranges from 20 to 28. Any number not in that range will be ignored in favor of the default value, 28.
> 
> **Default:**
> ```JSON
>   "navItemHeight": 28
> ```
> **Sync mode:**
> ```JSON
>   "syncModes": {
>     "navItemHeight": "synced"
>   }
> ```
> Disabling sync mode will set `navItemHeight` to `"local"`.

> [!important] My settings
> I set this to `20`.
##### Scale text with item height
Reduce navigation text size when item height is decreased.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "navItemHeightScaleText": true
> ```
> **Sync mode:**
> ```JSON
>   "syncModes": {
>     "navItemHeightScaleText": "synced"
>   }
> ```
> Disabling sync mode will set `navItemHeightScaleText to `"local"`.

> [!important] My settings
> I set this to `false`.
### Behavior
#### Collapse items
Choose what to expand/collapse all button affects.
- All folders and tags (*"all"*)
- Folders only (*"folders-only"*)
- Tags only (*"tags-only"*)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "collapseBehavior": "all"
> ```
#### Keep selected item expanded
When collapsing, keep the currently selected folder or tag and its parents expanded.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "smartCollapse": true
> ```
#### Auto-select first note
Automatically open the first note when switching folders or tags.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "autoSelectFirstFileOnFocusChange": false
> ```
#### Expand on selection
Expand folders, tags, and properties when selected. In single pane mode, first selection expands, second selection shows files.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "autoExpandNavItems": false
> ```

> [!important] My settings
> I set this to `true`.
#### Spring-loaded folders
Expand folders and tags on hover during drag operations.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "springLoadedFolders": true
> ```
##### First expand delay
Delay before the first folder or tag expands during a drag operation (seconds).

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> The slider ranges from 0.10 to 2.00, in increments of 0.10. A more specific value can be set in the JSON file directly. The maximum delay is 3.00 seconds, even if a higher value is set. The minimum delay is 0 seconds, even if a lower value is set.
> **Default:**
> ```JSON
>   "springLoadedFoldersInitialDelay": 0.5
> ```

> [!important] My settings
> I set this to `0.25`.
##### Subsequent expand delay
Delay before expanding additional folders or tags during the same drag operation (seconds).

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> The slider ranges from 0.10 to 2.00, in increments of 0.10. A more specific value can be set in the JSON file directly. The maximum delay is 3.00 seconds, even if a higher value is set. The minimum delay is 0 seconds, even if a lower value is set.
> **Default:**
> ```JSON
>   "springLoadedFoldersSubsequentDelay": 0.5
> ```

> [!important] My settings
> I set this to `0.25`.
## Shortcuts
#### Show icons for shortcuts and recent items
Display icons for navigation sections like Shortcuts and Recent files.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "showSectionIcons": true
> ```
#### Show shortcuts
Display the shortcuts section in the navigation pane.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "showShortcuts": true
> ```
##### Shortcut badge
What to display next to shortcuts. Use 'Open shortcut 1-9' commands to open shortcuts directly.
- Position (1-9) (*"index"*)
- Item counts (*"count"*)
- None (*"none"*)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "shortcutBadgeDisplay": "index"
> ```

> [!important] My settings
> I set this to `"counts"`.
##### Disable auto-scroll for shortcuts
Don't scroll the navigation pane when clicking items in shortcuts.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "skipAutoScroll": false
> ```
#### Show recent notes
Display the recent notes section in the navigation pane.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "showRecentNotes": true
> ```
##### Hide notes
Choose which note types to hide in the recent notes section.
- None (*"none"*)
- Folder notes (*"folder-notes"*)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "hideRecentNotes": "none"
> ```
##### Pin recent notes with shortcuts
Include recent notes when shortcuts are pinned.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "pinRecentNotesWithShortcuts": false
> ```

> [!important] My settings
> I set this to `true`.
##### Recent notes count
Number of recent notes to display.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> The slider ranges from 1 to 10. Values greater than 10 can be set manually in the JSON file, however it **requires the vault cache to be rebuilt**.
> 
> **Default:**
> ```JSON
>   "recentNotesCount": 5
> ```
## Folders
### %% ----- %%
#### Show folder icons
Display icons next to folders in the navigation pane

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "showFolderIcons": true
> ```
#### Show root folder
Display the vault name as the root folder in the tree.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "showRootFolder": true
> ```

> [!important] My settings
> I set this to `false`.
#### Inherit folder colors
Child folders inherit color from parent folders.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "inheritFolderColors": false
> ```

> [!important] My settings
> I set this to `true`.
#### Folder sort order
Right-click any folder to set a different sort order for its children.
- A to Z (*"alpha-asc"*)
- Z to A (*"alpha-desc"*)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "folderSortOrder": "alpha-asc"
> ```
> **Sync mode:**
> ```JSON
>   "syncModes": {
>     "folderSortOrder": "synced"
>   }
> ```
> Disabling sync mode will set `folderSortOrder` to `"local"`.
### Folder notes
#### Enable folder notes
Folders with a matching note file are displayed as clickable links.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "enableFolderNotes": false
> ```

> [!important] My settings
> I set this to `true`.
##### Default folder note type
Folder note type created from the context menu.
- Ask before creating (*"ask"*)
- Markdown (*"markdown"*)
- Canvas (*"canvas"*)
- Base (*"base"*)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "folderNoteType": "markdown"
> ```
##### Folder note name
Name of the folder note without extension. Leave empty to use the same name as the folder. (*placeholder text:* index)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "folderNoteName": ""
> ```
##### Folder note name pattern
Name pattern for folder notes without extension. Use {{folder}} to insert the folder name.
When set, **Folder note name** does not apply. (*placeholder text:* \_{{folder}})

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "folderNoteNamePattern": ""
> ```

> [!tip] "Folder note name" vs "Folder note name pattern"
> - **Folder note name** — a static name that every folder note gets, like `index`. Every single folder note would be called `index.md` regardless of what the folder is named.
> - **Folder note name pattern** — a dynamic name using `{{folder}}` to insert the actual folder name, so each folder note gets a unique name based on its folder.
##### Folder note template
Template file for new markdown folder notes. Set template folder location in General > Templates.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "folderNoteTemplate": null
> ```
##### Enable folder note links
Folder labels are styled as links and open folder notes on click. When off, folder notes still provide name, icon and color metadata.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "enableFolderNoteLinks": true
> ```
##### Hide folder notes in list
Hide the folder note from appearing in the folder's note list.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "hideFolderNoteInList": true
> ```
##### Pin created folder notes
Automatically pin folder notes when created from the context menu.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "pinCreatedFolderNote": false
> ```
##### Open folder notes in new tab
Always open folder notes in a new tab when clicking on a folder.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "openFolderNotesInNewTab": false
> ```
## Tags
#### Show tags
Displays tags section in the navigator.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "showTags": true
> ```
##### Show tag icons
Display icons next to tags in the navigation pane.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default**
> ```JSON
>   "showTagIcons": true
> ```
##### Inherit tag colors
Child tags inherit color from parent tags.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default**
> ```JSON
>   "inheritTagColors": true
> ```
##### Tag sort order
Right-click any tag to set a different sort order for its children.
- A to Z (*"alpha-asc"*)
- Z to A (*"alpha-desc"*)
- Frequency (low to high) (*"frequency-asc"*)
- Frequency (high to low) (*"frequency-desc"*)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default**
> ```JSON
>   "tagSortOrder": "alpha-asc"
> ```
> **Sync mode:**
> ```JSON
>   "syncModes": {
>     "tagSortOrder": "synced"
>   }
> ```
> Disabling sync mode will set `tagSortOrder` to `"local"`.
##### Show tags folder
Display "Tags" as a collapsible folder.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default**
> ```JSON
>   "showAllTagsFolder": true
> ```
##### Show untagged notes
Display "Untagged" item for notes without any tags.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default**
> ```JSON
>   "showUntagged": true
> ```
##### Retain tags property after removing last tag
Keep the tags frontmatter property when all tags are removed. When disabled, the tags property is deleted from frontmatter.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default**
> ```JSON
>   "keepEmptyTagsProperty": false
> ```
## Properties
#### Show properties
Display properties section in the navigator.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default**
> ```JSON
>   "showProperties": true
> ```
##### Show property icons
Display icons next to properties in the navigation pane.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default**
> ```JSON
>   "showPropertyIcons": true
> ```
##### Inherit property colors
Property values inherit color and background from their property key.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default**
> ```JSON
>   "inheritPropertyColors": true
> ```
##### Property sort order
Right-click any property to set a different sort order for its values.
- A to Z (*"alpha-asc"*)
- Z to A (*"alpha-desc"*)
- Frequency (low to high) (*"frequency-asc"*)
- Frequency (high to low) (*"frequency-desc"*)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default**
> ```JSON
>   "propertySortOrder": "alpha-asc"
> ```
> **Sync mode:**
> ```JSON
>   "syncModes": {
>     "propertySortOrder": "synced"
>   }
> ```
> Disabling sync mode will set `propertySortOrder` to `"local"`.
##### Show properties folder
Display "Properties" as a collapsible folder.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default**
> ```JSON
>   "showAllPropertiesFolder": true
> ```