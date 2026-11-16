# Kyaw Lay Myint — Personal Portfolio

A modern, responsive personal portfolio website with a flat, minimal black-and-white Pixel look in light and dark themes, scroll-driven animations, and a full-featured contact form.

## Features

- **Dark / Light Mode** — Toggle with one click; preference saved in localStorage and follows the system setting (light by default)
- **Responsive Design** — Optimized for desktop, tablet, and mobile with a slide-out hamburger menu
- **SEO Optimized** — Open Graph, Twitter Card, meta description, semantic HTML5
- **Accessibility** — Skip-to-content link, ARIA labels, keyboard navigation, `prefers-reduced-motion` support
- **Project Showcase** — 11 project cards with flat icon thumbnails and technology badges
- **Skills Section** — Animated progress bars that fill on scroll, organized by Frontend / Backend / Automation & DevOps
- **About Section** — Profile image with animated stat counters (projects, skills, experience)
- **Contact Form** — Client-side validation with animated submit states (loading → success)
- **Contact Links** — Email, GitHub, Facebook, Twitter, Telegram
- **Scroll Progress Bar** — Thin flat bar at the top of the viewport
- **Back to Top Button** — Appears after scrolling 300px
- **Smooth Scroll** — Anchor links scroll smoothly with offset for the fixed navbar
- **Parallax Hero** — Subtle parallax effect on the hero section
- **Staggered Animations** — Cards and sections fade in with staggered delays via Intersection Observer

## Technologies

- HTML5 (semantic markup)
- CSS3 (custom properties, grid, flexbox, `clamp()`, media queries)
- Vanilla JavaScript (ES6+, Intersection Observer, localStorage)
- Google Fonts (Instrument Sans)
- Font Awesome 6

## Project Structure

```
Portfolio/
├── index.html          Main HTML
├── styles.css          All styles + dark/light themes + responsive
├── animations.css      Keyframes + scroll-reveal system
├── script.js           Theme toggle, form validation, animations, menu
├── KyawLayMyintID.png  Profile image
├── favicon.svg         SVG favicon
├── email.svg           Email icon asset
└── README.md           This file
```

## Sections

1. **Navbar** — Fixed solid header with the Pixel logo, navigation links, theme toggle, and hamburger menu
2. **Hero** — Greeting, name, subtitle, two CTA buttons
3. **About** — Profile image, bio paragraphs, animated stat counters
4. **Skills** — 3 categories with animated progress bars
5. **Projects** — 11 cards with flat icon thumbnails, descriptions, GitHub links
6. **Contact** — Form (name, email, subject, message) + social/contact links
7. **Footer** — 3-column layout (about, quick links, social icons) + copyright

## Quick Start

Open `index.html` in any modern browser.

## Responsive Breakpoints

| Breakpoint | Layout |
|---|---|
| 1024px+ | Full 3-column grids, side-by-side contact |
| 768–1024px | 2-column grids, stacked contact |
| < 768px | Single column, slide-out mobile menu |
| < 480px | Compact spacing, full-width buttons |

## Color Themes

### Light (default)
| Token | Value |
|---|---|
| Background | `#ffffff` |
| Surface (cards, alternate sections) | `#f4f4f2` |
| Text / muted | `#111111` / `#666660` |
| Border | `#e2e2de` |
| Accent (button fills) | `#111111` |

### Dark
| Token | Value |
|---|---|
| Background | `#111111` |
| Surface (cards, alternate sections) | `#1c1c1b` |
| Text / muted | `#f2f2ee` / `#a3a39c` |
| Border | `#30302d` |
| Accent (button fills) | `#f2f2ee` |

## Links

- **GitHub**: [KG3ee](https://github.com/KG3ee)
- **Email**: kyawlaymyint@icloud.com
- **Facebook**: [kyawlay.myint.12](https://www.facebook.com/kyawlay.myint.12)
- **Twitter**: [@KyawLayMyint1](https://x.com/KyawLayMyint1)
- **Telegram**: [@king_alexander94](https://t.me/king_alexander94)

## Browser Support

- Chrome / Edge 90+
- Firefox 88+
- Safari 14+
- iOS Safari, Chrome Mobile

---

**Created**: January 2026
**Last Updated**: February 2026
