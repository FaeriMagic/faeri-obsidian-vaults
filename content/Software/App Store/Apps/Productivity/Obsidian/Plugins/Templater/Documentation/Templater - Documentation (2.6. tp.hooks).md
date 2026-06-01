---
title: 2.6. tp.hooks
---
# Hooks Module

This module exposes hooks that allow you to execute code when a Templater event occurs.

- [[#Documentation]]
    - [[#tp.hooks.on_all_templates_executed(callback_function: () => any)]]
- [[#Examples]]

## Documentation

Function documentation is using a specific syntax. More information [[Templater - Documentation (1.3. Syntax)#Function documentation syntax|here]].

### [`tp.hooks.on_all_templates_executed(callback_function: () => any)`](https://silentvoid13.github.io/Templater/internal-functions/internal-modules/hooks-module.html#tphookson_all_templates_executedcallback_function---any)

Hooks into when all actively running templates have finished executing. Most of the time this will be a single template, unless you are using `tp.file.include` or `tp.file.create_new`.

Multiple invokations of this method will have their callback functions run in parallel.
##### Arguments

- `callback_function`: Callback function that will be executed when all actively running templates have finished executing.

## Examples

```
// Update frontmatter after template finishes executing
<%*
tp.hooks.on_all_templates_executed(async () => {
  const file = tp.file.find_tfile(tp.file.path(true));
  await tp.app.fileManager.processFrontMatter(file, (frontmatter) => {
    frontmatter["key"] = "value";
  });
});
%>

// Run a command from another plugin that modifies the current file, after Templater has updated the file
<%*
tp.hooks.on_all_templates_executed(() => {
  tp.app.commands.executeCommandById("obsidian-linter:lint-file");
});
-%>
```

← Go to [[Templater - Documentation (2.5. tp.frontmatter)|previous page]] | Go to [[Templater - Documentation (2.7. tp.obsidian)|next page]] →