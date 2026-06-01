---
title: 2.5. tp.frontmatter
---
# Frontmatter Module

This modules exposes all the frontmatter variables of a file as variables.

- Documentation
    - [[#tp.frontmatter.<frontmatter_variable_name>]]
- [[#Examples]]

## Documentation
### `tp.frontmatter.<frontmatter_variable_name>`
Retrieves the file's frontmatter variable value.

If your frontmatter variable name contains spaces, you can reference it using the bracket notation like so:

`<% tp.frontmatter["variable name with spaces"] %>`

## Examples

Let's say you have the following file:

```
---
alias: myfile
note type: seedling
---
file content
```

Then you can use the following template:

```
File's metadata alias: <% tp.frontmatter.alias %>
Note's type: <% tp.frontmatter["note type"] %>
```

For lists in frontmatter, you can use JavaScript array prototype methods to manipulate how the data is displayed.

```
---
categories:
  - book
  - movie
---
```

``<% tp.frontmatter.categories.map(prop => `  - "${prop}"`).join("\n") %>``

← Go to [[Templater - Documentation (2.4. tp.file)|previous page]] | Go to [[Templater - Documentation (2.6. tp.hooks)|next page]] →