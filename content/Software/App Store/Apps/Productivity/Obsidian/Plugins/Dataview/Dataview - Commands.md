---
tags:
  - documentation/commands
---
## Dataview: Drop all cached file metadata
Clears Dataview's entire metadata cache, forcing it to re-index every file in your vault from scratch. Useful if queries are returning stale or incorrect results across multiple notes. Requires the Dataview community plugin.
## Dataview: Force refresh all views and blocks
Immediately re-renders all Dataview queries and blocks across every open note without clearing the underlying cache. Use this when your views look outdated but the cache itself is likely still valid. Requires the Dataview community plugin.
## Dataview: Rebuild current view
Re-renders the Dataview query in the note you're currently viewing. A lighter alternative to refreshing everything vault-wide when only a single query needs updating. Requires the Dataview community plugin.