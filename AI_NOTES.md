# AI Notes & Project Knowledge Base

## Project Overview
- **Project Name:** Personal Portfolio Webpage (Assignment 1 - MDM College Work)
- **Author:** Pranav Lamkhade (GitHub: pranav-6944)
- **Repository:** https://github.com/pranav-6944/My_Portfolio
- **Tech Stack:** Pure HTML5 and Vanilla CSS3 (Strict constraint: No JavaScript required/used)
- **Theme/Design Direction:** Deep Slate/Midnight Dark Mode (`#0B0F19`, `#0F172A`, `#1E293B`), Emerald/Cyan Accents (`#10B981`, `#06B6D4`), Google Fonts (`Inter`, `JetBrains Mono`), Glassmorphism, Micro-interactions.

---

## Key Requirements & Constraints
- [x] Only HTML and CSS used (strict college assignment requirement).
- [x] Mandatory sections: Introduction / Hero, About Me, Skills, Projects, Contact Information, Footer.
- [x] Responsive layout with mobile-first CSS media queries (tested at 375px, 768px, 1024px, 1440px).
- [x] Multiple meaningful git commits demonstrating step-by-step development progression for evaluation.
- [x] UI/UX Pro Max guidelines applied: semantic HTML5, accessible contrast (WCAG AA 4.5:1+), visible focus rings (`:focus-visible`), inline SVGs (no emoji icons), smooth CSS transitions.

---

## File Structure Plan
```
Assi_1_portfolio/
├── index.html          # Semantic HTML5 single-page portfolio
├── style.css           # Modular Vanilla CSS3 stylesheet with design tokens
├── README.md           # Project documentation and submission details
├── AI_NOTES.md         # Persistent notes, keywords, and line numbers tracker
└── LICENSE             # MIT License (existing from repository setup)
```

---

## Important Keywords & References
- **CSS Custom Properties:** Defined in `:root` for colors, typography, spacing, border-radius, shadows, transitions.
- **Pure CSS Mobile Navigation:** Implemented using CSS checkbox hack (`#nav-toggle:checked ~ .nav-menu`) avoiding JavaScript.
- **Glassmorphism:** `backdrop-filter: blur(12px)`, semi-transparent background `rgba(30, 41, 59, 0.7)`, subtle border `rgba(255, 255, 255, 0.08)`.
- **CSS Grid & Flexbox:** Auto-fit project cards (`repeat(auto-fit, minmax(320px, 1fr))`), flex alignment for nav, skills, and contact cards.
- **Accessibility:** `prefers-reduced-motion` media query, `:focus-visible` outline rings, semantic `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`.

---

## Development Log & Commits
1. Commit 1: Project setup & initial documentation (`AI_NOTES.md`).
2. Commit 2: Semantic HTML5 structure scaffolding (`index.html`).
3. Commit 3: CSS design tokens, typography, CSS reset, and foundational utilities (`style.css`).
4. Commit 4: Header navigation and hero section styling.
5. Commit 5: About section and skills matrix styling.
6. Commit 6: Featured projects showcase grid and hover interactions.
7. Commit 7: Contact information, interactive form, and footer styling.
8. Commit 8: Responsive layouts, CSS-only mobile drawer, and accessibility tokens.
9. Commit 9: Final polishing, comprehensive README documentation, and submission readiness.
