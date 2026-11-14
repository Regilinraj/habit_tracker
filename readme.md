# Habits

A tiny habit tracker that runs entirely in the browser. Add a habit, tick it
off each day, and watch your streak grow. No account, no server, no tracking —
your data stays in your browser's `localStorage`.

**Live demo →** https://Regilinraj.github.io/habit_tracker/

## About

I wanted a habit tracker that loads instantly and doesn't ask me to sign up.
Every app I tried wanted an account, a subscription, or both. This is a single
page with no dependencies and no build step — just HTML, CSS, and JavaScript.

## Features

- Add and delete habits
- Tick a habit off for today
- Automatic streak counting (consecutive days)
- Streaks of 3+ days are highlighted
- Data persists across refreshes via `localStorage`
- Works offline, works on mobile, no build step

## How to run

No install, no npm, no build.

**Option 1 — just open it**

Double-click `index.html`. Works in most browsers.

> Some browsers restrict `localStorage` on `file://` URLs. If your data
> doesn't survive a refresh, use Option 2.

**Option 2 — local server (recommended)**

```bash
python3 -m http.server 8000