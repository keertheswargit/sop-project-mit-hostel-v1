# Hostel Laundry — Digital Laundry Card System

A mobile-first prototype that replaces the physical hostel laundry card with a
digital one. Built as a college project, structured so it can later grow into
a full **Hostel Companion App** (laundry, complaints, mess, maintenance and
announcements).

## Live demo

Open `index.html` in a browser, or serve the folder with any static server.

## Screens

- **Login** — student ID + password
- **Home** — laundry balance, quota progress, quick actions, recent activity
- **Digital Laundry Card** — replaces the physical card, with a QR placeholder
- **Submit Laundry** — pick categories and quantities, confirm in a modal
- **History** — timeline of past submissions
- **Status** — Submitted → Washing → Ready → Collected tracker
- **Notifications** — laundry updates
- **Profile** — student details + placeholders for future modules

## Tech

Vanilla HTML, CSS and JavaScript. No build step, no dependencies.

```
index.html   structure for every screen
style.css    design tokens + component styles
script.js    dummy data + all interactions
```

All data in `script.js` is in-memory dummy data for demonstration —
swap it for real API calls when wiring up a backend.

## Roadmap

- Complaints module
- Mess information
- Maintenance requests
- Announcements
- Backend integration (auth, real laundry records, QR scanning by staff)
