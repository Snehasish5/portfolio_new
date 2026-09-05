<div align="center">

# Snehasish Das - Personal Portfolio Website

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

A classy, formal, and fully interactive personal portfolio website built with pure HTML, CSS, and JavaScript.

</div>

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Sections](#sections)
- [Tech Stack](#tech-stack)
- [File Structure](#file-structure)
- [Getting Started](#getting-started)
- [Customization](#customization)
- [Contact](#contact)

---

## Overview

This is a personal developer portfolio website designed to be clean, formal, and highly attractive while showcasing skills, experience, projects, and achievements. Built entirely with vanilla HTML, CSS, and JavaScript (no frameworks or build tools), it features smooth animations, interactive elements, and a white and yellow color scheme.

---

## Features

| Feature | Description |
|---|---|
| White and Yellow Theme | Clean white backgrounds with golden-yellow (#FFD700) accents throughout |
| Typed Text Animation | Auto-cycling role titles in the hero section |
| Particle Canvas Background | Animated floating dots with connecting lines in the hero |
| Scroll Reveal Animations | Elements fade and slide in as you scroll using IntersectionObserver |
| Animated Skill Bars | Progress bars animate to fill width on scroll |
| Counter Animations | Stats count up from 0 when scrolled into view |
| Cursor Glow Effect | A soft yellow glow that follows the cursor |
| Fully Responsive | Mobile-first design with hamburger navigation |
| Hover Effects | Cards lift, icons rotate, buttons invert colors on hover |
| Contact Form | Form with floating labels, validation, and success state |
| Back to Top Button | Smooth scroll-to-top button appears after scrolling down |
| CV Download | One-click download of the CV from the navbar and the Let's Talk section |

---

## Sections

1. **Hero** - Full-screen greeting with animated rings around the profile photo, floating role badges, particle background, and CTA buttons
2. **About / Profile Summary** - Bio, education, location info chips, and animated stat counters
3. **Technical Skills** - Divided into 4 categories with animated progress bars:
   - Frontend (HTML, CSS)
   - Backend (Python, FastAPI, Flask, MongoDB, MySQL, JWT)
   - Analytical Tools (Power BI, Pandas, NumPy, Matplotlib, Seaborn, Excel, DAX)
   - Others (Git, VS Code, PyCharm, Cursor, Netlify, Vercel, Render)
4. **Experience** - Vertical timeline with work roles and education
5. **Projects** - Featured project cards in a responsive 3-column grid with GitHub and live links
6. **Achievements and Hackathons** - SIH 2025 Finalist, SIH 2024 Finalist, Professional Promotion
7. **Contact** - Contact info cards and a message form
8. **Let's Talk** - Full-width dark CTA section with yellow accents
9. **Footer** - Logo, copyright, and quick navigation links

---

## Tech Stack

```
Frontend
- HTML5              Semantic markup, accessibility (aria labels)
- CSS3               Custom properties, flexbox, grid, animations
  - Google Fonts     Montserrat (body) + Playfair Display (headings)
  - Font Awesome 6   Icons throughout the site
- Vanilla JavaScript All interactivity, no frameworks required

External CDNs (no build step required)
- https://fonts.googleapis.com
- https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/
```

---

## File Structure

```
portfolio_n/
|
|-- index.html              Main HTML — all sections and markup
|-- style.css               All styles — layout, animations, responsiveness
|-- script.js               All interactivity — typed text, particles, observers
|
|-- profile.jpg             (Optional) Profile photo — shows 'SD' initials if absent
|-- cv.pdf    CV file — linked for download in navbar and Let's Talk section
|-- README.md               Project documentation
```

---

## Getting Started

No build tools, no dependencies, no Node.js required.

### 1. Clone or Download

```bash
git clone https://github.com/Snehasish5/portfolio
```

Or download the ZIP from GitHub and extract it.

### 2. Add Your Photo (Optional)

Place your profile photo as `profile.jpg` in the root folder.
If not present, a stylish "SD" initials placeholder is shown automatically.

### 3. Open in Browser

Simply open `index.html` directly in any modern browser:

```
Double-click index.html
```

Or use the VS Code Live Server extension for live reload during development:

```
Right-click index.html → Open with Live Server
```

### 4. Deploy

Since it is pure static HTML, CSS, and JS, you can deploy instantly to:

- **Netlify** - Drag and drop the folder
- **Vercel** - Run `vercel --prod` in the terminal
- **GitHub Pages** - Push to the `gh-pages` branch

---

## Customization

### Change Colors

Edit the CSS custom properties at the top of `style.css`:

```css
:root {
  --yellow: #FFD700;       /* Primary accent color */
  --yellow-dark: #e6c200;  /* Darker yellow for text */
  --yellow-light: #fffde7; /* Light yellow for backgrounds */
  --dark: #111111;         /* Primary dark color */
  --white: #ffffff;        /* Background color */
}
```

### Update Personal Info

All personal content is in `index.html`. Locate sections using HTML comments:

```html
<!-- HERO -->
<!-- ABOUT -->
<!-- SKILLS -->
<!-- EXPERIENCE -->
<!-- PROJECTS -->
<!-- ACHIEVEMENTS -->
<!-- CONTACT -->
<!-- LET'S TALK -->
```

### Update Typed Roles

In `script.js`, edit the `roles` array:

```js
const roles = ['Data Analyst', 'Backend Developer', 'Python Developer', 'Power BI Expert', 'SIH Finalist'];
```

### Update Skill Bar Percentages

In `index.html`, change the `data-w` attribute on each `.bar-fill`:

```html
<div class="bar-fill" data-w="90"></div>
```

---

## Contact

| Platform | Details |
|----------|---------|
| Email | dsnehasish73@gmail.com |
| LinkedIn | linkedin.com/in/snehasish-das-0b9019295 |
| GitHub | github.com/Snehasish5 |
| Location | Kolkata, West Bengal, India |

---

## License

This project is open source and available under the [MIT License](LICENSE).
Feel free to use it as a template for your own portfolio — a credit is appreciated but not required.

---

<div align="center">
Designed and built by Snehasish Das — 2026
</div>
