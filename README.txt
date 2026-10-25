MY WORKOUT COACH — iPhone-friendly workout tracker

FILES
- index.html: the app
- manifest.webmanifest: install metadata
- sw.js: basic offline cache
- README.txt: setup notes

HOW TO USE NOW
1. Open index.html in a desktop browser to test it.
2. It includes the October 25, 2026 Upper A session as a starter history record.
3. Data saves in localStorage in that browser on that device.
4. In Settings > Backup, export JSON backups regularly. CSV exports workout set data.

HOW TO ADD TO IPHONE HOME SCREEN
The app needs to be served from an HTTPS URL for reliable installation and service-worker/offline support. A simple route:
1. Create a GitHub repository and upload index.html, manifest.webmanifest, and sw.js to its root.
2. In repository Settings > Pages, publish from the main branch/root.
3. Open the published HTTPS URL in Safari on iPhone.
4. Tap Share > Add to Home Screen.

IMPORTANT DATA NOTE
Browser storage is local to the browser/device and can be cleared. The app does not sync automatically between devices. Export backups before clearing site data or switching phones. The included service worker provides basic offline caching after the site has been opened online once.

PROGRAM NOTE
Suggested weights for lifts that were not logged are placeholders, not verified prescriptions. Confirm whether your prior 185 x 6 was a barbell squat or leg press, and whether 215 x 3 was a conventional deadlift or Romanian deadlift, before relying on those main-lift starting loads. Machine stack weights vary by gym.
