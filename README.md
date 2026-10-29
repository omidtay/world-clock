# World Clock

A minimal world clock for iPhone, built as an installable web app (PWA). No App Store and no Mac needed.

- Your current city is always first; add, remove and reorder the rest.
- Each city has a 24-hour strip. Drag any strip to move through time and every city follows.
- Tap a city's time to set it ("9:00 in London") and see what that is everywhere else.
- Daylight saving is handled by the time zone database built into iOS, so changes like London's
  switch on 25 Oct apply automatically. The app also notes recent and upcoming clock changes.
- Works offline after the first visit. Light and dark mode follow the phone.

## Install on iPhone

1. Open the site in **Safari**.
2. Tap **Share** → **Add to Home Screen** → **Add**.
3. Launch it from the home screen; it opens full screen like a normal app.

## Hosting

Static files only (`index.html`, `sw.js`, `manifest.webmanifest`, `icons/`), served by GitHub Pages
from `main` / root.

When you change the app, bump `CACHE` in `sw.js` so installed copies pick up the new version.
