---
created:
icon: LiList
summary: Settings listed under the "List" tab.
title: Settings/List
tags:
  - documentation/settings
---
# List
## %% List %%
### %% ----- %%
#### List pane title
Choose where the list pane title is shown.
- Show in header (*"header"*)
- Show in list pane (*"list"*)
- Do not show (*"hidden"*)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "listPaneTitle": "header"
> ```

> [!important] My settings
> I set this to `"list"`.
#### Sort notes by
Choose how notes are sorted in the note list.
- Date edited (newest on top) (*"modified-desc"*)
- Date edited (oldest on top) (*"modified-asc"*)
- Date created (newest on top) (*"created-desc"*)
- Date created (oldest on top) (*"created-asc"*)
- Title (A on top) (*"title-asc"*)
- Title (Z on top) (*"title-desc"*)
- File name (A on top) (*filename-asc"*)
- File name (Z on top) (*filename-desc"*)
- Property (A on top) (*"property-asc"*)
- Property (Z on top) (*"property-desc"*)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   defaultFolderSort": "modified-desc"
> ```

> [!important] My settings
> I set this to `"filename-asc"`.
#### Property to sort by
Used with Property sort. Notes with this frontmatter property are listed first and sorted by the property value. Arrays are joined into one value.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "propertySortKey": ""
> ```
##### Secondary sort
Used with Property sort when notes have the same property value or no property value.
- Title (*"title"*)
- File name (*"filename"*)
- Date created (*"created"*)
- Date edited (*"modified"*)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "propertySortSecondary": "title"
> ```
#### Scroll to selected file on list changes
Scroll to the selected file when pinning notes, showing descendant notes, changing folder appearance, or running file operations.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "revealFileOnListChanges": true
> ```
#### Show quick actions
Show action buttons when hovering over files. Button controls select which actions appear.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "showQuickActions": true
>   "quickActionRevealInFolder": false
>   "quickActionAddTag": true
>   "quickActionAddToShortcuts": true
>   "quickActionPinNote": true
>   "quickActionOpenInNewTab": false
> ```

> [!important] My settings
> I set `"quickActionRevealInFolder"` to `true`.
### Pinned notes
#### Limit pinned notes to their folder
Pinned notes appear only when viewing the folder and tag where they were pinned.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "filterPinnedByFolder": false
> ```

> [!important] My settings
> I set this to `true`.
#### Show pinned group header
Display the pinned section header above pinned notes.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "showPinnedGroupHeader": true
> ```
##### Show pinned icon
Show the icon next to the pinned section header.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "showPinnedIcon": true
> ```
### Appearance
#### Default list mode
Select the default list layout. Standard shows title, date, description, and preview text. Compact shows title only. Override appearance per folder.
- Standard (*"standard"*)
- Compact (*"compact"*)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "defaultListMode": "standard"
> ```
#### Show notes from subfolders / descendants
Include notes from nested subfolders and tag descendants when viewing a folder or tag.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "includeDescendantNotes": false
> ```
> **Sync mode:**
> ```JSON
>   "syncModes": {
>     "includeDescendantNotes": "synced"
>   }
> ```
> Disabling sync mode will set `includeDescendantNotes` to `"local"`.
#### Group notes
Display headers between notes grouped by date or folder. Tag views use date groups when folder is enabled.
- Don't group (*"none"*)
- Group by date (*"date"*)
- Group by folder (*"folder"*)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "noteGrouping": "date"
> ```
#### Variable note height
Use compact height for pinned notes and notes without preview text.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "optimizeNoteHeight": true
> ```

> [!important] My settings
> I set this to `20`.
#### Compact item height
Set the height of compact list items on desktop and mobile.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> The slider ranges from 20 to 28. Values outside this range will be ignored in favor of the default vale, 28.
> 
> **Default:**
> ```JSON
>   "compactItemHeight": 28
> ```
> **Sync mode:**
> ```JSON
>   "syncModes": {
>     "compactItemHeight": "synced"
>   }
> ```
> Disabling sync mode will set `compactItemHeight` to `"local"`.
##### Scale text with compact item height
Scale compact list text when the item height is reduced.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "compactItemHeightScaleText": true
> ```
> **Sync mode:**
> ```JSON
>   "syncModes": {
>     "compactItemHeightScaleText": "synced"
>   }
> ```
> Disabling sync mode will set `compactItemHeightScaleText` to `"local"`.

> [!important] My settings
> I set this to `false`.
## Frontmatter
#### Use frontmatter metadata
Use frontmatter for note name, timestamps, icons, and colors

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "useFrontmatterMetadata": false
> ```

> [!important] My settings
> I set this to `true`.
##### Icon field
Frontmatter field for file icons. Leave empty to use icons stored in settings.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "frontmatterIconField": "icon"
> ```
##### Color field
Frontmatter field for file colors. Leave empty to use colors stored in settings.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "frontmatterColorField": "color"
> ```
##### Background field
Frontmatter field for background colors. Leave empty to use background colors stored in settings.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "frontmatterBackgroundField": "background"
> ```
##### Name fields
Comma-separated list of frontmatter fields. First non-empty value is used. Falls back to file name.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "frontmatterNameField": ""
> ```

> [!important] My settings
> I set this to `"title, name"`.
##### Created timestamp field
Frontmatter field for the created timestamp. Leave empty to only used file system date.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "frontmatterCreatedField": ""
> ```

> [!important] My settings
> I set this to `"created"`.
##### Modified timestamp field
Frontmatter field name for the modified timestamp. Leave empty to only use file system date.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "frontmatterModifiedField": ""
> ```

> [!important] My settings
> I set this to `"modified"`.
##### Timestamp format
Format used to parse timestamps in frontmatter. Leave empty to use ISO 8601 parsing.
[Moment format](https://momentjs.com/docs/#/displaying/format/)

Common formats:
YYYY-MM-DD\[T]HH:mm:ss → 2025-01-04T14:30:45
YYYY-MM-DD\[T]HH:mm:ssZ → 2025-08-07T16:53:39+02:00
DD/MM/YYYY HH:mm:ss  04/01/2025 14:30:45
MM/DD/YYYY h:mm:ss a → 01/04/2025 2:30:45 PM

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "frontmatterDateField": ""
> ```

> [!important] My settings
> I set this to `"dddd, MMMM D, YYYY, HH:mm:ssZ"`.
## Notes
### Icons
#### Show file icons
Display file icons with left-aligned spacing. Disabling removes both icons and indentation. Priority: unfinished tasks icon > custom icon > file name icon > file type icon > default icon.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "showFileIcons": true
> ```
##### Unfinished tasks icon
Display a task icon when a note has unfinished tasks.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "showFileIconUnfinishedTask": false
> ```

> [!important] My settings
> I set this to `true`.
##### Icons by file name
Assign icons to files based on text in their names.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "showFilenameMatchIcons": true
> ```
###### File name icon map
Files containing the text get the specified icon. One mapping per line: text=icon

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "fileNameIconMap": {}
> ```

> [!important] My settings
> I set `"fileNameIconMap"` to :
> ```JSON
>   "fileNameIconMap": {
>     "data.json": "MiDataObject"
>     "github": "SiGithub"
  },
> ```

**Release history:**
- [[2.5.2]]: Icons in frontmatter now support wikilink-wrapped SVG paths like **\[\[icons/folder.svg]]**.
##### Icons by file type
Assign icons to files based on their extension.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "showCategoryIcons": false
> ```

> [!important] My settings
> I set this to `true`.
###### File type icon map
Files with the extension get the specified icon. One mapping per line: extension=icon

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "fileTypeIconMap": {}
> ```

**Release history:**
- [[2.5.2]]: Icons in frontmatter now support wikilink-wrapped SVG paths like **\[\[icons/folder.svg]]**.
### Title
#### Title rows
Number of rows to display for note titles.
- 1 row (*1*)
- 2 rows (*2*)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> Values other than 1 or 2 can be set manually in the JSON file.
> 
> **Warning:** Negative numbers will cause the notes to overlap.
> 
> **Default:**
> ```JSON
>   "fileNameRows": 1
> ```

**Release history:**
- [[2.5.2]]: **Single-line file titles and preview text in list pane now truncate with ellipsis** instead of dropping the last word before the ellipsis.
### Preview text
#### Show note preview
Display preview text beneath note names.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "showFilePreview": true
> ```
##### Skip headings in preview
Skip heading lines when generating preview text.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "skipHeadingsInPreview": true
> ```
##### Skip code blocks in preview
Skip code blocks when generating preview text.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "skipCodeBlocksInPreview": true
> ```
##### Strip HTML in previews
Remove HTML tags from preview text. May affect performance on large notes.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "stripHtmlInPreview": true
> ```
##### Strip LaTeX in previews
Remov
e inline and block LaTeX expressions from preview text.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "stripLatexInPreview": true
> ```
##### Preview rows
Number of rows to display for preview text.
- 1 row (*1*)
- 2 rows (*2*)
- 3 rows (*3*)
- 4 rows (*4*)
- 5 rows (*5*)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> Values other than 1 or 2 can be set manually in the JSON file.
> **Warning:** Negative numbers and 0 will function as if the `previewRows` is set to `1`.
> 
> **Default:**
> ```JSON
>   "previewRows": 2
> ```

**Release history:**
- [[2.5.2]]: **Single-line file titles and preview text in list pane now truncate with ellipsis** instead of dropping the last word before the ellipsis.
##### Preview properties
Comma-separated list of frontmatter properties to check for preview text. The first property with text will be used.

If no preview text is found in the specified properties, the preview will be generated from the note content.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "previewProperties": []
> ```

> [!important] My settings
> I set this to `"summary"`.
### Feature image
#### Show feature image
Display a thumbnail of the first image found in the note.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "showFeatureImage": true
> ```
##### Image properties
Comma-separated list of frontmatter properties to check first.
Falls back to the first image in markdown content.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "featureImageProperties": []
> ```

> [!important] My settings
> I set this to `"app icon"`.
##### Exclude notes with properties
Comma-separated list of frontmatter properties. Notes containing any of these properties do not store feature images.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "featureImageExcludeProperties": []
> ```
##### Force square feature image
Render feature images as square thumbnails.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "forceSquareFeatureImage": true
> ```

> [!important] My settings
> I set this to `false`.
##### Download external images
Download remote images and YouTube thumbnails for feature images.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "downloadExternalFeatureImages": true
> ```
### Tags
#### Show file tags
Display clickable tags in file items.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "showFileTags": true
> ```
##### Color file tags
Apply tag colors to tag badges on file items.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "colorFileTags": true
> ```
###### Show colored tags first
Sort colored tags before other tags on file items.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "prioritizeColoredFileTags": true
> ```
##### Show full tag paths
Display complete tag hierarchy paths. When enabled: 'ai/openai', 'work/projects/2024'. When disabled: 'openai', '2024'.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "showFileTagAncestors": false
> ```
##### Show file tags in compact mode
Display tags when date, preview, and image are hidden.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "showFileTagsInCompactMode": false
> ```
### Properties
#### Show file properties
Display clickable properties in file items.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "showFileProperties": true
> ```
##### Color file properties
Apply property colors to property badges on file items.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "colorFileProperties": true
> ```
###### Show colored properties first
Sort colored properties before other properties on file items.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "prioritizeColoredFileProperties": true
> ```
##### Show properties in compact mode
Display properties when compact mode is active.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "showFilePropertiesInCompactMode": false
> ```
#### Note property
Select the note property to display in file items.
- None (*"none"*)
- Word count (*"wordCount"*)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "notePropertyType": "none"
> ```

> [!important] My settings
> I set this to `"wordCount"`.
### Date
#### Show date
Display the date below note names.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "showFileDate": true
> ```
##### When sorting by name
Date to show when notes are alphabetically sorted.
- Created date (*"created"*)
- Modified date (*"modified"*)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "alphabeticalDateMode": "modified"
> ```
### Parent folder
#### Show parent folder
Display the parent folder name for notes in subfolders or tags.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "showParentFolder": true
> ```
##### Click parent folder to go to folder
Clicking the parent folder label opens the folder in list pane.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "parentFolderClickRevealsFile": false
> ```

> [!important] My settings
> I set this to `true`.
##### Show parent folder color
Use folder colors on parent folder labels.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "showParentFolderColor": false
> ```
##### Show parent folder icon
Show folder icons next to parent folder labels.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "showParentFolderIcon": false
> ```

> [!important] My settings
> I set this to `true`.