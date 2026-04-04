---
created: 2025-10-01T00:00:00
---
# Changing a file's creation date

1. Open **File Explorer** and navigate to the folder containing your note.
2. Right-click the folder and select **Open in Terminal**.
3. Enter the following command, replacing the filename and date with your own:
    
```
$(Get-Item "YOUR-NOTE.md").CreationTime = "2026-01-01T00:00:00Z"
```
    
> The date format is `YYYY-MM-DD` and the time uses 24-hour format (e.g. `14:00` = 2:00 PM). The time can be set to `00:00:00` if it doesn't matter to you.
    
4. Press **Enter**.
5. If the change doesn't show up in Obsidian immediately, reload it with **`Ctrl+R`**.