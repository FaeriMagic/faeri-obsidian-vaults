---
created: 2021-02-01T01:41:12Z
last updated: 2025-04-07T19:17:30Z
author: "[[Brenan, Michael|blacksmithgu]]"
icon: puzzle
platforms:
  - "[[Github]]"
programming languages:
  - "[[TypeScript]]"
version: 0.5.68
tags:
  - plugins/obsidian/dataview
  - plugins/obsidian/data-obsessed
color: "#f59e0b"
obsidian stats plugin category: Data Visualization
---
> Complex data views for-the data obsessed.

| [Obsidian Stats](https://www.obsidianstats.com/plugins/dataview) | [Official Dataview website](https://blacksmithgu.github.io/obsidian-dataview/) |
| :--------------------------------------------------------------: | ------------------------------------------------------------------------------ |
The Dataview plugin is a powerful tool that helps you visualize and navigate your Obsidian notes in a whole new way. With Dataview, you can create customizable views of your notes, filtering by tags, dates, and more. Imagine being able to see all your tasks due today, or all your notes related to a specific project, with just a glance. This plugin streamlines your note-taking experience, making it easier to find what you need, when you need it. Perfect for those who like to stay organized and focused!

> [!abstract] [Github](https://github.com/blacksmithgu/obsidian-dataview)
> ## About
> A data index and query language over Markdown files, for https://obsidian.md/.
> > [!info]- [[Dataview - Github README|README]]
> > ### Table of contents
> > - [[Dataview - Github README#Examples|Examples]]
> > - [[Dataview - Github README#Usage|Usage]]
> > 	- [[Dataview - Github README#Data|Data]]
> > 	- [[Dataview - Github README#Querying|Querying]]
> > 	- [[Dataview - Github README#JavaScript Queries Security Note|JavaScript Queries Security Note]]
> > - [[Dataview - Github README#Contributing|Contributing]]
> > 	- [[Dataview - Github README#Local Development|Local Development]]
> > 	- [[Dataview - Github README#Preparing for creating pull requests|Preparing for creating pull requests]]
> > 	- [[Dataview - Github README#Installing to Other Vaults|Installing to Other Vaults]]
> > 	- [[Dataview - Github README#Building Documentation|Building Documentation]]
> > 	- [[Dataview - Github README#Using Dataview Types In Your Own Plugin|Using Dataview Types In Your Own Plugin]]
> > - [[Dataview - Github README#Support|Support]]
> 
> > [!info]- [[App Store/Apps/Productivity/Obsidian/Plugins/Dataview/Release history/Release history.canvas|Release history]]
> > ### 2024
> > | Date   | Version                       | Author     | Commit message       |
> > | ------ | ----------------------------- | ---------- | ---------------------- |
> > | Mar 20 | [[Dataview (0.5.65)\|0.5.65]] | [[Brenan, Michael\|blacksmithgu]] | Auto-release 0.5.65 |
> > | Mar 23 | [[Dataview (0.5.66)\|0.5.66]] | [[Brenan, Michael\|blacksmithgu]] | Auto-release 0.5.66 |
> > | Jun 20 | [[Dataview (0.5.67)\|0.5.67]] | [[Brenan, Michael\|blacksmithgu]] | Auto-release 0.5.67 |
> > ### 2025
> > | Date   | Version                       | Author     | Commit message       |
> > | ------ | ----------------------------- | ---------- | ---------------------- |
> > | Mar 15 | [[Dataview (0.5.68)\|0.5.68]] | [[holroy]] | Auto-release 0.5.68   |
> > | Apr 7  | [[Dataview (0.5.70)\|0.5.70]] | [[holroy]] | Bug fix: Renders all elements in an inline field in Live Preview<br><br>Related to [#2557](https://github.com/blacksmithgu/obsidian-dataview/issues/2557), I tracked that bug down to [#2416](https://github.com/blacksmithgu/obsidian-dataview/pull/2416) which introduced code rendering on the last element within an inline field, when in _Live preview_. Now we loop on all elements, and render them all. |

> [!abstract] Plugin
> > [!info]- Settings
> > - [[Dataview - Settings#Enable inline queries|Enable inline queries]]
> > - [[Dataview - Settings#Enable JavaScript queries|Enable JavaScript queries]]
> > - [[Dataview - Settings#Enable inline JavaScript queries|Enable inline JavaScript queries]]
> > - [[Dataview - Settings#Enable inline field highlighting in reading view|Enable inline field highlighting in reading view]]
> > - [[Dataview - Settings#Enable inline field highlighting in Live Preview|Enable inline field highlighting in Live Preview]]
> >
> > **Codeblocks**
> > - [[Dataview - Settings#DataviewJS keyword|DataviewJS keyword]]
> > - [[Dataview - Settings#Inline query prefix|Inline query prefix]]
> > - [[Dataview - Settings#JavaScript inline query prefix|JavaScript inline query prefix]]
> > 
> > **View**
> > - [[Dataview - Settings#Display result count|Display result count]]
> > - [[Dataview - Settings#Warn on empty result|Warn on empty result]]
> > - [[Dataview - Settings#Render null as|Render null as]]
> > - [[Dataview - Settings#Automatic view refreshing|Automatic view refreshing]]
> > - [[Dataview - Settings#Refresh interval|Refresh interval]]
> > - [[Dataview - Settings#Date format|Date format]]
> > - [[Dataview - Settings#Date + time format|Date + time format]]
> >   
> > **Tables**
> > - [[Dataview - Settings#Primary column name|Primary column name]]
> > - [[Dataview - Settings#Grouped column name|Grouped column name]]
> >
> > **Tasks**
> > - [[Dataview - Settings#Automatic task completion tracking|Automatic task completion tracking]]
> > - [[Dataview - Settings#Use emoji shorthand for completion|Use emoji shorthand for completion]]
> > - [[Dataview - Settings#Completion field name|Completion field name]]
> > - [[Dataview - Settings#Completion date format|Completion date format]]
> > - [[Dataview - Settings#Recursive sub-task completion|Recursive sub-task completion]]
> 
> > [!info]- Commands
> > | Command                                              | Hotkey      |
> > | :--------------------------------------------------- | -----------: |
> > | [[Dataview - Commands#Dataview Drop all cached file metadata\|Dataview: Drop all cached file metadata]]    | `Blank` |
> > | [[Dataview - Commands#Dataview Force refresh all views and blocks\|Dataview: Force refresh all views and blocks]] | `Blank` |
> > | [[Dataview - Commands#Dataview Rebuild current view\|Dataview: Rebuild current view]]                                 | `Blank` |

