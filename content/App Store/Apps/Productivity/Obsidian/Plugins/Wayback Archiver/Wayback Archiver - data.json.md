---
summary: The data.json file for Wayback Archiver.
cssclasses:
  - cascadia-mono
tags:
  - documentation/data-json
---
{
&nbsp;&nbsp;"activeProfileId": "default",
&nbsp;&nbsp;"[[Wayback Archiver - Settings#Active profile|profiles]]": {
&nbsp;&nbsp;&nbsp;&nbsp;"default": {
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"[[Wayback Archiver - Settings#Date format|dateFormat]]": `"yyyy-MM-dd"`,
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp"[[Wayback Archiver - Settings#Archive link text|archiveLinkText]]": `"(Archived on {date})"`,
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"[[Wayback Archiver - Settings#Ignore URL patterns|ignorePatterns]]": [
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;`"web.archive.org/"`
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;],
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"[[Wayback Archiver - Settings#URL substitution rules|substitutionRules]]": [
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"find": "",
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"replace": "",
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"regex": false
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;],
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"[[Wayback Archiver - Settings#API request delay (ms)|apiDelay]]": `<NUMBER-VALUE: 500 to 10000>`,
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"[[Wayback Archiver - Settings#Max status check retries|maxRetries]]": `<NUMBER-VALUE: 1 to 10>`,
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"[[Wayback Archiver - Settings#Archive freshness (days)|archiveFreshnessDays]]": `<NUMBER-VALUE>`,
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"[[Wayback Archiver - Settings#Path patterns|pathPatterns]]": [],
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"[[Wayback Archiver - Settings#URL patterns|urlPatterns]]": [],
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"[[Wayback Archiver - Settings#Word/phrase patterns|wordPatterns]]": [],
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"[[Wayback Archiver - Settings#Capture screenshot|captureScreenshot]]": `true OR false`,
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"[[Wayback Archiver - Settings#Capture all resources (capture_all=1)|captureAll]]": `true OR false`,
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"[[Wayback Archiver - Settings#JS behaviour timeout (ms)|jsBehaviorTimeout]]": `<NUMBER-VALUE>`,
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"[[Wayback Archiver - Settings#Force GET request (force_get=1)|forceGet]]": `true OR false`,
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"[[Wayback Archiver - Settings#Capture outlinks (capture_outlinks=1)|captureOutlinks]]": `true OR false`,
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"[[Wayback Archiver - Settings#Auto clear failed logs|autoClearFailedLogs]]": `true OR false`
&nbsp;&nbsp;&nbsp;&nbsp;}
&nbsp;&nbsp;},
&nbsp;&nbsp;"failedArchives": [],
&nbsp;&nbsp;"[[Wayback Archiver - Settings#Archive.org SPN access key|spnAccessKey]]": `""`,
&nbsp;&nbsp;"[[Wayback Archiver - Settings#Archive.org SPN secret key|spnSecretKey]]": `""`
}