# Tape — MMA training log

Free, offline, no accounts, no subscriptions. Everything is stored on your phone.

## Put it on your phone (free, ~5 minutes)

1. Create a free GitHub account, then a new **public** repository called `tape`.
2. On the repo page: **Add file → Upload files**. Drag in every file from this folder and commit.
3. Go to **Settings → Pages**. Under "Build and deployment", set Source to **Deploy from a branch**, Branch **main**, folder **/ (root)**. Save.
4. After about a minute your app is live at `https://<your-username>.github.io/tape/`.
5. Open that link in **Chrome on your Android phone** → ⋮ menu → **Install app** (or "Add to home screen").

It now opens from your app drawer like any other app and works with no signal.

## Back up your data

Your log lives only on your phone. In the app: ⚙ → **Export backup**, then save the file to Google Drive.
Clearing Chrome's site data or uninstalling Chrome will erase the log; restore with ⚙ → **Import**.

## Updating the app

Upload the changed files to the repo, and change `tape-v1` to `tape-v2` (etc.) at the top of `sw.js`.
Your phone picks up the new version the next time you open the app twice.

## Files

- `index.html` — the whole app
- `sw.js` — makes it work offline
- `manifest.webmanifest` + `icon-*.png` — lets Android install it as an app
