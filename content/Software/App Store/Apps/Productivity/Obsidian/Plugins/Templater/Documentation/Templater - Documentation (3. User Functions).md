---
title: 3. User Functions
---
# User Functions

You can define your own functions in Templater.

There are two types of user functions you can use:

- [[Templater - Documentation (3.1. User Scripts)|Script User Functions]]
- [[Templater - Documentation (3.2. System Commands)|System Command User Functions]]

## Invoking User Functions

You can call a user function using the usual function call syntax: `tp.user.<user_function_name>()`, where `<user_function_name>` is the function name you defined.

For example, if you defined a system command user function named `echo`, a complete command invocation would look like this:

`<% tp.user.echo() %>`

## No mobile support

Currently user functions are unavailable on Obsidian for mobile.

← Go to [[Templater - Documentation (2.10. Contributing)|previous page]] | Go to [[Templater - Documentation (3.1. User Scripts)|next page]] →