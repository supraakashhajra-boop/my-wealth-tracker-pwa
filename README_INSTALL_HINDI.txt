MY WEALTH TRACKER V3.8.0 — PWA INSTALL FIX PACKAGE
This package keeps the app files and all three icons in the repository root.

IMPORTANT: Upload the CONTENTS of this folder directly to the repository root:
index.html
manifest.webmanifest
sw.js
icon-192.png
icon-512.png
icon-512-maskable.png
README_INSTALL_HINDI.txt

The manifest icon paths and service-worker precache paths now match these root-level icon files.
GitHub Pages settings: Deploy from a branch -> main -> /(root).

After uploading and committing:
1. Wait for GitHub Pages deployment to complete.
2. Open the published HTTPS site in Chrome.
3. Refresh the page, then close/reopen the tab.
4. If Chrome still shows the old install state, clear site data/cache for this GitHub Pages site, reopen it, and wait for service worker registration.
5. Use Chrome menu -> Install app. The app icon should be sourced from the manifest.

DATA SAFETY:
Keep the old app and a fresh JSON backup until the hosted PWA has been rechecked.
Never upload backup JSON, PINs, passwords, or private financial data to GitHub.
This is a static PWA; no cloud sync, Zerodha API, or live market feed is included.
