# Criativo - Creative Agency Homepage

<p align="left">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
</p>

This repository contains the source code for a static, multi-section homepage for a fictional creative agency named "Criativo". This project is a front-end exercise built purely with HTML5 and modern CSS3, demonstrating complex layout and styling techniques.

The entire layout is orchestrated using a top-level **CSS Grid** (`.conteaner`), with **Flexbox** employed extensively for component-level alignment, such as in the navigation bar, hero content, and feature boxes.

---

## 🚀 Key Features

The homepage is a comprehensive, single-page design featuring multiple distinct sections:

* **Header:** Sticky navigation bar with logo and menu links.
* **Hero Section:** Main promotional content with a call-to-action.
* **Services:** A 4-quadrant grid highlighting "What We Do".
* **About Us:** A split-layout section with text and imagery.
* **Statistics:** A full-width parallax-style section displaying key metrics (Projects Done, Happy Customers, etc.).
* **Latest Projects:** A two-column layout showcasing recent case studies.
* **Sponsors/Partners:** A logo bar for social proof.
* **Team Showcase:** A card-based layout to "Meet Expert Team".
* **Portfolio Gallery:** An extensive 3-column image grid for "Latest Work".
* **Testimonials:** A section for client feedback with a background image.
* **Blog/News:** A 3-card layout for "Our Latest News".
* **Contact & Footer:** A "Get In Touch" contact form alongside a detailed footer with site links and social media icons.

---

## 🛠️ Technical Breakdown

* **HTML5:** All structure is built using semantic HTML.
* **CSS3:** All styling, layout, and effects are handled by pure CSS.
    * **CSS Grid:** The primary layout mechanism for the entire page's sections.
    * **Flexbox:** Used internally within sections for fine-grained alignment of content.
    * **Custom Properties:** (Not used, but a potential improvement).
    * **Transitions:** Simple `hover` effects are used on cards and buttons for interactivity.
    * **Background Images:** Multiple sections use `background-image` with effects like `background-attachment: fixed` to create visual depth.

---

## 📂 Project Structure

```
/
├── index.html       (The main HTML document)
├── styles.css       (The main stylesheet)
└── imagess/         (A directory for all project assets)
```
