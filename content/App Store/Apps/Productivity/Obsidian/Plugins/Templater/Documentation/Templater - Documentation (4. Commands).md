---
title: 4. Commands
---
# Commands

## Command Types

[[Templater]] defines 2 types of opening tags, that defines 2 types of **commands**:

- `<%`: Interpolation command. It will output the result of the expression that's inside.
- `<%*`: [[Templater - Documentation (4.2. Execution Commands)|JavaScript execution command]]. It will execute the JavaScript code that's inside. It does not output anything by default.

The closing tag for a command is always the same: `%>`

## Command utilities

In addition to the different types of commands, you can also use command utilities. They are also declared in the opening tag of the command. All command utilities work with all command types. The available command utilities are:

- [[Templater - Documentation (4.3. Whitespace Control)|Whitespace Control]]
- [[Templater - Documentation (4.1. Dynamic Commands)|Dynamic Commands]]

← Go to [[Templater - Documentation (3.2. System Commands)|previous page]] | Go to [[Templater - Documentation (4.1. Dynamic Commands)|next page]] →