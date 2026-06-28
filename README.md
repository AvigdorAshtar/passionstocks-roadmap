# PassionStocks Roadmap

A shared, live, password-protected product roadmap for PassionStocks. Single-file HTML app — no build step, no dependencies.

## What's in here

- **`index.html`** — the live roadmap app. Open it directly in a browser, or host it (see below).
- **`CHANGELOG.md`** — a running log of what changed, when, and why. Update this every time the roadmap structure changes (new sections, new roles, restructures).
- **`docs/releases/`** — point-in-time snapshots of what's actually shipped in each release (Beta, V1.0, etc). Markdown files, one per release.

## How the roadmap is organized

The app has 5 root sections:

1. **Product** — every user role (Basic/Buyer, Creator, Agency, Manager, Cross-seller, Legal & Financial, Business, Nonprofit) with their feature tree. Columns are To Do / In Progress / Done (or Tier 1/2/3 for subscription features).
2. **Back office** — internal admin tooling (Dashboard, Users, Portfolio, Notifications, Waitlists, Payment Portal, Platform Settings, Bug Reports, Agency Structure).
3. **Notifications** — per-role notification matrix (In-app / Push / Email / SMS).
4. **Content** — mirrors Product structure. For every feature being released, track Social Media / FAQ / Announcement / Done — so content prep can start before or alongside dev work.
5. **Versions** — Beta is the active version by default. Marking a Product/Back office item "Done" auto-logs it to the active version. Switch active versions any time; create new ones (V1.0, Alpha, etc) as you go.

This mirrors how a PM thinks about it: **what exists today** (Done items), **what's being built** (To Do / In Progress), **what's released** (Versions tab), and **what changed** (CHANGELOG.md).

## Running it locally

Just open `index.html` in any browser. No server needed for solo use.

Password: `***` (change this in `index.html` — search for `const PASS`)

## Hosting it live (so the team can access it)

### Option A — GitHub Pages (recommended)
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to the `main` branch, root folder
4. Your live URL will be `https://<your-username>.github.io/<repo-name>/`

### Option B — Netlify / Vercel
Drag this folder into [netlify.com/drop](https://app.netlify.com/drop) for an instant live URL. No account needed for a quick share; sign up for persistent hosting.

## Data storage

The app uses Claude's `window.storage` API when running inside a Claude artifact, and falls back to browser `localStorage` when run standalone (e.g. on GitHub Pages). This means:

- **Inside Claude**: data syncs live across anyone using the same conversation/artifact.
- **Standalone / hosted**: data is stored per-browser (`localStorage`). For true multi-user sync on a hosted version, you'll need to wire up a real backend (Firebase, Supabase, or a small API) in place of the `storage` calls in `index.html`. Flag this to your developer if/when the team needs real-time shared editing outside of Claude.

## Updating the roadmap

Each time the roadmap structure or content changes:
1. Make the edit in `index.html`
2. Add a dated entry to `CHANGELOG.md`
3. If a release goes out, update or add a file in `docs/releases/`
4. Commit and push — GitHub Pages updates automatically within ~1 minute
