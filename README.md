# AeroDash — Drone Delivery Data Dashboard

ENGR 321 Project 1 prototype: a drone delivery operations app and fleet data dashboard, packaged as an installable web app (PWA).

## Live demo

Once GitHub Pages is enabled for this repo, the site will be live at:

`https://<your-username>.github.io/<repo-name>/`

## Install it as an app

Because this includes a manifest and service worker, it can be installed like a native app instead of just opened as a webpage:

- **iPhone/iPad (Safari):** open the live link → Share icon → "Add to Home Screen"
- **Android (Chrome):** open the live link → ⋮ menu → "Install app" (or "Add to Home Screen")
- **Desktop (Chrome/Edge):** open the live link → click the install icon in the address bar

Once installed, it opens full-screen with no browser chrome and works offline (the service worker caches both pages after the first visit).

## Files

- `index.html` — six-screen delivery flow prototype (fleet dashboard, address & drop-zone input, drop-zone/geofence selection, live tracking, confirmation & notifications, emergency abort/return-to-base)
- `dashboard.html` — fleet analytics data dashboard (KPIs, delivery volume, on-time trend, battery health, zone performance), linked from the fleet dashboard screen
- `manifest.json` — app name, icons, and standalone display mode
- `sw.js` — service worker for offline caching
- `icons/` — app icon set (192px, 512px, maskable, and Apple touch icon)

## Course context

Built for ENGR 321 Project 1 (Human Factors / Systems Engineering) to satisfy the Part 2 system design deliverables: diagram, UI flow, wireframes, and a working code/prototype link.
