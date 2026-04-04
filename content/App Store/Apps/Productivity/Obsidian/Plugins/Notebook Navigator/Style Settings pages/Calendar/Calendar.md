---
summary: Customize the daily notes calendar.
tags:
  - style-settings/element/calendar
---
> [!important] These settings require the [[App Store/Apps/Productivity/Obsidian/Plugins/Style Settings/Style Settings|Style Settings]] plugin.

← Go back to [[2011]]
# Calendar
Customize the daily notes calendar.
### Header text color
Text color for month/year and header buttons.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect. 
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-calendar-header-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-calendar-header-color@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Weekday label text color
Text color for weekday labels (Mon, Tue, Wed...).

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect. 
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-calendar-weekday-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-calendar-weekday-color@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Week number text color
Text color for week numbers.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect. 
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-calendar-week-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-calendar-week-color@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Day text color (current month)
Text color for days within the current month.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect. 
> 
> **Note:** This settings also affects the months in the yearly calendar.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-calendar-day-in-month-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-calendar-day-in-month-color@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Day text color (outside month)
Text color for days outside the current month.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect. 
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-calendar-day-outside-month-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-calendar-day-outside-month-color@@dark": "#" 
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Weekend day background
Background color for weekend day cells.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect. 
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-calendar-weekend-bg@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-calendar-weekend-bg@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Hover background (calendar)
Background color when hovering calendar buttons and days.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect. 
> 
> **Note:** The left border of the first day of the week is also affected.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-calendar-hover-bg@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-calendar-hover-bg@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Daily note indicator
Color for the dot indicator shown on dates with a daily note.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect. 
>
>**Note:** This will also affect the unfinished task indicator.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-calendar-day-has-note-bg@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-calendar-day-has-note-bg@@dark": "#" 
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Unfinished task indicator
Color for the hollow indicator shown on dates with unfinished tasks.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect. 
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-calendar-day-has-unfinished-task-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-calendar-day-has-unfinished-task-color@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Feature image text color
Text color for dates with feature images.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect. 
> 
> **Note:** A third dot will be added to cells that contain feature images.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-calendar-day-has-feature-image-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-calendar-day-has-feature-image-color@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Feature image overlay color
Adds a color overlay to darken or tint feature images in calendar days and months. Set separate colors for light and dark mode.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-calendar-feature-image-overlay-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-calendar-feature-image-overlay-color@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.

**Release history:**
- [[2.5.2]]: The setting was implemented.
### Day text color (today)
Text color for today's date.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-calendar-day-today-color@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-calendar-day-today-color@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.
### Today highlight background
Background color for today's date highlight.

> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Only values set through the color picker are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>   "notebook-navigator-style-settings@@nn-theme-calendar-day-today-color-bg@@light": "#",
>   "notebook-navigator-style-settings@@nn-theme-calendar-day-today-color-bg@@dark": "#"
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.