# Fernando Paz — QA Automation Portfolio

Personal portfolio site: experience, skills, featured projects and downloadable CV, in English and Spanish.

**Live site:** https://fernando-qa-portfolio.vercel.app

## Stack

- [Astro](https://astro.build) — static site, no client framework
- Plain CSS + a small inline script for the EN/ES language toggle
- Deployed on [Vercel](https://vercel.com): every push to `main` publishes a new version

## Run locally

Requires Node.js 22.12+.

```bash
npm install
npm run dev       # http://localhost:4321
```

## Build

```bash
npm run build     # output in dist/
npm run preview   # serve the build locally
```

## Project structure

```text
public/              static files served as-is (photo, favicon, CV PDFs)
src/layouts/         base HTML layout, fonts and global styles
src/pages/index.astro  page content (EN/ES copy), markup and styles
```

All texts live in the `copy` object at the top of `src/pages/index.astro`, one block per language.

## Featured projects

- [ecommerce-bike](https://github.com/FerPazAutomation/ecommerce-bike) — full-stack e-commerce with pytest, Vitest and Playwright test layers
- [qa-automation-learning](https://github.com/FerPazAutomation/qa-automation-learning) — Playwright + TypeScript learning path and portfolio suite with CI

## Contact

- LinkedIn: [linkedin.com/in/fernandollanespaz](https://www.linkedin.com/in/fernandollanespaz/)
- GitHub: [github.com/FerPazAutomation](https://github.com/FerPazAutomation)
