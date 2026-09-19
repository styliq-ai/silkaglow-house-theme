# SilkaGlow House theme

Latest draft upload: **SilkaGlow-House-v108-cta-fix.zip** (House v108 — restore Why IQ GlowMatch AI Start the Quiz / The rooms click handlers; rooms.silkaglow.com quiz host; mobile X only in quiz; header logo contain)

Live store reference: House v104 until v108 is previewed and approved.

## Shopify upload
Admin → Online Store → Themes → Add theme → Upload zip → preview as draft.
Password page shows SilkaGlow (no Shopify credit). Store password stays ON.

## v108 root cause
House v104-why-lux lux CSS rewrite dropped the portal `<script>` that wired `data-gm-start` / `data-gm-rooms`, so both bottoms did nothing on draft preview.
