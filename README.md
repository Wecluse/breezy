# Breezy

A fictional aircon cleaning, repair, and installation website for a freelance web development portfolio.

## Current milestone

Astro starter configured with strict TypeScript and Tailwind CSS. The homepage displays the Breezy name and service tagline. Full service pages, a quote estimator, and inquiry handling are planned, not implemented yet.

## Stack

- Astro for static pages
- TypeScript 6 (compatible with the installed Astro checker)
- Tailwind CSS 4 through its Vite plugin
- Git and GitHub for version control
- Planned hosting: Cloudflare Pages, using its free tier

## Local development

Use a supported Node.js release meeting the package.json engine requirement and npm.

```sh
npm ci
npm run dev -- --background
npx astro dev status
npx astro dev logs
```

Open the URL reported by Astro. Stop the background server with `npx astro dev stop`.

## Verification

```sh
npm run check
npm run build
```

The static production output is generated in `dist/`.

## Workflow

Work in small milestones. Review changes and run checks before committing. The project owner runs all Git pushes manually. Do not commit credentials, environment files, generated output, or dependencies.

This project represents a fictional business; it does not accept real service requests. Hosting and a public GitHub repository have not been configured as part of this milestone.
