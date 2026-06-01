---
created: 2025-06-22T16:17:13Z
tags:
  - documentation/settings
---
## Dates
#### Enable custom date formats for date and datetime properties
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "enableCustomDateFormat": false
> ```
#### Custom date format
**Requires `"enableCustomDateFormat": true`.**
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "customDateFormat": ""
> ```
#### Custom datetime format
**Requires `"enableCustomDateFormat": true`.**
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "customDateTimeFormat": ""
> ```
#### Enable custom date formats in bases (can affect performance)
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "enableCustomDateFormatInBases": false
> ```
#### Past date color
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "dateColors": {
>     "past": {
>       "pillColor": "default",
>       "textColor": "default"
>     }
>   }
> ```
> **Note:** Selecting "default" will *remove* the related property from the data.json.
#### Present date color
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "dateColors": {
>     "present": {
>       "pillColor": "default",
>       "textColor": "default"
>     }
>   }
> ```
> **Note:** Selecting "default" will *remove* the related property from the data.json.
#### Future date color
> [!info] In [[Pretty Properties - data.json|data.json]]
> Only written to `data.json` upon update. If there isn't a `data.json`, it will be created.
> 
> **Default:**
> ```JSON
>   "dateColors": {
>     "future": {
>       "pillColor": "default",
>       "textColor": "default"
>     }
>   }
> ```
> **Note:** Selecting "default" will *remove* the related property from the data.json.