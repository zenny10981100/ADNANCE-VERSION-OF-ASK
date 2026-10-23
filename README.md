# ASK — Personal workspace

A responsive Progressive Web App for notes, reminders, tasks, and calculations.

## Run locally
Because service workers require a secure context, run ASK from `localhost` or HTTPS rather than opening `index.html` directly.

If Python is installed, open a terminal in this folder and run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Install on a phone
1. Upload the folder to an HTTPS host (for example, GitHub Pages, Netlify, or your own web server).
2. Open the deployed URL in your phone's browser.
3. Android/Chrome: use the install prompt or browser menu → Install app.
4. iPhone/Safari: Share → Add to Home Screen.

## Features
- Notes with search, create, edit, and delete
- Reminders with in-app alerts while the app is open; optional browser notifications
- Task list with complete/delete and filters
- Calculator with keyboard input
- Light and dark themes
- Responsive mobile layout and offline app-shell caching
- Local storage for app data

## Notes about browser limitations
- Data is saved in this browser on this device. Clearing browser data can remove it.
- A service worker needs HTTPS or localhost.
- Web apps cannot guarantee scheduled alarms while fully closed on every device/browser. Notification and background behavior depends on platform support.
