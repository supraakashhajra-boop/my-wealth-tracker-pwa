SUPRAAKASH WEALTH TRACKER — V4.1.2 PWA INSTALL FIX
===================================================

This package keeps the approved V4.1.2 app HTML and adds a UNIQUE PWA APP ID.
The unique manifest ID is intended to stop Chrome from reusing the older already-installed V3.8.0 app identity.

UPLOAD TO THE ROOT OF THE SAME GITHUB PAGES REPOSITORY:
- index.html
- manifest.webmanifest
- sw.js
- icons/ (icon-192.png and icon-512.png)

Do not create a new repository. Keep the same GitHub Pages repository and URL.

BEFORE UPLOADING:
1. Open the old working app, if possible, and export a JSON backup.
2. Keep that backup safely. Do not clear Chrome site data or uninstall the old app yet.

UPLOAD:
1. Extract this ZIP.
2. In the SAME repository, replace index.html, manifest.webmanifest, and sw.js.
3. Replace both files inside icons/.
4. Commit the changes to main branch.
5. Wait for GitHub Pages deployment to finish.

INSTALL THE NEW APP:
1. Open Chrome and visit:
   https://supraakashhajra-boop.github.io/my-wealth-tracker-pwa/
2. Reload the page once after deployment.
3. Open Chrome menu (three dots).
4. Choose "Install app" (not "Create shortcut").
5. The new app should identify itself as SUPRAAKASH / SUPRAAKASH WEALTH TRACKER.
6. Keep the old app until the new app has been checked and existing data is confirmed.

IMPORTANT:
- This package uses a new manifest app ID: ./?app=supraakash-wealth-tracker-v412-final
- The app's V4.1.2 workflows and data model are not intentionally changed.
- The service-worker cache name is bumped to trigger a fresh app-shell cache.
- The app still uses browser local storage; keep the same site origin and do not clear site data.
- No cloud sync or live Zerodha integration is added.

APP VERSION: V4.1.2
APP NAME: SUPRAAKASH WEALTH TRACKER
APP ICON: Approved final Navy Blue + Gold design
