SHUBH TOUR & TRAVELS — V5 STABLE BUILD

Upload ALL files to the GitHub Pages repository root.
Required: index.html, logo.png, branding_header.png, manifest.webmanifest, sw.js.

Verified fixes in this build:
- New bookings are listed newest-created first.
- Completed bill history is newest-first.
- Manual bill generation is protected against double-tap duplicates.
- Loyalty completion is de-duplicated by booking/bill completion key.
- Local India date handling avoids UTC date rollover errors.
- Customer contact import button is wired to the contact picker.
- Service worker uses network-first for the HTML shell and cache fallback for offline assets, with a new cache version.
- HTML no longer embeds the large logo repeatedly; logo is loaded from logo.png.

Operational data remains in browser storage. Cloud sync, if configured, remains dependent on the existing Google Apps Script endpoint.
