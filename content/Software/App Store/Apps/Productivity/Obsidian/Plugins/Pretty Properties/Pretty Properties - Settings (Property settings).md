---
created: 2025-06-22T16:17:13Z
tags:
  - documentation/settings
---
## Property settings
#### Add paddings to list properties
Paddings make colored pills look better, but may look strange on non-colored pills if default color is not set. Select the option that fits better for your theme.
- all (*"all"*)
- none (*"none"*)
- only colored (*"colored"*)
- only non-transparent (*"non-transparent"*)
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "addPillPadding": "all"
> ```
#### Enable colored properties
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "enableColoredProperties": true
> ```
#### Enable colored inline tags
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "enableColoredInlineTags": false
> ```
#### Show colored tags in tag pane
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "enableColoredTagsInTagPane": false
> ```
#### Show color buttons when hovering over text properties
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "enableColorButton": true
> ```
#### Show color buttons of text properties in bases
Buttons allow to change colors of text properties but can slow down bases loading. You need to reopen the file if you change this setting
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "enableColorButtonInBases": false
> ```
#### Also hide hidden properties in sidebar property tab
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "hidePropertiesInPropTab": false
> ```
#### Hide all empty properties
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "hideAllEmptyProperties": false
> ```
#### Hide properties block in editing view if all properties are hidden
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "hideMetadataContainerIfAllPropertiesHiddenEditing": false
> ```
#### Hide properties block in reading view if all properties are hidden
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "hideMetadataContainerIfAllPropertiesHiddenReading": false
> ```
#### Autohide properties block when banner is enabled
Properties will be revealed when hovering over the top of the banner.
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "autoHidePropertiesWithBanner": false
> ```
#### Hide properties title
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "hidePropTitle": false
> ```
#### Hide add property button
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "hideAddPropertyButton": false
> ```
#### Enable rendering math expressions in properties and bases
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "enableMath": false
> ```
#### Show colored list properties
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "showColorSettings": false
> ```
> **After adding a property:**
> ```JSON
>   "propertyPillColors": {
>     "<PROPERTY-NAME>": {
>       "pillColor": "",
>       "textColor": ""
>     }
>   }
> ```
#### Show colored tags
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "showTagColorSettings": false
> ```
> **After adding a tag:**
> ```JSON
>   "tagColors": {
>     "<TAG-NAME>": {
>       "pillColor": "",
>       "textColor": ""
>     }
>   }
> ```
#### Show colored text properties
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "showTextColorSettings": false
> ```
> **After adding a property:**
> ```JSON
>   "propertyLongtextColors": {
>     "<PROPERTY-NAME>": {
>       "pillColor": "",
>       "textColor": ""
>     }
>   }
> ```
#### Show the hidden properties list
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "showHiddenSettings": false
> ```
> **After adding a property:**
> ```JSON
>   "hiddenProperties": {
>     "<PROPERTY-NAME>",
>     "<PROPERTY-NAME>"
>   }
> ```
#### Show the list of properties hidden when empty
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "showHiddenEmptySettings": false
> ```