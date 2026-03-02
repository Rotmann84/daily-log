Alcohol Tracker (Daily Log)

A minimal, privacy-focused alcohol tracking web app built with pure HTML, CSS, and JavaScript.
Runs entirely in the browser — no backend, no database, no cloud storage.

---
Description

The Alcohol Tracker is a minimal, privacy-focused daily alcohol tracking web app.
The application is intentionally built to:
- send no data to any server
- use no backend or database
- require no login
- store all data locally in the browser

The entire app runs client-side.

---
Features

Manual daily tracking:
- No alcohol/Alcohol (with optional reason)
- Edit and backfill previous days
- CSV import (Date; Alcohol; Reason)
- CSV export (only recorded days)
- Dynamic yearly statistics
- Overall statistics
- Current alcohol-free streak (based on continuous recorded days)
- Longest alcohol-free streak
- Last 21 days overview (including open days)

---
Privacy & Data Storage

- All data is stored in the browser’s localStorage.

There is:
- no server communication
- no cloud sync
- no data transfer to GitHub

If browser storage is cleared, data will be lost.
Regular CSV export is recommended for backup purposes.

---
Technical Stack

- Pure HTML
- CSS (no framework)
- Vanilla JavaScript

Deployed via GitHub Pages
