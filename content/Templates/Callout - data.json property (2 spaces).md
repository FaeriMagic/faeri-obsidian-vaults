<%* const key = await tp.system.prompt("JSON key") -%>
<%* const value = await tp.system.prompt("Default value") -%>
<%* const linkIt = await tp.system.suggester(["Yes", "No"], [true, false], false, "Link data.json?") -%>
<%* const folderName = tp.file.folder() -%>
<%* const dataJson = linkIt ? `[[${folderName} - data.json|data.json]]` : "`data.json`" -%>
> [!info] In <% dataJson %>
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "<% key %>": <% value %>
> ```
