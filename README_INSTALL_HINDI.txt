MY WEALTH TRACKER V3.8.0 — COMPLETE PWA PACKAGE
Selected app icon: OPTION 1 — Bull + Growth (Forest Green & Gold)

PACKAGE CONTENTS
- index.html: MY WEALTH TRACKER V3.8.0 app (PWA install hooks added; app logic retained)
- manifest.webmanifest: PWA identity and icon references
- sw.js: service worker for app shell/offline loading
- icons/icon-192.png: selected Option 1 icon
- icons/icon-512.png: selected Option 1 icon
- icons/icon-512-maskable.png: maskable-safe version of selected icon

GITHUB PAGES SETUP
1. Create a NEW GitHub repository, for example: my-wealth-tracker-pwa.
2. Upload the CONTENTS of this folder to the repository ROOT (not the outer folder itself):
   index.html
   manifest.webmanifest
   sw.js
   icons/ (folder with all 3 PNG files)
   README_INSTALL_HINDI.txt
3. Repository -> Settings -> Pages.
4. Under Build and deployment choose Deploy from a branch.
5. Branch: main; Folder: /(root); Save.
6. Wait for GitHub Pages to publish the HTTPS URL.
7. Open that HTTPS URL in Chrome on Android.
8. Confirm the app loads, then Chrome menu -> Install app / Add to Home screen.

DATA MIGRATION — IMPORTANT
The old local HTML and hosted PWA use different browser origins/storage.
Old localStorage data will NOT automatically appear in the PWA.
Before moving:
1. Open the old V3.8.0 app.
2. Export a fresh JSON backup and keep a second copy somewhere safe.
3. Open the hosted PWA URL and use Import Backup to restore that JSON.
4. Verify transaction count, portfolio, trading journal, settings, PIN, and backup history.
5. Do not delete or overwrite the old HTML/backup until all checks pass.

SECURITY / LIMITATIONS
- Do not upload API keys, passwords, PINs, backup JSON, or private financial data to GitHub.
- Treat the published Pages website as accessible to anyone who has its URL; do not rely on the app PIN as website access control.
- This package has no cloud database, cross-device sync, Zerodha API, or live market data.
- App data remains in this browser/device storage unless exported. Keep regular JSON backups.
- Service worker caches the app shell. Browser-permission features may behave differently in installed mode.
- The app's accounting and trading logic are retained; this package adds the PWA shell and selected icon.
