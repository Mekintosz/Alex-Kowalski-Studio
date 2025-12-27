# Alex Kowalski Studio — Responsive Landing Page

Single-page portfolio site for an earthenware and clay studio. Built as a responsive, mobile‑first static website with semantic HTML and modern CSS. Original brief/template from The Odin Project; adapted and redesigned to meet a fictional client’s needs.

Live demo: https://mekintosz.github.io/Alex-Kowalski-Studio/

## To do

- Add a lightweight build setup (Vite) to the existing vanilla project
- Create gh-pages branch (deploy from dist/ folder)

## Tech Stack

- HTML5

  - Semantic structure with `header`, `main`, `footer`
  - Responsive images using `<picture>` and media queries
  - Meta viewport and favicon setup

- CSS3

  - Custom properties (CSS variables) for color theming
  - Mobile‑first responsive design with breakpoints at ~550px, 1100px, 1550px
  - Layout with Flexbox and CSS Grid
  - Google Fonts integration (Gluten, Overlock)
  - Reusable utility patterns (shadows, spacing, simple cards)

- Assets & Delivery
  - Optimized JPG/PNG images sized for different viewports
  - Inline/linked SVG icons for social links
  - Pure static hosting (no JS, no build step)

## Skills Gained

- Planning and implementing a mobile‑first layout, then progressively enhancing for larger screens
- Building responsive image strategies with `<picture>` and media queries for bandwidth efficiency
- Using CSS custom properties to centralize theming and maintain visual consistency
- Composing layouts with Flexbox and CSS Grid for adaptable components (header, gallery, footer)
- Establishing typography scale and hierarchy with web fonts and accessible contrast
- Organizing a small static project for easy hosting and maintenance

## Project Structure

```
.
├── index.html        # Semantic markup and responsive images
├── style.css         # Variables, media queries, Flexbox/Grid layout
└── assets/           # Images, icons, and favicon
```

## Run Locally

- Option 1: open `index.html` directly in your browser
- Option 2: serve the folder with a simple HTTP server

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Credits

- Photos: Yan Krukau — https://www.pexels.com/collections/eramic-workshop-kq7lm38/
- Brief/template: The Odin Project

## Screenshot

<img width="1920" height="2892" alt="Landing page screenshot" src="https://github.com/user-attachments/assets/c2069723-781a-46be-b4e0-2c717e46a84f" />
