---
title: 1.2. Terminology
---
# Terminology

To understand how [[Templater]] works, let's define a few terms:

- A **template** is a file that contains **[[Templater - Documentation (4. Commands)|commands]]**.
- A text snippet that starts with an opening tag `<%`, ends with a closing tag `%>` is what we will call a **command**.
- A **function** is an object that we can invoke inside a **command** and that returns a value (the replacement string)

There are two types of functions you can use:

- [[Templater - Documentation (2. Internal Functions)|Internal functions]]. They are **predefined** functions that are built within the plugin. As an example, `tp.date.now` is an internal function that will return the current date.
- [[Templater - Documentation (3. User Functions)|User functions]]. Users can define their own functions. They are either [[Templater - Documentation (3.2. System Commands)|system command]] or [[Templater - Documentation (3.1. User Scripts)|user scripts]].

### Example

The following template contains 2 commands, calling 2 different internal functions:

`Yesterday: <% tp.date.yesterday("YYYY-MM-DD") %> Tomorrow: <% tp.date.tomorrow("YYYY-MM-DD") %>`

We'll see in the next part the syntax required to write some commands.

← Go to [[Templater - Documentation (1.1. Installation)|previous page]] | Go to [[Templater - Documentation (1.3. Syntax)|next page]] →