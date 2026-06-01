---
title: 2.1. tp.app
---
# App Module

This module exposes the app instance. Prefer to use this over the global app instance.

This is mostly useful when writing scripts.

Refer to the Obsidian [developer documentation](https://docs.obsidian.md/Reference/TypeScript+API/App) for more information.

## Examples

```
// Get all folders
<%
tp.app.vault.getAllLoadedFiles()
	.filter(x => x instanceof tp.obsidian.TFolder)
	.map(x => x.name)
%>

// Update frontmatter of existing file
<%*
const file = tp.file.find_tfile("path/to/file");
await tp.app.fileManager.processFrontMatter(file, (frontmatter) => {
	frontmatter["key"] = "value";
});
%>
```

← Go to [[Templater - Documentation (2. Internal Functions)|previous page]] | Go to [[Templater - Documentation (2.2. tp.config)|next page]] →