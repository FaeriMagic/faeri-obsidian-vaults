---
icon:
color:
background:
name: Settings/Calendar
summary: Settings listed under the "Calendar" tab.
created:
modified:
---
# Calendar
## %% ---- %%
### %% ----- %%
#### Calendar placement
Display in the left or right sidebar.
- Left sidebar (*"left-sidebar"*)
- Right sidebar (*"right-sidebar"*)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "calendarPlacement": "left-sidebar"
> ```
> **Sync mode:**
> ```JSON
>   "syncModes": {
>     "calendarPlacement": "synced"
>   }
> ```
> Disabling sync mode will set `calendarPlacement` to `"local"`. 

> [!important] My settings
> I set this to `"right-sidebar"`.
#### Confirm before creating new note
Show a confirmation dialog when creating a new daily note.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "calendarConfirmBeforeCreate": true
> ```
### Appearance
#### Locale
Controls week numbering and first day of the week.

> [!abstract]- Locales
> | Language code                     | Start of Week |
> | --------------------------------- | ------------- |
> | Default (en) (*"system-default"*) | Sun           |
> | af (*"af"*)                       | Mon           |
> | ar (*"ar"*)                       | Sat           |
> | ar-dz (*"ar-dz"*)                 | Sun           |
> | ar-kw (*"ar-kw"*)                 | Sun           |
> | ar-ly (*"ar-ly"*)                 | Sat           |
> | ar-ma (*"ar-ma"*)                 | Mon           |
> | ar-sa (*"ar-sa"*)                 | Sun           |
> | ar-tn (*"ar-tn"*)                 | Mon           |
> | az (*"az"*)                       | Mon           |
> | be (*"be"*)                       | Mon           |
> | bg (*"bg"*)                       | Mon           |
> | bm (*"bm"*)                       | Mon           |
> | bn (*"bn"*)                       | Sun           |
> | bn-bd (*"bn-bd"*)                 | Sun           |
> | bo (*"bo"*)                       | Sun           |
> | br (*"br"*)                       | Mon           |
> | bs (*"bs"*)                       | Mon           |
> | ca (*"ca"*)                       | Mon           |
> | cs (*"cs"*)                       | Mon           |
> | cv (*"cv"*)                       | Mon           |
> | cy (*"cy"*)                       | Mon           |
> | da (*"da"*)                       | Mon           |
> | de (*"de"*)                       | Mon           |
> | de-at (*"de-at"*)                 | Mon           |
> | de-ch (*"de-ch"*)                 | Mon           |
> | dv (*"dv"*)                       | Mon           |
> | el (*"el"*)                       | Mon           |
> | en (*"en"*)                       | Sun           |
> | en-au (*"en-au"*)                 | Sun           |
> | en-ca (*"en-ca"*)                 | Sun           |
> | en-gb (*"en-gb"*)                 | Mon           |
> | en-ie (*"en-ie"*)                 | Mon           |
> | en-il (*"en-il"*)                 | Sun           |
> | en-in (*"en-in"*)                 | Sun           |
> | en-nz (*"en-nz"*)                 | Mon           |
> | en-sg (*"en-sg"*)                 | Mon           |
> | eo (*"eo"*)                       | Mon           |
> | es (*"es"*)                       | Mon           |
> | es-do (*"es-do"*)                 | Mon           |
> | es-mx (*"es-mx"*)                 | Sun           |
> | es-us (*"es-us"*)                 | Sun           |
> | et (*"et"*)                       | Mon           |
> | eu (*"eu"*)                       | Mon           |
> | fa (*"fa"*)                       | Sat           |
> | fi (*"fi"*)                       | Mon           |
> | fil (*"fil"*)                     | Mon           |
> | fo (*"fo"*)                       | Mon           |
> | fr (*"fr"*)                       | Mon           |
> | fr-ca (*"fr-ca"*)                 | Sun           |
> | fr-ch (*"fr-ch"*)                 | Mon           |
> | fy (*"fy"*)                       | Mon           |
> | ga (*"ga"*)                       | Mon           |
> | gd (*"gd"*)                       | Mon           |
> | gl (*"gl"*)                       | Mon           |
> | gom-deva (*"gom-deva"*)           | Sun           |
> | gom-latn (*"gom-latn"*)           | Sun           |
> | gu (*"gu"*)                       | Sun           |
> | he (*"he"*)                       | Sun           |
> | hi (*"hi"*)                       | Sun           |
> | hr (*"hr"*)                       | Mon           |
> | hu (*"hu"*)                       | Mon           |
> | hy-am (*"hy-am"*)                 | Mon           |
> | id (*"id"*)                       | Sun           |
> | is (*"is"*)                       | Mon           |
> | it (*"it"*)                       | Mon           |
> | it-ch (*"it-ch"*)                 | Mon           |
> | ja (*"ja"*)                       | Sun           |
> | jv (*"jv"*)                       | Mon           |
> | ka (*"ka"*)                       | Mon           |
> | kk (*"kk"*)                       | Mon           |
> | km (*"km"*)                       | Mon           |
> | kn (*"kn"*)                       | Sun           |
> | ko (*"ko"*)                       | Sun           |
> | ku (*"ku"*)                       | Sat           |
> | ky (*"ky"*)                       | Mon           |
> | lb (*"lb"*)                       | Mon           |
> | lo (*"lo"*)                       | Sun           |
> | lt (*"lt"*)                       | Mon           |
> | lv (*"lv"*)                       | Mon           |
> | me (*"me"*)                       | Mon           |
> | mi (*"mi"*)                       | Mon           |
> | mk (*"mk"*)                       | Mon           |
> | ml (*"ml"*)                       | Sun           |
> | mn (*"mn"*)                       | Sun           |
> | mr (*"mr"*)                       | Sun           |
> | ms (*"ms"*)                       | Mon           |
> | ms-my (*"ms-my"*)                 | Mon           |
> | mt (*"mt"*)                       | Mon           |
> | my (*"my"*)                       | Mon           |
> | nb (*"nb"*)                       | Mon           |
> | ne (*"ne"*)                       | Sun           |
> | nl (*"nl"*)                       | Mon           |
> | nl-be (*"nl-be"*)                 | Mon           |
> | nn (*"nn"*)                       | Mon           |
> | oc-lnc (*"oc-lnc"*)               | Mon           |
> | pa-in (*"pa-in"*)                 | Sun           |
> | pl (*"pl"*)                       | Mon           |
> | pt (*"pt"*)                       | Mon           |
> | pt-br (*"pt-br"*)                 | Sun           |
> | ro (*"ro"*)                       | Mon           |
> | ru (*"ru"*)                       | Mon           |
> | sd (*"sd"*)                       | Mon           |
> | se (*"se"*)                       | Mon           |
> | si (*"si"*)                       | Sun           |
> | sk (*"sk"*)                       | Mon           |
> | sl (*"sl"*)                       | Mon           |
> | sq (*"sq"*)                       | Mon           |
> | sr (*"sr"*)                       | Mon           |
> | sr-cyrl (*"sr-cyrl"*)             | Mon           |
> | ss (*"ss"*)                       | Mon           |
> | sv (*"sv"*)                       | Mon           |
> | sw (*"sw"*)                       | Mon           |
> | ta (*"ta"*)                       | Sun           |
> | te (*"te"*)                       | Sun           |
> | tet (*"tet"*)                     | Mon           |
> | tg (*"tg"*)                       | Mon           |
> | th (*"th"*)                       | Sun           |
> | tk (*"tk"*)                       | Mon           |
> | tl-ph (*"tl-ph"*)                 | Mon           |
> | tlh (*"tlh"*)                     | Mon           |
> | tr (*"tr"*)                       | Mon           |
> | tzl (*"tzl"*)                     | Mon           |
> | tzm (*"tzm"*)                     | Sat           |
> | tzm-ltn (*"tzm-ltn"*)             | Sat           |
> | ug-cn (*"ug-cn"*)                 | Mon           |
> | uk (*"uk"*)                       | Mon           |
> | ur (*"ur"*)                       | Mon           |
> | uz (*"uz"*)                       | Mon           |
> | uz-ltn (*"uz-ltn"*)               | Mon           |
> | vi (*"vi"*)                       | Mon           |
> | x-pseudo (*"x-pseudo"*)           | Mon           |
> | yo (*"yo"*)                       | Mon           |
> | zh-cn (*"zh-cn"*)                 | Mon           |
> | zh-hk (*"zh-hk"*)                 | Sun           |
> | zh-mo (*"zh-mo"*)                 | Sun           |
> | zh-tw (*"zh-tw"*)                 | Sun           |

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "calendarLocale": "system-default"
> ```
#### Weekend days
Show weekend days with a different background color.
- None (*"none"*)
- Saturday and Sunday (*"sat-sun"*)
- Friday and Saturday (*"fri-sat"*)
- Thursday and Friday (*"thu-fri"*)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "calendarWeekendDays": "sat-sun"
> ```
#### Month name format
Full or short month name when the year is hidden.
- January (full) (*"full"*)
- Jan (short) (*"short"*)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "calendarMonthHeadingFormat": "full"
> ```

**Release history:**
- [[2.5.2]]: This setting was implemented.
#### Highlight today's date
Highlight today's date with a background color and bold text.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "calendarHighlightToday": true
> ```
#### Show feature image
Display feature images for notes in the calendar.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "calendarShowFeatureImage": true
> ```
#### Show week number
Add a column with the week number.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "calendarShowWeekNumber": false
> ```

> [!important] My settings
> I set this to `true`.
#### Show quarter
Add a quarter label in the calendar header.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "calendarShowQuarter": false
> ```

> [!important] My settings
> I set this to `true`.
### Left sidebar
#### Single pane placement
Where the calendar is shown in single pane mode.
- Below panes (*"below"*)
- Navigation pane (*"navigation"*)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "calendarLeftPlacement": "navigation"
> ```
> **Sync mode:**
> ```JSON
>   "syncModes": {
>     "calendarLeftPlacement": "synced"
>   }
> ```
> Disabling sync mode will set `calendarLeftPlacement` to `"local"`. 

> [!important] My settings
> I set this to `"below"`.
#### Weeks to show in left sidebar
Calendar in the right sidebar always displays the full month.
- 1 week (*1*)
- 2 weeks (*2*)
- 3 weeks (*3*)
- 4 weeks (*4*)
- 5 weeks (*5*)
- Full month (*6*)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> Any number set in the JSON file that is not 1-6 shall be ignored in favor of the default value, 1.
> 
> **Default:**
> ```JSON
>   "calendarWeeksToShow": 1
> ```
> **Sync mode:**
> ```JSON
>   "syncModes": {
>     "calendarWeeksToShow": "synced"
>   }
> ```
> Disabling sync mode will set `calendarWeeksToShow` to `"local"`. 
### Right sidebar
#### Show year calendar
Display year navigation and month grid in the right sidebar.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "calendarShowYearCalendar": true
> ```

**Release history:**
- [[2.5.2]]: **Yearly calendar months now longer show "(n)" suffix**, instead they show the same circles as daily notes (filled circle for notes, hollow circle for tasks). The yearly calendar month outline now always follows the active month.
### Calendar integration
#### Daily note source
Source for calendar notes.
- Daily notes (core plugin) (*"daily-notes"*)
- Notebook Navigator (*"notebook navigator"*)

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "calendarIntegrationMode": "notebook-navigator"
> ```
#### Root folder (vault profile)
Base folder for periodic notes. Date patterns can include subfolders.
Changes with the selected vault profile.

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>       "periodicNotesFolder": ""
> ```

> [!important] My settings
> I set this to `"Daily notes"`.
#### Daily notes

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "calendarCustomFilePattern": "YYYY/YYYYMMDD"
> ```
> **Template:**
> ```JSON
>   "calendarCustomFileTemplate": null
> ```

> [!important] My settings
> I set this to `"YYYY/[Quarter] Q/MMMM/[Week] WW/YYYY-MM-DD"`.
#### Weekly notes

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "calendarCustomWeekPattern": "gggg/[W]ww"
> ```
> **Template:**
> ```JSON
>   "calendarCustomWeekTemplate": null
> ```

> [!important] My settings
> I set this to `"YYYY/[Quarter] Q/MMMM/[Week] ww"`.
#### Monthly notes

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "calendarCustomMonthPattern": "YYYY/YYYYMM"
> ```
> **Template:**
> ```JSON
>   "calendarCustomMonthTemplate": null
> ```

> [!important] My settings
> I set this to `"YYYY/[Quarter] Q/MM MMMM/MM MMMM"`.
#### Quarterly notes

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "calendarCustomQuarterPattern": "YYYY/[Q]Q"
> ```
> **Template:**
> ```JSON
>   "calendarCustomQuarterTemplate": null
> ```

> [!important] My settings
> I set this to `"YYYY/[Quarter] Q"`.
#### Yearly notes

> [!info] In [[App Store/Apps/Productivity/Obsidian/Plugins/Notebook Navigator/Settings pages/Notebook Navigator - data.json|data.json]]
> **Default:**
> ```JSON
>   "calendarCustomYearPattern": "YYYY"
> ```
> **Template:**
> ```JSON
>   "calendarCustomYearTemplate": null
> ```

> [!important] My settings
> I set this to `"YYYY/YYYY"`.
