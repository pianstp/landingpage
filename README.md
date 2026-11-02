# Auspify Technologies — Landing Page

> **Bring Future Through Tech.**

A modern, responsive landing page for Auspify Technologies built with pure HTML, CSS, and JavaScript — no frameworks, no dependencies.

---

## Preview

![Hero Section](https://via.placeholder.com/1200x600/f4f4f0/ff6b35?text=Auspify+Technologies)

---

## Project Structure

```
landing_page/
├── index.html       # Main HTML structure
├── style.css        # All styles + responsive design
├── script.js        # Interactivity + animations
└── README.md        # Project documentation
```

---

## Sections

| Section | Description |
|---|---|
| **Navbar** | Fixed, glassmorphism nav with smooth scroll + mobile hamburger |
| **Hero** | Animated particle canvas, tagline, CTA buttons, stats |
| **Marquee** | Auto-scrolling services ticker |
| **Services** | 6-card grid with SVG icons, featured dark card |
| **Work** | 3 portfolio cards with live UI mockups (dashboard, phone, shop) |
| **Process** | 4-step workflow — Discovery → Strategy → Build → Launch |
| **Testimonials** | 3 client reviews on dark background |
| **CTA** | Full-width call-to-action with email link |
| **Footer** | Brand info + navigation + social links |

---

## Features

- **Custom cursor** — orange dot with smooth follower ring
- **Particle canvas** — animated dots with connecting lines in the hero
- **Scroll animations** — elements fade + slide in on scroll via `IntersectionObserver`
- **Marquee ticker** — infinite scrolling services strip
- **UI mockups** — AI dashboard, mobile finance app, and e-commerce grid built with pure HTML/CSS/SVG
- **Fully responsive** — works on desktop, tablet, and mobile (480px+)
- **Zero dependencies** — no libraries, no frameworks

---

## Tech Stack

- **HTML5** — semantic structure
- **CSS3** — custom properties, grid, flexbox, animations, `clamp()`
- **JavaScript (ES6+)** — canvas API, IntersectionObserver, DOM events
- **Google Fonts** — Inter (300–800)

---

## Getting Started

No build step required. Just open the file in a browser:

```bash
# Clone or download the project
cd landing_page

# Open directly in browser
open index.html
```

Or use a local dev server (recommended for live reload):

```bash
# Using VS Code Live Server extension
# Right-click index.html → Open with Live Server

# Using Python
python -m http.server 3000

# Using Node.js
npx serve .
```

Then visit `http://localhost:3000`

---

## Responsive Breakpoints

| Breakpoint | Layout |
|---|---|
| `> 900px` | Full desktop layout |
| `≤ 900px` | Services 2-col, testimonials stacked, process vertical |
| `≤ 768px` | Mobile nav, single column, cursor hidden |
| `≤ 480px` | Compact hero, stats wrap |

---

## Color Palette

| Variable | Value | Usage |
|---|---|---|
| `--black` | `#0a0a0a` | Backgrounds, text |
| `--white` | `#ffffff` | Backgrounds, text |
| `--orange` | `#ff6b35` | Primary accent, CTAs |
| `--gray` | `#f4f4f0` | Section backgrounds |
| `--muted` | `#6b6b6b` | Subtext, descriptions |

---

## Company

**Auspify Technologies**
Bring Future Through Tech.
📧 hello@auspify.com

---

## License

This project is for Auspify Technologies. All rights reserved © 2025.
