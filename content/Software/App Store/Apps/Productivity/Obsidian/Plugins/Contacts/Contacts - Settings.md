---
tags:
  - documentation/settings
---
## Settings for "Contacts" plugin
#### Contacts folder location
Files in this folder and all subfolders will be available as contacts
> [!info] In [[Contacts - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "contactsFolder": ""
> ```
#### Contact file template
Template to be used when creating a new contact file
- Custom (*"custom"*)
- Frontmatter (YAML Metadata) (*"frontmatter"*)

> [!info] In [[Contacts - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "template": "custom"
> ```
##### Release log
- [[Contacts (1.1.0)|1.1.0]]: Add support of frontmatter contact file format
#### Default hashtag
Hashtag to be used for every contact created
> [!info] In [[Contacts - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "defaultHashtag": ""
> ```
##### Release log
- [[Contacts (1.2.0)|1.2.0]]: Support optional tag parameter for all new contacts