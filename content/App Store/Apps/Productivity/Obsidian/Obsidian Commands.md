---
tags:
  - meta/guide
---
# Obsidian Commands

← Go back to [[Obsidian#Hotkeys|Hotkeys]]
## Add cursor above
Places an additional cursor on the line above your current position, letting you type or edit on multiple lines simultaneously. Useful for making the same change across several consecutive lines without selecting and replacing.
## Add cursor below
Same as above but adds the extra cursor on the line below instead. You can keep triggering it to stack multiple cursors downward, then type once to affect all of them at the same time.
## Audio recorder: Start recording
Begins recording audio through your device's microphone and saves it as an attachment in your vault. The Audio recorder core plugin must be enabled in Settings > Core plugins for this command to appear. An audio recorder icon will also appear in the left side ribbon.
## Audio recorder: Stop recording
Stops the current audio recording and saves the file to your vault. The Audio recorder core plugin must be enabled in Settings > Core plugins for this command to appear. An audio recorder icon will also appear in the left side ribbon.
## Backlinks: Toggle backlinks in document
Opens or closes the inline backlinks panel at the bottom of your current note, showing you every other note that links to this one. A quick way to see what's connected without switching to the sidebar.
## Bookmarks: Remove bookmark for the current file
Unbookmarks the note you're currently viewing, removing it from your Bookmarks panel. The note itself is untouched — only the bookmark entry is deleted.

> [!warning]
> For the "Bookmarks: Remove bookmark for the current file" command, there is **no** confirmation dialog before the bookmark is removed.
## Canvas: Convert to file...
Takes a selected card on a Canvas board and converts its content into a proper standalone note in your vault, replacing the card with a file card that links to it. Good for when a quick idea you jotted on a canvas has grown into something worth its own page.
## Canvas: Export as image
When using this command, you will receive this popup:

> [!warning] Export as image
> Export "canvas-name" as a PNG file with the settings below.
> 
> **Viewport**
> Choose to render the entire canvas or just the current visible viewport
> - Full canvas *(Default)*
> - Viewport only
> 
> **Zoom**
> Estimated image dimensions: (estimate dimensions listed here)
> *Default:* 1.0 (slider ranges from 0.5 to 2.0)
> 
> **Show logo**
> This will add an Obsidian logo to the bottom left.
> *Default:* true
>
>**Privacy mode**
>This will obscure any text on your canvas.
>*Default:* false
## Clear file properties
Deletes all properties (frontmatter) from the current note in one go, removing fields like tags, aliases, or any custom key-value pairs you've set. The rest of your note content is left intact.

> [!warning]
> For the "Clear file properties" command, there is **no** confirmation dialog before the your properties are deleted.
## Close all other tabs
Closes every open tab in the current window except the one you're on. Handy for decluttering when you've accumulated a bunch of tabs during a research or editing session.

> [!warning]
> For the "Close all other tabs" command, there is **no** confirmation dialog before all of the other tabs are closed.
## Close current tab
Closes the tab you're currently viewing. If it's the only tab open, the tab will close and leave the pane empty.

> [!warning]
> For the "Close current" command, there is **no** confirmation dialog before the current tab is closed.
### Close others in tab group
Closes all other open tabs within the same pane as your current tab, leaving any other panes untouched. If you're only working in one pane, this behaves the same as Close all other tabs.
## Daily note: Open next daily note
Opens the daily note for the day after your currently viewed daily note. Requires the next day's note to already exist — if it hasn't been created yet, the command won't do anything.
# Daily note: Open previous daily note
Opens the daily note for the day before your currently viewed daily note. Requires the previous day's note to already exist — if it hasn't been created yet, the command won't do anything.
## Daily note: Open's today's daily note
Opens the daily note for today. If today's note doesn't exist yet, it will be created automatically.
## Delete paragraph
Deletes the entire paragraph your cursor is currently in, including the trailing newline. The rest of your note shifts up to fill the gap.

> [!warning]
> For the "Delete paragraph" command, there is **no** confirmation dialog before the paragraph is deleted.
## Export to PDF...
When using this command, you will receive this popup:

> [!warning] Export as PDF
> Export "note-name" to PDF with the settings below.
> 
> **Include file name as title**
> *Default:* false
> 
> **Page size**
> - A3
> - A4
> - A5
> - Legal
> - Letter *(Default)*
> - Tabloid
> 
> **Landscape**
> *Default:* false
>
>**Margin**
>- Default *(Default)*
>- Minimal
>- None
>
>**Downscale percent**
>*Default:* 100 (slider ranges from 10 to 100)
## Focus on last note
Returns keyboard focus to the last note you were editing. Useful if you've clicked into a sidebar panel (such as search or the file explorer) and want to get back to typing in your note without reaching for the mouse.
## Fold less
Expands the current fold level, revealing the next layer of hidden content. Each time you run it, it unfolds one level at a time.
## Fold more
Collapses the next level of headings or list items, hiding more of your document. Each time you run it, it folds one level deeper than the current fold state.
## Follow link under cursor
Opens the note or URL that your cursor is currently positioned on, without needing to use the mouse. Equivalent to Ctrl+clicking a link.

>[!bug] 
>As of version 1.12.4, this command may not work even with the hotkey correctly assigned and no conflicts. Alt+Left click works as a partial workaround, but behavior is inconsistent — for example, following a link works from some notes but not others, with no clear pattern.
## Footnotes view: Show footnotes
Opens a dedicated panel displaying all footnotes in the current note, letting you view and navigate them without scrolling to the bottom of the page. The Footnotes view core plugin must be enabled in Settings > Core plugins for this command to appear.
## Format converter: Open format converter
Opens a tool that batch converts legacy Markdown syntax from other apps (such as Roam Research or Bear) into Obsidian-compatible formatting across your entire vault. The Format converter core plugin must be enabled in Settings > Core plugins for this command to appear.

When using this command, you will receive this popup:

> [!warning] Format converter
> **Roam Research tag fixer** (*default:* false)
> Convert "#tag" and "#\[\[tag]]" to "\[\[tag]]".
> 
> **Roam Research highlight fixer**
> Converts "^^highlight^^ to "\=\=highlight\=\=".
> 
> **Roam Research TODO converter**
> Converts "{{\[\[TODO]]}}" to "\[ ]".
> 
> **Bear highlight fixer**
> Converts "::highlight::" to "\=\=highlight\=\=".
> 
> **Zettelkasten link beautifier**
> Fixes "\[\[UID]]" links and also beautify then "\[\[UID File Name|File Name]]".
> 
> **Frontmattter migration**
> Migrate frontmatter tags, aliases, and cssclasses to the strict format required by Obsidian v1.9+
> 
> <span style="color: #FB464C;">Warning: the converter will convert all the files in your vault, not just the current file.</span>
> 
> <span style="color: #FB464C;">Your files will be overwritten. Back up all your files before attempting conversion.</span>
## Graph view: Start graph timelapse animation
Plays an animation in the graph view that shows your notes appearing chronologically in the order they were created, letting you watch your vault grow over time.

> [!warning] Local graph
> The timelapse animation does **not** work with the local graph.
## Note composer: Extract current selection
Takes the text you currently have selected and moves it into a new note, replacing the selection in the original note with a link to the newly created one. Useful for splitting out content that has grown large enough to deserve its own page.

>[!bug] 
>This command is currently incorrectly linked to the "Merge current file with another file..." function.
## Open link under cursor in new tab
Opens the note or URL your cursor is currently positioned on in a new tab, keeping your current note open.

>[!bug] 
> As of version 1.12.4, The hotkey (Ctrl+Enter) does not work. The functionality itself works via Ctrl+Left click instead, suggesting the command was accidentally wired to a click event rather than the keyboard shortcut.
## Open link under cursor in new window
Opens the note or URL your cursor is currently positioned on in a new window, keeping your current note open in its original window.

> [!bug]
> As of version 1.12.4, the hotkey (Ctrl+Alt+Shift+Enter) does not work. The functionality itself works correctly via Ctrl+Alt+Shift+Left click instead, suggesting the command was accidentally wired to a click event rather than the keyboard shortcut.
## Open link under cursor to the right
Opens the note or URL your cursor is currently positioned on in a new pane to the right, keeping your current note open on the left.

> [!bug] 
> As of version 1.12.4, the hotkey (Ctrl+Alt+Enter) does not work. The functionality itself works correctly via Ctrl+Alt+Left click instead, suggesting the command was accidentally wired to a click event rather than the keyboard shortcut.
## Publish: Open in live site
Opens the published version of the current note in your browser, letting you see how it appears on your live Obsidian Publish site. Requires the Publish core plugin to be enabled and an active Obsidian Publish subscription.
## Publish: Publish changes
Opens the Publish dialog showing all notes with unpublished changes, allowing you to review and selectively push updates to your live site. Requires the Publish core plugin to be enabled and an active Obsidian Publish subscription.
## Publish: Publish current file
Publishes the current note directly to your Obsidian Publish site without going through the full publish dialog. Requires the Publish core plugin to be enabled and an active Obsidian Publish subscription.
## Quick switcher: Open quick switcher
Opens the quick switcher, a search bar that lets you rapidly navigate to any note in your vault by typing part of its name.

> [!bug] 
> The hotkey for this command is documented as Ctrl+0, but the actual working hotkey is Ctrl+P. This appears to be a typo in Obsidian's documentation, as P is directly below 0 on the keyboard.
## Save current file
Manually saves the current note to disk. In practice, Obsidian saves your notes automatically as you type, so this command is rarely necessary — it exists mainly as a familiar fallback for those accustomed to manually saving in other applications.
## Slides: Start presentation
Launches the current note as a slideshow presentation, treating each horizontal rule (`---`) as a slide break. Requires the Slides core plugin to be enabled in Settings > Core plugins for this command to appear.
## Sync: Show activity log
Opens a log of all recent sync activity, showing which files have been synced, updated, or flagged for conflicts. **Requires an active Obsidian Sync subscription.**
## Sync: Open version history for the current file
Opens a panel showing the full revision history of the current note, allowing you to browse and restore previous versions. **Requires an active Obsidian Sync subscription.**
## Sync: Set up Sync
Opens the setup wizard for Obsidian Sync, guiding you through connecting your vault to a remote server for backup and cross-device synchronization. **Requires an active Obsidian Sync subscription.**

If you do not have an active Obsidian Sync subscription, this will be displayed on the core plugin's page:

> [!warning] 
> Obsidian Sync is Obsidian's add-on sync service with end-to-end encryption and version history.
> 
> To start syncing, please log in or create a new Obsidian account.
## Sync: Show Sync history
Opens a full log of all sync events across your vault, including file changes, deletions, and conflict resolutions. **Requires an active Obsidian Sync subscription.**
## Toggle default mode for new tabs
Switches the default mode that new tabs open in, toggling between editing mode and reading mode. Whichever mode is set will be applied automatically whenever you open a new tab.
## Toggle pin
Pins or unpins the current tab. A pinned tab will not be replaced when opening other notes, forcing them to open in a new tab instead. Useful for keeping a reference note permanently accessible while you navigate around your vault.
## Toggle window always on top
Keeps the Obsidian window floating above all other windows, even when it's not in focus. Press again to turn it off.

> [!bug] 
> As of version 1.12.4, this command does not appear to work — Obsidian will still go behind other windows even when toggled on.
## Web viewer: Focus address bar
Moves keyboard focus to the address bar in the web viewer panel, letting you type or edit a URL without reaching for the mouse. Requires the Web viewer core plugin to be enabled in Settings > Core plugins.
## Web viewer: Open web viewer
Opens a new web viewer panel inside Obsidian, letting you browse the web without leaving the app. Requires the Web viewer core plugin to be enabled in Settings > Core plugins.
## Web viewer: Reset zoom
Resets the zoom level of the current web viewer page back to the default. Requires the Web viewer core plugin to be enabled in Settings > Core plugins.
## Web viewer: Save to vault
Opens a web search prompt directly from within Obsidian, loading the results in the web viewer panel. Requires the Web viewer core plugin to be enabled in Settings > Core plugins.
## Web viewer: Search the web
Opens a web search prompt directly from within Obsidian, loading the results in the web viewer panel. Requires the Web viewer core plugin to be enabled in Settings > Core plugins.
## Web viewer: Show history
Displays your browsing history within the web viewer, letting you navigate back to previously visited pages. Requires the Web viewer core plugin to be enabled in Settings > Core plugins.
## Web viewer: Toggle reader mode
Switches the current web viewer page into a simplified, distraction-free reading view that strips away ads and clutter. Requires the Web viewer core plugin to be enabled in Settings > Core plugins.
## Web viewer: Zoom in
Increases the zoom level of the current page in the web viewer. Requires the Web viewer core plugin to be enabled in Settings > Core plugins.
## Web viewer: Zoom out
Decreases the zoom level of the current page in the web viewer. Requires the Web viewer core plugin to be enabled in Settings > Core plugins.
## Workspaces: Load workspace layout
Opens a saved workspace layout, restoring the arrangement of tabs, panes, and panels you had when it was saved. Requires the Workspaces core plugin to be enabled in Settings > Core plugins.
## Workspaces: Manage workspace layouts
Opens a panel where you can view, rename, and delete your saved workspace layouts. Requires the Workspaces core plugin to be enabled in Settings > Core plugins.
## Workspaces: Save and load another layout
Saves your current workspace layout and immediately switches to a different one in a single step. Requires the Workspaces core plugin to be enabled in Settings > Core plugins.
## Workspaces: Save layout
Saves your current arrangement of tabs, panes, and panels as a named workspace layout that you can return to later. Requires the Workspaces core plugin to be enabled in Settings > Core plugins.