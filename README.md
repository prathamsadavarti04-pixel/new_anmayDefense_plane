# Anmay Defence website

A responsive, dependency-free static website built from the supplied homepage brief.

## Preview locally

1. Extract `anmay-defence-website.zip` (if using the ZIP).
2. Open `index.html` in a current browser.
3. No build step, server, external fonts, or third-party JavaScript is required.

For local development, you can also run a simple static server from this folder, for example:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Files

- `index.html`: complete homepage.
- `styles.css`: palette, typography, responsive layouts, and components.
- `script.js`: mobile navigation and current year in the footer.
- `products.html`, `about.html`, `contact.html`, `strike-gen1.html`, `strike-gen2.html`: requested Coming Soon placeholder pages.

## Brand decisions

The site uses the supplied colours exactly: Steel Navy `#1B3552`, Deep Navy `#142B45`, Off-white `#F4F5F6`, Card White `#FFFFFF`, Steel Blue `#7198B8`, Body Text `#536477`, Soft Border `#D8DEE6`, and Tech Cyan `#06B6D4`. Cambria is the primary font, with Georgia and a generic serif fallback.

The radar and product visuals are original conceptual SVG illustrations, clearly labelled as illustrations rather than actual prototype photographs or live sensor data. No performance figures or unverified capabilities are claimed.

## Before publishing

- Replace conceptual illustrations with approved product/prototype photography when available, keeping accurate labels.
- Connect the Request a Demo / Contact Us page to the official contact workflow when those details are ready.
- Review company and product wording for final approval before public release.
