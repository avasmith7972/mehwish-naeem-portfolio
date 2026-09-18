# Mehwish Naeem — Personal Portfolio

A single-file, multi-page personal portfolio website built as Part 2 of the Leverify AI Vibe Coding Course Final Capstone Project.

**Live Site:** https://mehwish-naeem-portfolio.netlify.app

---

## Overview

This portfolio serves as a professional showcase of my skills, projects, experience, and background. It is designed for potential clients, collaborators, and employers who want to learn more about my work and get in touch.

---

## Features

- **7-page single-page application** — Home, About, Skills, Projects, Experience, Testimonials, Contact
- **Animated page transitions** — smooth opacity fade between pages with staggered reveal animations
- **Project case studies** — detailed breakdowns of 7 real projects with live links and GitHub repositories
- **Skills tabs** — categorised across Development & Tech, Business & Management, Research & Analysis, and Amazon VA
- **Testimonials** — 6 genuine testimonials from colleagues, clients, and collaborators
- **Interactive home page** — canvas-based particle system, typewriter role animation, and diary writing effect
- **Fully responsive** — works across desktop, tablet, and mobile
- **Dark vintage theme** — custom design with gold accent palette, Playfair Display typography, and vintage background images

---

## Tech Stack

| Layer | Technology |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 (custom properties, flexbox, grid, animations) |
| Interactivity | Vanilla JavaScript |
| Fonts | Google Fonts (Playfair Display, DM Sans, Dancing Script, JetBrains Mono) |
| Deployment | Netlify (drag-and-drop) |

No frameworks, no build tools, no dependencies — entirely self-contained in a single `index.html` file.

---

## Architecture

The portfolio is a **client-side SPA** built without any framework:

- Each page is a `position: fixed` full-screen element that switches visibility via CSS opacity and `pointer-events`
- Page navigation is handled by a lightweight `showPage()` JavaScript function
- Reveal animations use a CSS `.rv` / `.rv.in` class system triggered on page entry with staggered `setTimeout` calls
- Background images are layered directly in CSS using `linear-gradient` overlays — no extra DOM elements needed

---

## File Structure

```
portfolio/
├── index.html        # Complete website (single file)
├── bg.jpg            # Home page background
├── bg-about.jpg      # About & Testimonials background
├── bg-skills.jpg     # Skills page background
├── bg-projects.jpg   # Projects page background
├── bg-experience.jpg # Experience page background
├── bg-contact.jpg    # Contact page background
└── parchment.jpg     # Diary section texture
```

---

## Deployment

Deployed via **Netlify Drop** — no CI/CD pipeline required. To redeploy:

1. Update `index.html` locally
2. Drag the project folder onto the Netlify dashboard
3. Changes go live instantly

---

## AI Tools Used

This project was built using AI-assisted development as part of the Leverify AI Vibe Coding curriculum:

- **Claude (Anthropic)** — primary coding assistant for HTML structure, CSS design system, JavaScript logic, and iterative refinements
- **Vibe Coding methodology** — natural language prompting to generate, debug, and enhance code without writing it manually from scratch

---

## About the Author

**Mehwish Naeem** is an HR professional, Amazon VA specialist, and aspiring AI-assisted developer based in Wah Cantt, Pakistan. This portfolio represents her transition into tech through the Leverify Quest AI-Vibe Coding programme.

- LinkedIn: [linkedin.com/in/mehwish-naeem](https://www.linkedin.com/in/mehwish-naeem)
- GitHub: [github.com/MehwishNaeem](https://github.com/MehwishNaeem)
