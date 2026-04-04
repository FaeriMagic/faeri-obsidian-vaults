---
title:
aliases:
summary:
tags:
---
← Go back to \<link>
## \<Style Setting>

<%* const key = await tp.system.prompt("JSON key") -%>
> [!info] In `plugins/obsidian-style-settings/data.json`
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "<% key %>@@light": <% await tp.system.prompt("Default value (light)") %>
>   "<% key %>@@dark": <% await tp.system.prompt("Default value (dark)") %>
> ```
> If `⟲` is clicked, the JSON property will be removed from `data.json`.