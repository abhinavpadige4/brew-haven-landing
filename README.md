# Brew Haven — Landing Page

A static landing page for Brew Haven coffee shop.

## Project Overview

Single-page static site featuring:
- Hero/banner section
- Menu highlights
- About us
- Location/contact
- Footer

Built with vanilla HTML, CSS, and JavaScript. No frameworks or external libraries.

## Tech Stack

- **HTML5** — semantic markup
- **CSS3** — mobile-first responsive design with design tokens
- **Vanilla ES6 JavaScript** — mobile menu toggle and smooth scrolling

## Design Tokens

| Token | Value |
|-------|-------|
| Primary | `#4B2E2A` |
| Secondary | `#8C5A43` |
| Accent | `#D4A373` |
| Background | `#FAF8F0` |
| Text | `#333333` |
| Heading Font | Playfair Display (serif) |
| Body Font | Open Sans (sans-serif) |
| Spacing Unit | 8px |
| Section Spacing | 4rem |
| Gutter | 1rem |

## File Structure

```
/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
└── README.md
```

## Setup

No build step or dependencies required.

1. Clone or download the repository.
2. Open `index.html` in any modern browser.

## Local Development

Option 1 — Open directly:
```
open index.html
```

Option 2 — Use a local server:
```
npx serve .
```

Then navigate to `http://localhost:3000`.

## Conventions

- CSS linked via `<link rel="stylesheet" href="css/style.css">` in `<head>`.
- JavaScript placed before closing `</body>` tag.
- Vanilla ES6, `DOMContentLoaded` event, no external libraries.
- Mobile-first layout with responsive breakpoints.
- All spacing uses the 8px unit system.

## Routes

| Route | Description |
|-------|-------------|
| `/` | Main landing page |

## Contributing

1. Fork the repository.
2. Create a feature branch.
3. Make changes following the conventions above.
4. Ensure `index.html`, `css/style.css`, and `js/script.js` paths remain unchanged.
5. Submit a pull request.

## License

MIT
