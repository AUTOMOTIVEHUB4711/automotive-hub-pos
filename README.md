# Automotive Hub POS

A lightweight workshop POS application for managing inventory, job cards, and bills.

## Features
- Inventory panel with search
- Add items to current job card
- Quantity controls and remove functionality
- Total calculation in PKR
- Customer and vehicle input fields
- Printable bill/receipt generation
- Local bill history
- Offline support via service worker and manifest
- Responsive layout for desktop and tablets

## Run locally
Open `index.html` in a browser.

## Files
- `index.html` — Main app UI and logic
- `manifest.json` — PWA manifest
- `sw.js` — Service worker for offline caching
- `icon.svg` — App icon

## Notes
This project stores inventory and cart data in `localStorage` for quick workshop usage and works as a PWA when served from a local web server or a static hosting provider.
