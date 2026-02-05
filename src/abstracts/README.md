# Modern Art Gallery

🔗 [Live Demo] https://irenemendoza.github.io/modern-art-gallery/

A responsive two-page website for a modern art gallery, built with a focus on relative units and fluid design.

## Responsive Design

Breakpoints:
- Mobile: < 768px (tested on iPhone SE - 375x667)
- Tablet: 768px - 1199px (tested on iPad Air - 820x1180)
- Desktop: ≥ 1200px (tested on Nest Hub Max - 1280x800)

**Note:** The design is specifically optimized for these dimensions and may require adjustments for other viewport sizes.

## Features

- Fully responsive design with two breakpoints:
  - Mobile: < 768px
  - Tablet: 768px - 1199px
  - Desktop: ≥ 1200px
- Relative units (vw, rem) for scalable layouts
- SCSS with organized architecture
- Two-page structure (home and location)

## Tech Stack

- HTML5
- SCSS (compiled with Sass)
- Vite

## Getting Started
```bash
npm install
npm run dev
```

## Deployment
```bash
npm run deploy
```

Deploys to GitHub Pages via the `gh-pages` branch.

## Notes

- Prioritizes relative units over fixed pixel values for better scalability across different screen sizes.