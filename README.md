# DevFolio — Personal Developer Portfolio

A responsive personal developer portfolio showcasing modern frontend web development skills, built with semantic HTML5 and clean CSS3 (Flexbox & CSS Grid).

## 🚀 Live Demo

- **Live URL**: [https://vivegan-21-7.github.io/devfolio/](https://vivegan-21-7.github.io/devfolio/)
- **Repository URL**: [https://github.com/vivegan-21-7/devfolio](https://github.com/vivegan-21-7/devfolio)

---

## 🛠️ Features & Technical Highlights

- **Semantic HTML5 Structure**: Fully structured with `<header>`, `<main>`, `<section id="about">`, `<section id="projects">`, and `<footer id="contact">`.
- **CSS Colour & Type System**: Custom CSS properties (`:root`) for color palette (`--brand`, `--ink`, `--bg`, etc.) and consistent responsive typography.
- **Modern Layouts**:
  - **Flexbox** for the header, navigation bar, and contact button groups.
  - **CSS Grid** for the featured projects showcase.
- **Responsive Media Query**: Adapts smoothly across all screen sizes (1-column grid on mobile to 3-column grid on desktop via `@media (min-width: 768px)`).
- **Flexible Media**: Responsive image rule (`img { max-width: 100%; height: auto; }`) ensuring clean scaling.

---

## 📋 Build & Rubric Checklist

- [x] Semantic structure: `<header>`, `<main>`, `<footer>` + `<section>` elements for `#about` and `#projects`
- [x] `<title>` and viewport `<meta>` tag in `<head>`
- [x] Colour + type system applied consistently via CSS variables
- [x] Flexbox used for navigation header row
- [x] CSS Grid used for the projects section
- [x] At least one `@media (min-width: ...)` breakpoint changing layout
- [x] Responsive images rule (`max-width: 100%`)
- [x] Real content: name, bio, 3 project cards, working contact links
- [x] `README.md` with description and live link
- [x] Deployed and active on GitHub Pages

---

## 💻 Local Setup & Running Instructions

To preview locally:
1. Clone or download this repository:
   ```bash
   git clone https://github.com/YOUR-USERNAME/devfolio.git
   ```
2. Navigate into the project folder:
   ```bash
   cd devfolio
   ```
3. Open `index.html` in any web browser:
   - On macOS: `open index.html`
   - Or right-click `index.html` and choose **Open with > Chrome / Safari**.
