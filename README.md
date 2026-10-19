# ME2 Drill Bank (STAT/DATA 1810)

389 practice questions for midterm 2. Installs on a phone home screen and works offline.

## Put it on GitHub Pages

1. Create a new public repo (for example `me2-drill`).
2. Upload everything in this folder to the repo root: `index.html`, `manifest.webmanifest`, `sw.js`, the four `.png` icons, `.nojekyll` and this README. The files must sit at the top level, not inside a subfolder.
3. Repo Settings, Pages, Source: "Deploy from a branch", Branch: `main`, folder `/ (root)`. Save.
4. After a minute the site is live at `https://<your-username>.github.io/<repo-name>/`.

## Add it to the home screen

- iPhone: open the link in Safari (not Chrome), tap Share, then Add to Home Screen.
- Android: open it in Chrome, tap the menu, then Install app (or Add to Home screen).

Open it once with a connection so it can cache itself. After that it runs offline.

## Good to know

- Progress is saved on the device, per browser. The home screen app and Safari keep separate progress, so pick one and stay with it.
- To change anything later, edit the files, then change `CACHE = 'me2-drill-v2'` in `sw.js` to `v3` so phones pick up the update.
- Everything is local: no CDN, no tracking, no account.
