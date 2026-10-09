# 🚀 Pranav Lamkhade | Personal Portfolio Webpage

A modern, responsive, and accessible personal portfolio website designed and developed from scratch using **pure HTML5 and Vanilla CSS3** with **zero external JavaScript dependencies**.

This project was built for **College MDM (Multimedia / Web Development) Assignment 1** to demonstrate mastery of semantic markup, CSS custom properties, responsive layout design (Flexbox & CSS Grid), CSS animations, and modern UI/UX design standards.

---

## 🌐 Live Repository & Contact Channels
- **GitHub Repository:** [https://github.com/pranav-6944/My_Portfolio](https://github.com/pranav-6944/My_Portfolio)
- **Author:** Pranav Lamkhade
- **Title:** Full-Stack Developer & Data Analytics Student
- **College:** MIT Academy of Engineering (MITAOE), SPPU Affiliated
- **Degree:** B.Tech in Computer Engineering & Data Science (3rd Year)
- **Location:** Alandi, Pune, Maharashtra, India
- **Email:** [pranavlamkhade21@gmail.com](mailto:pranavlamkhade21@gmail.com)
- **Phone:** [+91 7276356052](tel:+917276356052)
- **LinkedIn:** [linkedin.com/in/pranav-lamkhade-6b48bb372](https://www.linkedin.com/in/pranav-lamkhade-6b48bb372)

---

## 📸 Key Sections & Architecture

### 1. Header & Navigation (`<header>`, `<nav>`)
- **Brand Identity:** Distinct developer logo with code brackets `<Pranav.dev/>`.
- **Navigation Links:** Smooth scrolling anchor navigation to `#about`, `#skills`, `#projects`, `#contact`.
- **Pure CSS Mobile Navigation:** Responsive hamburger drawer menu powered entirely by the CSS checkbox hack (`#nav-toggle:checked ~ .nav-menu`), eliminating any requirement for JavaScript.

### 2. Hero / Introduction (`<section class="hero-section">`)
- **Status Badge:** Real-time pulse indicator dot with CSS keyframe animation (`pulse-dot`) indicating 3rd Year B.Tech internship availability.
- **Hero Title & Gradient:** High-contrast heading styled with custom multi-stop gradient clipping (`--gradient-text`).
- **Interactive Action Buttons:** Primary button with subtle elevation shadows and secondary glassmorphic button.
- **Terminal Mockup Visual:** Pure CSS code card (`pranav.config.ts`) featuring syntax highlighting (keywords, definitions, strings, comments) and floating feature badges (`float` keyframe).

### 3. About Me (`<section class="about-section">`)
- **Bento Grid Architecture:** 3-column asymmetric grid layout showcasing personal journey, academic background, and engineering philosophy.
- **Academic Foundation:** Degree details (**B.Tech Computer Engineering & Data Science** at **MIT Academy of Engineering, SPPU Affiliated**) and key focus areas (*Web Development, DSA, DBMS, AI/ML, Data Analytics*).
- **Quantitative Metrics Row:** Highlighting 4+ featured GitHub projects, 3rd Year standing, and 100% pure HTML5 & CSS3 build.

### 4. Technical Skills Arsenal (`<section class="skills-section">`)
- **Categorized Domains:**
  1. *Programming Languages* (Python, C++, JavaScript ES6+, SQL, OOP)
  2. *Frontend Engineering* (HTML5, CSS3, React, Tailwind CSS, Responsive Design)
  3. *Backend & Databases* (Node.js, Express.js, MySQL, PostgreSQL, MongoDB, REST APIs)
  4. *Tools & Core Computer Science* (Git, GitHub, VS Code, DSA, DBMS, AI/ML & Data Analytics)
- **Visual Progress Tracks:** Animated meter bars with percentage indicators and interactive tech tag pills.

### 5. Real Featured Projects Showcase (`<section class="projects-section">`)
- **Responsive 2-Column Grid:** Auto-adjusting cards with hover lift transitions (`transform: translateY(-6px)`).
- **CSS Browser Mockups:** Interactive window previews simulating application interfaces (metrics, columns, and data visualizations).
- **Real Highlighted Projects:**
  - **[Vakratunda-Misal](https://github.com/pranav-6944/Vakratunda-Misal):** Authentic restaurant platform communicating Maharashtrian culinary identity, driving customer visits, menu exploration, and orders.
  - **[ContextOS](https://github.com/pranav-6944/ContextOS):** Local-first RAG knowledge platform enabling users to chat with documents via a locally hosted LLM with semantic retrieval and source citations.
  - **[E-Commerce-Starter-Template](https://github.com/pranav-6944/E-Commerce-Starter-Template):** Clean, production-ready starter template engineered for building modern responsive e-commerce web applications.
  - **[Student-Career-Skill-Recommendation-System](https://github.com/pranav-6944/Student-Career-Skill-Recommendation-System-):** AI-powered system analyzing student profiles, predicting optimal career paths, and recommending personalized learning pathways.
- **Action Triggers:** Direct links to live GitHub repositories with interactive pure CSS buttons.

### 6. Contact Information & Form (`<section class="contact-section">`)
- **Direct Reach Cards:** Quick links to Email, Phone (`+91 7276356052`), LinkedIn, GitHub profile, Location (Alandi, Pune, Maharashtra), and Work Availability status.
- **Interactive Contact Form:** Accessible pure HTML5 form with styled sunken debossed inputs, active focus rings (`:focus`), and styled clay submit button.

### 7. Semantic Footer (`<footer class="site-footer">`)
- Brand mission statement, quick navigation links, social icons (GitHub, LinkedIn, Email, Phone), copyright information, and a smooth back-to-top button.

---

## 🎨 UI/UX Design System (Master Claymorphism)

| Design Token | Specification | Purpose |
| :--- | :--- | :--- |
| **Theme** | Master Claymorphism | Soft 3D, tactile surfaces, toy-like plumpness & premium feel |
| **Canvas Background** | `#EEF4FA` (Soft Slate) | Warm, airy, glare-free canvas with floating clay blobs |
| **Clay Slabs** | `#FFFFFF` with 4-way shadows | Chunky floating 3D cards with inner bevels & outer drops |
| **Debossed Insets** | `inset 4px 4px 8px...` | Carved grooves for inputs & skill progress tracks |
| **Accent Primary** | `#6366F1` (Royal Indigo) | 3D clay buttons, brand marks, and active states |
| **Accent Sky** | `#0EA5E9` (Sky Blue) | Floating clay spheres, tags, and category highlights |
| **Accent Emerald** | `#10B981` (Mint Clay) | Availability status pill and live preview badges |
| **Typography (Sans)** | `'Plus Jakarta Sans', sans-serif` | Friendly, geometric, ultra-crisp modern letterforms |
| **Typography (Mono)** | `'JetBrains Mono', monospace` | Code snippets, terminal card, tech tags |
| **Tactile Motion** | `cubic-bezier(0.34, 1.56, 0.64, 1)` | Playful, bouncy physical clay spring transitions |
| **Accessibility** | `:focus-visible` & `prefers-reduced-motion` | WCAG AAA contrast (7:1+) & keyboard accessibility |

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
