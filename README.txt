# DailyTrack mobile setup

DailyTrack is a static, installable web app (PWA) with a phone-first responsive layout, touch-friendly controls, and a bottom navigation bar on small screens.

## Publish it free with GitHub Pages
1. On a computer, sign in to GitHub and create a new **public** repository named `dailytrack`.
2. Extract this ZIP file.
3. Upload all extracted files (`index.html`, `manifest.webmanifest`, `service-worker.js`, `icon-192.png`, `icon-512.png`) to the repository root.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
6. Wait for GitHub Pages to publish. Your URL will look like `https://YOUR-USERNAME.github.io/dailytrack/`.
7. Open that URL on your phone.

## Add to your phone's home screen
- Android (Chrome): open the site → tap ⋮ → **Install app** or **Add to Home screen**.
- iPhone (Safari): open the site → Share → **Add to Home Screen**.

## Important data note
Entries are saved in browser storage on the device. This version does **not** sync data between your phone and computer. Export a JSON backup regularly. Do not clear browser site data unless you have exported a backup.

Reminders are browser notifications and generally require the app/site to be open; this is not a cloud reminder service.
