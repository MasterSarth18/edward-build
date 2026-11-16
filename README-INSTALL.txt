EDWARD BUILD — ANDROID INSTALLATION

IMPORTANT:
This is a Progressive Web App bundle. Android Chrome cannot properly install a website opened as a local file.
It must first be hosted on an HTTPS website. The included manifest and service worker make it installable and cache the app for offline use after its first successful load.

EASY ROUTE — GITHUB PAGES
1. On your Android phone or computer, sign in to GitHub.
2. Create a new public repository named edward-build.
3. Upload ALL files and folders from this package (index.html, manifest.webmanifest, sw.js, icons/).
   Keep the folder structure exactly as provided.
4. In the repository, open Settings > Pages.
5. Under Build and deployment, choose Deploy from a branch.
6. Select branch main and folder /(root), then Save.
7. Wait for GitHub Pages to publish. Open the published https://...github.io/edward-build/ address in Chrome.
8. In Chrome, tap ⋮ > Install app (or Add to Home screen) and confirm.
   If an Install button appears inside the website, you can use that too.

AFTER INSTALLING
- Open Edward Build from its home-screen icon.
- Your records are saved in the browser/app storage on that device.
- Use Export backup regularly. Do not clear site data unless you have exported a backup.
- The app works offline after it has been loaded once while online.

Do not upload only index.html: the manifest, service worker and icons are required.
