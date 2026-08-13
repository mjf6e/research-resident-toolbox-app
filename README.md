# Research Resident Virtual Toolbox — mobile web app

Installable (PWA) version of the toolbox, built for phones.

## Deploy with GitHub Pages
1. Go to Settings → Pages → Source: **Deploy from a branch**, Branch: `main`, folder: `/ (root)`. Save.
2. Wait ~1 minute, then open `https://<user>.github.io/<repo>/` on a phone.

## Install on a phone
- **iPhone (Safari):** Share → Add to Home Screen.
- **Android (Chrome):** menu → Add to Home screen / Install app.

Launches full-screen with its own icon. `sw.js` caches the app so it opens without signal.

## Updating content
All entries live in the `DATA` array at the top of the `<script>` block in index.html. Bump `CACHE` in sw.js (`toolbox-v1` → `toolbox-v2`) after edits so phones pick up the new version.
