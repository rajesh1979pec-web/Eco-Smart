# Climate Smart — GitHub Pages-ready app

A responsive, installable-style climate assistance web app for farmers, shopkeepers, dairy owners, workers, small businesses and households.

## Publish without writing code (GitHub web interface)
1. Sign in to GitHub and create a new public repository named `climate-smart`.
2. Choose **Add file → Upload files**.
3. Upload `index.html`, `manifest.webmanifest`, `service-worker.js`, and `README.md` from this folder.
4. Choose **Commit changes**.
5. Open repository **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
7. Wait for GitHub Pages to publish. Open the URL shown in Settings → Pages on your phone or computer.

## Features
- Live current weather via Open-Meteo geocoding and forecast APIs
- Current UV index, rain chance, sunrise/sunset, hourly outlook and 7-day forecast
- Location search and optional device geolocation permission
- Basic heat/UV/rain indicators and climate reminders
- Farmer crop-protection and irrigation reminders, shop refrigerator safety, dairy heat-stress tips, worker heat-safety tips
- Power-cut business-loss and battery-backup calculators
- Solar savings and electricity-related carbon estimates
- Water use and electricity tracking; local records and JSON export
- English/Hindi interface, browser speech input when supported, text-to-speech when supported
- Emergency safety checklist, responsive layout and basic offline caching
- Green Climate Smart branding and “AI-assisted prototype” watermark

## Important limitations
- Weather data requires internet and is supplied by Open-Meteo.
- Weather indicators are simple app-generated reminders, **not official IMD/district emergency alerts**.
- Browser notification permission is included, but real scheduled background push notifications require a push service/backend.
- Data is saved in browser local storage on the device; there is no user account or cloud synchronization.
- For geolocation and PWA service workers, use the deployed HTTPS GitHub Pages URL or localhost.
- Estimates are for planning only. Follow official local advisories and qualified safety guidance.
