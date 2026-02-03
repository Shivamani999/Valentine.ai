# Valentine Site — Standalone Version

## What it does

- Girl opens the site
- Sees "Will you be my Valentine?" with Yes and No buttons
- No button runs away when she tries to click it (stays inside the card box)
- She clicks Yes → full-screen celebration with hearts and sparkles

**No database, no backend, no Firebase.** Just a single HTML file.

## How to use

### Option 1 — Open locally (no deployment needed)
Just double-click `index.html` — opens in your browser, works fully offline.

### Option 2 — Deploy to Vercel (get a shareable link)
1. Push `index.html` and `vercel.json` to a GitHub repo
2. Go to https://vercel.com → New Project → import your repo → Deploy
3. You get a live URL like: `https://valentine-abc123.vercel.app`
4. Send that link to her

## Files

| File        | What it does                          |
|-------------|---------------------------------------|
| index.html  | The entire site (one file, no deps)   |
| vercel.json | Config for Vercel deployment          |
| README.md   | This file                             |
