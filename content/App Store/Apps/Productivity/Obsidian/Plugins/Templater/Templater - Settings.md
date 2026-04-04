---
icon: LiSettings
title: Settings
summary: A template for data.json properties with a 2-space indent.
tags:
  - documentation/style-settings
---
#### Template folder location
Files in this folder will be available as templates.

> [!info] In [[Templater - data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "templates_folder": ""
> ```

> [!warning] 
> Be careful when using `Esc` to close out the Settings menu, as it could actually clear the set template folder location instead.
#### Internal variables and functions
Templater provides multiples predefined variables / functions that you can use.
Check the [[Templater - Documentation (1. Introduction)|documentation]] to get a list of all the available internal variables / functions.
#### Syntax highlighting on desktop
Adds syntax highlighting for Templater commands in edit mode.

> [!info] In [[Templater - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "syntax_highlighting": true
> ```
#### Syntax highlighting on mobile
Adds syntax highlighting for Templater commands in edit mode on mobile. Use with caution: this may break live preview on mobile platforms.

> [!info] In [[Templater - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "syntax_highlighting_mobile": false
> ```
#### Automatic jump to cursor
Automatically trigger `tp.file.cursor` after inserting a template. You can also set a hotkey to manually trigger [[Templater - Documentation (2.4. tp.file)#tp.file.cursor(order? number)|tp.file.cursor]].

> [!info] In [[Templater - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "auto_jump_to_cursor": false
> ```
#### Trigger Templater on new file creation
Templater will listen for the new file creation event, and, if it matches a rule you've set, replace every command it finds in the new file's content. This makes Templater compatible with other plugins like the Daily note core plugin, Calendar plugin, Review plugin, Note refactor plugin, etc.

Make sure to set up rules under either folder templates or file regex template below.

**Warning:** This can be dangerous if you create new files with unknown / unsafe content on creation. Make sure that every new file's content is safe on creation.

> [!info] In [[Templater - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "trigger_on_file_creation": false
> ```
### Folder templates

> [!warning]
> The settings in this section only appear if [[#Trigger Templater on new file creation]] is set to `true`.

Folder templates are triggered when a new **empty** file is created in a given folder.
Templater will fill the empty file with the specified template.
The deepest match is used. A global default template would be defined on the root `/`.
#### Enable folder templates
When enabled, Templater will make use of the folder templates defined below. This option is mutually exclusive with [[#File regex templates|file regex templates]] below, so enabling one will disable the other.

> [!info] In [[Templater - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "enable_folder_templates": true,
>   "folder_templates": [
>     {
>       "folder": "",
>       "template": ""
>     }
>   ]
> ```
### File regex templates

> [!warning]
> The settings in this section only appear if [[#Trigger Templater on new file creation]] is set to `true`.

File regex templates are triggered when a new **empty** file is created that matches one of them. Templater will fill the empty file with the specified template.
The first match from the top is used, so the order of the rules is important.
Use `.*` as a final catch-all, if you need it.
#### Enable file regex templates
When enabled, Templater will make of the file regex templates defined below. This option is mutually exclusive with [[#Folder templates|folder templates]] above, so enabling one will disable the other.

> [!info] In [[Templater - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "enable_file_templates": false,
>   "file_templates": [
>     {
>       "regex": ".*",
>       "template": ""
>     }
>   ]
> ```
### Template hotkeys
Template hotkeys allows you to bind a template to a hotkey.

> [!info] In [[Templater - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "enabled_templates_hotkeys": [
>     ""
>   ]
> ```
### Startup templates
Startup templates are templates that will get executed once when Templater starts.
These templates won't output anything.
This can be useful to set up templates adding hooks to Obsidian events for example.

> [!info] In [[Templater - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "startup_templates": []
> ```
### User script functions
#### Script files folder location
All JavaScript files in this folder will be loaded as CommonJS modules, to import custom user functions.
The folder needs to be accessible from the vault.
Check the [[Templater - Documentation (1. Introduction)|documentation]] for more information.

> [!info] In [[Templater - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "user_scripts_folder": ""
> ```
#### User script intellisense
Determine how you'd like to have user script intellisense render.
Note values will not render if not in the script.
- Turn off intellisense (*0*)
- Render method description, parameters list, and return (*1*)
- Render method description and parameters list (*2*)
- Render method description and return (*3*)
- Render method description (*4*)

> [!info] In [[Templater - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "intellisense_render": 1
> ```
### User system command functions
#### Enable user system command functions
Allows you to create user functions linked to system commands.
**Warning:** It can be dangerous to execute arbitrary system commands from untrusted sources. Only run system commands that you understand, from trusted sources.

> [!info] In [[Templater - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "enable_system_commands": false
> ```
#### Timeout

> [!warning]
> This setting only appear if [[#Enable user system command functions]] is set to `true`.

Maximum timeout in seconds for a system command.

> [!info] In [[Templater - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "command_timeout": 5
> ```
#### Shell binary location

> [!warning]
> This setting only appear if [[#Enable user system command functions]] is set to `true`.

Full path to the shell binary to execute the command with.
This setting is optional and will default to the system's default shell if not specified.
You can use forward slashes ('/') as path separators on all platforms if in doubt.

> [!info] In [[Templater - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "shell_path": ""
> ```

> [!info] In [[Templater - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> This property is used to define system command user functions.
> 
> **Default:**
> ```JSON
>   "template_pairs": []
> ```
#### Donate
If you like this Plugin, consider donating to support continued development.

[GitHub Sponsors](https://github.com/sponsors/silentvoid13) | [Paypal](https://www.paypal.com/donate?hosted_button_id=U2SRGAFYXT32Q)