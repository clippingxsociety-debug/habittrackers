# Habitly — Personal Habit Tracker

## Included
- Premium responsive mobile-first UI with dark/light themes
- Add, edit, delete and complete habits
- Daily completion percentage, streaks, weekly goals
- Weekly, monthly and yearly analytics
- Calendar history and per-habit last-30-day stats
- Local persistent storage, JSON export and restore
- Offline app shell through a service worker (requires HTTPS hosting and one initial online load)

## Important limitations
This version stores data locally in the browser on this device. It does **not** include automatic cloud sync between devices. Cloud sync requires a configured backend/database and a safe authentication strategy; do not put private service-role keys in frontend code.

## Host free using GitHub Pages from an iPhone
1. On your iPhone, open https://github.com/ and create/sign into an account.
2. Create a new **public** repository named `habitly`.
3. Upload `index.html`, `manifest.json`, `sw.js`, and `icon.svg` from this ZIP to the repository root.
4. In repository **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to publish. Open the Pages URL in Safari and allow it to load once online.
6. In Safari, use **Share → Add to Home Screen** to install it like an app.
7. Test offline by opening it once, then enable Airplane Mode and reopen it.

GitHub Pages public repositories are public hosting: these files contain no personal habit data or API keys. Habit data stays in the browser's local storage.

## Backups
Use Settings (gear) → Export backup regularly. To move data to another browser/device, export the JSON there and use Restore backup on the other device. This is manual transfer, not cloud sync.
