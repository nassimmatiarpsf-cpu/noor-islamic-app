NOOR — BROWSER APP PACKAGE

FILES
- index.html: the app
- manifest.webmanifest: Home Screen / PWA metadata
- sw.js: basic app-shell caching for hosted HTTPS use

PUBLISH ON YOUR EXISTING GITHUB PAGES SITE
1. Open your repository on GitHub.
2. Upload/replace index.html at the repository root.
3. Upload manifest.webmanifest and sw.js at the same root.
4. Commit the changes.
5. Wait for Pages to redeploy, then open the existing GitHub Pages address in Safari.
6. If the old version remains, refresh the page or open it in a private tab. A service worker may briefly cache the old shell.

IMPORTANT
- Noor is a browser-based app/PWA starter, not yet a native App Store app.
- Qur'an Arabic text and optional translations are fetched live from AlQuran Cloud. Internet is needed to load them. Verify data and licensing before commercial release.
- Prayer times are fetched from AlAdhan. Check calculations with your local mosque.
- Prayer reminders are best-effort only; browsers cannot reliably deliver scheduled reminders when the app is closed.
- Qibla compass sensors require a compatible phone/browser, permission, HTTPS, and a suitable sensor. A bearing is shown when location is available.
- Zakat is a simplified estimate, not a fatwa. Nisab and Zakat al-Fitr rates must be entered/verified by the user.
- Bookmarks, progress, and counters are stored in localStorage on that browser/device. They do not automatically sync across devices.
- For production: conduct security/privacy, accessibility, religious-content, legal/licensing, and device testing; add reliable notifications and reviewed offline content.
