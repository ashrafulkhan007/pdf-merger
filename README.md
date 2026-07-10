# Stackline — PDF merger

A single-page web app that merges PDF files entirely in your browser. No installs, no uploads, no backend — everything runs client-side using [pdf-lib](https://pdf-lib.js.org/).

## Features

- Drag and drop (or select) multiple PDFs
- Reorder files before merging by dragging cards
- Remove individual files before merging
- Skips unreadable/corrupted PDFs instead of failing the whole merge
- Downloads the result as `merged.pdf`
- Files never leave your browser tab — nothing is uploaded anywhere

## Usage

Open `index.html` (or `pdf_merger.html`) in any modern browser. That's it.

## Hosting on GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under "Build and deployment," set Source to **Deploy from a branch**.
4. Choose branch `main`, folder `/ (root)`, then save.
5. Your app will be live at:
   ```
   https://<your-username>.github.io/<repo-name>/
   ```

## Tech

- Plain HTML, CSS, and JavaScript — no build step, no dependencies to install
- [pdf-lib](https://pdf-lib.js.org/) loaded from a CDN for PDF parsing and merging

## Credit

Created by Md Ashraful Hakim Khan Siddiquee
