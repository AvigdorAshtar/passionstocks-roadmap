# Changelog

All notable changes to the PassionStocks roadmap structure and content are logged here, newest first.

## 2026-04-15

### Added
- **Content** root section — mirrors Product structure (Basic/Buyer, Creator, Agency, Manager, Cross-seller, Legal & Financial, Business, Nonprofit). Columns: Social Media / FAQ / Announcement / Done. Purpose: track content prep (social posts, FAQs, announcements) for every feature being released, independent of dev work.
- Pre-populated Content section with 15 Beta feature cards (Sign up/Log in, Profile, AI Marketplace Shoutouts + Perks, Wallet, Shoutouts Portfolio, IPO Index, In-app notifications, Creator Asset Profile, Personal Brand Hub, Agency Profile, Agency Hub dashboard, Creators Hub, Agency Team, My Manager Profile) — all starting in the Social Media column.

### Fixed
- Version view (Beta tab) reorganized to group completed items by the same structure as the tree: Product → user role → section, then Back office, then Notifications, then Content — instead of a flat list.

## 2026-04-15 (earlier)

### Added
- **Manager** as its own user role under Product, separate from Agency. Includes: Agency Hub, My Manager Profile, Creators Hub, Agency Team, plus its own Subscription tier tree (Verification, Commission window, AI agent credits, AI agent capabilities, Role-specific features: Seats, Valuation strategy meeting, Shoutout controls roster-wide, Analytics & reporting).
- Manager added to Notifications tree (In-app / Push / Email / SMS per Manager section).
- Manager role color (teal, `#0F6E56`) added to role color map.

### Confirmed via live product walkthrough (Chrome browsing session)
- **Basic / Buyer**: Sign up/Log in, Profile, AI Marketplace (Shoutouts + Perks tabs), Wallet, Shoutouts Portfolio, Personal Brand IPO Index, in-app notifications — all marked Done, logged to Beta.
- **Creator**: Asset Profile (own + public view), Personal Brand Hub (3-step journey, brand worth, IPO readiness, 4 AI agent score gauges, action cards) — marked Done, logged to Beta.
- **Agency**: Agency Profile (niches, specialties, stats panel, performance metrics) — marked Done, logged to Beta.
- **Manager**: Agency Hub dashboard, Creators Hub, Agency Team, My Manager Profile — all confirmed live via Manager account walkthrough, marked Done, logged to Beta.
- **Back office** (test-admin.passionstocks.com): all 9 sections confirmed live and marked Done in Beta — Dashboard, Users, Portfolio, Notifications, Waitlists, Payment Portal, Platform Settings, Bug Reports, Agency Structure (with org chart, manager/creator breakdown, buy fee %).

## 2026-04-14

### Added
- Initial roadmap structure built: 4 root sections (Product, Back office, Notifications, Versions).
- Product tree: Basic/Buyer, Creator, Agency, Cross-seller, Legal & Financial, Business, Nonprofit — each with subscription tier structure (Verification, Commission window, AI agent credits, AI agent capabilities, Role-specific features).
- Back office sections added from BackOffice nav screenshot: Dashboard, Users, Portfolio, Notifications, Waitlists, Payment Portal, Platform Settings, Bug Reports, Agency Structure (replacing initial "Sections TBD" placeholder).
- Notifications tree mirrors Product structure with In-app / Push / Email / SMS columns, plus a standalone Marketing branch per role.
- Versions system: Beta as default active version, auto-logging of Done items, ability to create and switch active versions.
- Password-gated access (shared team password), live auto-sync every ~11 seconds, search, expand/collapse, card CRUD (add/edit/move/done/delete).
