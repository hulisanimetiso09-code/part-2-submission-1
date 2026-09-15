# Guts & Guys - Web Platform (Part 2)

Welcome to the official **Guts & Guys** website repository. This system is styled with modern CSS architecture, responsive multi-breakpoint layouts, and verified web accessibility principles.

---

## Key Technical Implementation Features
- **External CSS Architecture**: Centralized `css/style.css` delivering consistency across all HTML documents.
- **Custom Properties & Tokenization**: Managed layout schemes, font scales, and spacing tokens in CSS `:root`.
- **Responsive Engines**: CSS Grid for adaptative 3-column, 2-column, and 1-column page layouts; Flexbox for dynamic navigation bars.
- **Interactive Pseudo-Classes**: Custom styling applied across `:hover`, `:focus-visible`, and `:active` component states.
- **Responsive Media Architecture**: `<picture>` wrappers combined with `srcset` and `sizes` for bandwidth efficiency.

---

## Responsive Layout Matrix & Verification Evidence

| Device Class | Viewport Range | Layout Configuration | Evidence Link |
| :--- | :--- | :--- | :--- |
| **Desktop** | > 992px | Multi-Column Grid (3 Columns), Horizontal Header Nav | `docs/screenshots/desktop-view.png` |
| **Tablet** | 601px - 992px | 2-Column Grid Layout, Scaled Container Padding | `docs/screenshots/tablet-view.png` |
| **Mobile** | ≤ 600px | Single-Column Vertical Stack, Full-Width Interactive Elements | `docs/screenshots/mobile-view.png` |

---

## Comprehensive Changelog

### Version 2.0.0 (Part 2 CSS & Responsiveness Release)
- **Added**: Centralized stylesheet (`css/style.css`) linked across all platform HTML pages.
- **Added**: CSS custom properties for color tokens, typography scales, and unified box shadows.
- **Added**: Responsive media query breakpoints for Tablet (992px) and Mobile (600px) viewports.
- **Added**: Interactive component states using `:hover`, `:focus-visible`, and `:active` pseudo-classes.
- **Added**: Adaptive dynamic image syntax utilizing `<picture>` and `srcset` attributes.
- **Fixed (Part 1 Feedback)**: Resolved missing `alt` attributes across media assets for accessibility.
- **Fixed (Part 1 Feedback)**: Corrected HTML structural semantics by wrapping content within `<header>`, `<main>`, and `<footer>` containers.

### Version 1.0.0 (Part 1 Initial Submission)
- **Added**: Initial repository layout and basic HTML structural templates.

---

## Academic References

1. MDN Web Docs. (2026). *CSS Grid Layout*. Available at: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout [Accessed 15 Sep. 2026].
2. MDN Web Docs. (2026). *Responsive images*. Available at: https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images [Accessed 15 Sep. 2026].
3. W3C. (2023). *Web Content Accessibility Guidelines (WCAG) 2.2*. Available at: https://www.w3.org/TR/WCAG22/ [Accessed 15 Sep. 2026].
