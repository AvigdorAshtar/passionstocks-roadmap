# Beta Release — What's Actually Shipped

Snapshot as of 2026-04-15. This is the "what exists today" view — confirmed live on `test.passionstocks.com` and `test-admin.passionstocks.com` via direct walkthrough.

## Product

### Basic / Buyer
- Sign up / Log in
- Profile page (name, handle, link to AI Marketplace)
- AI Marketplace — Shoutouts tab (browse, quick-buy, pricing, units sold)
- AI Marketplace — Perks tab (search)
- Wallet (Est. Net Worth, Available Balance, Projected Sales Potential, Withdraw/Deposit, pending funds, transaction history)
- Shoutouts Portfolio (total spent, total value, value change %, est. impact, portfolio table, My Shoutout Tracker)
- Personal Brand IPO Index (ranked creator leaderboard)
- In-app notifications (e.g. Trade Successful, Deposit Successful)

### Creator
- Asset Profile — own view (bio, niches, location, lexicon, followers, buyers/buys/following/followers, "Complete Your Profile" CTA, connect socials)
- Asset Profile — public view (brand worth range, IPO readiness progress bar toward $1B, "Would You Invest In Me" comments)
- Personal Brand Hub (3-step journey: Sell / Sell More / Keep Selling; brand worth; IPO readiness; 4 AI agent score gauges — Brand Understanding, Execution Readiness, Investability, Insurability; action cards: pricing strategy, create perk, post to socials, invite fans, work with agency)
- AI Marketplace access (same as buyer)
- Shoutouts Portfolio access (same as buyer)
- Wallet (Net Worth includes brand valuation)

### Agency
- Agency Profile (name, handle, founding year, niches, specialties, admin; stats: est. portfolio worth, management score, IPO readiness %, brand assets on platform, creators managed, agency managers; performance: total brand valuation, total revenue, avg revenue, total followers under management; Preview Search Card)

### Manager
- Agency Hub dashboard (total brand valuation created, active creators under management — verified/unverified, team members count, top performing creators, top contributing managers to IPO progress)
- Creators Hub (roster management — Active/Applications/Invites, My Creators vs Agency Creators, search, Add Creator)
- Agency Team (Members/Applications/Invites, team table with role/email/added/permissions, Invite Team Members)
- My Manager Profile (manager card, IPO contribution gauge, Updates & Actions, performance stats: creators managed, valuation added, revenue generated, commission earned, units sold)

## Back office

All 9 sections confirmed live at `test-admin.passionstocks.com`:

1. **Dashboard** — Users (active, issuers/creators, managers, deactivated, new today/30d), Financials (platform balance, portfolios, assets held), Activity (shoutouts purchased today, refund requests, top user by balance), Dev Tools (dev/demo only)
2. **Users** — search, Create User, table (avatar, roles, verified, username, name, email)
3. **Portfolio** — search, table (user, balance, assets — expandable)
4. **Notifications** — Send Notification (by recipient group: All Users/Investors/Issuers/Managers/Specific User), Send Email, In-App Templates, Email Templates
5. **Waitlists** — Beta Access Control toggle, tabs (Leads, Invest In Me, Academy, Issuer Requests, Agency Registration), Send Beta Code, Decline
6. **Payment Portal** — stats (records, pending, completed, total deposited), Deposits/Withdrawals tabs, status filters, fee breakdown
7. **Platform Settings** — social platform icon/key management (YouTube, Facebook, Instagram, TikTok, etc.)
8. **Bug Reports** — search, status filter, table (ID, user, message, status, created)
9. **Agency Structure** — per-agency selector, stats (managers, creators, founders, avg creators/manager), Org Chart / Managers / Creators tabs, buy fee % visibility

## Not yet covered in this Beta snapshot

- Cross-seller, Legal & Financial, Business, Nonprofit roles — tree structure exists in the roadmap but not yet confirmed live in product
- Notifications matrix — tree exists, not yet confirmed live per-channel
- Content prep (social/FAQ/announcement) — tracked separately in the Content section of the roadmap, not part of this dev snapshot
