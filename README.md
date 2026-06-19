# Dotwise

A premium, offline-first **habit, goal & focus tracker** — single-page web app, installable as a PWA, with optional cloud sync (Supabase).

**Live:** _add your Vercel URL here_

## Features
- Habits with **single or multi-count** daily targets (e.g. drink water ×8)
- Weekly / Monthly / Yearly views + GitHub-style heatmap
- Goals with progress, Focus (Pomodoro) timer
- 9 themes + custom theme builder, accent colors, glow effects
- Custom emoji **or uploaded image/GIF** icons
- **Login + cloud sync** across devices (Supabase) — works fully offline too
- Installable PWA (Add to Home Screen)

## Tech
- Vanilla HTML/CSS/JS — no build step
- Supabase (auth + Postgres) for sync
- Service worker for offline + auto-update

## Run locally
Just open `index.html` in a browser. (For PWA/login features, serve over HTTPS — e.g. Vercel.)

## Deploy
Hosted on Vercel — every push to `main` auto-deploys.

## Config
Supabase URL + anon key live in `index.html` (the anon key is safe to expose; row-level security protects data).
