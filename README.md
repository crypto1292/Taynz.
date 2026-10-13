# Taynz. — iPhone PWA

A simple, privacy-first cycle tracker and wellness companion.

## Run locally
Open `index.html` in a browser for a local demo. For installability/offline caching, serve the folder over HTTPS (GitHub Pages works well) or localhost.

## Publish with GitHub Pages
1. Create a repository or open your existing one.
2. Upload `index.html`, `manifest.json`, `sw.js`, and `icon.svg` to the site root.
3. Enable GitHub Pages in repository Settings → Pages.
4. Open the HTTPS site in Safari on iPhone → Share → Add to Home Screen.

## Current features
- Cycle setup and predicted cycle phases
- Calendar with estimated period/fertile/ovulation days
- Period start/end logging
- Symptom, mood, energy and note check-ins
- Phase-based food and comfort suggestions
- User-controlled invitation text and JSON summary export
- Local data export and delete controls
- PWA manifest and service worker

## Important sharing limitation
This starter version stores data locally in the current browser/device. The invite feature shares a manually selected snapshot; it does **not** provide live cross-device syncing. To enable secure partner access to changing cycle data, add an authenticated backend, consent controls, access revocation, encrypted transport/storage, and a clear deletion policy.

## Health note
Taynz. provides general education and estimates, not diagnosis or contraception. Predictions can be wrong. Seek medical care for concerning symptoms; urgent warning signs are included in the app.
