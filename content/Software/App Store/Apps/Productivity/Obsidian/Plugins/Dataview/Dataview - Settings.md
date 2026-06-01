---
tags:
  - documentation/settings
---
#### Enable inline queries
Enable or disable executing regular inline Dataview queries.
> [!info] In [[Dataview - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "enableInlineDataview": true
> ```
#### Enable JavaScript queries
Enable or disable executing DataviewJS queries.
> [!info] In [[Dataview - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "enableDataviewJs": false
> ```
#### Enable inline JavaScript queries
Enable or disable executing inline Dataview JS queries. Requires that Dataview JS queries are enabled.
> [!info] In [[Dataview - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "enableInlineDataviewJs": false
> ```
#### Enable inline field highlighting in reading view
Enables or disables visual highlighting / pretty rendering for inline fields in reading view.
> [!info] In [[Dataview - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "prettyRenderInlineFields": true
> ```
#### Enable inline field highlighting in Live Preview
Enables or disables visual highlighting / pretty rendering for inline Fields in Live Preview.
> [!info] In [[Dataview - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "prettyRenderInlineFIeldsInLivePreview": true
> ```
### Codeblocks
#### DataviewJS keyword
Keyword for DataviewJS blocks. Defaults to 'dataviewjs'. Reload required for changes to take effect.
> [!info] In [[Dataview - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "dataviewJsKeyword": "dataviewjs"
> ```
#### Inline query prefix
The prefix to inline queries (to mark them as Dataview queries). Defaults to '='.
> [!info] In [[Dataview - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "inlineQueryPrefix": "="
> ```
#### JavaScript inline query prefix
The prefix to JavaScript inliine queries (to mark them as DataviewJS queries). Defaults to '$='.
> [!info] In [[Dataview - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "inlineJsQueryPrefix": "$="
> ```
#### Code block inline queries
If enabled, inline queries will also be evaluated inside full code blocks.
> [!info] In [[Dataview - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "inlineQueriesInCodeblocks": true
> ```
### View
#### Display result count
If toggled off, the small number in the result header of TASK and TABLE queries will be hidden.
> [!info] In [[Dataview - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "showResultCount": true
> ```
#### Warn on empty result
If set, queries which return 0 results will render a warning message.
> [!info] In [[Dataview - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "warnOnEmptyResult": true
> ```
#### Render null as
What null/non-existent should show up as in tables, by default. This supports Markdown notation.
> [!info] In [[Dataview - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "renderNullAs": "\\-"
> ```
#### Automatic view refreshing
If enabled, views will automatically refresh when files in your vault change; this can negatively affect some functionality like embeds in views, so turn it off if such functionality is not working.
> [!info] In [[Dataview - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "refreshEnabled": true
> ```
#### Refresh interval
How long to wait (in milliseconds) for files to stop changing before updating views.
> [!info] In [[Dataview - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "refreshInterval": 2500
> ```
#### Date format
The default date format (see Luxon date format options).
> [!info] In [[Dataview - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "defaultDateFormat": "MMMM dd, yyyy"
> ```
#### Date + time format
The default date and time format (see LUXON date format options)
> [!info] In [[Dataview - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "defaultDateTimeFormat": "h:mm a - MMMM dd, yyyy"
> ```
### Tables
#### Primary column name
The name of the default ID column in tables; this is the auto-generated first column that links to the source file.
> [!info] In [[Dataview - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "tableIdColumnName": "File"
> ```
#### Grouped column name
The name of the default ID column in tables; when the table is on grouped data; this is the auto-generated first columnthat <span style="color: gray;">[sic]</span> links to the source file/group.
> [!info] In [[Dataview - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "tableGroupColumnName": "Group"
> ```
### Tasks
#### Automatic task completion tracking
If enabled, Dataview will automatically append tasks with their completion date when they are checked in Data views.
Example with default field name and date format: 
~~~
- [x] my task [completion:: 2022-01-01]
~~~
> [!info] In [[Dataview - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "taskCompletionTracking": false
> ```
#### Use emoji shorthand for completion
**Only available when "[[#Automatic task completion tracking|automatic task completion tracking]]" is enabled.**
If enabled, will use emoji shorthand instead of inline field formatting to fill out implicit task field "completion".
Example: - [x] my task ✅ 2022-01-01
Disable this to customize the completion date format or field name, or to use Dataview inline field formatting.
> [!info] In [[Dataview - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "taskCompletionUseEmojiShorthand": false
> ```
#### Completion field name
**Only available when "[[#Automatic task completion tracking]]" is enabled and "[[#Use emoji shorthand for completion]] is disabled.**
Text used as inline field key for task completion date when toggling a task's checkbox in a Dataview view.
> [!info] In [[Dataview - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "taskCompletionText": "completion"
> ```
#### Completion date format
**Only available when "[[#Automatic task completion tracking]]" is enabled and "[[#Use emoji shorthand for completion]] is disabled.**
Date-time format for task completion date when toggling a task's checkbox in a Dataview view (See Luxon date format options).
> [!info] In [[Dataview - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "taskCompletionDateFormat": "yyyy-MM-dd"
> ```

#### Recursive sub-task completion
If enabled, completing a task in a Dataview will automatically complete its subtasks too.
> [!info] In [[Dataview - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "recursiveSubTaskCompletion": false
> ```
