# Thesis & EP Tracker

A single-page web app for a daily log (wake, sleep, gym, thesis, PhD and EP hours), a locum roster and PhD and EP milestones. All times run on Perth time.

## Files

- `index.html`: the app
- `manifest.webmanifest`, `sw.js`: make it installable and work offline
- `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`: home screen icons

## Data

Everything is stored in the browser on the device that uses it (localStorage). Nothing is uploaded and nothing personal is in this repository.

- **Back up** shares or downloads a JSON file of everything. Do it weekly and keep the file in iCloud Drive.
- **Restore** merges a backup file into the app. Use it to load the setup file the first time, or to move to a new phone.

## Updating

After uploading a new `index.html`, change `CACHE` in `sw.js` (for example `tracker-v2`) so phones pick up the new version.
