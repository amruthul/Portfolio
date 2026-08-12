# Amruthul P V — Portfolio

A one-page interactive portfolio built around a "workshop passport" concept — activities rendered as stamped ticket stubs, scroll-triggered reveals, an animated skills meter and education timeline. Plain HTML/CSS/JS, no build step, no dependencies beyond three Google Fonts.

**Live:** _add your deployed URL here once you've published it_

## Run locally
Just open `index.html` in a browser. No install needed.

## Deploy for free

### Option A — GitHub Pages (recommended)
Keeps the code and the live site in the same place.

1. Push this repo to GitHub (commands below).
2. On GitHub: **Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder `/ (root)` → Save**.
3. Your site is live at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

### Option B — Netlify Drop (fastest, no account required)
1. Go to **app.netlify.com/drop**.
2. Drag this folder into the browser window.
3. You get a live URL instantly. Add a free account later if you want to keep updating it.

Both are genuinely free for a static site like this — no card, no trial period.

## Push to GitHub
Create a new **empty** repository on GitHub first (no README/license/.gitignore, so it doesn't conflict with this one), then:

```bash
git remote add origin https://github.com/<your-username>/amruthul-portfolio.git
git push -u origin main
```

## Before you publish
Replace the placeholder Email / GitHub / LinkedIn links in the Connect section of `index.html` with your real ones.

## Customize
Colors, fonts, and spacing are CSS custom properties at the top of the `<style>` block in `index.html` (`--paper`, `--ink`, `--stamp`, `--moss`, `--dusk`, `--gold`...). All content is plain HTML — edit directly, no build step to re-run.

## License
MIT — see [LICENSE](./LICENSE). Do whatever you'd like with it.
