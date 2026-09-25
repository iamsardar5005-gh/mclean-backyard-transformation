# McLean Backyard Transformation

Static one-page site for backyard transformations in McLean, Virginia. The page is built around a short transformation film that runs from the neglected yard to the plan, the build and the finished space in use.

## Structure

```
index.html                 the page
css/mclean-backyard.css    styles
js/mclean-backyard.js      hero film loading, stage rail, before/after slider, build strip, demo form
assets/mclean/
  hero-1280.mp4 / .webm    hero film, desktop (1280×714, H.264 with VP9 fallback)
  hero-720m.mp4 / .webm    hero film, mobile crop (720×576)
  poster-1280 / -720m      poster frame (WebP + JPEG), also the reduced-motion still
  before / after / dusk    stills for the problem, before/after and closing sections
  seq-*.webp               build-stage stills
```

All stills and the web videos are taken from the original master film (not included in this repo, since it is 16.5 MB).

## Running locally

Any static server works, for example:

```
npx http-server .
```

## GitHub Pages

All paths are relative, so the site works from the repo root or from a project subpath. Enable Pages under Settings → Pages → Deploy from branch → `main` / root.

## Before launch

- The form at the bottom is a demo. It validates input but sends nothing. Connect it to an inbox or CRM.
- Replace the descriptive wordmark "Backyard Transformations" with the business name.
- Confirm the McLean/Fairfax County notes (soils, permits, Virginia 811, Resource Protection Areas) against current county guidance.
