# Quali.chat — Ready-to-Upload GitHub Pages Package

Your upload was only the browser 'Save Page As' **assets folder** (`*_files`) — it does **not** include the main HTML page.
This package relocates those assets under `assets/quali_files/` and gives you an `index.html` placeholder.

## What to do
- Paste your main page's HTML into `index.html` (replace the placeholder), or upload it to the repo and rename to `index.html`.
- Change asset references from `..._files/` to `assets/quali_files/`.
- If you have more pages, create `about.html`, `features.html`, etc., paste each page’s HTML, and keep asset paths under `assets/quali_files/`.

## Publish (GitHub Pages)
1) Create a **public** repo (e.g., `qualichat`).
2) Add file → Upload files → drag everything from inside this ZIP → Commit.
3) Settings → Pages → Source: **Deploy from a branch** → Branch `main`, Folder `/ (root)` → Save.
4) Open `https://<your-username>.github.io/qualichat/`.
