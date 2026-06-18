# CMportfolio — Charis Martakis Portfolio Website

A personal portfolio website built by **Charis Martakis** while following Angela Yu's *The Complete Full-Stack Web Developer Bootcamp* course. The project is intentionally built manually with minimal AI assistance to reinforce hands-on learning.

Live repo: [github.com/CharisMartakis/portfolio-website](https://github.com/CharisMartakis/portfolio-website)

---

## Purpose

This website serves as a living showcase of progress through the bootcamp. Each section and project was coded by hand. As new skills are learned (JavaScript, React, Node.js, SQL), they get added here.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 (semantic) |
| Styling | Custom CSS3 + Bootstrap 5.3.8 |
| Interactivity | Vanilla JavaScript |
| Fonts | Helvetica (system font) |
| Icons | SVG (GitHub, LinkedIn) |
| Hosting | GitHub Pages (planned) |

---

## Color Palette

| Role | Hex |
|---|---|
| Page background | `#3396D3` (blue) |
| Header / Footer | `#EBCB90` (warm yellow) |
| Card / Section background | `#EEEEEE` (light gray) |
| Hover accent | `#ddb56b` (darker yellow) |
| Body text | Helvetica, sans-serif |

---

## Project Structure

```
portfolio-website/
├── index.html               ← Home page (hero, about, project previews, contact teaser)
├── style.css                ← Shared CSS for all pages
├── assets/
│   ├── images/
│   │   ├── duck_button_logo.png   ← Site logo / favicon
│   │   ├── Charis-Martakis-photo.jpg
│   │   ├── github.svg / linkedin.svg
│   │   ├── dices/                 ← dice1–6.png (used by Dice Game)
│   │   └── drum-kit/              ← drum pad images (used by Drum Kit)
│   └── sounds/
│       └── drum-kit/              ← .mp3 files for drum pads
├── public/
│   ├── projects.html        ← Project gallery with Bootstrap cards + modals
│   ├── resume.html          ← About / CV page with sidebar skills layout
│   ├── contact.html         ← Contact form (UI only — backend pending)
│   └── projects/
│       ├── greek-flag-css.html       ← Pure CSS Greek flag (Grid)
│       ├── pricing-table.html        ← Flexbox pricing table
│       ├── piet-Mondrian-painting.html ← CSS Grid Mondrian recreation
│       ├── eshop-with-bootstrap.html ← Bootstrap e-shop layout
│       ├── dice-game.html            ← JS dice game (DOM + Math.random)
│       └── drum-kit.html             ← JS drum kit (keyboard + click events)
└── Misc/                    ← Scratchpad files (not part of the live site)
```

---

## Pages Overview

### `index.html` — Home
- Hero section: name, title, photo, social links
- About Me: short bio paragraph
- Projects preview: 4 card grid linking to individual pages
- Contact teaser: email link + link to contact form

### `public/projects.html` — Projects Gallery
- Bootstrap card grid (col-12 / col-md-6 / col-lg-4)
- Each card has a "Details" button that opens a Bootstrap modal
- Projects currently listed: Portfolio Website, Greek Flag, Pricing Table, Mondrian, Dice Game
- **TODO**: Add Drum Kit card + modal

### `public/resume.html` — About / CV
- Two-column layout: sticky sidebar (photo + skills) + main timeline
- Skills grouped by category: Languages/Frameworks, Tools, Other Technical, Languages, Soft Skills
- `*` asterisk marks skills currently being learned
- "Download CV" button present (JS not yet wired up)

### `public/contact.html` — Contact
- Contact form UI (name, email, subject, message fields)
- **Not functional yet** — note says backend integration is in progress
- Email fallback: `charis.martakis@gmail.com`

---

## Projects Inside the Portfolio

| # | Project | Tech Used | Status |
|---|---|---|---|
| 1 | Portfolio Website | HTML, CSS, Bootstrap, JS | In progress |
| 2 | Greek Flag (CSS) | HTML, CSS Grid | Complete |
| 3 | Pricing Table | HTML, CSS Flexbox | Complete |
| 4 | Piet Mondrian Painting | HTML, CSS Grid | Complete |
| 5 | E-shop with Bootstrap | HTML, Bootstrap | Complete |
| 6 | Dice Game | HTML, CSS, JavaScript | Complete |
| 7 | Drum Kit | HTML, CSS, JavaScript | Complete |

---

## Owner / Author

- **Name**: Charis Martakis (Charalampos Martakis)
- **Email**: charis.martakis@gmail.com
- **LinkedIn**: [linkedin.com/in/charis-martakis](https://www.linkedin.com/in/charis-martakis/)
- **GitHub**: [github.com/CharisMartakis](https://github.com/CharisMartakis)
- **Location**: Athens, Greece
- **Background**: Integrated Master's in Electrical & Electronics Engineering; currently working as Web Content Executive while transitioning to full-stack development

---

## Version History & Changelog

### Version 0.1 — Pure HTML & CSS (branch: `Version0.1`)
Built entirely without Bootstrap. Focused on learning raw HTML structure and hand-written CSS.

**What was built in this version (in order):**
1. Initial site scaffold — `index.html`, `style.css`, basic `resume.html`
2. Replaced "About" page with a proper `resume.html` (CV-style layout)
3. **Project: Greek Flag** — pure CSS recreation using Grid
4. **Project: Pricing Table** — responsive layout using Flexbox
5. **Project: Piet Mondrian Painting** — CSS Grid composition
6. Added `projects.html` page to list projects (early Bootstrap experiment here)
7. **Project: E-shop with Bootstrap** — first Bootstrap-heavy project

---

### Version 0.2 — Bootstrap Redesign (branch: `Version0.2`)
A full redesign of the entire site using Bootstrap 5. Every page was rebuilt or heavily refactored. This is when the site started looking professional.

**What changed vs Version 0.1:**
- Completely rewrote `style.css` — removed old manual CSS, rebuilt around Bootstrap utilities
- Rebuilt `index.html` with Bootstrap grid: hero section, about, projects preview, contact teaser
- Rebuilt `resume.html` with sidebar + main-column two-column layout and skills cards
- Rebuilt `projects.html` with Bootstrap card grid + modals for each project
- Built `contact.html` — full form UI (name, email, subject, message)
- Added screenshot images for all projects (used as card thumbnails)
- Added profile photo, doge image, GitHub/LinkedIn SVG icons
- Removed two early Misc projects (`birthday-invite.html`, `motivational-quote.html`) from public pages
- Published the site via GitHub Pages (CNAME was added/tweaked)

---

### Version 0.3 — JavaScript & Interactivity (branch: `develop`, in progress)
Learning JavaScript and DOM manipulation from the course, then implementing it in the site.

**What is being built in this version:**
- **Project: Dice Game** — DOM manipulation, `Math.random()`, dynamic image swapping
- **Project: Drum Kit** — keyboard events, click events, audio playback, CSS animation on keypress
- More JS projects to be added as the course progresses
- Contact form backend (planned)
- CV download button (planned)

---

## Known Issues / TODOs

- [ ] Contact form has no backend — needs a service like Formspree, EmailJS, or a Node.js backend
- [ ] "Download CV" button on resume.html is not wired up yet
- [ ] Drum Kit project page exists but is not listed on the home page or in the projects.html gallery
- [ ] Copyright year in footer says 2025 — should be updated to 2026
- [ ] `aria-controls` attribute in some nav togglers incorrectly includes `#` prefix (minor HTML bug)
- [ ] Hero image hover in CSS changes `width`/`height` directly (causes layout shift) — should use `transform: scale()` only

---

## How to Run Locally

No build tools needed. Just open `index.html` in a browser, or use the VS Code Live Server extension.

---

## Course Context

Built while completing **Angela Yu's The Complete 2024 Web Development Bootcamp** (Udemy). Each mini-project added to `public/projects/` represents a course exercise that was expanded and integrated into the portfolio.

---

*Last updated: June 2026*
