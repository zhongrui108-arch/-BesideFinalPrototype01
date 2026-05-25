# Beside — Full Journey Prototype

A high-fidelity interactive prototype of Beside, a micro-connection app for parks and public spaces in Savannah, GA.

## View live

This is a single self-contained HTML file. Open `index.html` in any modern browser — no install, no build step, no internet required.

## Publish on GitHub Pages

1. Create a new GitHub repository (e.g. `beside-prototype`) — public.
2. Upload these two files (`index.html` + this README) to the repo root.
3. In the repo: **Settings → Pages → Source: Deploy from branch → Branch: `main` / `/root` → Save**.
4. Wait ~30 seconds, then visit:
   `https://<your-username>.github.io/<repo-name>/`

## What's inside

The prototype walks through the full visitor and organizer journey:

- **Visitor:** Landing → Role select → 7-question onboarding → Profile → Match events → Detail → Map → Pre-event check-in → Arrival → During event (with rebook flow) → Feedback → Loyalty stickers → Done
- **Organizer:** Onboarding → Preview & publish → Live dashboard → Pre-event readiness check → Attendee list → In-session check-in → Post-event feedback → Visitor feedback summary → Host loyalty

## Stack

Plain HTML + inline React (via Babel) — everything inlined into one offline-capable file.
