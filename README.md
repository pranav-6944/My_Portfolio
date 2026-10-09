# 🚀 Pranav Lamkhade | Personal Portfolio Webpage

A modern, responsive, and accessible personal portfolio website designed and developed from scratch using **pure HTML5 and Vanilla CSS3** with **zero external JavaScript dependencies**.

This project was built for **College MDM (Multimedia / Web Development) Assignment 1** to demonstrate mastery of semantic markup, CSS custom properties, responsive layout design (Flexbox & CSS Grid), CSS animations, and modern UI/UX design standards.

---

## 🌐 Live Repository & Demo
- **GitHub Repository:** [https://github.com/pranav-6944/My_Portfolio](https://github.com/pranav-6944/My_Portfolio)
- **Author:** Pranav Lamkhade
- **Email:** [pranavlamkhade21@gmail.com](mailto:pranavlamkhade21@gmail.com)

---

## 📸 Key Sections & Architecture

### 1. Header & Navigation (`<header>`, `<nav>`)
- **Brand Identity:** Distinct developer logo with code brackets `<Pranav.dev/>`.
- **Navigation Links:** Smooth scrolling anchor navigation to `#about`, `#skills`, `#projects`, `#contact`.
- **Pure CSS Mobile Navigation:** Responsive hamburger drawer menu powered entirely by the CSS checkbox hack (`#nav-toggle:checked ~ .nav-menu`), eliminating any requirement for JavaScript.

### 2. Hero / Introduction (`<section class="hero-section">`)
- **Status Badge:** Real-time pulse indicator dot with CSS keyframe animation (`pulse-dot`).
- **Hero Title & Gradient:** High-contrast heading styled with custom multi-stop gradient clipping (`--gradient-text`).
- **Interactive Action Buttons:** Primary button with subtle elevation shadows and secondary glassmorphic button.
- **Terminal Mockup Visual:** Pure CSS code card (`pranav.config.ts`) featuring syntax highlighting (keywords, definitions, strings, comments) and floating feature badges (`float` keyframe).

### 3. About Me (`<section class="about-section">`)
- **Bento Grid Architecture:** 3-column asymmetric grid layout showcasing personal journey, academic background, and engineering philosophy.
- **Academic Foundation:** Degree details (B.E. in Computer Engineering) and key coursework (Data Structures, Web Technologies, Database Systems).
- **Quantitative Metrics Row:** Highlighting 10+ completed projects, 100% responsive layouts, and 0 external JS dependencies.

### 4. Technical Skills Arsenal (`<section class="skills-section">`)
- **Categorized Domains:**
  1. *Frontend Engineering* (HTML5, CSS3, Flexbox/Grid, JavaScript ES6+, React)
  2. *Backend & Databases* (Node.js, Express, Python, SQL, MongoDB, REST APIs)
  3. *Tools & Workflow* (Git, GitHub, VS Code, Chrome DevTools, Terminal, npm)
  4. *Core Fundamentals* (Data Structures, OOP, Web Accessibility, Responsive UI)
- **Visual Progress Tracks:** Animated meter bars with percentage indicators and interactive tech tag pills.

### 5. Featured Projects Showcase (`<section class="projects-section">`)
- **Responsive 2-Column Grid:** Auto-adjusting cards with hover lift transitions (`transform: translateY(-6px)`).
- **CSS Browser Mockups:** Interactive window previews simulating application interfaces (metrics, columns, and sorting visualizations).
- **Highlighted Projects:**
  - **DevPulse:** Developer Productivity & Habit Analytics Dashboard.
  - **ShopSphere:** Responsive E-Commerce storefront with category filters and product cards.
  - **NeuroTask:** Agile Kanban task management board with glassmorphic cards.
  - **AlgoVisualizer:** Interactive algorithm visualization tool depicting sorting algorithms with CSS bar heights.
- **Action Triggers:** Direct links to GitHub repository and live previews.

### 6. Contact Information & Form (`<section class="contact-section">`)
- **Direct Reach Cards:** Quick links to Email, GitHub profile, Location, and Work Availability status.
- **Interactive Contact Form:** Accessible pure HTML5 form with styled floating inputs, active focus rings (`:focus`), and styled submit button.

### 7. Semantic Footer (`<footer class="site-footer">`)
- Brand mission statement, quick navigation links, social links, copyright information, and a smooth back-to-top button.

---

## 🎨 UI/UX Design System (UI/UX Pro Max)

| Design Token | Specification | Purpose |
| :--- | :--- | :--- |
| **Theme** | Dark OLED / Midnight Slate | Reduces eye strain, modern developer aesthetic |
| **Primary Background** | `#0A0F1D` | Deep midnight canvas |
| **Surface Elevate** | `#1E293B` / `#243248` | Card elevation and visual hierarchy |
| **Accent Primary** | `#06B6D4` (Electric Cyan) | Focus indicators, icons, and CTA highlights |
| **Accent Secondary** | `#10B981` (Emerald Green) | Availability status and success indicators |
| **Typography (Sans)** | `'Inter', sans-serif` | Highly legible modern geometric sans-serif |
| **Typography (Mono)** | `'JetBrains Mono', monospace` | Code snippets, terminal card, tags |
| **Transitions** | `0.25s cubic-bezier(0.4, 0, 0.2, 1)` | Butter-smooth micro-interactions |
| **Accessibility** | `:focus-visible` & `prefers-reduced-motion` | Full keyboard and screen-reader friendliness |

---

## 📱 Responsive Breakpoints Tested

- **Desktop (1440px / 1200px):** Multi-column grid layouts, side-by-side terminal card, full horizontal navigation.
- **Tablet (1024px / 768px):** Bento grid adapts to 2 columns, centered hero layout, optimized touch target spacing.
- **Mobile (375px / 480px):** Single-column stacked layout, sliding mobile drawer menu, full-width touch buttons, zero horizontal scroll.

---

## 🛠️ Step-by-Step Commit History (Development Progression)

| # | Commit Hash | Message & Milestone |
| :---: | :---: | :--- |
| 1 | `601c128` | `docs: initialize project knowledge base and assignment plan` |
| 2 | `300bedf` | `feat(html): scaffold complete semantic HTML5 portfolio layout` |
| 3 | `af97d2e` | `style(core): implement CSS custom properties, reset, typography, and base layout styles` |
| 4 | `aa54bc0` | `style(nav-hero): add sticky header navigation and hero intro with terminal card` |
| 5 | `558e9bb` | `style(about-skills): design about me bento grid and technical skills progress indicators` |
| 6 | `f052d54` | `style(projects): style featured projects grid, mockup previews, and link interactions` |
| 7 | `15a8f8e` | `style(contact-footer): style interactive contact form, contact cards, and site footer` |
| 8 | `a563c84` | `feat(responsive): add mobile hamburger navigation, media queries, and accessibility features` |
| 9 | *Head* | `docs: add comprehensive README.md and update AI_NOTES.md for assignment submission` |

---

## 🏃‍♂️ How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/pranav-6944/My_Portfolio.git
   cd My_Portfolio
   ```

2. **Open in browser:**
   - Simply double-click `index.html` to open it in your default web browser (Chrome, Edge, Firefox, Safari).
   - Alternatively, serve it via any simple local server:
     ```bash
     # Using Python
     python -m http.server 3000
     ```
     Then navigate to `http://localhost:3000`.

---

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).
