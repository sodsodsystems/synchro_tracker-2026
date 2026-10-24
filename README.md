# Synchro Tracker

A collection of lightweight, offline-first web tools for **ICpEP.SE UST-Legazpi** event management. No build step — open any file directly in a browser or host on GitHub Pages.

## Tools

| Tool | File | Description |
|---|---|---|
| **Tardiness Tracker** | [`Tardiness Tracker System.html`](./Tardiness%20Tracker%20System.html) | Real-time countdown to call time, per-person attendance marking (On time / Late / Absent), ambagan & fines calculation, and payment tracking |
| **Synchro Tracker** | [`SYNCHRO_TRACKER.html`](./SYNCHRO_TRACKER.html) | Schedule and synchronization tracker |

## Features (Tardiness Tracker)

- ⏱ Live countdown to call time with configurable grace period
- 📋 Attendance marking for 27 students + 5 faculty
- 💵 Ambagan and fines auto-calculated per person
- 💳 Per-person payment tracking with Paid / Partial / Unpaid status pills
- 📤 One-tap "Copy summary" for group chats
- 🌙 Automatic light/dark mode
- 💾 State persists in `localStorage` — no server needed

## Usage

1. Open `index.html` (or any tool directly) in a browser
2. No internet connection required after first load (fonts load from Google Fonts)

## GitHub Pages

Hosted at: `https://<your-username>.github.io/<repo-name>/`

Enable via **Settings → Pages → Source: Deploy from branch `main` (root `/`)**

## Tech Stack

Pure HTML · CSS · Vanilla JS · No dependencies · No build step
