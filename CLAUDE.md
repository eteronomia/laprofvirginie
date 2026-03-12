# La Prof Virginie — Website Project

## Quick Start
```bash
export PATH="$HOME/local/node/bin:$PATH"
cd "/Users/lorenzonicolini/Vibe Coding Projects/Virginie/La Prof Virginie Website/site"
npx astro dev --host   # Dev server on localhost:4321
```

## Tech Stack
- Astro 6.0.3 + Tailwind CSS 4.2.1 + GSAP 3.14.2
- Deploy: git push → Vercel auto-deploys

## Important CSS Notes
- Tailwind CSS 4 uses CSS Cascade Layers — NEVER add unlayered CSS that competes with Tailwind utility classes
- `.reveal.active` must use LONGHAND transition properties (not shorthand) to preserve inline transition-delay on grid children

## Pages
- `src/pages/index.astro` — Homepage (8 sections)
- `src/pages/about.astro` — About page
- `src/pages/contact.astro` — Contact page (Web3Forms, placeholder key needs replacement)

## Content Source
- All copy from: `../SITE_CONTENT_EXTRACTION.md`
- Images: `public/images/` (compressed, originals in `../../_originals_backup/`)

## Design Principles
- Liquid glass EVERYWHERE (Apple-style glassmorphism)
- Warm cream (#F5F0E8) + gold (#F0C44C) + charcoal (#1A1A1A)
- Poppins font, scroll-triggered reveals, floating French-themed SVG decorations
