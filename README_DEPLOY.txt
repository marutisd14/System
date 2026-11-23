SYSTEM — Installable PWA Deployment Guide
=========================================

1. SHARE & INSTALL FOR FREE (2 MINUTES):
   - Unzip this folder (system-pwa-app).
   - Go to https://app.netlify.com/drop (or upload to GitHub Pages / Vercel).
   - Drag and drop the unzipped folder containing index.html, manifest.json, sw.js, and icons.
   - Share the HTTPS link! Anyone on Android (Chrome) or iPhone (Safari -> Share -> Add to Home Screen) can install SYSTEM as a full-screen app with its own icon and live camera food scanner.

2. HOW TO UPGRADE LATER:
   - Whenever you upgrade index.html, bump CACHE_NAME in sw.js (e.g. 'system-workout-v2') and re-upload the folder.
   - Users get the update automatically without losing their saved workouts, XP, or diet logs.
