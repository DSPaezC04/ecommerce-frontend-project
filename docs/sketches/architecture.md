# Project Architecture

This document explains the **technical structure** and **development flow** of the e-commerce frontend project — from file organization to technology usage and GitFlow strategy.

---

## General Overview

The project follows a **modular and scalable architecture**, ensuring that each layer (design, layout, logic, and API integration) is independent and easy to maintain.

Main technologies:
- **HTML5** – semantic structure of the app.
- **CSS3 / Tailwind / Bootstrap** – responsive design and reusable UI components.
- **JavaScript (ES6+) / React** – dynamic behavior and component-based development.
- **Git & GitFlow** – version control and team workflow.
- **Figma** – UI/UX design and prototyping.

---

## Folder Structure

```bash
ecommerce-frontend-project/
│
├── assets/                 # Images, icons, and media files
│
├── docs/                   # Project documentation
│   ├── figma/
│   │   └── figmaLink.md
│   ├── sketches/
│   │   ├── planning.md
│   │   └── architecture.md
│   └── README.md
│
├── src/                    # Main source code
│   ├── css/
│   │   └── styles.css      # Global styles
│   ├── js/
│   │   ├── main.js         # JS logic or React entry point
│   │   └── api.js          # API call handling (to be added)
│   └── index.html          # Main HTML template
│
├── .gitignore
├── LICENSE
└── README.md
