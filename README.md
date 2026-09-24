# profile-web

Personal profile and portfolio page for Marcos Feole: a single static `index.html` (plain HTML, CSS, and a little JavaScript, with no build step).

## Preview

Open `index.html` in a browser, or serve the folder with `python3 -m http.server`.

## Review notes

Sections that still need work carry dashed orange **"Improve a lot"** notes, and placeholder content has a dashed outline. The **✎ Notes** button in the top bar hides or shows them.

Before publishing:

1. Fill in the placeholders: projects and talks.
2. Delete the `<div class="note ...">` blocks, or change `data-notes="on"` to `data-notes="off"` on the `<html>` tag. That hides the notes and the Notes button.
3. Keep `photo.jpg` and the `papers/` folder next to `index.html`; the page links to them.

## Deploy

The page is one static file, so any static host works: GitHub Pages (Settings → Pages → deploy from branch), Netlify, Cloudflare Pages, and so on.
