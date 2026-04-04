---
icon: MiDataObject
color:
background:
name: data.json
summary: Notebook Navigator's data.json structure.
created:
modified:
---
← Go back to [[2011]]
# data.json
{
  "[[Notebook Navigator - Settings (General)#Vault profiles|vaultProfiles]]": [
    {
      "id": "default", `<!-- <YOUR-PROFILE-NAME> does NOT affect this -->`
      "name": "Default", `<!-- <YOUR-PROFILE-NAME> does NOT affect this -->`
      "[[Notebook Navigator - Settings (General)#Show file types (vault profile)|fileVisibility]]": `"documents", "supported", OR "all"`,
      "[[Notebook Navigator - Settings (General)#Property keys (vault profile)|propertyKeys]]": [
        {
          "key": `"YOUR-PROPERTY-NAME"`,
          "showInNavigation": `true OR false`,
          "showInList": `true OR false`,
          "showInFileMenu": `true OR false`
        }
      ],
      "[[Notebook Navigator - Settings (General)#Hide folders (vault profile)|hiddenFolders]]": [],
      "[[Notebook Navigator - Settings (General)#Hide tags (vault profile)|hiddenTags]]": [],
      "[[Notebook Navigator - Settings (General)#Hide files (vault profile)|hiddenFileNames]]": [],
      "[[Notebook Navigator - Settings (General)#Hide notes with tags (vault profile)|hiddenFileTags]]": [],
      "[[Notebook Navigator - Settings (General)#Hide notes with property rules (vault profile)|hiddenFileProperties]]": [],
      "[[Notebook Navigator - Settings (Navigation)#Navigation banner (vault profile)|navigationBanner]]": `null OR <IMAGE-PATH>`,
	  "[[Notebook Navigator - Settings (Calendar)#Root folder (vault profile)|periodicNotesFolder]]": `"<PERIODIC-NOTES-FOLDER>"`,
      "shortcuts": [
        {
          "type": "folder",
          "path": "Templates"
        }
      ]
    }
  ],
  "[[Notebook Navigator - Settings (General)#Vault profile|vaultProfile]]": `"<YOUR-PROFILE-NAME>"`,
  "[[Notebook Navigator - Settings (General)#Vault title placement|vaultTitle]]": `"header" OR "navigation"`,
  "syncModes": {
    "[[Notebook Navigator - Settings (General)#Vault profile|vaultProfile]]": `"synced" OR "local"`,
    "[[Notebook Navigator - Settings (Navigation)#Folder sort order|folderSortOrder]]": `"synced" OR "local"`,
    "[[Notebook Navigator - Settings (Navigation)#Tag sort order|tagSortOrder]]": `"synced" OR "local"`,
    "[[Notebook Navigator - Settings (Navigation)#Property sort order|propertySortOrder]]": `"synced" OR "local"`,
    "[[Notebook Navigator - Settings (List)#Show notes from subfolders / descendants|includeDescendantNotes]]": `"synced" OR "local"`,
    "useFloatingToolbars": "synced",
    "[[Notebook Navigator - Settings (General)#Dual pane layout|dualPane]]": `"synced" OR "local"`,
    "[[Notebook Navigator - Settings (General)#Dual pane orientation|dualPaneOrientation]]": `"synced" OR "local"`,
    "[[Notebook Navigator - Settings (General)#Single pane animation|paneTransitionDuration]]": `"synced" OR "local"`,
    "[[Notebook Navigator - Settings (General)#Toolbar buttons|toolbarVisibility]]": `"synced" OR "local"`,
    "[[Notebook Navigator - Settings (Navigation)#Pin banner|pinNavigationBanner]]": `"synced" OR "local"`,
    "[[Notebook Navigator - Settings (Navigation)#Tree indentation|navIndent]]": `"synced" OR "local"`,
    "[[Notebook Navigator - Settings (Navigation)#Item height|navItemHeight]]": `"synced" OR "local"`,
    "[[Notebook Navigator - Settings (Navigation)#Scale text with item height|navItemHeightScaleText]]": `"synced" OR "local"`,
    "[[Notebook Navigator - Settings (Calendar)#Calendar placement|calendarPlacement]]": `"synced" OR "local"`,
    "[[Notebook Navigator - Settings (Calendar)#Single pane placement|calendarLeftPlacement]]": `"synced" OR "local"`,
    "calendarWeeksToShow": "synced",
    "[[Notebook Navigator - Settings (List)#Compact item height|compactItemHeight]]": `"synced" OR "local",
    "[[Notebook Navigator - Settings (List)#Scale text with compact item height|compactItemHeightScaleText]]": `"synced" OR "local",
    "[[Notebook Navigator - Settings (General)#Zoom level|uiScale]]": `"synced" OR "local"`
  },
  "[[Notebook Navigator - Settings (General)#Open new notes in new tab|createNewNotesInNewTab]]": `true OR false`,
  "[[Notebook Navigator - Settings (General)#Auto-reveal active note|autoRevealActiveFile]]": `true OR false`,
  "[[Notebook Navigator - Settings (General)#Use shortest path|autoRevealShortestPath]]": `true OR false`,
  "[[Notebook Navigator - Settings (General)#Ignore events from right sidebar|autoRevealIgnoreRightSidebar]]": `true OR false`,
  "[[Notebook Navigator - Settings (General)#Single pane animation|paneTransitionDuration]]": `<value>`,
  "[[Notebook Navigator - Settings (General)#Multi-select modifier|multiSelectModifier]]": `"cmdCtrl" OR "optionAlt"`,
  "[[Notebook Navigator - Settings (General)#Press Enter to open files|enterToOpenFiles]]": `true OR false`,
  "shiftEnterOpenContext": "tab",
  "cmdCtrlEnterOpenContext": "split",
  "[[Notebook Navigator - Settings (General)#Default startup view|startView]]": `"navigation" OR "files"`,
  "[[Notebook Navigator - Settings (General)#Show info buttons|showInfoButtons]]": `true OR false`,
  "[[Notebook Navigator - Settings (General)#Homepage|homepage]]": `null OR <YOUR-PAGE-NAME>`,
  "mobileHomepage": null,
  "[[Notebook Navigator - Settings (General)#Separate mobile homepage|useMobileHomepage]]": `true OR false`,
  "[[Notebook Navigator - Settings (General)#Dual pane layout|dualPane]]": `true OR false`,
  "[[Notebook Navigator - Settings (General)#Dual pane orientation|dualPaneOrientation]]": `"horizontal" OR "vertical"`,
  "[[Notebook Navigator - Settings (General)#Show tooltips|showTooltips]]": `true OR false`,
  "[[Notebook Navigator - Settings (General)#Show path|showTooltipPath]]": `true OR false`,
  "[[Notebook Navigator - Settings (General)#Background color|desktopBackground]]": `"separate" OR "primary" OR "secondary"`,
  "[[Notebook Navigator - Settings (General)#Zoom level|desktopScale]]": `<value>`,
  "mobileScale": 1,
  "useFloatingToolbars": true,
  "[[Notebook Navigator - Settings (General)#Toolbar buttons|toolbarVisibility]]": {
    "[[Notebook Navigator - Settings (General)#Navigation toolbar|navigation]]": {
      "toggleDualPane": `true OR false`,
      "expandCollapse": `true OR false`,
      "calendar": `true OR false`,
      "hiddenItems": `true OR false`,
      "rootReorder": `true OR false`,
      "newFolder": `true OR false`
    },
    "[[Notebook Navigator - Settings (General)#List toolbar|list]]": {
      "back": `true OR false`,
      "search": `true OR false`,
      "descendants": `true OR false`,
      "sort": `true OR false`,
      "appearance": `true OR false`,
      "newNote": `true OR false`
    }
  },
  "[[Notebook Navigator - Settings (General)#Interface icons|interfaceIcons]]": {
    "nav-show-single-pane": `<ICON-NAME>`
    "nav-show-dual-pane": `<ICON-NAME>`
    "nav-profile-chevron": `<ICON-NAME>`
    "nav-shortcuts": `<ICON-NAME>`
    "nav-expand-all": `<ICON-NAME>`
    "nav-collapse-all": `<ICON-NAME>`
    "nav-calendar": `<ICON-NAME>`
    "nav-hidden-items": `<ICON-NAME>`
    "nav-root-reorder": `<ICON-NAME>`
    "nav-new-folder": `<ICON-NAME>`
    "nav-recent-files": `<ICON-NAME>`
    "nav-tree-expand": `<ICON-NAME>`
    "nav-tree-collapse": `<ICON-NAME>`
    "nav-folder-open": `<ICON-NAME>`
    "nav-folder-closed": `<ICON-NAME>`
    "nav-tags": `<ICON-NAME>`
    "nav-tag": `<ICON-NAME>`
    "nav-properties": `<ICON-NAME>`
    "nav-property": `<ICON-NAME>`
    "nav-property-value": `<ICON-NAME>`
    "list-search": `<ICON-NAME>`
    "list-descendants": `<ICON-NAME>`
    "list-sort-ascending": `<ICON-NAME>`
    "list-sort-descending": `<ICON-NAME>`
    "list-appearance": `<ICON-NAME>`
    "list-new-note": `<ICON-NAME>`
    "list-pinned": `<ICON-NAME>`
    "file-unfinished-task": `<ICON-NAME>`
    "file-word-count": `<ICON-NAME>`
  },
  "[[Notebook Navigator - Settings (General)#Apply color to icons only|colorIconOnly]]": `true OR false`,
  "[[Notebook Navigator - Settings (General)#Date format|dateFormat]]": `"<DATE-FORMAT>"`,
  "[[Notebook Navigator - Settings (General)#Formatting|timeFormat]]": `"<TIME-FORMAT>"`,
  "[[Notebook Navigator - Settings (General)#Template folder location|calendarTemplateFolder]]": `"<TEMPLATE-FOLDER-NAME>"`,
  "[[Notebook Navigator - Settings (General)#Confirm before deleting|confirmBeforeDelete]]": `true OR false`,
  "[[Notebook Navigator - Settings (General)#Delete attachments when deleting files|deleteAttachments]]": `"ask", "always", OR "never"`,
  "[[Notebook Navigator - Settings (General)#Move conflicts|moveFileConflicts]]": `"ask" OR "rename"`,
  "[[Notebook Navigator - Settings (General)#Icon packs|externalIconProviders]]": {
    "[[Notebook Navigator - Settings (General)#Bootstrap Icons (version 1.13.1)|bootstrap-icons]]": `true OR false`,
    "[[Notebook Navigator - Settings (General)#Font Awesome (version 7.1.0)|fontawesome-solid]]": `true OR false`,
    "[[Notebook Navigator - Settings (General)#Material Icons (version 145)|material-icons]]": `true OR false`,
    "[[Notebook Navigator - Settings (General)#Phosphor Icons (version 2.1.2)|phosphor]]": `true OR false`,
    "[[Notebook Navigator - Settings (General)#RPG Awesome (version 0.2.0)|rpg-awesome]]": `true OR false`, 
    "[[Notebook Navigator - Settings (General)#Simple Icons (version 15.20.0)|simple-icons]]": `true OR false`
  },
  "[[Notebook Navigator - Settings (General)#Check for new version on start|checkForUpdatesOnStart]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#Pin banner|pinNavigationBanner]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#Show note count|showNoteCount]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#Show current and descendant counts separately|separateNoteCounts]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#Show indent guides|showIndentGuides]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#Root item spacing|rootLevelSpacing]]": `<NUMBER-VALUE>`,
  "[[Notebook Navigator - Settings (Navigation)#Tree indentation|navIndent]]": `<NUMBER-VALUE>`,
  "[[Notebook Navigator - Settings (Navigation)#Item height|navItemHeight]]": `<NUMBER-VALUE>`,
  "[[Notebook Navigator - Settings (Navigation)#Scale text with item height|navItemHeightScaleText]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#Collapse items|collapseBehavior]]": `"all", "folders-only", OR "tags-only"`,
  "[[Notebook Navigator - Settings (Navigation)#Keep selected item expanded|smartCollapse]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#Auto-select first note|autoSelectFirstFileOnFocusChange]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#Expand on selection|autoExpandNavItems]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#Spring-loaded folders|springLoadedFolders]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#First expand delay|springLoadedFoldersInitialDelay]]": `<NUMBER-VALUE>`,
  "[[Notebook Navigator - Settings (Navigation)#Subsequent expand delay|springLoadedFoldersSubsequentDelay]]": `<NUMBER-VALUE>`,
  "[[Notebook Navigator - Settings (Navigation)#Show icons for shortcuts and recent items|showSectionIcons]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#Show shortcuts|showShortcuts]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#Shortcut badge|shortcutBadgeDisplay]]": `"index", "count", OR "none"`,
  "[[Notebook Navigator - Settings (Navigation)#Disable auto-scroll for shortcuts|skipAutoScroll]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#Show recent notes|showRecentNotes]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#Hide notes|hideRecentNotes]]": `"none" OR "folder-notes"`,
  "[[Notebook Navigator - Settings (Navigation)#Pin recent notes with shortcuts|pinRecentNotesWithShortcuts]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#Recent notes count|recentNotesCount]]": `<NUMBER-VALUE>`,
  "[[Notebook Navigator - Settings (Navigation)#Show folder icons|showFolderIcons]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#Show root folder|showRootFolder]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#Inherit folder colors|inheritFolderColors]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#Folder sort order|folderSortOrder]]": `"alpha-asc" OR "alpha-desc"`,
  "[[Notebook Navigator - Settings (Navigation)#Folder notes|enableFolderNotes]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#Default folder note type|folderNoteType]]": `"ask", "markdown", "canvas", OR "base"`,
  "[[Notebook Navigator - Settings (Navigation)#Folder note name|folderNoteName]]": `"<DEFAULT-FOLDER-NOTE-NAME>"`,
  "[[Notebook Navigator - Settings (Navigation)#Folder note name pattern|folderNoteNamePattern]]": `"<DEFAULT-FOLDER-NOTE-NAME-PATTERN>"`,
  "[[Notebook Navigator - Settings (Navigation)#Folder note template|folderNoteTemplate]]": `null OR <TEMPLATE-FILE-PATH>`,
  "[[Notebook Navigator - Settings (Navigation)#Enable folder note links|enableFolderNoteLinks]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#Hide folder notes in list|hideFolderNoteInList]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#Pin created folder notes|pinCreatedFolderNote]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#Open folder notes in new tab|openFolderNotesInNewTab]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#Show tags|showTags]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#Show tag icons|showTagIcons]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#Show tags folder|showAllTagsFolder]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#Show untagged notes|showUntagged]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#Tag sort order|tagSortOrder]]": `"alpha-asc", "alpha-desc", "frequency-asc", OR "frequency-desc"`,
  "[[Notebook Navigator - Settings (Navigation)#Inherit tag colors|inheritTagColors]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#Retain tags property after removing last tag|keepEmptyTagsProperty]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#Show properties|showProperties]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#Show property icons|showPropertyIcons]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#Inherit property colors|inheritPropertyColors]]": `true OR false`,
  "[[Notebook Navigator - Settings (Navigation)#Property sort order|propertySortOrder]]": `"alpha-asc", "alpha-desc", "frequency-asc", OR "frequency-desc"`,
  "[[Notebook Navigator - Settings (Navigation)#Show properties folder|showAllPropertiesFolder]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Default list mode|defaultListMode]]": `"standard" OR "compact"`,
  "[[Notebook Navigator - Settings (List)#Show notes from subfolders / descendants|includeDescendantNotes]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Sort notes by|defaultFolderSort]]": `"modified-desc", "modified-asc", "created-desc", "created-asc", "title-asc", "title-desc", "filename-asc", "filename-desc", "property-asc", OR "propety-desc"`,
  "[[Notebook Navigator - Settings (List)#Property to sort by|propertySortKey]]": `"<PROPERTY-NAME>"`,
  "[[Notebook Navigator - Settings (List)#Secondary sort|propertySortSecondary]]": `"title", "filename", "created", OR "modified"`,
  "[[Notebook Navigator - Settings (List)#Scroll to selected file on list changes|revealFileOnListChanges]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#List pane title|listPaneTitle]]": `"header", "list", OR "hidden"`,
  "[[Notebook Navigator - Settings (List)#Group notes|noteGrouping]]": `"none", "date", OR "folder"`,
  "[[Notebook Navigator - Settings (List)#Limit pinned notes to their folder|filterPinnedByFolder]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Show pinned group header|showPinnedGroupHeader]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Show pinned icon|showPinnedIcon]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Variable note height|optimizeNoteHeight]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Compact item height|compactItemHeight]]": `<NUMBER-VALUE`,
  "[[Notebook Navigator - Settings (List)#Scale text with compact item height|compactItemHeightScaleText]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Show quick actions|showQuickActions]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Show quick actions|quickActionRevealInFolder]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Show quick actions|quickActionAddTag]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Show quick actions|quickActionAddToShortcuts]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Show quick actions|quickActionPinNote]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Show quick actions|quickActionOpenInNewTab]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Use frontmatter metadata|useFrontmatterMetadata]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Icon field|frontmatterIconField]]": `"<ICON-PROPERTY-NAME>"`,
  "[[Notebook Navigator - Settings (List)#Color field|frontmatterColorField]]": `"<COLOR-PROPERTY-NAME>"`,
  "[[Notebook Navigator - Settings (List)|frontmatterBackgroundField]]": `"<BACKGROUND-PROPERTY-NAME>"`,
  "[[Notebook Navigator - Settings (List)#Name fields|frontmatterNameField]]": `"<NAME-PROPERTY-NAME(S)>"`,
  "[[Notebook Navigator - Settings (List)#Created timestamp field|frontmatterCreatedField]]": `"<CREATED-PROPERTY-NAME(S)>"`,
  "[[Notebook Navigator - Settings (List)#Modified timestamp field|frontmatterModifiedField]]": `"<MODIFIED-PROPERTY-NAME(S)>"`,
  "[[Notebook Navigator - Settings (List)#Timestamp format|frontmatterDateFormat]]": `"<TIMESTAMP FORMAT>"`,
  "[[Notebook Navigator - Settings (List)#Show file icons|showFileIcons]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Unfinished tasks icon|showFileIconUnfinishedTask]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Icons by file name|showFilenameMatchIcons]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#File name icon map|fileNameIconMap]]": `{`
    `"<NAME>": "<ICON>"`
  `}`,
  "[[Notebook Navigator - Settings (List)#Icons by file type|showCategoryIcons]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#File type icon map|fileTypeIconMap]]": `{`
      `"<EXTENSION>": "<ICON>"`
  `}`,
  "[[Notebook Navigator - Settings (List)#Title rows|fileNameRows]]": `<NUMBER-VALUE>`,
  "[[Notebook Navigator - Settings (List)#Show note preview|showFilePreview]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Skip headings in preview|skipHeadingsInPreview]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Skip code blocks in preview|skipCodeBlocksInPreview]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Strip HTML in previews|stripHtmlInPreview]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Strip LaTeX in previews|stripLatexInPreview]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Preview rows|previewRows]]": `<NUMBER-VALUE>`,
  "[[Notebook Navigator - Settings (List)#Preview properties|previewProperties]]": `[`
    `"<PREVIEW-PROPERTY-NAME>"`
  `]`,
  "[[Notebook Navigator - Settings (List)#Show feature image|showFeatureImage]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Image properties|featureImageProperties]]":  `[`
    `"<IMAGE-PROPERTY-NAME>"`
  `]`,
  "[[Notebook Navigator - Settings (List)#Exclude notes with properties|featureImageExcludeProperties]]": `[`
    `"<EXCLUDED-PROPERTY-NAME>"`
  `]`,
  "[[Notebook Navigator - Settings (List)#Force square feature image|forceSquareFeatureImage]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Download external images|downloadExternalFeatureImages]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Show file tags|showFileTags]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Color file tags|colorFileTags]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Show colored tags first|prioritizeColoredFileTags]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Show full tag paths|showFileTagAncestors]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Show file tags in compact mode|showFileTagsInCompactMode]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Show file properties|showFileProperties]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Color file properties|colorFileProperties]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Show colored properties first|prioritizeColoredFileProperties]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Note property|notePropertyType]]": `"none" OR "wordCount"`,
  "[[Notebook Navigator - Settings (List)#Show properties in compact mode|showFilePropertiesInCompactMode]]": `true OR false`,
  "showPropertiesOnSeparateRows": false,
  "[[Notebook Navigator - Settings (List)#Show date|showFileDate]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#When sorting by name|alphabeticalDateMode]]": `"created" OR "modified"`,
  "[[Notebook Navigator - Settings (List)#Show parent folder|showParentFolder]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Click parent folder to go to folder|parentFolderClickRevealsFile]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Show parent folder color|showParentFolderColor]]": `true OR false`,
  "[[Notebook Navigator - Settings (List)#Show parent folder icon|showParentFolderIcon]]": `true OR false`,
  "[[Notebook Navigator - Settings (Calendar)#Calendar placement|calendarPlacement]]": `"left-sidebar" OR "right-sidebar"`,
  "[[Notebook Navigator - Settings (Calendar)#Confirm before creating new note|calendarConfirmBeforeCreate]]": `true OR false`,
  "[[Notebook Navigator - Settings (Calendar)#Locale|calendarLocale]]": `"<LOCALE>"`,
  "[[Notebook Navigator - Settings (Calendar)#Weekend days|calendarWeekendDays]]": `"none", "sat-sun", "fri-sat", OR "thu-fri"`,
  "[[Notebook Navigator - Settings (Calendar)#Month name format|calendarMonthHeadingFormat]]": `"full" OR "short"`,  
  "[[Notebook Navigator - Settings (Calendar)#Highlight today's date|calendarHighlightToday]]": `true OR false`,
  "[[Notebook Navigator - Settings (Calendar)#Show feature image|calendarShowFeatureImage]]": `true OR false`,
  "[[Notebook Navigator - Settings (Calendar)#Show week number|calendarShowWeekNumber]]": `true OR false`,
  "[[Notebook Navigator - Settings (Calendar)#Show quarter|calendarShowQuarter]]": `true OR false`,
  "[[Notebook Navigator - Settings (Calendar)#Show year calendar|calendarShowYearCalendar]]": `true OR false`,
  "[[Notebook Navigator - Settings (Calendar)#Single pane placement|calendarLeftPlacement]]": `"below" OR "navigation"`,
  "[[Notebook Navigator - Settings (Calendar)#Weeks to show in left sidebar|calendarWeeksToShow]]": `1, 2, 3, 4, 5, OR 6`,
  "[[Notebook Navigator - Settings (Calendar)#Calendar integration|calendarIntegrationMode]]": `"daily-notes" OR "notebook-navigator"`,
  "[[Notebook Navigator - Settings (Calendar)#Daily notes|calendarCustomFilePattern]]": `"<DATE-FORMAT>"`,
  "[[Notebook Navigator - Settings (Calendar)#Weekly notes|calendarCustomWeekPattern]]": `"<WEEK-FORMAT>"`,
  "[[Notebook Navigator - Settings (Calendar)#Monthly notes|calendarCustomMonthPattern]]": `"<MONTH-FORMAT"`,
  "[[Notebook Navigator - Settings (Calendar)#Quarterly notes|calendarCustomQuarterPattern]]": `"<QUARTERLY-FORMAT>"`,
  "[[Notebook Navigator - Settings (Calendar)#Yearly notes|calendarCustomYearPattern]]": `"<YEARLY-FORMAT>"`,
  "[[Notebook Navigator - Settings (Calendar)#Daily notes|calendarCustomFileTemplate]]": `null OR <TEMPLATE-PATH>`,
  "[[Notebook Navigator - Settings (Calendar)#Weekly notes|calendarCustomWeekTemplate]]": `null OR <TEMPLATE-PATH>`,
  "[[Notebook Navigator - Settings (Calendar)#Monthly notes|calendarCustomMonthTemplate]]": `null OR <TEMPLATE-PATH>`,
  "[[Notebook Navigator - Settings (Calendar)#Quarterly notes|calendarCustomQuarterTemplate]]": `null OR <TEMPLATE-PATH>`,
  "[[Notebook Navigator - Settings (Calendar)#Yearly notes|calendarCustomYearTemplate]]": `null OR <TEMPLATE-PATH>`,
  "keyboardShortcuts": {
    "pane:move-up": [
      {
        "key": "ArrowUp",
        "modifiers": []
      }
    ],
    "pane:move-down": [
      {
        "key": "ArrowDown",
        "modifiers": []
      }
    ],
    "pane:page-up": [
      {
        "key": "PageUp",
        "modifiers": []
      }
    ],
    "pane:page-down": [
      {
        "key": "PageDown",
        "modifiers": []
      }
    ],
    "pane:home": [
      {
        "key": "Home",
        "modifiers": []
      }
    ],
    "pane:end": [
      {
        "key": "End",
        "modifiers": []
      }
    ],
    "navigation:collapse-or-parent": [
      {
        "key": "ArrowLeft",
        "modifiers": []
      }
    ],
    "navigation:expand-or-focus-list": [
      {
        "key": "ArrowRight",
        "modifiers": []
      }
    ],
    "navigation:focus-list": [
      {
        "key": "Tab",
        "modifiers": []
      }
    ],
    "pane:delete-selected": [
      {
        "key": "Delete",
        "modifiers": []
      },
      {
        "key": "Backspace",
        "modifiers": []
      }
    ],
    "list:focus-navigation": [
      {
        "key": "ArrowLeft",
        "modifiers": []
      },
      {
        "key": "Tab",
        "modifiers": [
          "Shift"
        ]
      }
    ],
    "list:focus-editor": [
      {
        "key": "ArrowRight",
        "modifiers": []
      },
      {
        "key": "Tab",
        "modifiers": []
      }
    ],
    "list:select-all": [
      {
        "key": "A",
        "modifiers": [
          "Mod"
        ]
      }
    ],
    "list:extend-selection-up": [
      {
        "key": "ArrowUp",
        "modifiers": [
          "Shift"
        ]
      }
    ],
    "list:extend-selection-down": [
      {
        "key": "ArrowDown",
        "modifiers": [
          "Shift"
        ]
      }
    ],
    "list:range-to-start": [
      {
        "key": "Home",
        "modifiers": [
          "Shift"
        ]
      }
    ],
    "list:range-to-end": [
      {
        "key": "End",
        "modifiers": [
          "Shift"
        ]
      }
    ],
    "search:focus-list": [
      {
        "key": "Tab",
        "modifiers": []
      },
      {
        "key": "Enter",
        "modifiers": []
      }
    ],
    "search:focus-navigation": [
      {
        "key": "Tab",
        "modifiers": [
          "Shift"
        ]
      }
    ],
    "search:close": [
      {
        "key": "Escape",
        "modifiers": []
      }
    ]
  },
  "customVaultName": "",
  "pinnedNotes": {
    "App Store/Apps/Productivity/Obsidian/Plugins/Tabs/Tabs.md": {
      "folder": true,
      "tag": false,
      "property": false
    },
    "App Store/Apps/Productivity/Obsidian/Plugins/HTML Tabs/HTML Tabs.md": {
      "folder": true,
      "tag": false,
      "property": false
    },
    "App Store/Apps/Productivity/Obsidian/Plugins/Plugins.md": {
      "folder": true,
      "tag": false,
      "property": false
    },
    "App Store/Apps/Productivity/Obsidian/Themes/Things/Things.md": {
      "folder": true,
      "tag": false,
      "property": false
    },
    "App Store/Apps/Productivity/Obsidian/Plugins/Style Settings/Style Settings.md": {
      "folder": true,
      "tag": false,
      "property": false
    },
    "App Store/Apps/Productivity/Obsidian/Obsidian.md": {
      "folder": true,
      "tag": false,
      "property": false
    },
    "App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Notebook Navigator.md": {
      "folder": true,
      "tag": false,
      "property": false
    }
  },
  "fileIcons": {},
  "fileColors": {},
  "folderIcons": {},
  "folderColors": {},
  "folderBackgroundColors": {},
  "folderSortOverrides": {},
  "folderTreeSortOverrides": {},
  "folderAppearances": {
    "App Store/Apps/Productivity/Obsidian/Plugins/Tabs": {
      "mode": "compact"
    }
  },
  "tagIcons": {},
  "tagColors": {},
  "tagBackgroundColors": {},
  "tagSortOverrides": {},
  "tagTreeSortOverrides": {},
  "tagAppearances": {},
  "propertyIcons": {},
  "propertyColors": {},
  "propertyBackgroundColors": {},
  "propertyTreeSortOverrides": {},
  "navigationSeparators": {
    "folder:/": true,
    "section:tags": true,
    "section:properties": true
  },
  "userColors": [
    "#ffffff",
    "#d9d9d9",
    "#a6a6a6",
    "#737373",
    "#000000",
    "#404040",
    "#404040",
    "#404040",
    "#404040",
    "#404040",
    "#404040",
    "#404040",
    "#404040",
    "#404040",
    "#404040",
    "#404040",
    "#404040",
    "#404040",
    "#404040",
    "#404040"
  ],
  "lastShownVersion": "2.4.3",
  "rootFolderOrder": [],
  "rootTagOrder": [],
  "rootPropertyOrder": []
}