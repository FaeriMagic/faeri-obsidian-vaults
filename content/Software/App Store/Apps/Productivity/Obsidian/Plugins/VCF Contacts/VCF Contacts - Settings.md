---
icon: LiSettings
summary: A template for data.json properties with a 4-space indent.
tags:
  - documentation/settings
---
### Contacts folder location
New contacts will be saved here.
If empty, contacts will be created in the root of your vault.
> [!info] In [[VCF Contacts - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "calloutFolder": ""
> ```

> [!tip] My settings
> I set this to `"People"`
### Default hashtags
New contacts are automatically tagged with this hashtags.
The hashtags are inserted at the end of the note.

**Attention:** You must include the # -sign
> [!info] In [[VCF Contacts - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "defaultHashtag": ""
> ```
## Insights processors
### UidProcessor
Generates a unique identifier for contact when missing.
> [!info] In [[VCF Contacts - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>     "UidProcessor": true
> ```
### SyncUnknownProcessor
query the configured remote contact server and allow you to decide to import
> [!info] In [[VCF Contacts - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>     "SyncUnknownProcessor": true
> ```
## Contacts server synchornization settings

> [!warning] Use synchronization carefully
> Before enabling contact server sync, ensure you have a recent backup. These features are best suited for users who have some technical experiance. <span style="color: gray;">[sic]</span>
### Synchronization
> [!info] In [[VCF Contacts - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> Requires a [[#Sync method]] to work.
> 
> **Default:**
> ```JSON
>   "syncEnabled": false
> ```
### Sync method
Choose how you want to synchronize your contacts.
- No synchronization (*"None"*)
- CardDAV address book (*"CardDAV"*)
> [!info] In [[VCF Contacts - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "syncSelected": "None"
> ```
### Address book URL
**Requires `"syncSelected": "CardDAV"`.**
URL of your CardDAV address book.
> [!info] In [[VCF Contacts - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Note:** Unsure if working properly.
> 
> **Default:**
> ```JSON
>     "addressBookUrl": ""
> ```
### Username
**Requires `"syncSelected": "CardDAV"`.**
account username.
> [!info] In [[VCF Contacts - data.json|data.json]]
> **Note:** Unsure if working properly.
### Password
**Requires `"syncSelected": "CardDAV"`.**
CardDAV account password
> [!info] In [[VCF Contacts - data.json|data.json]]
> **Note:** Unsure if working properly.
### API Key
**Requires `"syncSelected": "CardDAV"`.**
API key used instead of username and password
> [!info] In [[VCF Contacts - data.json|data.json]]
> **Note:** Unsure if working properly.