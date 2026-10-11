# Daishi11 Portfolio

A static GitHub Pages portfolio: plain HTML, CSS, and one real screenshot. No build step or external framework required.

## Local preview

Open `index.html` in your browser, or run a small local HTTP server:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000/`.

## Deploy

Copy `index.html`, `styles.css`, and `assets/` into the root of the `Daishi11/daishi11.github.io` repository.

```powershell
git status --short
git add index.html styles.css assets/youtube-punch-eq.png README.md
git commit -m 'feat: build project portfolio'
git push origin main
```

GitHub Pages already needs to be configured to deploy from `main` / root.

## Updating content

- Edit project descriptions directly in `index.html`.
- The Cyan Moon widget uses the official Steam Store iframe with App ID `5176400`.
- The Steam demo button links to the main Steam product page, where the demo can be downloaded.
- The itch.io demo is intentionally shown as **coming soon**, without an unverified or unpublished link. Add the actual link after publication.
- `assets/youtube-punch-eq.png` is the supplied screenshot of the real Firefox extension UI.
- ShortcutManager has no fabricated screenshot or dead link.
- Colors, layout, and responsive rules are in `styles.css`.

The external Steam iframe is controlled by Valve and may be blocked by privacy settings; the direct Steam link is always available.
