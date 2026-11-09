MY WEALTH TRACKER V3.3.1 — PWA PACKAGE

IMPORTANT: Original local HTML app and its backups are not changed.

WHAT IS INCLUDED
- index.html: your V3.3.1 app, with PWA manifest and service-worker registration added
- manifest.webmanifest: install name, icon, standalone display settings
- sw.js: caches the app shell for offline reopening after first successful load
- icons/: Android PWA icons

HOW TO USE
1. Keep your existing V3.3.1 local HTML and latest JSON backup safe.
2. Upload the CONTENTS of this folder to a static HTTPS hosting service. Do not open index.html directly from the phone's Downloads folder.
3. Open the hosted HTTPS address ending in /index.html in Google Chrome.
4. Choose the latest MY WEALTH TRACKER JSON backup using Choose Backup JSON, then press Restore Backup.
5. Verify Dashboard totals, Transactions, Portfolio quantities/cost, Journal setups, and Old Tradebook.
6. Export a fresh backup from the hosted PWA.
7. Only after successful verification, use Chrome menu > Install app (or Add to Home screen, depending on Chrome/device).
8. Test closing and reopening the installed icon. For offline use, first open the app online once so its shell can be cached.

DATA SAFETY
- Browser storage is separated by site origin. Your current content:// local file data will NOT automatically appear at the hosted HTTPS address.
- Restore your latest JSON backup into the hosted PWA. Do not delete the old local app or backups.
- This package does not add cloud sync, live market data, Zerodha API, or server-side backup.
- PWA local data remains on this browser/device. Export backups regularly.
- Service worker caches app files only; it does not upload transaction records.
