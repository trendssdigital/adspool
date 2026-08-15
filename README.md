# Adspool MVP

GitHub Pages-ready single-page MVP for Adspool.

## Features
- Admin login (demo credentials shown in the UI)
- Create, edit, duplicate, publish, unpublish and delete ads
- Unique Ad ID generation (`ADS-000001` format)
- Categories and category filtering
- Up to 15 services per ad with responsive sizing
- Automatic background/text contrast
- Start and end date/time scheduling
- Automatic status lifecycle: Scheduled → Published → Expired
- Expired ads are automatically removed from Public Ads
- Expiry checks on page load, tab focus/visibility and every 30 seconds
- Published/scheduled/draft/expired filters and pagination
- Public ad cards with Call/WhatsApp actions
- LocalStorage persistence for demo purposes

## GitHub Pages
Upload `index.html` to the repository root and enable GitHub Pages from the `main` branch, `/ (root)`.

## Important MVP limitation
This version uses browser `localStorage`, so ads are stored per browser/device. GitHub Pages is static hosting and does not provide a shared database or server-side scheduler. For a production Adspool platform, add a backend/database and server-side expiry rules.
