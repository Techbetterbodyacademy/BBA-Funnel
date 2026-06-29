# Better Body Academy — Funnels

Mobile-first, self-contained marketing pages for Better Body Academy.
Shared brand: black `#0a0a0a` · accent `#00AEEF` · Inter / Roboto / JetBrains Mono.

## Pages

- `index.html` — "Book a Free Call" funnel
- `sales.html` — VSL / sales page for the 12-Week Transformation System
- `coach-team.webp` — coaching team photo (used by both)

## Wiring it up

**index.html** — find `[GHL EMBED]` and paste your GoHighLevel calendar iframe.
Every "Book my free call" button already scrolls to that section.

**sales.html** — two placeholders:
- `[VSL EMBED]` — paste your video iframe (Vimeo / Wistia / YouTube) and delete the placeholder block.
- `[CHECKOUT LINK]` — replace `href="#"` on every `.js-buy` button with your real checkout URL.
