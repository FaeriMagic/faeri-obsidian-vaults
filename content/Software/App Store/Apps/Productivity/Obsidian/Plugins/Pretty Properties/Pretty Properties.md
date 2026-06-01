---
created: 2025-06-22T16:17:13Z
last updated: 2026-02-28T12:42:25Z
author: "[[Fedotova, Anastasia|Anareaty]]"
icon: puzzle
platforms:
  - "[[Github]]"
programming languages:
  - "[[TypeScript]]"
  - "[[CSS]]"
  - "[[JavaScript]]"
status: Installed
version: 1.10.17
tags:
  - plugins/obsidian/property
  - plugins/obsidian/metadata
  - plugins/obsidian/color-coding
  - plugins/obsidian/cover-image
  - plugins/obsidian/progress-bar
color: "#f59e0b"
obsidian stats plugin category: Customization & UI
---
> Makes note properties look more fun: adds side image, banners, list property colors and allows to hide specific properties.

| [Obsidian Stats](https://www.obsidianstats.com/plugins/pretty-properties) |
| :------------: |
The Pretty properties plugin transforms how frontmatter metadata appears by adding visual flair and interactivity. You can embed cover images, banners, and icons directly into the metadata area, with customizable shapes, placements, and sizes. It supports colorful styling for list values, tags, text fields, and even dates-allowing you to visually distinguish metadata at a glance. It also offers progress bars for number fields, relative date coloring, and clickable property values for instant search. For power users, it integrates with Bases (still experimental) and TaskNotes, syncing task counts into note properties. The plugin also includes several quality-of-life touches, like the ability to hide properties or apply custom CSS to pill elements.

> [!abstract] [Github](https://github.com/anareaty/pretty-properties)
> > [!info]- README
> > - [[Pretty Properties - Github README#Features|Features]]
> >	- [[Pretty Properties - Github README#Cover image|Cover image]]
> >	- [[Pretty Properties - Github README#Banner|Banner]]
> >	- [[Pretty Properties - Github README#Icon|Icon]]
> >	- [[Pretty Properties - Github README#Hide properties|Hide properties]]
> >	- [[Pretty Properties - Github README#Colorful list properties|Colorful list properties]]
> >	- [[Pretty Properties - Github README#Colorful tags|Colorful tags]]
> >	- [[Pretty Properties - Github README#Colorful text properties|Colorful text properties]]
> >	- [[Pretty Properties - Github README#Date colors|Date colors]]
> >	- [[Pretty Properties - Github README#Custom date formats|Custom date formats]]
> >	- [[Pretty Properties - Github README#Progress bars|Progress bars]]
> >	- [[Pretty Properties - Github README#Sync tasks count to properties|Sync tasks count to properties]]
> >	- [[Pretty Properties - Github README#TaskNotes integration|TaskNotes integration]]
> >	- [[Pretty Properties - Github README#Property search|Property search]]
> > - [[Pretty Properties - Github README#Bases support|Bases support]]
> > - [[Pretty Properties - Github README#Installation|Installation]]
> > - [[Pretty Properties - Github README#Acknowledgments|Acknowledgments]]
> 
> > [!info]- [[App Store/Apps/Productivity/Obsidian/Plugins/Pretty Properties/Release history/Release history.canvas|Release history]]
> > ### 2006
> > | Date    | Release | Commit message |
> > | ------- | -------- | ------------------- |
> > | Feb 28 | [[Pretty Properties (1.10.17)\|1.10.17]] | 1.10.17                  |

> [!abstract] Plugin
> > [!info] Settings
> > >[!example]- Banners
> > > - [[Pretty Properties - Settings (Banners)#Enable banners|Enable banners]]
> > > 
> > > > [!attention]- Requires `"enableBanner": true`
> > > > - [[Pretty Properties - Settings (Banners)#Banner property|Banner property]]
> > > > - [[Pretty Properties - Settings (Banners)#Banner position property|Banner position property]]
> > > > - [[Pretty Properties - Settings (Banners)#Folder with images for banners|Folder with images for banners]]
> > > > - [[Pretty Properties - Settings (Banners)#Banner fading|Banner fading]]
> > > > - [[Pretty Properties - Settings (Banners)#Show banners in page previews|Show banners in page previews]]
> > > > - [[Pretty Properties - Settings (Banners)#Banner height|Banner height]]
> > > > - [[Pretty Properties - Settings (Banners)#Banner height on mobile|Banner height on mobile]]
> > > > - [[Pretty Properties - Settings (Banners)#Banner height in page preview|Banner height in page preview]]
> > > > - [[Pretty Properties - Settings (Banners)#Gap after banner|Gap after banner]]
> > > > - [[Pretty Properties - Settings (Banners)#Gap after banner on mobile|Gap after banner on mobile]]
> > > > - [[Pretty Properties - Settings (Banners)#Gap after banner with icon|Gap after banner with icon]]
> > > > - [[Pretty Properties - Settings (Banners)#Gap after banner with icon on mobile|Gap after banner with icon on mobile]]
> > 
> > > [!example]- Icons
> > > - [[Pretty Properties - Settings (Icons)#Enable icons|Enable icons]]
> > >   
> > > > [!attention]- Requires `"enableIcon": true`
> > > > - [[Pretty Properties - Settings (Icons)#Place icon in inline title|Place icon in inline title]]
> > > > - [[Pretty Properties - Settings (Icons)#Icon property|Icon property]]
> > > > - [[Pretty Properties - Settings (Icons)#Icons folder|Icons folder]]
> > > > - [[Pretty Properties - Settings (Icons)#Show icons in page previews|Show icons in page previews]]
> > > > - [[Pretty Properties - Settings (Icons)#Icon size|Icon size]]
> > > > - [[Pretty Properties - Settings (Icons)#Icon size on mobile|Icon size on mobile]]
> > > > - [[Pretty Properties - Settings (Icons)#Icon size in page preview|Icon size in page preview]]
> > > > - [[Pretty Properties - Settings (Icons)#Icon size in inline title|Icon size in inline title]]
> > > > - [[Pretty Properties - Settings (Icons)#Text and emoji icons in inline title match title size|Text and emoji icons in inline title match title size]]
> > > > - [[Pretty Properties - Settings (Icons)#Icon color for the light theme|Icon color for the light theme]]
> > > > - [[Pretty Properties - Settings (Icons)#Icon color for the dark theme|Icon color for the dark theme]]
> > > > - [[Pretty Properties - Settings (Icons)#Icon background|Icon background]]
> > > > - [[Pretty Properties - Settings (Icons)#Icon left margin|Icon left margin]]
> > > > - [[Pretty Properties - Settings (Icons)#Icon top margin without banner|Icon top margin without banner]]
> > > > - [[Pretty Properties - Settings (Icons)#Icon top margin with banner|Icon top margin with banner]]
> > > > - [[Pretty Properties - Settings (Icons)#Icon top margin with banner on mobile|Icon top margin with banner on mobile]]
> > > > - [[Pretty Properties - Settings (Icons)#Gap after icon without banner|Gap after icon without banner]]
> > 
> > > [!example]- Covers
> > > - [[Pretty Properties - Settings (Covers)#Enable covers|Enable covers]]
> > >   
> > > > [!attention]- Requires `"enableCover": true"`
> > > > - [[Pretty Properties - Settings (Covers)#Cover property|Cover property]]
> > > > - [[Pretty Properties - Settings (Covers)#Folder with images for covers|Folder with images for covers]]
> > > > - [[Pretty Properties - Settings (Covers)#Add extra cover property|Add extra cover property]]
> > > > - [[Pretty Properties - Settings (Covers)#Show covers in page previews|Show covers in page previews]]
> > > > - [[Pretty Properties - Settings (Covers)#Hide cover when properties are collapsed|Hide cover when properties are collapsed]]
> > > > - [[Pretty Properties - Settings (Covers)#Cover default position|Cover default position]]
> > > > - [[Pretty Properties - Settings (Covers)#Maximum height for left and right covers|Maximum height for left and right covers]]
> > > > - [[Pretty Properties - Settings (Covers)#Maximum height for top and bottom covers|Maximum height for top and bottom covers]]
> > > > - [[Pretty Properties - Settings (Covers)#Default cover width|Default cover width]]
> > > > - [[Pretty Properties - Settings (Covers)#Cover width 2|Cover width 2]]
> > > > - [[Pretty Properties - Settings (Covers)#Cover width 3|Cover width 3]]
> > > > - [[Pretty Properties - Settings (Covers)#Vertical cover width|Vertical cover width]]
> > > > - [[Pretty Properties - Settings (Covers)#Horizontal cover width|Horizontal cover width]]
> > > > - [[Pretty Properties - Settings (Covers)#Square cover width|Square cover width]]
> > > > - [[Pretty Properties - Settings (Covers)#Circle cover width|Circle cover width]]
> > > >- [[Pretty Properties - Settings (Covers)#Maximal cover width in page preview|Maximal cover width in page preview]]
> > 
> > > [!example]- Tasks
> > > - [[Pretty Properties - Settings (Tasks)#Enable task count|Enable task count]]
> > >   
> > > > [!attention]+ Requires `"enableTasksCount": true`
> > > > - [[Pretty Properties - Settings (Tasks)#Property to count all tasks|Property to count all tasks]]
> > > > - [[Pretty Properties - Settings (Tasks)#Property to count uncompleted tasks|Property to count uncompleted tasks]]
> > > > - [[Pretty Properties - Settings (Tasks)#Property to count completed tasks|Property to count completed tasks]]
> > > > - [[Pretty Properties - Settings (Tasks)#Uncompleted tasks statuses|Uncompleted tasks statuses]]
> > > > - [[Pretty Properties - Settings (Tasks)#Completed tasks statuses|Completed tasks statuses]]
> > > ### TaskNotes integration
> > > - [[Pretty Properties - Settings (Tasks)#Enable TaskNotes count|Enable TaskNotes count]]
> > >  
> > > > [!attention]- Requires `"enableTaskNotesCount": true`
> > > > - [[Pretty Properties - Settings (Tasks)#Property to count all project TaskNotes tasks|Property to count all project TaskNotes tasks]]
> > > > - [[Pretty Properties - Settings (Tasks)#Property to count completed project TaskNotes tasks|Property to count completed project TaskNotes tasks]]
> > > > - [[Pretty Properties - Settings (Tasks)#Property to count uncompleted project TaskNotes tasks|Property to count uncompleted project TaskNotes tasks]]
> > > > - [[Pretty Properties - Settings (Tasks)#Property to count all inline TaskNotes tasks|Property to count all inline TaskNotes]]
> > > > - [[Pretty Properties - Settings (Tasks)#Property to count completed inline TaskNotes tasks|Property to count completed inline TaskNotes tasks]]
> > > > - [[Pretty Properties - Settings (Tasks)#Property to count uncompleted inline TaskNotes tasks|Property to count uncompleted inline TaskNotes tasks]]
> > > > - [[Pretty Properties - Settings (Tasks)#Property to count all inline and project TaskNotes tasks|Property to count all inline and project TaskNotes tasks]]
> > > > - [[Pretty Properties - Settings (Tasks)#Property to count completed inline and project TaskNotes tasks|Property to count completed inline and project TaskNotes tasks]]
> > > > - [[Pretty Properties - Settings (Tasks)#Property to count uncompleted inline and project TaskNotes tasks|Property to count uncompleted inline and project TaskNotes tasks]]
> > > > - [[Pretty Properties - Settings (Tasks)#Property to count all TaskNotes tasks and checkbox tasks|Property to count all TaskNotes tasks and checkbox tasks]]
> > > > - [[Pretty Properties - Settings (Tasks)#Property to count completed TaskNotes tasks and checkbox tasks|Property to count completed TaskNotes tasks and checkbox tasks]]
> > > > - [[Pretty Properties - Settings (Tasks)#Property to count uncompleted TaskNotes tasks and checkbox tasks|Property to count uncompleted TaskNotes tasks and checkbox tasks]]
> > > 
> > > > [!attention]+ Requires `"enableTasksCount": true / "enableTaskNotesCount": true`
> > > > - [[Pretty Properties - Settings (Tasks)#Update all tasks automatically|Update all tasks automatically]]
> > 
> > > [!example]- Property settings
> > > - [[Pretty Properties - Settings (Property settings)#Add paddings to list properties|Add paddings to list properties]]
> > > - [[Pretty Properties - Settings (Property settings)#Enable colored properties|Enable colored properties]]
> > > - [[Pretty Properties - Settings (Property settings)#Enable colored inline tags|Enable colored inline tags]]
> > > - [[Pretty Properties - Settings (Property settings)#Show colored tags in tag pane|Show colored tags in tag pane]]
> > > - [[Pretty Properties - Settings (Property settings)#Show color buttons when hovering over text properties|Show color buttons when hovering over text properties]]
> > > - [[Pretty Properties - Settings (Property settings)#Show color buttons of text properties in bases|Show color buttons of text properties in bases]]
> > > - [[Pretty Properties - Settings (Property settings)#Also hide hidden properties in sidebar property tab|Also hide hidden properties in sidebar property tab]]
> > > - [[Pretty Properties - Settings (Property settings)#Hide properties block in editing view if all properties are hidden|Hide properties block in editing view if all properties are hidden]]
> > > - [[Pretty Properties - Settings (Property settings)#Hide properties block in reading view if all properties are hidden|Hide properties block in reading view if all properties are hidden]]
> > > - [[Pretty Properties - Settings (Property settings)#Autohide properties block when banner is enabled|Autohide properties block when banner is enabled]]
> > > - [[Pretty Properties - Settings (Property settings)#Hide properties title|Hide properties title]]
> > > - [[Pretty Properties - Settings (Property settings)#Hide add property button|Hide add property button]]
> > > - [[Pretty Properties - Settings (Property settings)#Show colored list properties|Show colored list properties]]
> > > - [[Pretty Properties - Settings (Property settings)#Show colored tags|Show colored tags]]
> > > - [[Pretty Properties - Settings (Property settings)#Show colored text properties|Show colored text properties]]
> > > - [[Pretty Properties - Settings (Property settings)#Show the hidden properties list|Show the hidden properties list]]
> > > - [[Pretty Properties - Settings (Property settings)#Show the list of properties hidden when empty|Show the list of properties hidden when empty]]
> > 
> > > [!example]- Dates
> > > - [[Pretty Properties - Settings (Dates)#Enable custom date formats for date and datetime properties|Enable custom date formats for date and datetime properties]]
> > >   
> > > > [!attention]- Requires `"enableCustomDateFormat": true`
> > > > - [[Pretty Properties - Settings (Dates)#Custom date format|Custom date format]]
> > > > - [[Pretty Properties - Settings (Dates)#Custom datetime format|Custom datetime format]]
> > > - [[Pretty Properties - Settings (Dates)#Enable custom date formats in bases (can affect performance)|Enable custom date formats in bases (can affect performance)]]
> > > - [[Pretty Properties - Settings (Dates)#Past date color|Past date color]]
> > > - [[Pretty Properties - Settings (Dates)#Present date color|Present date color]]
> > > - [[Pretty Properties - Settings (Dates)#Future date color|Future date color]]
> >  
> > > [!example]- Other
> > > - [[Pretty Properties - Settings (Other)#Image link format|Image link format]]
> 
> > [!info]- Commands
> > | Command                                                              | Hotkey        |
> > | :------------------------------------------------------------------- | ------------: |
> > | [[Pretty Properties - Commands#Pretty Properties Remove banner\|Pretty Properties: Remove banner]]                                             | `Blank` |
> > | [[Pretty Properties - Commands#Pretty Properties Remove cover\|Pretty Properties: Remove cover]]                                              | `Blank` |
> > | [[Pretty Properties - Commands#Pretty Properties Remove icon\|Pretty Properties: Remove icon]]                                               | `Blank` |
> > | [[Pretty Properties - Commands#Pretty Properties Select banner image\|Pretty Properties: Select banner image]]                                       | `Blank` |
> > | [[Pretty Properties - Commands#Pretty Properties Select cover image\|Pretty Properties: Select cover image]]                                        | `Blank` |
> > | [[Pretty Properties - Commands#Pretty Properties Select cover shape\|Pretty Properties: Select cover shape]]                                        | `Blank` |
> > | [[Pretty Properties - Commands#Pretty Properties Select icon\|Pretty Properties: Select icon]]                                               | `Blank` |
> > | [[Pretty Properties - Commands#Pretty Properties Show images menu\|Pretty Properties: Show images menu]]                                          | `Blank` |
> > | [[Pretty Properties - Commands#Pretty Properties Toggle reveal / hide hidden properties\|Pretty Properties: Toggle reveal / hide hidden properties]] | `Blank` | 

