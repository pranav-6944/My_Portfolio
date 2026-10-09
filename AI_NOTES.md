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

## Real Profile & Academic Knowledge
- **Full Name:** Pranav Lamkhade
- **Tagline / Exact Title:** Full-Stack Developer & Data Analytics Student
- **College / University:** MIT Academy of Engineering (MITAOE), SPPU Affiliated
- **Degree & Branch:** B.Tech Computer Engineering & Data Science
- **Current Standing:** 3rd Year
- **Location:** Alandi, Pune, Maharashtra, India
- **Public Email:** `pranavlamkhade21@gmail.com`
- **Phone:** `+91 7276356052`
- **LinkedIn:** [linkedin.com/in/pranav-lamkhade-6b48bb372](https://www.linkedin.com/in/pranav-lamkhade-6b48bb372)
- **GitHub:** [github.com/pranav-6944](https://github.com/pranav-6944)

## Real Featured GitHub Projects
1. **Vakratunda-Misal:** Restaurant platform communicating authentic Maharashtrian identity, driving customer visits, phone orders, directions, and ordering.
   - *URL:* https://github.com/pranav-6944/Vakratunda-Misal
   - *Stack:* Python, HTML, CSS, JavaScript, SQL
2. **ContextOS:** Local-first RAG knowledge platform enabling users to chat with documents using a locally hosted LLM, with semantic retrieval, source citations, and pipeline visualization.
   - *URL:* https://github.com/pranav-6944/ContextOS
   - *Stack:* Python, Local LLM, RAG Pipeline, Semantic Search, Interactive UI
3. **E-Commerce-Starter-Template:** Clean, production-ready starter template for building modern e-commerce web applications.
   - *URL:* https://github.com/pranav-6944/E-Commerce-Starter-Template
   - *Stack:* HTML5, CSS3, JavaScript, Responsive UI, E-Commerce Workflows
4. **Student-Career-Skill-Recommendation-System:** AI-powered system that analyzes student profiles, predicts optimal career paths, and recommends personalized learning pathways.
   - *URL:* https://github.com/pranav-6944/Student-Career-Skill-Recommendation-System-
   - *Stack:* Python, Machine Learning, Data Analytics, Career AI, Web UI

---

## Important Keywords & References
- **Claymorphism Physics:** 4-tier shadow stack:
  `14px 18px 36px rgba(148, 163, 184, 0.35), -10px -10px 24px rgba(255, 255, 255, 0.95), inset 3px 3px 6px rgba(255, 255, 255, 0.9), inset -4px -4px 10px rgba(148, 163, 184, 0.2)`
- **Carved Debossed Insets:** `inset 4px 4px 8px rgba(148, 163, 184, 0.28), inset -3px -3px 6px rgba(255, 255, 255, 0.95)`
- **Pure CSS Mobile Navigation:** Implemented using CSS checkbox hack (`#nav-toggle:checked ~ .nav-menu`) avoiding JavaScript.
- **Spring Transition:** `cubic-bezier(0.34, 1.56, 0.64, 1)` for squishy tactile feedback.
- **Accessibility:** `prefers-reduced-motion` media query, `:focus-visible` outline rings, semantic `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`.

## HTML Structure Line Map (`index.html`) — 1075 lines total
- Lines 1–28: Header metadata, SEO tags, OpenGraph, font imports (`Plus Jakarta Sans`, `Inter`, `JetBrains Mono`).
- Lines 32–61: Accessible header & nav with pure CSS checkbox toggle (`#nav-toggle`).
- Lines 65–186: Hero section, status badge, CTA buttons, mock terminal card (`pranav.config.ts`), floating metric badges, and quick social links (GitHub, LinkedIn, Email, Phone).
- Lines 188–275: About section with 4-card clay bento grid (My Journey, Academic Foundation at MITAOE SPPU, Core Principles, Metrics).
- Lines 278–605: Technical Skills matrix across 4 domains (Languages: Python, C++, JS, SQL; Frontend: HTML, CSS, React, Tailwind; Backend: Node, Express, MySQL, Postgres, Mongo; Tools/Core CS: Git, VS Code, DSA, DBMS, AI/ML, Data Analytics).
- Lines 608–851: Featured Projects showcase (Vakratunda-Misal, ContextOS, E-Commerce-Starter-Template, Student-Career-Skill-Recommendation-System).
- Lines 854–974: Contact information cards (Email, Phone, LinkedIn, GitHub, Location, Work Status) and accessible debossed clay contact form.
- Lines 978–1061: Semantic footer with brand tagline, directory links, social links (GitHub, LinkedIn, Email, Phone), and back-to-top navigation.

## CSS Architecture Map (`style.css`) — 1979 lines total
- Lines 11–130: Master Claymorphism design tokens & custom properties (`:root` - colors, clay shadows, gradients, typography, radius).
- Lines 131–227: CSS reset, global base elements, accessible `:focus-visible` rings and skip-to-content.
- Lines 228–395: Layout containers, section headers, gradient text, 3D clay button components (`.btn-primary`, `.btn-secondary`).
- Lines 396–536: Sticky navigation header, porcelain clay surface, brand mark, hover animations, mobile toggle checkbox hack.
- Lines 537–806: Hero section layout, ambient clay spheres, status pill dot animation (`pulse-dot`), terminal card with syntax highlighting, floating badges (`float` keyframe).
- Lines 807–999: About Me clay bento grid layout (large story card, academic card, core principles tag cloud, and metrics highlight row).
- Lines 1000–1218: Technical skills section across 4 domains, debossed meter tracks (`.progress-bar-track`), fill animations (`.progress-bar-fill`), and tactile tech pills (`.tech-tag`).
- Lines 1219–1441: Featured projects showcase grid, mockup preview browser screens, category badges, and clay action link buttons.
- Lines 1442–1620: Contact information cards (Email, Phone, LinkedIn, GitHub, Location, Availability) and carved debossed contact form inputs.
- Lines 1621–1726: Clay site footer layout with branding, directory links, social anchors, and pure CSS back-to-top button.
- Lines 1727–1955: Responsive media queries (`@media (max-width: 1024px)`, `(max-width: 768px)`, `(max-width: 480px)`), sliding mobile drawer menu with animated hamburger transforms.
- Lines 1956–1979: Accessibility compliance with `@media (prefers-reduced-motion: reduce)`.

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
- [x] **Commit 9:** `docs: add comprehensive README.md and update AI_NOTES.md for assignment submission` (5f6c517)
- [x] **Commit 10:** `style(claymorphism): overhaul portfolio design to tactile 3D claymorphic aesthetic` (9a63387)
- [x] **Commit 11:** `feat(profile): integrate real academic background, contact channels, and GitHub projects` (77e07d9)
- [x] **Commit 12:** `ci(pages): configure automated GitHub Pages deployment workflow and live URL` (574ccfa)

## Live Deployment Details
- **Live Production URL:** https://pranav-6944.github.io/My_Portfolio/
- **Deployment Strategy:** GitHub Actions automated static deployment pipeline (`.github/workflows/deploy.yml`) + Direct branch deployment fallback (`main` / root).
- **Settings Path:** `https://github.com/pranav-6944/My_Portfolio/settings/pages`








