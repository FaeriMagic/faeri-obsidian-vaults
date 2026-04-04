---
author: "[[石津, 栄太郎|@IshizuEitaro]]"
version: 1.1.5
created: 2025-04-20T06:17:49Z
last updated: 2026-03-31T14:49:45Z
programming language:
  - "[[TypeScript]]"
  - "[[JavaScript]]"
  - "[[CSS]]"
platforms:
  - "[[Github]]"
category: Productivity Tools
tags:
  - plugins/Obsidian/archiving
  - plugins/Obsidian/wayback-machine
  - plugins/Obsidian/web-links
---
# Wayback Archiver
> Automatically archives web links via Wayback Machine and appends archived versions in notes.

| [Github](https://github.com/IshizuEitaro/obsidian-wayback-archiver) | [Obsidian Stats](https://www.obsidianstats.com/plugins/wayback-archiver) |
| :-----------------------------------------------------------------: | :----------------------------------------------------------------------: |
```tabs
tab: Github documentation
# Table of Contents
- [[Wayback Archiver - Github documentation#Installation|Installation]]
- [[Wayback Archiver - Github documentation#Core Concepts|Core Concepts]]
    - [[Wayback Archiver - Github documentation#Archiving Process|Archiving Process]]
    - [[Wayback Archiver - Github documentation#Archive Links|Archive Links]]
    - [[Wayback Archiver - Github documentation#Profiles|Profiles]]
    - [[Wayback Archiver - Github documentation#Filtering|Filtering]]
    - [[Wayback Archiver - Github documentation#Substitution|Substitution]]
    - [[Wayback Archiver - Github documentation#Failed Archives|Failed Archives]]
- [[Wayback Archiver - Github documentation#Commands|Commands]]
    - [[Wayback Archiver - Github documentation#Archive links in current note|Archive links in current note]]
    - [[Wayback Archiver - Github documentation#Archive all links in vault|Archive all links in vault]]
    - [[Wayback Archiver - Github documentation#Force Re-archive links in current note|Force Re-archive links in current note]]
    - [[Wayback Archiver - Github documentation#Force Re-archive all links in vault|Force Re-archive all links in vault]]
    - [[Wayback Archiver - Github documentation#Retry failed archive attempts|Retry failed archive attempts]]
    - [[Wayback Archiver - Github documentation#Retry failed archive attempts (Force Replace)|Retry failed archive attempts (Force Replace)]]
    - [[Wayback Archiver - Github documentation#Export failed archive log|Export failed archive log]]
    - [[Wayback Archiver - Github documentation#Clear failed archive log|Clear failed archive log]]
- [[Wayback Archiver - Github documentation#Settings Guide|Settings Guide]]
    - [[Wayback Archiver - Github documentation#Global API Keys|Global API Keys]]
    - [[Wayback Archiver - Github documentation#Profiles Management|Profiles Management]]
    - [[Wayback Archiver - Github documentation#Profile Settings|Profile Settings]]
        - [[Wayback Archiver - Github documentation#General|General]]
        - [[Wayback Archiver - Github documentation#Filtering Rules|Filtering Rules]]
        - [[Wayback Archiver - Github documentation#URL Substitution Rules|URL Substitution Rules]]
        - [[Wayback Archiver - Github documentation#Advanced Settings|Advanced Settings]]
        - [[Wayback Archiver - Github documentation#SPN API v2 Options|SPN API v2 Options]]
- [[Wayback Archiver - Github documentation#Troubleshooting FAQ|Troubleshooting FAQ]]
- [[Wayback Archiver - Github documentation#Limitations|Limitations]]
- [[Wayback Archiver - Github documentation#LICENSE|LICENSE]]
  
tab: Settings
# Archive.org API keys (global)
- [[Wayback Archiver - Settings#Archive.org SPN access key|Archive.org SPN access key]]
- [[Wayback Archiver - Settings#Archive.org SPN secret key|Archive.org SPN secret key]]
  
# Profiles
- [[Wayback Archiver - Settings#Active profile|Active profile]]

# Archive link format
- [[Wayback Archiver - Settings#Date format|Date format]]
- [[Wayback Archiver - Settings#Archive link text|Archive link text]]

# Filtering rules (optional)
- [[Wayback Archiver - Settings#Ignore URL patterns|Ignore URL patterns]]
  - [[Wayback Archiver - Settings#Path patterns|Path patterns]]
  - [[Wayback Archiver - Settings#URL patterns|URL patterns]]
- [[Wayback Archiver - Settings#URL substitution rules|URL substitution rules]]
  
# Advanced
- [[Wayback Archiver - Settings#API request delay (ms)|API request delay (ms)]]
- [[Wayback Archiver - Settings#Max status check retries|Max status check retries]]
- [[Wayback Archiver - Settings#Archive freshness (days)|Archive freshness (days)]]
- [[Wayback Archiver - Settings#Auto clear failed logs|Auto clear failed logs]]

# SPN API v2 options
- [[Wayback Archiver - Settings#Capture screenshot|Capture screenshot]]
- [[Wayback Archiver - Settings#Capture all resources (capture_all=1)|Capture all resources (capture_all=1)]]
- [[Wayback Archiver - Settings#JS behaviour timeout (ms)|JS behaviour timeout (ms)]]
- [[Wayback Archiver - Settings#Force GET request (force_get=1)|Force GET request (force_get=1)]]
- [[Wayback Archiver - Settings#Capture outlinks (capture_outlinks=1)|Capture outlinks (capture_outlinks=1)]] 
 
tab: Commands (& hotkeys)
| Command                     | Hotkey    |
| --------------------------- | --------: |
| Plugin 1                    | `Alt + #` |
| Plugin 2                    | `Alt + #` |
| Remember to use \ for pipes | `Alt + #` |

tab: Release history

**Year**
- Version: Date
```