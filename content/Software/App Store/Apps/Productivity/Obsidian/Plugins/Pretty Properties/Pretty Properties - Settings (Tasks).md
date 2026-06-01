---
created: 2025-06-22T16:17:13Z
tags:
  - documentation/settings
---
## Tasks
#### Enable task count
If enabled, the plugin would automatically count tasks checkboxes in the active note and periodically save the count numbers into the specified properties. This function only works in notes that already contain at least one of this <span style="color: gray;">[sic]</span> properties.
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "enableTasksCount": true
> ```
#### Property to count all tasks
**Requires `"enableTasksCount": true`.**
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "allTasksCount": "tasks"
> ```
#### Property to count uncompleted tasks
**Requires `"enableTasksCount": true`.**
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "uncompletedTasksCount": "tasks_uncompleted"
> ```
#### Property to count completed tasks
**Requires `"enableTasksCount": true`.**
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "completedTasksCount": "tasks_completed"
> ```

Set statuses that will be count as completed or uncompleted. Tasks with any other statuses will be ignored in all counts (including task count)
#### Uncompleted tasks statuses
**Requires `"enableTasksCount": true`.**
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "uncompletedTasksStatuses": [
>     " "
>   ]
> ```
#### Completed tasks statuses
**Requires `"enableTasksCount": true`.**
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "completedTasksStatuses": [
>     "x"
>   ]
> ```

### TaskNotes integration
You can save tasks count not only for regular tasks, but also for tasks created by [[TaskNotes]] plugin. You can count tasks, linked to the current note as project, inline TaskNotes tasks or both at once. You can also get the total count of all TaskNotes tasks and regular checkbox tasks.
#### Enable TaskNotes count
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "enableTaskNotesCount": false
> ```
#### Property to count all project TaskNotes tasks
**Requires `"enableTaskNotesCount": true`.**
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "allTNProjectTasksCount": "tn_project_tasks"
> ```
#### Property to count completed project TaskNotes tasks
**Requires `"enableTaskNotesCount": true`.**
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "completedTNProjectTasksCount": "tn_project_tasks_completed"
> ```
#### Property to count uncompleted project TaskNotes tasks
**Requires `"enableTaskNotesCount": true`.**
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "uncompletedTNProjectTasksCount": "tn_project_tasks_uncompleted"
> ```
#### Property to count all inline TaskNotes tasks
**Requires `"enableTaskNotesCount": true`.**
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "allTNInlineTasksCount": "tn_inline_tasks"
> ```
#### Property to count completed inline TaskNotes tasks
**Requires `"enableTaskNotesCount": true`.**
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "completedTNInlineTasksCount": "tn_inline_tasks_completed"
> ```
#### Property to count uncompleted inline TaskNotes tasks
**Requires `"enableTaskNotesCount": true`.**
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "uncompletedTNInlineTasksCount": "tn_inline_tasks_uncompleted"
> ```
#### Property to count all inline and project TaskNotes tasks
**Requires `"enableTaskNotesCount": true`.**
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "allTNTasksCount": "allTNTasksCount"
> ```
#### Property to count completed inline and project TaskNotes tasks
**Requires `"enableTaskNotesCount": true`.**
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "completedTNTasksCount": "tn_tasks_completed"
> ```
#### Property to count uncompleted inline and project TaskNotes tasks
**Requires `"enableTaskNotesCount": true`.**
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "uncompletedTNInlineTasksCount": "tn_inline_tasks_uncompleted"
> ```
#### Property to count all TaskNotes tasks and checkbox tasks
**Requires `"enableTaskNotesCount": true`.**
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "allTNAndCheckboxTasksCount": "tn_and_checkbox_tasks"
> ```
#### Property to count completed TaskNotes tasks and checkbox tasks
**Requires `"enableTaskNotesCount": true`.**
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "completedTNAndCheckboxTasksCount": "tn_and_checkbox_tasks_completed"
> ```
#### Property to count uncompleted TaskNotes tasks and checkbox tasks
**Requires `"enableTaskNotesCount": true`.**
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "uncompletedTNAndCheckboxTasksCount": "tn_and_checkbox_tasks_uncompleted"
> ```
---
#### Update all tasks automatically
**Requires `"enableTasksCount": true / "enableTaskNotesCount": true`.**
Cann <span style="color: gray;">[sic]</span> affect performance. If disabled, tasks counts can only be updated by command.
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "autoTasksCount": true
> ```
