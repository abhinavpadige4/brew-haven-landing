# Brew Haven — Landing Page

A static landing page for Brew Haven coffee shop.

## Project Overview

Single-page site featuring hero banner, menu highlights, about us, location/contact, and footer sections. Built with vanilla HTML, CSS, and JavaScript — no frameworks or external libraries.

## Tech Stack

- **HTML5** — semantic structure
- **CSS3** — mobile-first responsive design with custom design tokens
- **Vanilla ES6 JavaScript** — mobile menu toggle and smooth scrolling

## Design Tokens

| Token | Value |
|---|---|
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
/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
└── README.md
```

## Setup

1. Clone or download the repository.
2. Open `index.html` directly in any modern browser.

No build step, no dependencies, no server required.

## Local Development

- Edit `index.html` for content and structure.
- Edit `css/style.css` for styling. All design tokens are defined as CSS custom properties at the top of the file.
- Edit `js/script.js` for interactivity. JavaScript runs on `DOMContentLoaded`.

### Conventions

- CSS is linked via `<link rel="stylesheet" href="css/style.css">` in `<head>`.
- JavaScript is placed before the closing `</body>` tag.
- No external libraries or CDNs are used.
- Mobile-first layout: base styles target small screens, media queries add larger-screen enhancements.

## Sections

1. **Hero/Banner** — Full-width hero with shop name and tagline.
2. **Menu Highlights** — Featured drinks and pastries.
3. **About Us** — Shop story and values.
4. **Location/Contact** — Address, hours, and contact details.
5. **Footer** — Copyright and social links.

## Browser Support

All modern browsers (Chrome, Firefox, Safari, Edge).

## License

MIT
