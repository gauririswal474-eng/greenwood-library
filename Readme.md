# Greenwood Public Library – Tailwind Landing Page

Minimal, editorial landing page built with HTML and Tailwind CSS (CDN) only.
No external CSS frameworks and no custom fonts (Tailwind's default font stack).

## Files
- `index.html` – the whole page (Tailwind CDN + extended config for custom keyframes/animation)
- `assets/` – local SVG illustrations used as images

## Features
- Sticky navbar with `backdrop-blur-md`, underline-on-hover via `after:w-0 hover:after:w-full`, inverting "Visit Us" pill
- Editorial hero with staggered entry animation, `hover:scale-105` feature image, 4-column stats
- Sections grid with per-card hover colours and group-hover text colour transitions
- 2x2 gallery with `group-hover:scale-105` zoom and floor tags
- Asymmetric bento grid using column/row spans and pastel cards
- Newspaper-style text columns (`columns-1 sm:columns-2`)
- Membership cards (`brightness-95`, absolute "Popular" badge), testimonial with grayscale-to-colour avatar
- Tinted contact block, 4-column events grid, multi-column footer
- Custom `fadeUp` keyframes defined in `tailwind.config`

## Run
Open `index.html` in a browser (internet is needed for the Tailwind CDN).
