# PitchPilot

PitchPilot is a cricket tournament operating system for tournament setup, team/group management, fixture generation, per-day scheduling, match move/swap operations, match-day control, results/NRR, playoffs, poster publishing, and public tournament views.

## Current production app

https://hariharan-t-personal-portfolio.vercel.app/pitchpilot/

## Current product version

PitchPilot V9.3 — Simple Organizer

### Main organizer flow

- Home
- Setup
- Schedule
- Match Day
- Publish

### Core capabilities

- Quick Setup with recommended tournament structure
- Arbitrary/odd team counts and balanced groups
- Group + knockout, league, IPL-style, World Cup-style, Champions League-style and knockout formats
- Per-date and per-weekday match limits
- Custom daily time slots, reserve/no-match days and locked days
- Fair fixture generation with team/venue/rest constraints
- Move a single match while preserving its Match Number
- Swap two match scheduling slots while preserving both Match Numbers
- Conflict validation, alternate-slot suggestions, force override, Undo and schedule history
- Match-day control room
- Results, points table and Net Run Rate
- Qualification and playoff planning
- Fixture downloads and poster publishing
- Simple Mode / Advanced Mode
- Reusable Guided Tour
- Browser-local persistence and backup/restore

## Architecture

The current app is intentionally dependency-free and runs entirely in the browser. Tournament data is stored using `localStorage`. No AI agents, API keys, or backend services are required.

## Deployment

The standalone project is suitable for Vercel static hosting. Once the dedicated repository is created, deploy the repository root as a static site. A custom domain can then be attached from Vercel Domains.

## Domain status checked 2026-09-08

- `pitchpilot.com` — unavailable
- `pitchpilot.app` — unavailable
- `pitchpilot.live` — available when checked
- `pitchpilotcricket.com` — available when checked

Domain availability can change and should be rechecked before purchase.
