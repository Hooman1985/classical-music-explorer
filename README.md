# The Classical Music Explorer

A mobile-first PWA prototype.

## Run locally
Because service workers require HTTPS or localhost, do not open index.html directly using file://.
From this folder run:
- Python: `python -m http.server 8000`
- Then visit `http://localhost:8000`

## Deploy
Upload the folder contents to a static HTTPS host such as GitHub Pages or Netlify. The service worker will cache the app shell and JSON data for offline use after the first successful load.

## Included
- 31 composer profiles (Persian descriptions, English names and work titles)
- Period overview and vertical timeline
- Music Detective quiz
- Favourites, local notes, quiz score
- JSON export of personal data

## Notes
This is a first functional foundation. User data is currently stored in localStorage; the next iteration should migrate it to IndexedDB and add import/restore, richer composer pages, verified work catalogues, and audio listening links. Google Fonts are optional online enhancements; system serif/sans fonts remain as fallbacks.
