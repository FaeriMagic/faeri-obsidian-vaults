---
created:
last updated:
author: "[[Broekema, Roland|broekema41]]"
color: "#ef4444"
icon: x
platforms:
  - "[[Github]]"
programming languages:
  - "[[TypeScript]]"
  - "[[CSS]]"
  - "[[JavaScript]]"
version: 2.3.2
tags:
  - plugins/obsidian/contact
  - plugins/obsidian/vcf
  - plugins/obsidian/vcard
  - plugins/obsidian/contact-management
  - plugins/obsidian/markdown-database
obsidian stats plugin category: Note Enhancements
---
> Effortlessly manage, organize, and interact with your contacts. Import, export, and structure vCard (VCF) files seamlessly while keeping all contact details accessible in your knowledge base. Includes click-to-call, right-click copy, structured metadata, and more!

| [Obsidian Stats](https://www.obsidianstats.com/plugins/vcf-contacts) |
| :------------: |
The VCF Contacts plugin enables you to manage and organize contact information directly within your vault, using structured vCard (VCF) fields. You can import or export `.vcf` files, add avatars, and maintain detailed records for each contact-like phone numbers, emails, birthdays, addresses, and social profiles. Each contact is stored as a markdown file, making it easy to link notes and use existing Obsidian workflows. Features like click-to-call, quick copy, and avatar processing add convenience, while Quick Switcher support ensures fast navigation. Ideal for users who want to integrate personal or professional networks into their knowledge management system.

> [!abstract] Github
> > [!info]- README
> > ## Table of Contents
> > - [[VCF Contacts - Github README|VCF Contacts Plugin for Obsidian]]
> >	- [[VCF Contacts - Github README#🚀 Features at a Glance|🚀 Features at a Glance]]
> >	- [[VCF Contacts - Github README#📦 Installation|📦 Installation]]
> >		- [[VCF Contacts - Github README#🔄 Automatic via Community Plugins|🔄 Automatic via Community Plugins]]
> >		- [[VCF Contacts - Github README#🧰 Manual Installation|🧰 Manual Installation]]
> >	- [[VCF Contacts - Github README#🛠️ Getting Started|🛠️ Getting Started]]
> >		- [[VCF Contacts - Github README#📁 Set Your Contacts Folder|📁 Set Your Contacts Folder]]
> >	- [[VCF Contacts - Github README#📥 Importing vCards (.vcf)|📥 Importing vCards (.vcf)]]
> >	- [[VCF Contacts - Github README#📤 Exporting Contacts to vCard|📤 Exporting Contacts to vCard]]
> >	- [[VCF Contacts - Github README#🖼️ Adding Avatars|🖼️ Adding Avatars]]
> >	- [[VCF Contacts - Github README#📞 Quick Actions|📞 Quick Actions]]
> >	- [[VCF Contacts - Github README#➕ Create a New Contact|➕ Create a New Contact]]
> >	- [[VCF Contacts - Github README#🔎 Searching Contacts (Fast!)|🔎 Searching Contacts (Fast!)]]
> > - [[VCF Contacts - Github README#📖 Understanding the vCard (VCF) Format|📖 Understanding the vCard (VCF) Format]]
> > - [[VCF Contacts - Github README#📄 Example Contact Note (Foo Bar)|📄 Example Contact Note (Foo Bar)]]
> > - [[VCF Contacts - Github README#📌 Supported vCard Fields|📌 Supported vCard Fields]]
> >	- [[VCF Contacts - Github README#📞 Basic Contact Information|📞 Basic Contact Information]]
> >	- [[VCF Contacts - Github README#🏠 Address Fields|🏠 Address Fields]]
> >	- [[VCF Contacts - Github README#🌐 Online Presence|🌐 Online Presence]]
> >	- [[VCF Contacts - Github README#🖼️ Profile Photo|🖼️ Profile Photo]]
> >	- [[VCF Contacts - Github README#🗂️ Categorization & Metadata|🗂️ Categorization & Metadata]]
> > - [[VCF Contacts - Github README#🚀 Why This Format? Why a Plugin for Obsidian?|🚀 Why This Format? Why a Plugin for Obsidian?]]
> > - [[VCF Contacts - Github README#🙏 Acknowledgements|🙏 Acknowledgements]]
> 
> > [!info]- Release history
> > **2026**
> > - Apr 13 - [[VCF Contacts (2.3.2)|2.3.2]]: Releasing 2.3.2 patch including #68 #73 #78 #79 #83 #84

> [!abstract] Plugin
> > [!info]- Settings
> > %% Leave this line blank, otherwise Quarts will merge the contents into the header. %%
> > - [[VCF Contacts - Settings#Contacts folder location|Contacts folder location]]
> > - [[VCF Contacts - Settings#Default hashtags|Default hashtags]]
> >   
> > **Insights processors**
> > - [[VCF Contacts - Settings#UidProcessor|UidProcessor]]
> > - [[VCF Contacts - Settings#SyncUnknownProcessor|SyncUnknownProcessor]]
> >   
> > **Contacts server synchronization settings**
> > - [[VCF Contacts - Settings#Synchronization|Synchronization]]
> > - [[VCF Contacts - Settings#Sync method|Sync method]]
> > - [[VCF Contacts - Settings#Address book URL|Address book URL]] (Requires `"syncSelected": "CardDAV"`.)
> > - [[VCF Contacts - Settings#Username|Username]]  (Requires `"syncSelected": "CardDAV"`.)
> > - [[VCF Contacts - Settings#Password|Password]] (Requires `"syncSelected": "CardDAV"`.)
> > - [[VCF Contacts - Settings#API Key|API Key]] (Requires `"syncSelected": "CardDAV"`.)
> 
> > [!info]- Commands (& hotkeys)
> > | Command                                            | Hotkey |
> > | :----------------------------------------- | -----------: |
> > | [[VCF Contacts - Commands#VCF Contacts Create Contact\|VCF Contacts: Create Contact]]              | `Blank` |
> > | [[VCF Contacts - Commands#VCF Contacts Open Contacts Sidebar\|VCF Contacts: Open Contacts Sidebar]] | `Blank` |

