# Prime Creator

A free, installable web-app/PWA starter for Team Prime.

## Files
- index.html — app
- manifest.webmanifest — install/app metadata
- sw.js — offline caching
- icon.svg — app icon

## Run it
Open index.html in a browser for a preview.

## Make it installable on phones
The service worker and manifest need to be served over HTTPS (or localhost). GitHub Pages can host it over HTTPS. Once hosted, compatible browsers can offer "Install app"/"Add to Home Screen".

For a true APK/IPA or app-store release, this web app can later be packaged with a PWA/app wrapper.
