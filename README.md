# Czechcouver

**Czechcouver** is a responsive editorial-style website showcasing stories of Czech people living in Vancouver, BC.  
The project focuses on clean typography, accessibility, responsive design, and modern native CSS techniques, with subtle animations to enhance user experience.

---

## 🌍 Project Overview

The website presents interviews, articles, and photo galleries highlighting members of the Czech community in Vancouver.  
It includes multiple pages (Home, Gallery, Contact, 404) and emphasizes readability, performance, and accessibility.

---

## 🛠️ Technologies Used

- **HTML5**
  - Semantic markup (`header`, `nav`, `main`, `article`, `aside`, `footer`)
  - Accessible elements and attributes (`alt`, `aria-label`, `time`, `details/summary`)
  - Responsive images using `<picture>` and `<source>`

- **Native CSS (Vanilla CSS)**
  - CSS variables (`:root`)
  - Flexbox & CSS Grid layouts
  - Responsive units (`rem`, `%`, `vw`, `vh`, `ch`)
  - Media queries
  - Transitions and hover states
  - Custom keyframe animations
  - Accessibility support with `prefers-reduced-motion`

- **CSS Library**
  - **Animate.css** for decorative, predefined animations

---

## 🎨 Key Features

### Responsive Design
- Fluid typography using `clamp()`
- Flexible layouts adapting to mobile, tablet, and desktop
- Responsive images with optimized formats (`.webp`)

### Images
- Article images scale proportionally using `width: 100%` and `height: auto`
- Gallery images maintain aspect ratio using `object-fit: cover`
- Responsive image example using `<picture>` and `<source>`
- All images include meaningful `alt` attributes

### Animations & Transitions
- Native CSS keyframe animations (`fadeUp`, `pulse`)
- Smooth transitions for navigation and gallery interactions
- Animate.css used for expressive UI elements (e.g. quotes, 404 page)
- Motion is disabled for users who prefer reduced motion

### Accessibility
- Keyboard focus styles (`:focus-visible`)
- Reduced motion support
- Semantic HTML structure
- Readable line lengths and contrast-aware color usage

---

## 📄 Pages Included

- **Home (Index)** – Editorial layout with article content and sidebar
- **Gallery** – Responsive image grid with hover interactions
- **Contact** – Form layout with FAQ section
- **404 Page** – Custom error page with animated heading

---

## 🧩 Native CSS vs CSS Library

- **Native CSS** is used for:
  - Layout
  - Typography
  - Responsiveness
  - Custom animations
  - Transitions and interactions

- **Animate.css** is used selectively for:
  - Decorative animations (e.g. quote animations, 404 heading movement)

This ensures full control over design while benefiting from lightweight, reusable animation utilities.

---

## 🚀 How to Run the Project

1. Clone or download the repository
2. Open `index.html` in your browser
3. Navigate through pages using the navigation menu

No build tools or dependencies required.

---

## 👤 Author

**Vojtech Kousal**  
2025

---

## 📌 Notes

This project was created for educational purposes, demonstrating modern HTML and CSS practices with an emphasis on clarity, maintainability, and accessibility.
