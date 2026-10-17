NOOR — UPDATED BROWSER APP PACKAGE (v3)

FILES
- index.html: the app
- manifest.webmanifest: Home Screen / PWA metadata
- sw.js: basic app-shell caching for hosted HTTPS use; cache version was bumped so this update can replace the old cached app

UPDATE YOUR EXISTING GITHUB PAGES SITE
1. Open the same repository where your Noor site is published.
2. Upload/replace all four files from this folder directly in the repository root.
3. Commit the changes and wait a few minutes for GitHub Pages to deploy.
4. Open the same GitHub Pages address in Safari. If it still shows the old app, refresh or open a private tab once.

WHAT CHANGED
- Auto-scroll stops on screen interaction, keyboard interaction, visibility change, and navigation to another app tab.
- Qur'an reading now uses the API's 604-page Madinah Mushaf page divisions and appends consecutive pages as you scroll, rather than requiring next/previous-surah page buttons.
- A sticky animated progress indicator shows Qur'an page/overall progress and current surah/ayah/surah progress.
- Adhkar uses a large circular tap counter, a small upward fading +1 animation, default SubhanAllah/Alhamdulillah/Allahu Akbar options, and a custom saying/goal option.

IMPORTANT
- Page groupings follow the 604-page Mushaf divisions supplied by the Qur'an API, but responsive line wrapping/font rendering may not be pixel-identical to a printed Mushaf on every phone.
- Qur'an text and optional translations are fetched live from AlQuran Cloud; an internet connection is needed. Verify text/translation sources and licensing before public or commercial release.
- Prayer times are fetched from AlAdhan. Verify calculations with your local mosque.
- Prayer reminders are best-effort only; browsers cannot reliably deliver scheduled reminders when the app is closed.
- Qibla sensors require a compatible phone/browser, permission, HTTPS, and a suitable sensor. A bearing is shown when location is available.
- Zakat is a simplified estimate, not a fatwa. Nisab and Zakat al-Fitr rates must be entered/verified by the user.
- Bookmarks, progress, and counters are stored in localStorage on that browser/device; they do not automatically sync across devices.
- For production: conduct security/privacy, accessibility, religious-content, licensing, and device testing; add reliable notifications and reviewed offline content.
