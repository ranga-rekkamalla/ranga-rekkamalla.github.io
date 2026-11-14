# Rangaprasad Rekkamalla — Professional Portfolio

> Senior Frontend Engineer · Frontend Architecture · Angular · React

This directory contains the standalone portfolio website for **Rangaprasad Rekkamalla**, a frontend engineer with 10+ years of experience building scalable enterprise web applications.

## Portfolio

The portfolio presents:

- Frontend architecture and enterprise UI engineering
- Angular and React experience
- Reusable component libraries and design systems
- Accessibility and responsive UX
- Performance optimization
- Unit, E2E and visual regression testing
- Framework migrations and developer experience
- Professional experience across SEEBURGER, MSYS Technologies, Mindtree and Photon Interactive

## Technology Focus

### Frontend
- Angular / AngularJS
- React
- TypeScript / JavaScript
- RxJS
- Angular Signals
- NgRx / Redux
- Standalone Components

### Architecture
- Design Systems
- Reusable UI Component Libraries
- Micro Frontends
- Module Federation
- Nx Monorepo
- Frontend Architecture

### UI & Styling
- HTML5 / CSS3
- SCSS
- Tailwind CSS
- Bootstrap
- Angular Material
- Material UI
- Vaadin
- PrimeNG

### Quality & Testing
- Vitest
- Jest
- Testing Library
- Playwright
- Karma / Jasmine
- Visual Regression Testing
- Storybook

### Delivery & Engineering
- GitHub Actions
- Jenkins
- SonarQube
- Webpack
- Vite
- Rspack
- CI/CD

## Portfolio Structure

```text
portfolio/
├── index.html
├── Rangaprasad_Rekkamalla_Resume.pdf
├── favicon.svg / favicon.ico / apple-touch-icon.png
├── brand/                  # Modular R logo files
├── rangaprasad/index.html  # redirect from the old /rangaprasad/ URL
└── README.md
```

### index.html

The current portfolio is a lightweight, responsive static site designed to demonstrate the visual direction and professional presentation.

It includes:

- "Blueprint" visual identity: Prussian-blue drafting ink with a brass accent (dark) and blueprint paper (light), WCAG AA contrast in both
- Dark / light theme switching with a circular View Transition reveal from the toggle
- Responsive desktop and mobile layout
- Hero drafting sequence on load: headline drafts in, axis lines and rings draw, architecture core settles, labels arrive in order
- Blueprint corner marks on card hover/focus and a timeline line that draws on scroll (decorative only; content is never hidden)
- Load-time hero animation (content below the hero is never hidden, so full-page captures, print and link previews render completely)
- Scroll progress indicator
- Selected work (project case cards), capabilities and technology map
- Downloadable résumé (PDF)
- Open Graph metadata, skip link and visible focus states
- Career timeline
- Technology overview
- GitHub and LinkedIn links
- Reduced-motion support

## GitHub Pages Deployment

The repository includes a GitHub Actions workflow:

```text
.github/workflows/portfolio-pages.yml
```

The workflow publishes the `portfolio/` directory through GitHub Pages whenever changes are pushed to the `main` branch.

Live site: **https://ranga-rekkamalla.github.io/** (this repository is the `ranga-rekkamalla.github.io` user site; the old `/rangaprasad/` path redirects here).

After GitHub Pages is enabled for the repository, the Actions workflow provides the deployed site URL.

## Development Direction

The current static portfolio is the visual foundation for the professional portfolio.

The next evolution can include:

- Angular 21 implementation
- Live GitHub repository/project data
- Project filtering
- Detailed project case studies
- Contact section
- Additional accessibility and performance refinements

## Professional Links

- GitHub: https://github.com/ranga-rekkamalla
- LinkedIn: https://www.linkedin.com/in/rangaaprasad
- Email: rangaprasad88@gmail.com
- WhatsApp: +91 98846 46015

---

© Rangaprasad Rekkamalla · Senior Frontend Engineer · Angular Specialist
