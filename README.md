# Verve — Event Discovery & Booking

**A responsive event discovery and reservation portfolio project.**

Verve is a fictional UK events platform built with semantic HTML, custom responsive CSS, vanilla JavaScript, and Font Awesome SVG icons. It is designed to show frontend UI design, state management, filtering, dynamic rendering, client-side validation, data persistence, and accessibility fundamentals. A separate **full-stack Django edition** adds session-scoped database-backed events and reservations.

## Features

- 12 **fictional sample events**, with demo dates rolling forward over time, across music, arts, technology, food, wellness and outdoors.
- Search by activity, venue, category or city; filter by city, date and category; sort by time or price.
- Switch between a card-based catalogue and interactive month calendar.
- Save favourite events (browser-local), including saved-only filtering.
- Explore event details and select ticket types and quantities.
- Complete a **demo booking** with validation, confirmation reference, and My Tickets page.
- Cancel demo reservations; print bookings; download an `.ics` calendar file.
- Create and browse locally hosted demo events using the event creation form.
- Responsive UI tested at mobile, tablet and desktop widths; supports keyboard interaction and reduced motion.
- Unsplash event photos where available, with original SVG poster fallbacks when offline.
- Font Awesome icons loaded as SVG geometry, so icons still appear without a CDN.

## Use it

1. Extract the ZIP. **Do not upload the ZIP itself to GitHub.**
2. Open `index.html` in a browser, or serve the folder with `python3 -m http.server 8000` and open `http://localhost:8000`.
3. For GitHub, upload **all files at the repository root**; GitHub Pages can serve this edition directly from the root of `main`.

Suggested repository name: `verve-event-booking-app`.

## File guide

- `index.html`: semantic layout, event and booking dialogues.
- `styles.css`: layout, responsive breakpoints, modal, calendar and UI styles.
- `events.js`: fictional sample event dataset.
- `app.js`: filters, calendar, favourites, booking state, localStorage persistence and optional API integration.
- `icons.js`: Font Awesome Free SVG paths + custom minimalist SVG shapes (no font files).
- `favicon.svg`: brand mark.
- `CREDITS.md`: external images and licences.

## Demo limitations and ethical transparency

The listings are **entirely fictional**. This is NOT a real ticket-booking service; it charges no money, sends no emails, has no real accounts and does not issue valid admission tickets. In the static edition, bookings, events and attendee names/emails remain in the visitor's own browser `localStorage`; do not enter sensitive personal information. Clearing the browser data clears these records. Capacity checking is illustrative and is **not shared between visitors**.

In the optional Django edition, events and bookings live in a local SQLite database, and bookings are tied to a browser session. It is a local development example, **not production-ready**: it has no authentication, payment gateway, email notification, organiser verification, hardened inventory concurrency or production deployment configuration.

## Portfolio presentation and academic integrity

Explain what parts you understand, personalise the experience, and document your own contributions and improvements. If using this in assessed coursework, disclose AI assistance according to the assessment's rules.

Built for UI/development demonstration, not for commercial use as-is.

## Icon rendering

The project uses the self-contained `icons.js` SVG icon renderer. It does not load the Font Awesome icon-font CSS CDN, because combining both systems can render each icon twice (for example the favourites heart). Font Awesome SVG vector geometry used in `icons.js` remains credited in `CREDITS.md`.
