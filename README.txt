AFTERGLOW — INSTALLABLE WEB APP

Files included:
- index.html: your game, with PWA metadata and service-worker registration added
- manifest.json: install name, display mode, colours and icons
- service-worker.js: caches the game shell for offline launches
- icons/: app icons

IMPORTANT: A PWA must be served from HTTPS (or localhost). Opening index.html directly as a file will not enable installation/offline caching.

EASY HOSTING WITH GITHUB PAGES:
1. Sign in to GitHub and create a new repository (e.g. afterglow-game).
2. Upload the contents of this folder (index.html, manifest.json, service-worker.js, icons folder).
3. In the repository, open Settings > Pages. Choose Deploy from a branch, select main and /(root), then Save.
4. Wait for GitHub Pages to publish the site and open its HTTPS URL.
5. In Microsoft Edge or Chrome on Windows, use the install icon in the address bar or menu > Apps > Install this site as an app.
6. On Android Chrome, open the site menu and choose Install app / Add to Home screen.

OFFLINE NOTE: Open the hosted game online once and allow it to finish loading before testing offline. The Google Fonts used by the game are external, so the game itself can work offline but those fonts may fall back to system fonts without internet.
