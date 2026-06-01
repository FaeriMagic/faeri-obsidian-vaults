---
icon: LiCheckSquare
---
## Music releases
- Review [[2CELLOS - 2CELLOS]].
## Obsidian
### Plugins
- [[Dataview]] release history

%%
# Obsidian
- [ ] Obsidian Mobile
- [ ] Obsidian Sync

## Plugins
- [ ] HTML Tabs release history
- [ ] Notebook Navigator release history
### Backlog release history
#### Plugins
- [ ] Style Settings
- [ ] Tabs
- [ ] Templater
#### Themes
- [ ] Things

## Obsidian quirks that need researching
### Cannot format links
- [[Templater - Documentation (2.2. tp.config)]]

Variant coding block colors
- [[Templater - Documentation (2.3. tp.date)]]

Bugs:
- Notebook Navigator doesn't always display title frontmatter as note title
- Solution: Go back to the navigation pane and switch back to list pane

- [ ] Replace "If `⟲` is clicked, this JSON property will be removed from `data.json`." to "If `⟲` is clicked, the JSON property will be removed from `data.json`."



Notes:
- Removed WeWard on iPad, because you can only login on one device at a time, and ads are limited, so it's just inconvenient to keep on logging in
- Removed Bitwalk on iPad, because accumulated BTCp are NOT transferred over.
- Currently, you CANNOT change your name in ByPet.%%

## Orphaned links
```dataviewjs
const unresolved = app.metadataCache.unresolvedLinks;
let results = [];
for (let [source, links] of Object.entries(unresolved)) {
    for (let [linkText, count] of Object.entries(links)) {
        results.push([dv.fileLink(source), linkText]);
    }
}
dv.table(["File", "Unresolved Link"], results);
```