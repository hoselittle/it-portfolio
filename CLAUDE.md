# CLAUDE.md

## Project Overview

This is a personal IT/cybersecurity portfolio website for Joselito Augustinus, hosted on GitHub Pages. It showcases cybersecurity skills, certifications, projects, and career objectives, targeting a Security Operations Center (SOC) Tier 1 Analyst role.

This is a **static website** — HTML + CSS with no build system, frameworks, or package manager.

## Repository Structure

```
it-portfolio/
├── index.html      # Main portfolio website (single-page layout)
├── style.css       # All styles — dark cybersecurity theme, fully responsive
├── README.md       # GitHub profile content (Markdown)
└── CLAUDE.md       # This file — guidance for AI assistants
```

## Technology & Format

- **HTML5 + CSS3** — no JavaScript frameworks; vanilla JS for scroll effects and mobile menu
- **Google Fonts** — Inter (body) and Fira Code (monospace/accents)
- **Design theme** — dark background (#0a0e17), cyan accent (#38bdf8), card-based layout
- **Fully responsive** — breakpoints at 900px and 640px
- **No build tools, package managers, or CI/CD pipelines**
- **No external JS dependencies**

## Website Sections

1. **Navigation** — fixed top bar with smooth-scroll links, mobile hamburger menu
2. **Hero** — name, title, animated grid background, CTA buttons
3. **About** — bio text + highlight cards (Education, Goal, Certifications)
4. **Skills** — 4-category grid: Security Operations, Network Security, Systems & Tools, Governance & Compliance
5. **Certifications** — CompTIA Security+, CompTIA Network+, ISC2 CC
6. **Projects** — SIEM Home Lab, Vulnerability Assessment Lab, Network Traffic Analysis
7. **Contact** — LinkedIn and GitHub links with SVG icons
8. **Footer** — copyright

## CSS Architecture

- CSS custom properties (variables) defined in `:root` for colors, spacing, typography
- BEM-like class naming (e.g., `.hero-content`, `.cert-card`, `.skill-category-title`)
- Scroll-reveal animations via IntersectionObserver
- Card hover effects with border glow and translate transforms
- Mobile-first responsive approach with max-width media queries

## Key Conventions

- Keep the dark theme consistent — use CSS variables, not hardcoded colors
- Certification badges use colored circular logos (red for CompTIA, green for ISC2)
- Project cards include tags styled with monospace font and accent color
- All external links open in new tabs with `rel="noopener noreferrer"`
- HTML entities used for icons (no icon library dependency)

## Branching

- `master` / `main` — primary branch with portfolio content
- Feature branches for changes, merged via pull request

## Development Workflow

1. Create a feature branch from `master`
2. Edit HTML/CSS files directly (no build step required)
3. Preview locally by opening `index.html` in a browser
4. Commit with clear, descriptive messages
5. Push and open a pull request

## Deployment

This site is designed for **GitHub Pages**. To enable:
1. Go to repository Settings > Pages
2. Set source to the main branch, root directory
3. The site will be available at `https://<username>.github.io/it-portfolio/`

## Guidelines for AI Assistants

- This is a static site with no build tools. Do not introduce frameworks, bundlers, or package managers unless explicitly requested.
- Use CSS variables from `:root` when styling — do not hardcode colors.
- Maintain the existing section order in index.html.
- Do not remove or alter the LinkedIn/GitHub contact links.
- When adding new sections, follow the existing card-based pattern with hover effects.
- Keep language professional and concise — this is a public-facing portfolio.
- Preserve responsive behavior — test changes against both desktop and mobile layouts.
- README.md serves as the GitHub profile view; index.html is the deployed website.
