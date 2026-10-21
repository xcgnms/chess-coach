CHESS COACH — INSTALLABLE WEB APP

This folder contains the app shell and install metadata. To install it as an app on Android, the files must be served from an HTTPS website (opening index.html directly from Downloads does not enable PWA installation).

QUICK DEPLOY (GitHub Pages)
1. Create a GitHub repository.
2. Upload all files in this folder to the repository root.
3. In the repository, open Settings > Pages and publish from the main branch / root.
4. Open the published HTTPS address in Chrome on Android.
5. Use Chrome's menu > Install app or Add to Home screen.

ENGINE NOTE
The chess rules library and Stockfish engine are currently loaded from external CDNs, so the first launch and engine analysis require internet access. The service worker caches the app shell, not the external engine. This package is an installable web app, not a signed Android APK. Engine loading has not been verified on every Android browser.
