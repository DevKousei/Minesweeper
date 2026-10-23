# Minesweeper by Kousei

A single-file, mobile-friendly monochrome Minesweeper game for GitHub Pages.

## Publish with GitHub Pages
1. Create a new public repository (for example `minesweeper-by-kousei`).
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under Build and deployment, choose **Deploy from a branch**, branch `main`, folder `/ (root)`, then Save.
5. Wait for GitHub Pages to publish the site.

## Included
- Classic, Risk Run, 60-second Time Attack, and Endless modes
- 10×10 grid with 10/15/20/25 starting bombs
- Board crack/shatter game-over effect; no image pop-up
- Local XP, levels, achievements, stats, and leaderboard
- Sound toggle, animation toggle, flag mode, responsive layout
- Progress saved in the current browser using localStorage

## Important notes
- Progress and leaderboard are local to each browser/device. They are not synced globally.
- A real global leaderboard needs a database plus server-side score validation. Do not trust browser-submitted scores as competitive records.
- The original reaction image is intentionally not included or shown.
