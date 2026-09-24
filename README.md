# Brew Haven — Landing Page

A static landing page for the Brew Haven coffee shop.

## Project Overview

Single-page site featuring a hero banner, menu highlights, about section, location/contact info, and footer. Built with vanilla HTML, CSS, and JavaScript — no frameworks or external libraries.

## Tech Stack

- **HTML5** — semantic markup
- **CSS3** — mobile-first responsive design with custom design tokens
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
├── index.html      # Main page: hero, menu, about, location, footer
├── css/
│   └── style.css   # All styles: tokens, layout, components, responsive
├── js/
│   └── script.js   # Mobile menu toggle, smooth scroll
└── README.md       # This file
```

## Setup & Local Development

1. **Clone or download** the repository.
2. **Open `index.html`** directly in any modern browser (Chrome, Firefox, Safari, Edge).
3. No build step, no server, no dependencies required.

### Optional: Local Server

For a more realistic environment:

```bash
# Python 3
python3 -m http.server 8000

# Node.js
npx serve .
```

Then visit `http://localhost:8000`.

## Development Guidelines

- **Mobile-first**: CSS starts at mobile breakpoints and scales up with `min-width` media queries.
- **No external libraries**: All JavaScript is vanilla ES6, loaded before `</body>`.
- **CSS linked in `<head>`**: Use `<link rel="stylesheet" href="css/style.css">`.
- **Design tokens**: All colors, fonts, and spacing are defined as CSS custom properties in `style.css`.
- **Accessibility**: Semantic HTML5 elements, ARIA labels on interactive controls, sufficient color contrast.
- **Performance**: No external dependencies; fonts loaded via Google Fonts `<link>` in `<head>`.

## Contributing

1. Fork the repository.
2. Create a feature branch.
3. Make changes following the guidelines above.
4. Ensure the page renders correctly at mobile (320px), tablet (768px), and desktop (1024px+) widths.
5. Submit a pull request.

## License

MIT
