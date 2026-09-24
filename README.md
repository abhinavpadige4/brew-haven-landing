# Brew Haven — Landing Page

A static landing page for Brew Haven coffee shop.

## Project Overview

Single-page site featuring hero banner, menu highlights, about section, location/contact, and footer. Built with vanilla HTML, CSS, and JavaScript — no frameworks or external libraries.

## Tech Stack

- **HTML5** — semantic markup
- **CSS3** — mobile-first responsive layout with design tokens
- **Vanilla ES6 JavaScript** — mobile menu toggle and smooth scrolling

## Design Tokens

| Token | Value |
|-------|-------|
| Primary | #4B2E2A |
| Secondary | #8C5A43 |
| Accent | #D4A373 |
| Background | #FAF8F0 |
| Text | #333333 |
| Heading Font | Playfair Display (serif) |
| Body Font | Open Sans (sans-serif) |
| Spacing Unit | 8px |
| Section Spacing | 4rem |
| Gutter | 1rem |

## File Structure

```
project/
├── index.html      # Main page: hero, menu, about, location, footer
├── css/
│   └── style.css   # All styles: tokens, layout, components
├── js/
│   └── script.js   # Mobile menu toggle, smooth scroll
└── README.md       # This file
```

## Setup

No build step required. Clone and open directly.

```bash
git clone <repo-url>
cd brew-haven
```

Open `index.html` in any modern browser.

## Local Development

1. Edit files directly — changes reflect on page refresh.
2. Use a local server for live reload:

```bash
npx serve .
```

3. Navigate to `http://localhost:3000`.

## Conventions

- CSS linked via `<link rel="stylesheet" href="css/style.css">` in `<head>`.
- JavaScript placed before closing `</body>` tag.
- Vanilla ES6 only — no external libraries.
- Mobile-first responsive design.
- All spacing uses 8px base unit.

## Routes

| Path | Description |
|------|-------------|
| `/` | Single landing page |

## Sections

1. **Hero** — Full-width banner with tagline and CTA.
2. **Menu Highlights** — Featured drinks and pastries.
3. **About Us** — Shop story and values.
4. **Location & Contact** — Address, hours, map link.
5. **Footer** — Social links and copyright.

## Browser Support

All modern browsers (Chrome, Firefox, Safari, Edge).

## License

Proprietary — Brew Haven.
