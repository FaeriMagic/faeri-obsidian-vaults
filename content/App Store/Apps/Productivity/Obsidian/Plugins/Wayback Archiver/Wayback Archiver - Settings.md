---
icon: LiSettings
title: Settings
tags:
  - documentation/obsidian-settings
---
## Archive.org API keys (global)
This is used globally across all profiles. [You can generate your API keys here.](https://archive.org/account/s3.php)
### Archive.org SPN access key
Your S3-like access key for the SPN API v2.

> [!info] In [[Wayback Archiver - data.json|data.json]]
> **Default:**
> ```JSON
>   "spnAccessKey": ""
> ```
### Archive.org SPN secret key
Your S3-like secret key for the SPN API v2.

> [!info] In [[Wayback Archiver - data.json|data.json]]
> **Default:**
> ```JSON
>   "spnSecretKey": ""
> ```
## Profiles
### Active profile
Select the settings profile to use.

> [!info] In [[Wayback Archiver - data.json|data.json]]
> **Default:**
> ```JSON
>   "profiles": {
>    "default": {
>      "dateFormat": "yyyy-MM-dd",
>      "archiveLinkText": "(Archived on {date})",
>      "ignorePatterns": [
>        "web.archive.org/"
>      ],
>      "substitutionRules": [],
>      "apiDelay": 2000,
>      "maxRetries": 3,
>      "archiveFreshnessDays": 0,
>      "pathPatterns": [],
>      "urlPatterns": [],
>      "wordPatterns": [],
>      "captureScreenshot": false,
>      "captureAll": false,
>      "jsBehaviorTimeout": 0,
>      "forceGet": false,
>      "captureOutlinks": false,
>      "autoClearFailedLogs": false
>    }
>  }
> ```
## Archive link format
### Date format
Format for the {date} placeholder in the archive link text (using date-fns format}).

> [!info] In [[Wayback Archiver - data.json|data.json]]
> **Default:**
> ```JSON
>       "dateFormat": "yyyy-MM-dd"
> ```
### Archive link text
Text used for the inserted archive link. Use {date} as a placeholder.

> [!info] In [[Wayback Archiver - data.json|data.json]]
> **Default:**
> ```JSON
>       "archiveLinkText": "(Archived on {date})"
> ```
## Filtering rules (optional)
### Ignore URL patterns
URLS matching these patterns (one per line, regex or simple text) will be ignored. Example: youtube\.com or internal-wiki

> [!info] In [[Wayback Archiver - data.json|data.json]]
> **Default:**
> ```JSON
>       "ignorePatterns": [
>         "web.archive.org/"
>       ],
> ```

**Define patterns to ONLY archive links within notes matching these criteria. If multiple filter types are used, the note/link must match ALL active filter types.**
#### Path patterns
Only archive links in notes whose file path matches these patterns (one per line, regex or simple text). Leave empty to ignore path.

> [!info] In [[Wayback Archiver - data.json|data.json]]
> **Default:**
> ```JSON
>       "pathPatterns": []
> ```
> **Placeholder:**
> ```
> ^Journal/.*
> Projects/MyProject/
> ```
#### URL patterns
Only archive links whose URL matches these patterns (one per line, regex or simple text). Leave empty to ignore URL.

> [!info] In [[Wayback Archiver - data.json|data.json]]
> **Default:**
> ```JSON
>       "urlPatterns": []
> ```
> **Placeholder:**
> ```
> ^https://specific-domain\.com/
> news-site
> ```
#### Word/phrase patterns
Only archive links in notes containing ANY of these words or phrases (one per line, simple text match). Leave empty to ignore content.

> [!info] In [[Wayback Archiver - data.json|data.json]]
> **Default:**
> ```JSON
>       "wordPatterns": []
> ```
> **Placeholder:**
> ```
> Project Alpha
> #research-topic
> ```
### URL substitution rules
Apply find/replace rules to URLs before archiving. Useful for removing tracking parameters or normalizing links.

> [!info] In [[Wayback Archiver - data.json|data.json]]
> **Default:**
> ```JSON
>       "substitutionRules": []
> ```
> **Blank rule:**
> ```JSON
>       "substitutionRules": [
>         {
>           "find": "",
>           "replace": "",
>           "regex": false
>         }
>       ]
> ```
## Advanced
### API request delay (ms)
Delay between API calls (initiate, status check, next link) in milliseconds.

> [!info] In [[Wayback Archiver - data.json|data.json]]
> The slider ranges from 500 to 10000. Only values set through the slider are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>       "apiDelay": 2000
> ```
### Max status check retries
Maximum number of times to check the status of a pending archive job.

> [!info] In [[Wayback Archiver - data.json|data.json]]
> The slider ranges from 1 to 10. Only values set through the slider are accepted; manually editing the JSON file will have no effect.
> 
> **Default:**
> ```JSON
>       "maxRetries": 3
> ```
### Archive freshness (days)
Only archive if the URL has not ben archived within this many days (0 = always archive if note present). Yses SPSN API `if_not_archived_within`.

> [!info] In [[Wayback Archiver - data.json|data.json]]
> 
> **Default:**
> ```JSON
>       "archiveFreshnessDays": 0
> ```
### Auto clear failed logs
Automatically clear failed logs after successful retries without confirmation.

> [!info] In [[Wayback Archiver - data.json|data.json]]
> 
> **Default:**
> ```JSON
>       "autoClearFailedLogs": false
> ```
## SPN API v2 options
These options correspond to parameters available in the Archive.org SPD API v2. [See documentation for details.](https://docs.google.com/document/d/1Nsv52MvSjbLb2PCpHlat0gkzw0EvtSgpKHu4mk0MnrA/edit?tab=t.0#heading=h.1gmodju1d6p0)
### Capture screenshot
Request a screenshot of the page during archive (SPN option).

> [!info] In [[Wayback Archiver - data.json|data.json]]
> 
> **Default:**
> ```JSON
>       "captureScreenshot": false
> ```
### Capture all resources (capture_all=1)
Attempt to capture more resources like JS, CSS, embeds (SPN option). May increase capture time/failure rate.

> [!info] In [[Wayback Archiver - data.json|data.json]]
> 
> **Default:**
> ```JSON
>       "captureAll": false
> ```
### JS behaviour timeout (ms)
Max time (milliseconds) to allow JS execution during capture (0 = default). (SPN option)

> [!info] In [[Wayback Archiver - data.json|data.json]]
> 
> **Default:**
> ```JSON
>       "jsBehaviorTimeout": 0
> ```
### Force GET request (force_get=1)
Force the archiver to use a GET request (SPN option).

> [!info] In [[Wayback Archiver - data.json|data.json]]
> 
> **Default:**
> ```JSON
>       "forceGet": false
> ```
### Capture outlinks (capture_outlinks=1)
Attempt to capture pages linked from the main URL (SPN option). Use with caution, can be slow.

> [!info] In [[Wayback Archiver - data.json|data.json]]
> 
> **Default:**
> ```JSON
>       "captureOutlinks": false
> ```
