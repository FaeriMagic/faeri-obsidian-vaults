---
summary: The data.json file for Templater.
cssclasses:
  - cascadia-mono
tags:
  - documentation/data-json
---
{
&nbsp;&nbsp;"[[Templater - Settings#Timeout|command_timeout]]": `<NUMBER-VALUE>`,
&nbsp;&nbsp;"[[Templater - Settings#Template folder location|templates_folder]]": `"<TEMPLATE-FOLDER-PATH>"`,
&nbsp;&nbsp;"[[Templater - Settings#User system command functions|templates_pairs]]": [],
&nbsp;&nbsp;"[[Templater - Settings#Trigger Templater on new file creation|trigger_on_file_creation]]": `true OR false`,
&nbsp;&nbsp;"[[Templater - Settings#Automatic jump to cursor|auto_jump_to_cursor]]": `true OR false`,
&nbsp;&nbsp;"[[Templater - Settings#Enable user system command functions|enable_system_commands]]": `true OR false`,
&nbsp;&nbsp;"[[Templater - Settings#Shell binary location|shell_path]]": `"<SHELL-PATH>"`,
&nbsp;&nbsp;"[[Templater - Settings#Script files folder location|user_scripts_folder]]": `"<FOLDER-PATH>"`,
&nbsp;&nbsp;"[[Templater - Settings#Enable folder templates|enable_folder_templates]]": `true OR false`,
&nbsp;&nbsp;"[[Templater - Settings#Folder templates|folder_templates]]": [
&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"folder": `"<FOLDER-PATH>"`,
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"template": `"<TEMPLATE-PATH>"`
&nbsp;&nbsp;&nbsp;&nbsp;}
&nbsp;&nbsp;],
&nbsp;&nbsp;"[[Templater - Settings#Enable file regex templates|enable_file_templates]]": `true OR false`,
&nbsp;&nbsp;"[[Templater - Settings#File regex templates|file_templates]]": [
&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"regex": `"<REGEX-RULE>"`,
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"template": `"<TEMPLATE-PATH>"`
&nbsp;&nbsp;&nbsp;&nbsp;}
&nbsp;&nbsp;],
&nbsp;&nbsp;"[[Templater - Settings#Syntax highlighting on desktop|syntax_highlighting]]": `true OR false`,
&nbsp;&nbsp;"[[Templater - Settings#Syntax highlighting on mobile|syntax_highlighting_mobile]]": `true OR false`,
&nbsp;&nbsp;"[[Templater - Documentation (1.4. Settings)#Template Hotkeys|enabled_templates_hotkeys]]": [
&nbsp;&nbsp;&nbsp;&nbsp;`"<TEMPLATE-PATH>"`
&nbsp;&nbsp;],
&nbsp;&nbsp;"[[Templater - Settings#Startup templates|startup_templates]]": [],
&nbsp;&nbsp;"[[Templater - Settings#User script intellisense|intellisense_render]]": `<NUMBER-VALUE: 0 to 4>`
}