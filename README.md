# Cyborg Coach — interactive guide (public)

This repository hosts one thing: the public interactive reading guide for Cyborg Coach, served at **https://nudesk.github.io/cyborg-coach-guide/**. Anyone with the link can read it; no GitHub account or sign-in is required.

The Cyborg Coach plugin itself is a private, invitation-only prototype and is **not** published here. A public guide is not a public plugin release. Requests for plugin access go to the organizer who sent you the guide.

## What ships here

Only reviewed, sanitized files belong in this repository:

- `index.html` — the guide page
- `.nojekyll`
- the reviewed CSS
- the two sanitized image assets
- this `README.md`

Explicitly excluded: plugin source, Design archives and uploads, private internal documentation, and historical guide versions. If a file is not on the list above, it does not get copied in.

## Hosting

GitHub Pages serves this repository from the **`main` branch, root folder**. The `.nojekyll` file is required — without it Jekyll ignores the underscore-prefixed asset directory and required styles will be missing.

The primary HTML is authored natively by Design Opus / nuDesk. The canonical source lives in the private project; this repository holds a published copy, so edits are made upstream and copied here, never authored here.

## Updating

1. Make the change in the private canonical project.
2. Copy only the reviewed guide file and reviewed assets into a branch here.
3. Open a PR against `main` and review the diff for anything outside the shipping list.
4. After merge, confirm the live site: the page returns HTTP 200, the CSS and both images load, and full-guide and prompt copying work.

## Visitor data

GitHub serves this site and keeps its usual security and access logs, including visitor IP addresses. The page requests typefaces from Google Fonts, which is an ordinary browser request to Google, and falls back to system fonts when unavailable. nuDesk adds no analytics or session tracking. The page's local JavaScript supports navigation and copying guide text.
