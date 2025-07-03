# Week 1 - SWE Skills Bootcamp Website

---

## Overview

This repository contains a basic website built during the first week of my Software Engineering (SWE) skills bootcamp with JUST IT in the North East of England. The purpose of this project was to complete a series of fundamental HTML and CSS tasks assigned over a four-day period.

**Please note:** While this project demonstrates my ability to meet core requirements and implement basic web development concepts, it does **not** represent the peak of my current skills or the complexity of projects I'm capable of undertaking. This was a foundational exercise, and I've already worked on more advanced concepts and projects beyond this initial bootcamp phase.

## Features

This website showcases the following core HTML and CSS concepts:

* **Semantic HTML5 Structure:** Use of appropriate semantic tags (e.g., `<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`, `<aside>`) for improved accessibility and document outline.
* **CSS Styling:**
    * Basic element and class selectors.
    * An example of an ID selector for specific styling.
    * Application of fundamental CSS properties such as `margin`, `padding`, `border`, `height`, and `width` for layout and spacing.
    * **Flexbox Layouts:** Demonstrations of various Flexbox properties for aligning and distributing items, including:
        * Centering items vertically and horizontally.
        * Reversing item order (vertical and horizontal).
        * Distributing space evenly between items (vertical and horizontal).
    * **CSS Positioning:** Examples of `static`, `relative`, `absolute`, `fixed`, and `sticky` positioning.
    * **CSS Grid Layouts:** Various Grid layout examples, including:
        * Basic 3x2 and 3x3 grids.
        * Connecting grid items vertically and horizontally (\`grid-row\` and \`grid-column\`).
        * Creating full column and row spans.
    * **CSS Grid Template Areas:** Implementation of a responsive layout using `grid-template-areas`.
* **Interactive Elements:**
    * A basic navigation bar with links to different demonstration pages.
    * An enquiry form demonstrating various input types, including email, range, date, and file upload, along with legal requirement checkboxes/radio buttons.
    * Accessibility enhancements such as `aria-describedby` for form fields.

---

## Project Structure

.
├── static/
│   ├── imgs/
│   │   └── boxModel.png
│   └── styles/
│       └── style.css
└── templates/
├── enquire.html
├── flexbox.html
├── grid.html
├── gridTemplate.html
├── headings.html
├── image.html
├── index.html
└── positionings.html

* `static/imgs/`: Contains images used in the website.
* `static/styles/`: Contains the main CSS stylesheet (`style.css`).
* `templates/`: Contains all the HTML pages for the website.
* `index.html`: The main homepage providing an overview and links to daily tasks.
    * `headings.html`: Demonstrates HTML heading tags (`<h1>` to `<h6>`).
    * `image.html`: Shows how to display an image.
    * `enquire.html`: Features a detailed enquiry form with various input types.
    * `flexbox.html`: Showcases different Flexbox alignment and distribution methods.
    * `positionings.html`: Illustrates various CSS positioning properties.
    * `grid.html`: Provides multiple examples of CSS Grid layouts.
    * `gridTemplate.html`: Demonstrates responsive layout using `grid-template-areas`.

---

## How to View

To view this website, simply clone this repository to your local machine and open any of the `.html` files in your web browser. Starting with `index.html` is recommended to navigate through the demonstrations.

```bash
git clone <repository-url>
cd <repository-name>
# Then open templates/index.html in your browser
```
---

## Learnings
Through this project, I solidified my understanding of:

* Structuring web pages with semantic HTML.

* Styling elements and controlling layout using CSS, especially with Flexbox and Grid.

* Creating accessible and user-friendly forms.

* Organizing project files effectively.

---
## Future Enhancements
While this project fulfills the bootcamp's initial requirements, potential future enhancements could include:

* Adding JavaScript for dynamic content or form validation.

* Implementing responsive design for better mobile viewing.

* Refining the visual design and aesthetics.
