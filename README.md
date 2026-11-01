# Daily Philosophy

A different philosophy quote every day from 1 November to 31 December 2026 (61 days, no repeats). Installs on your phone's home screen like an app, and works offline.

## Files
- `index.html`: the app itself, with all 66 quotes built in
- `manifest.webmanifest`: the app's name, icon and colors, so phones can install it
- `sw.js`: the offline script, which saves the app on the phone after the first visit
- `icons/`: the home-screen icons

## Put it online (GitHub Pages, free)
1. Create a free account at github.com if you don't have one.
2. Click **+**, then **New repository**. Name it `daily-philosophy`, set it to **Public**, and click **Create repository**.
3. On the new repo page, click **uploading an existing file**. Drag in everything in this folder, including the `icons` folder. Then click **Commit changes**.
4. Go to **Settings**, then **Pages**. Under "Branch", choose `main` and `/ (root)`, then click **Save**.
5. Wait about a minute. Your app will be at `https://YOUR-USERNAME.github.io/daily-philosophy/`.

## Install it on your phone
- **iPhone:** open the link in **Safari**, tap **Share**, then **Add to Home Screen**.
- **Android:** open the link in **Chrome**, tap the **⋮** menu, then **Install app** (or **Add to Home screen**).

Open it once while you're online. After that, it works with no connection.

## Updating it later
Edit the files and upload them again. Then change `VERSION` in `sw.js` (for example `"v1"` to `"v2"`), so phones download the new version instead of using the saved one. Phones pick up the update the next time the app is opened, or the time after that.
