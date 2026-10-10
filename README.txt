AXLFF07 SENSI — INSTALLABLE WEB APP (PWA)

CONTENTS
- index.html: the responsive companion app
- manifest.webmanifest: app name, display settings and icons
- service-worker.js: caches the app shell for offline reopening after first load
- icons/: 192px and 512px install icons

IMPORTANT
This is a fan-made Free Fire practice companion. It does not connect to, modify, automate, or overlay Free Fire. Sensitivity values are starting suggestions only.

INSTALL ON ANDROID
1. Publish these files to a public HTTPS website. GitHub Pages is one possible free host.
2. Open the published HTTPS page in Chrome on your POCO.
3. Tap Chrome ⋮ and choose Install app. If that is not shown, choose Add to Home screen.
4. Launch Axlff07 Sensi from its new home-screen icon.
5. Open it once while online so the service worker can cache its files; then try airplane mode to test offline reopening.

GITHUB PAGES QUICK ROUTE (PHONE-ONLY)
1. Sign in to GitHub in Chrome and create a new public repository, for example axlff07-sensi.
2. Open the repository, use Add file → Upload files, and upload the CONTENTS of this folder (index.html, manifest.webmanifest, service-worker.js, icons folder, README.txt).
3. Commit the files to the main branch.
4. In repository Settings → Pages, set deployment to deploy from a branch, select main and /(root), then Save.
5. Wait for GitHub Pages to publish the site. Open the URL shown in Settings → Pages. It should begin with https://.
6. In Chrome, open that URL and install/add to Home screen.

If the mobile GitHub interface does not let you upload the folder in one go, upload the files individually; create the icons folder and upload both icon PNGs into it. GitHub Pages URLs can take a few minutes to become available.

PRIVACY
Preference saving uses this browser's localStorage. Do not upload private keys or personal data.
