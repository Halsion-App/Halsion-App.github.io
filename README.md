# Halsion website

Static pages for the store listings: `index.html` (home), `privacy.html` (privacy policy URL), `terms.html`,
`support.html` (support URL), and `app-ads.txt` (AdMob; replace the placeholder publisher ID before launch).
No build step: host the folder as is (GitHub Pages, Netlify, Firebase Hosting or any static host), then point the
domain (for example halsion.in) at it. Keep `privacy.html` in step with the in-app policy (`AboutContent.swift`,
Android `strings.xml`).
