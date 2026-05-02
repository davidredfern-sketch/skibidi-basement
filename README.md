# Skibidi Basement

First-person stealth horror game in the Granny mould. Single-file browser-playable build.

## Play locally

Just open `index.html` in a modern browser (Chrome/Edge/Firefox).

## Hosting options

### Option A — GitHub Pages (recommended, free, zero config)

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<you>/skibidi-basement.git
git push -u origin main
```

Then on GitHub: **Settings → Pages → Source: Deploy from branch → main → /(root)** → Save.
Public URL appears at `https://<you>.github.io/skibidi-basement/` within ~1 minute.

### Option B — Netlify Drop (free, no Git needed)

1. Visit https://app.netlify.com/drop
2. Drag the `Skibidi Basement` folder onto the page
3. Get a public URL instantly

### Option C — Railway (uses the included `server.js`)

```bash
git init && git add . && git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<you>/skibidi-basement.git
git push -u origin main
```

On Railway: **New Project → Deploy from GitHub repo → pick repo**.
Railway auto-detects the `package.json`, runs `npm start`, and serves on `$PORT`.
Then **Settings → Networking → Generate Domain** for a public URL.

## Controls

- **WASD** move
- **Mouse** look
- **Shift** sprint (loud)
- **Ctrl** crouch (silent)
- **E** interact (pick up / hide / use exit)
- **F** throw distraction
- **Esc** release mouse

## Goal

Find 3 items. Reach the basement EXIT door. Don't get flushed.
