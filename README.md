# SilkaGlow House theme

Shopify theme zips for silkaglow.com (Dawn-based SilkaGlow House).

Latest draft upload: **SilkaGlow-House-v112-home-perf.zip** (House v112 — **homepage** first paint / LCP only; CTAs + logo from v108–v110 tip).

Previous on main: `SilkaGlow-House-v110-logo-balance.zip`.

## Upload (draft only — password ON)
1. Download the latest zip from this repo / PR.
2. Shopify Admin → Online Store → Themes → Add theme → Upload zip.
3. Preview as draft. Do **not** publish until Greisy confirms.
4. Store password stays ON.

## v112-home-perf — homepage LCP (HOLD merge)
Fail-closed. Scope = **silkaglow.com home** (header, announcement, concierge, GlowMatch cinema banner, below-fold). Rooms / GlowMatch app code-split deferred. Points theme PR #4 stays HOLD separately.

- Defer Insider sheet, memory bridge, countdown, non-critical CSS
- Concierge iframes hydrate after idle / intersect / open
- Cinema: poster-first; mp4 sources only near viewport; posters compressed
- Ending reel: no autoplay until intersect
- Header logo ~103KB → ~29KB; drop unused joypixels + webfont preloads
- Greisy doors / GlowMatch CTAs / logo layout unchanged
