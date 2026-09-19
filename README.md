# SilkaGlow House theme

Shopify theme zips for silkaglow.com (Dawn-based SilkaGlow House).

Latest draft upload: **SilkaGlow-House-v112-perf.zip** (House v112 — store first-paint / weight perf; CTAs + logo from v108–v110 tip).

Previous on main: `SilkaGlow-House-v110-logo-balance.zip`.

## Upload (draft only — password ON)
1. Download the latest zip from this repo / PR.
2. Shopify Admin → Online Store → Themes → Add theme → Upload zip.
3. Preview as draft. Do **not** publish until Greisy confirms.
4. Store password stays ON.

## v112 — store perf (HOLD merge until Greisy confirms speed)
Fail-closed. No visual redesign. Points / Insider share-day theme PR #4 stays HOLD separately (not in this zip).

- Defer non-critical JS (Insider sheet boot, memory bridge, countdown)
- Concierge iframes hydrate after idle / intersect / open (not eager)
- Lazy/non-blocking CSS for Silka account/membership/checkout/buttons
- Drop unused joypixels CDN + webfont preloads (swap remains)
- Compress header logo (~103KB → ~29KB); orb GIF recompressed
- Greisy doors / GlowMatch CTAs / logo layout from v108–v110 unchanged

## v110 notes (on main)
- Header logo enlarged for balance vs search + account name + bag
- Insider sheet WhatsApp/Text channel isolation (pairs with app)
- CTAs / quiz / rooms / Greisy doors unchanged from v108
