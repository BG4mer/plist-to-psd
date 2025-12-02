plist-to-psd
============

Simple static GitHub Pages site that converts a plist (sprite-sheet metadata) into a PSD file with:
- a top text layer containing the full plist XML (preserved)
- one text layer per frame describing name + key metadata

How to use
1. Create a new GitHub repo, drop index.html at the root (or inside docs/ for GitHub Pages).
2. Commit and enable GitHub Pages (branch: main, folder: root or docs).
3. Visit the page, paste your plist XML into the textarea, click Generate PSD.
4. The browser will download plist_preserved.psd

Notes & limitations
- This first version creates text layers only (no raster images embedded).
