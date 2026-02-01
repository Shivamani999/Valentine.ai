# Valentine's Site — Deployment Guide

## Files in this folder
| File          | What it does                                  |
|---------------|-----------------------------------------------|
| index.html    | The entire site (question + celebration)      |
| vercel.json   | Tells Vercel how to serve it                  |
| README.md     | This file                                     |

---

## Deploy to Vercel (free, no credit card)

### Step 1 — Create a GitHub repo
1. Go to https://github.com/new
2. Name it anything (e.g. `valentine-site`)
3. Click **Create repository**
4. Upload the three files above (`index.html`, `vercel.json`, `README.md`) into the repo root
   - Click **Add file → Upload file**, drag all three in, commit

### Step 2 — Deploy on Vercel
1. Go to https://vercel.com and sign up (free)
2. Click **New Project**
3. Click **Import** → select your GitHub repo `valentine-site`
4. Click **Deploy** (no settings to change — Vercel auto-detects it)
5. Vercel gives you a live URL like: `https://valentine-site-abc123.vercel.app`

### Step 3 — Share the link
Send that URL to your person. That's it.

---

## Run locally (no server needed)
Just double-click `index.html` — it opens in your browser and works fully offline.

---

## What happens on the site
1. Question screen with a heartbeat animation and floating petals
2. The **No** button dodges the mouse every time you get close
3. Click **Yes** → full-screen celebration fires:
   - 16 hearts burst outward from center
   - 18 hearts float upward continuously
   - 20 sparkle dots radiate outward on a loop
   - A pulsing glow ring pulses behind the main heart
