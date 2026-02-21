# Project Context — Atlantic AI Hackathon Sponsor Page

> This file is maintained across sessions so that context compaction doesn't lose critical info.
> Always read this file at the start of a new or compacted session.

## Project Overview
- **What:** Sponsor landing page for "The Atlantic AI Hackathon" in Halifax, NS (2026)
- **Who:** Organized by Jitakshi (Event Lead & Tech Partnerships) and Bethany Wilkie (Business Strategy)
- **Purpose:** A "good to read and watch" evidence page sent to potential sponsors via email. No form needed — conversations happen over email.
- **Previous event:** Lovable Halifax Women's AI Hackathon, Dec 2025 — 70 participants, 5 sponsors, 7 winners, 3 judges, 100% sold out
- **New event targets:** 100-150 participants, 10-15 sponsors, full day

## Tech Stack
- Single self-contained HTML file (`sponsor.html`) — no build tools, no frameworks
- Pure CSS + vanilla JS (no Tailwind)
- Google Fonts: Jost (geometric sans, Futura-like) + JetBrains Mono (monospace labels)
- Colors: near-black (#09090B), off-white (#FAFAF9), lemon-green accent (#CBEF43)
- Deployed via GitHub Pages from: https://github.com/JitakshiS/sme-halifax-hackathon.git
- Every `git push` to main auto-deploys via GitHub Actions workflow

## Design Preferences (User-confirmed)
- Font: Simple sans-serif like Futura/Optimistic → using Jost
- Accent color: Lemon/lemon-greenish (#CBEF43)
- Style: Minimal, modern, 2026-level design — NOT basic/2024-style
- No prices anywhere (flexibility for email negotiations)
- No contact form (removed — page is read-only evidence)
- No sponsorship tiers section (removed)
- White/light logos on dark backgrounds (NOT black logos)
- All text must be readable — no tiny gray-on-dark-gray text
- Photos should be high quality, not pixelated/blurry

## Current Page Structure (sponsor.html)
1. **Hero** — "The Atlantic AI Hackathon" with cursor-following spotlight
2. **01 — The Opportunity** (light section) — Bento grid with 4 stats
3. **02 — Track Record** (dark section) — Stats grid (3x2), photo grid, group photo, partner logos, link to polaroid wall
4. **03 — The Audience** (light section) — Short description + tag pills
5. **04 — Return on Investment** (dark section) — 4 ROI items with example cards + callout quote
6. **05 — The Team** (dark section) — Side-by-side with real headshots, bios, credentials
7. **Footer**

## Key Files
- `sponsor.html` — main page (~1100 lines)
- `images/` — keynote.jpg, building.jpg, demo.jpeg, awards.jpeg, group.jpeg, jitakshi.jpeg, bethany.jpeg
- `logos/` — lovable-light-png.png, shopify_logo_white.png, ywca.png, Onside-logo-white.png, Volta-Logo-White.png
- `Hackathon-Images/` — source photos (not committed to git)
- `The team/` — source headshots (not committed to git)
- `Atlantic-AI-Hackathon-Complete-Blueprint.md` — full strategy document
- `.github/workflows/deploy.yml` — GitHub Pages deployment

## Known Issues / Pending Items
- YWCA logo renders much smaller than other logos — needs per-logo height override
- Winners collage image — user wants to add it but hasn't dropped the file yet
- Lovable and Shopify logos have icons making them appear visually larger than text-only logos
- Stats cards (track record) blend into background — need shadow/elevation
- Second landing page (SMB waitlist) still to be built (Part 4 of blueprint)

## Session Log
- **Session 1:** Built v1 → v2 → v3 of sponsor.html. Iterated on fonts, colors, layout.
- **Session 2 (current):** Deployed to GitHub + GitHub Pages. Added real photos, white logos, team headshots, ROI examples. Fixed text readability, photo grid layout. Created this context file.
