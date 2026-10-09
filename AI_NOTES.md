# AI Notes & Project Knowledge Base

## Project Overview
- **Project Name:** Personal Portfolio Webpage (Assignment 1 - MDM College Work)
- **Author:** Pranav Lamkhade (GitHub: pranav-6944)
- **Repository:** https://github.com/pranav-6944/My_Portfolio
- **Tech Stack:** Pure HTML5 and Vanilla CSS3 (Strict constraint: No JavaScript required/used)
- **Theme/Design Direction:** Master Claymorphism (Soft 3D, tactile clay surfaces, porcelain white cards `#FFFFFF` on soft slate canvas `#EEF4FA`, vibrant 3D accents in Indigo `#6366F1`, Sky `#0EA5E9`, Mint `#10B981`, Rose `#F43F5E`).
- **Typography:** `Plus Jakarta Sans` (primary body & headings), `Inter` (geometric fallback), `JetBrains Mono` (code & tags).

---

## Key Requirements & Constraints
- [x] Only HTML and CSS used (strict college assignment requirement).
- [x] Mandatory sections: Introduction / Hero, About Me, Skills, Projects, Contact Information, Footer.
- [x] Responsive layout with mobile-first CSS media queries (tested at 375px, 768px, 1024px, 1440px).
- [x] Multiple meaningful git commits demonstrating step-by-step development progression for evaluation.
- [x] UI/UX Pro Max guidelines applied: semantic HTML5, accessible contrast (WCAG AAA 7:1+), visible focus rings (`:focus-visible`), inline SVGs (no emoji icons), smooth CSS transitions.

---

## Claymorphism Signature Shadow Formula
- **Floating Clay Slab (Outer Drop + Inner Specular + Inner Bevel):**
  `14px 18px 36px rgba(148, 163, 184, 0.35), -10px -10px 24px rgba(255, 255, 255, 0.95), inset 3px 3px 6px rgba(255, 255, 255, 0.9), inset -4px -4px 10px rgba(148, 163, 184, 0.2)`
- **Carved / Debossed Clay Inset (Inputs & Progress Tracks):**
  `inset 4px 4px 8px rgba(148, 163, 184, 0.28), inset -3px -3px 6px rgba(255, 255, 255, 0.95)`
- **Puffy Tactile Button (3D Pop + Squish Active State):**
  `8px 14px 26px rgba(99, 102, 241, 0.4), inset 2px 2px 5px rgba(255, 255, 255, 0.65), inset -3px -3px 8px rgba(49, 46, 129, 0.45)` with active press squish `translateY(2px) scale(0.98)`

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

## HTML Structure Line Map (`index.html`)
- Lines 1–28: Header metadata, SEO tags, OpenGraph, font imports (`Inter`, `JetBrains Mono`).
- Lines 32–61: Accessible header & nav with pure CSS checkbox toggle.
- Lines 66–173: Hero section, status badge, CTA buttons, mock terminal card.
- Lines 176–253: About section with 4-card bento grid (Story, Education, Principles, Metrics).
- Lines 256–477: Technical Skills matrix across 4 domains with progress indicators and tech pills.
- Lines 480–692: Featured Projects showcase (DevPulse, ShopSphere, NeuroTask, AlgoVisualizer).
- Lines 695–812: Contact information cards and accessible contact form.
- Lines 815–873: Semantic footer with back-to-top navigation and copyright.

## CSS Architecture Map (`style.css`)
- Lines 8–82: Design tokens & custom properties (`:root` - colors, gradients, typography, spacing, shadows).
- Lines 83–170: CSS reset, global base elements, accessible `:focus-visible` rings and skip-to-content.
- Lines 171–297: Layout containers, section headers, gradient text, button components (`.btn`, `.btn-primary`, `.btn-secondary`).
- Lines 298–408: Sticky navigation header, glassmorphism surface, brand logo, animated hover underline links, mobile toggle markup.
- Lines 409–677: Hero section layout, ambient glow orbs, status indicator dot animation (`pulse-dot`), headline gradients, social icon links, terminal card with syntax highlighting, floating badges (`float` keyframe).
- Lines 678–847: About Me bento grid layout (2-col large story card, academic card, core principles tag cloud, and 3-span metrics highlight row).
- Lines 848–1001: Technical skills section across 4 engineering domains, animated progress tracks (`.progress-bar-fill`), and interactive tech pills (`.tech-tag`).
- Lines 1002–1266: Featured projects showcase grid, mockup preview screens (browser bars, metric mockups, sorting bars), category pills, and code/demo action links.
- Lines 1267–1447: Contact information cards (Email, GitHub, Location, Availability) and interactive CSS form with focus glow states.
- Lines 1448–1541: Site footer layout with branding, directory links, social anchors, and pure CSS back-to-top button.
- Lines 1542–1755: Responsive media queries (`@media (max-width: 1024px)`, `(max-width: 768px)`, `(max-width: 480px)`), pure CSS mobile navigation drawer via `:checked` state with animated hamburger transform.
- Lines 1756–1779: Accessibility compliance with `@media (prefers-reduced-motion: reduce)`.

---

## Development Log & Commits
- [x] **Commit 1:** `docs: initialize project knowledge base and assignment plan` (601c128)
- [x] **Commit 2:** `feat(html): scaffold complete semantic HTML5 portfolio layout` (300bedf)
- [x] **Commit 3:** `style(core): implement CSS custom properties, reset, typography, and base layout styles` (af97d2e)
- [x] **Commit 4:** `style(nav-hero): add sticky header navigation and hero intro with terminal card` (aa54bc0)
- [x] **Commit 5:** `style(about-skills): design about me bento grid and technical skills progress indicators` (558e9bb)
- [x] **Commit 6:** `style(projects): style featured projects grid, mockup previews, and link interactions` (f052d54)
- [x] **Commit 7:** `style(contact-footer): style interactive contact form, contact cards, and site footer` (15a8f8e)
- [x] **Commit 8:** `feat(responsive): add mobile hamburger navigation, media queries, and accessibility features` (a563c84)
- [x] **Commit 9:** `docs: add comprehensive README.md and update AI_NOTES.md for assignment submission`







