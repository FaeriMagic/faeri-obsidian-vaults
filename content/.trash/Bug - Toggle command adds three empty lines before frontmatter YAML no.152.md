---
title: "Bug: Toggle command adds three empty lines before frontmatter YAML #152"
created: 2024-03-11T16:57:01.000Z
github: https://github.com/obsidian-community/obsidian-style-settings/issues/152
tags:
  - github/issues/closed
---
# Bug: Toggle command adds three empty lines before frontmatter YAML #152
## **[[kometenstaub]]** opened on Mar 11, 2024

When using the "Toggle between reduced and max image size" command defined by Shimmering Focus (cc [[Grieser, Chris|@chrisgrieser]], three empty lines are prepended to the document, rendering frontmatter YAML unusable.

When no YAML is present, only one line is prepended to the note.

cc [[Jung, Moritz|@mProjectsCode]], I think you initially PRed that feature?

Obsidian version: 1.5.10  
Installer version 1.5.6  
Style Settings: 1.0.7

This issue also happens in the sandbox with just Style Settings and Shimmering Focus installed.

![[311790652-fd80fe72-c434-468c-bad9-86e45b31d9b2.png]]
![[311790120-5cfa0ba1-4259-4db4-85a2-a4434e1722b8.png]]
## **[[Jung, Moritz|mProjectsCode]]** on Mar 11, 2024

It seems like [this commit](https://github.com/mgmeyers/obsidian-style-settings/commit/7805ab40555db7b3a80403b733763563ad1e4ed2#diff-e0306954f0632d49ed727e45b5d182218e1b97df0138a8e4e7e7f4fecb36989c) broke the toggle command and causes the error that you are seeing in the console. No idea why it modifies the document though.
## **[[kometenstaub]]** on Mar 11, 2024

It might trigger something Obsidian responds to in this way. No idea. 🤷

> [!example]  ![[avatar - Meyers, Matthew.png|14]] [[Meyers, Matthew|mgmeyers]] closed this as completed on Mar 11, 2024

> ![[avatar - Meyers, Matthew.png|14]] **[[Meyers, Matthew|mgmeyers]]** added a commit that references this issue on Mar 11, 2024
## **[[kometenstaub]]** on Mar 11, 2024

Thank you! ❤️

> ![[avatar - pull.png|14]] **pull** added a commit that references this issue on Mar 12, 2024

