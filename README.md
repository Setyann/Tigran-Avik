# Tigran-Avik — 5 redesign demos

Static HTML/CSS/JS package. No npm, framework, server-side code or build step is required.

## Open
Start with `index.html` and choose one of the five concepts.

## Concepts
1. `demo-01-cinematic` — ARVESSO-like cinematic direction; fullscreen video/photo hero, horizontal project carousel, reviews, process, gallery.
2. `demo-02-architectural` — light architectural minimalism; typography/grid-first.
3. `demo-03-industrial` — engineering/B2B direction; technical sections, project filter and process.
4. `demo-04-portfolio` — portfolio-first; work gallery and category filters dominate the page.
5. `demo-05-corporate` — premium corporate; balanced services, projects, process, reviews and CTA.

## Replace photos
Current placeholders are in `assets/images/`:
- `project-1.svg` ... `project-5.svg`
- `process.svg`

You can either overwrite these files with your edited photos while keeping the same filenames (change the HTML extension if using JPG/WebP), or edit the `<img>` / CSS URLs directly.

Recommended production format: WebP/AVIF plus JPG fallback if needed.

## Replace hero video
Demo 01 expects:
`assets/video/hero.mp4`

Suggested web export: H.264 MP4, muted, 8–15 sec loop, 1080p, compressed to roughly 8–12 MB or lower if visual quality allows.

## Content safety
Only the 2004 licensing date and broad construction scope are treated as grounded public facts. Project names, exact counts, client quotes, metrics and contact details should be replaced/confirmed by the company before publication.
