# Load Option Generator

A free single-page tool for US truck dispatchers to create a temporary load option in seconds and send it as copy-paste text, a PNG image, or via WhatsApp.

## What it does

- Form: truck/equipment type, pickup date, drop-off date, pickup by ZIP code, drop-off by ZIP or by state → city select, loaded miles, deadhead, rate per mile and total rate
- ZIP code auto-fills city & state (free Zippopotam API, no key needed)
- Loaded miles auto-calculated as road miles between the two ZIPs (free OSRM routing)
- Rate per mile ↔ total rate auto-calculates both ways
- Presented pickup: pick a city within 30 miles of the real pickup ZIP — that city shows as the pickup and its distance becomes the deadhead
- Live preview in a clean copy-paste text format (primary output), plus a ticket preview
- Copy Text, Download PNG, WhatsApp share
- Save loads in the browser (local storage) with Reuse/Delete — no account, no server, no database

## Usage

Open `index.html` in any browser, or deploy the single file to any static host (Vercel, Netlify, GitHub Pages).

No build step, no dependencies, no paid APIs.
