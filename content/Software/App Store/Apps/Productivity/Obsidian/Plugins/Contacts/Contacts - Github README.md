---
tags:
  - documentation/github
---
# Obsidian Contacts Plugin
Introducing the [Obsidian](https://obsidian.md/) Contacts Plugin! With this plugin, you can easily organize and manage your contacts within [Obsidian](https://obsidian.md/). Simply create a note with contact information and use the plugin's features to quickly search, and sort through your contacts. Contacts plugin also helps you to remember birthdays of your contacts and keeps track of the last time you met them.

![[Obsidian Contacts plugin image.png]]
## Installation
### Automatic
#### Disable `Safe Mode` in Obsidian to be able to install community plugins:
1. Go to the `Settings` menu and select `Community Plugins`.
2. In the `Community Plugins` menu, disable `Safe Mode`.
#### Install and enable `Contacts` plugin:
1. From the `Community Plugins` menu, click on `Browse`.
2. Search for the `Contacts` plugin.
3. Click the `Install` button to add the plugin.
4. In the `Community Plugins` menu, enable the `Contacts` plugin.
### Manual
1. Download `main.js`, `manifest.json`, and `styles.css` from the latest [release](https://github.com/vbeskrovnov/obsidian-contacts/releases).
2. Create a directory `obsidian-contacts` in your Obsidian vault plugins directory: `<VaultFolder>/.obsidian/plugins/`. The final path should be `<VaultFolder>/.obsidian/plugins/obsidian-contacts`.
3. Move the downloaded files (`main.js`, `manifest.json`, and `styles.css`) into the newly created directory.(`<VaultFolder>/.obsidian/plugins/obsidian-contacts`)
4. Restart Obsidian app.
5. Enable `Contacts` pugin in the `Community plugins` settings tab.
## Usage
After enabling the plugin in the settings menu, you should see the contacts button appear in the left sidebar. Click it to open the Contacts view in the right sidebar.

The plugin reads your contacts folder, which can be changed in the settings, to render all your contacts in the right sidebar.
### Changing the Contacts Folder
1. Go to the settings.
2. Find the "Contacts" tab.
3. Change the value of "Contacts Folder Location" to an existing folder.

![[enable_plugin_and_change_folder.mov]]
### Creating a New Contact
1. Click the "Contacts" icon in the left sidebar. The Contacts view should be opened in the right sidebar.
2. Click the "Create" button in the opened Contacts view in the right sidebar.
3. Fill out the created template. See an example below:
```
/---contact---/
| key       | value                    |
| --------- | ------------------------ |
| Name      | carl                     |
| Last Name | johnson                  |
| Phone     | +1 555 555 5555          |
| Telegram  | @carlj567                |
| Linkedin  | linkedin.com/in/carlj567 |
| Birthday  | 1966-12-06               |
| Last chat | 2022-12-06               |
| Friends   | [[Bob]] [[Sue]]          |
/---contact---/
```
Feel free to add more rows, and leave existing ones empty. **Do not rename** existing keys, as they can be used by the plugin.

![[create_contact.mov]]
### Searching for Сontacts
You can use different sorting options to find the required contacts:
- Use sorting by birthday to find contacts with the nearest birthdays.
- Use sorting by last contact date to find contacts that you haven't talked to in a long time.
- Use sorting by name to find a specific contact.
![[filter_and_open.mov]]
## Contact File Formats
Any of the following formats can be used for storing contact data in Obsidian files. The default for new contacts is `Custom Format`, but this behavior can be changed in the settings using the `Contact File Template` menu item.
### (Default) Custom Format
The default format used by this plugin is the markdown table for storing contact's data.
```
/---contact---/
| key       | value                    |
| --------- | ------------------------ |
| Name      | carl                     |
| Last Name | johnson                  |
| Phone     | +1 555 555 5555          |
| Telegram  | @carlj567                |
| Linkedin  | linkedin.com/in/carlj567 |
| Birthday  | 1966-12-06               |
| Last chat | 2022-12-06               |
| Friends   | [[Bob]] [[Sue]]          |
/---contact---/
```
### Frontmatter Format
The [Frontmatter](https://help.obsidian.md/Advanced+topics/YAML+front+matter) format is used by Obsidian as metadata for files and is also supported by the [Dataview](https://github.com/blacksmithgu/obsidian-dataview) plugin, allowing you to build queries for your contacts.
> ⚠️ **Do not change or remove `type` field**. It is used to detect if the current file is a contact.

> ⚠️ **It needs to be placed at the very top of the file**. Be very careful here!
```
---
name:
  first: carl
  last: johnson
phone: +1 555 555 5555
telegram: @carlj567 
linkedin: linkedin.com/in/carlj567
birthday: 1966-12-06 
last_chat: 2022-12-06 
friends: "[[Bob]] [[Sue]]"
type: contact
---
```
