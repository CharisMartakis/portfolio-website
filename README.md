# CMportfolio - Charis Martakis Portfolio Website

A personal portfolio website built by **Charis Martakis** while progressing through Angela Yu's *The Complete Full-Stack Web Development Bootcamp*. The site is a living showcase of my web development learning, professional background, selected projects, and contact information.

- Live site: [charismartakis.github.io/portfolio-website](https://charismartakis.github.io/portfolio-website/)
- Repository: [github.com/CharisMartakis/portfolio-website](https://github.com/CharisMartakis/portfolio-website)

---

## Purpose

This website documents my transition from web content operations into front-end development, QA/test automation, and technical tooling. It combines course projects, professional experience, and selected personal/internal projects as my skills grow.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | Custom CSS3 + Bootstrap 5.3.8 |
| Interactivity | Vanilla JavaScript |
| Fonts | Helvetica/system fonts |
| Icons | SVG assets |
| Hosting | GitHub Pages |

---

## Color Palette

| Role | Hex |
|---|---|
| Page background | `#3396D3` |
| Header / Footer | `#EBCB90` |
| Card / Section background | `#EEEEEE` |
| Hover accent | `#ddb56b` |

---

## Project Structure

```text
portfolio-website/
|-- index.html
|-- style.css
|-- README.md
|-- assets/
|   |-- images/
|   |   |-- duck_button_logo.png
|   |   |-- Charis-Martakis-photo.jpg
|   |   |-- github.svg
|   |   |-- linkedin.svg
|   |   |-- dices/
|   |   `-- drum-kit/
|   `-- sounds/
|       `-- drum-kit/
`-- public/
    |-- projects.html
    |-- resume.html
    |-- contact.html
    `-- projects/
        |-- greek-flag-css.html
        |-- pricing-table.html
        |-- piet-Mondrian-painting.html
        |-- eshop-with-bootstrap.html
        |-- dice-game.html
        `-- drum-kit.html
```

---

## Pages Overview

### `index.html` - Home

- Hero section with name, role, profile image, and social links
- Short About Me section
- Project preview cards
- Contact teaser with email and contact form link

### `public/projects.html` - Projects Gallery

- Bootstrap card grid with responsive columns
- Project detail modals
- Currently highlights:
  - Oh My Savior
  - Face Mask Detection
  - Personal Portfolio
  - Greek Flag (CSS)
  - Pricing Table
  - Piet Mondrian Painting
  - Dice Game

### `public/resume.html` - Resume / CV

- Two-column layout with sidebar profile, links, and grouped skills
- Main content with summary, education, and work experience
- Skills grouped by category
- Asterisk marks skills currently being learned
- Download CV button opens a print/PDF-friendly resume view

### `public/contact.html` - Contact

- Contact form UI
- Backend integration is still pending
- Email fallback: `charis.martakis@gmail.com`

---

## Projects Inside the Portfolio

| # | Project | Tech Used | Status |
|---|---|---|---|
| 1 | Oh My Savior | TypeScript, React, WXT, Supabase | Private / showcased |
| 2 | Face Mask Detection | Python, TensorFlow/Keras, OpenCV, TFLite, Raspberry Pi | Complete |
| 3 | Personal Portfolio | HTML, CSS, Bootstrap, JavaScript | In progress |
| 4 | Greek Flag (CSS) | HTML, CSS Grid | Complete |
| 5 | Pricing Table | HTML, CSS Flexbox | Complete |
| 6 | Piet Mondrian Painting | HTML, CSS Grid | Complete |
| 7 | E-shop with Bootstrap | HTML, Bootstrap | Complete |
| 8 | Dice Game | HTML, CSS, JavaScript | Complete |
| 9 | Drum Kit | HTML, CSS, JavaScript | Complete page / not yet listed in gallery |

---

## Owner / Author

- **Name**: Charis Martakis (Charalampos Martakis)
- **Email**: charis.martakis@gmail.com
- **LinkedIn**: [linkedin.com/in/charis-martakis](https://www.linkedin.com/in/charis-martakis/)
- **GitHub**: [github.com/CharisMartakis](https://github.com/CharisMartakis)
- **Location**: Athens, Greece
- **Background**: Integrated Master's in Electrical & Electronics Engineering; Web Content Specialist expanding into front-end development, QA/test automation, and technical tooling

---

## Version History

### Version 0.1 - Pure HTML & CSS

Initial hand-built version focused on raw HTML structure and custom CSS.

- Created the first home page, shared stylesheet, and resume page
- Added early course projects:
  - Greek Flag
  - Pricing Table
  - Piet Mondrian Painting
  - E-shop with Bootstrap

### Version 0.2 - Bootstrap Redesign

Rebuilt the site around Bootstrap 5 and a cleaner visual layout.

- Reworked the home page with Bootstrap grid/layout utilities
- Rebuilt the resume page with sidebar skills and main content
- Added project cards and Bootstrap modals
- Added the contact page UI
- Added project screenshots and social/profile assets
- Published via GitHub Pages

### Version 0.3 - JavaScript & Portfolio Expansion

Current in-progress version focused on JavaScript, interactivity, and stronger project presentation.

- Added Dice Game
- Added Drum Kit project page
- Added Face Mask Detection thesis project to the gallery
- Added Oh My Savior private extension showcase
- Updated resume content to match the latest CV direction
- Wired the Download CV button to a print/PDF-friendly view

---

## Known Issues / TODOs

- [ ] Contact form has no backend yet
- [ ] Drum Kit project page exists but is not listed on the home page or in the projects gallery
- [ ] Hero image hover changes `width`/`height`, which can cause layout shift; it should use `transform: scale()` only
- [ ] Continue adding new course and personal projects as skills grow

---

## How to Run Locally

No build tools are required. Open `index.html` in a browser, or use the VS Code Live Server extension.

---

## Course Context

Built while completing **Angela Yu's The Complete Full-Stack Web Development Bootcamp** on Udemy. Course exercises are expanded and integrated into the portfolio as standalone project pages.

---

*Last updated: June 2026*
