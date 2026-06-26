# ML for Solid Mechanics — WCCM-ECCOMAS 2026 Short Course Website

Static GitHub Pages site for the IACM short course at WCCM-ECCOMAS 2026, Munich.

## Pages
- `index.html` — Home: course overview, modules, objectives, scientific areas
- `instructors.html` — Instructor bios
- `schedule.html` — Full-day schedule + registration info
- `materials.html` — Lecture slides, notebooks, code repository (populated before the event)

## Deploy to GitHub Pages
1. Create a repo (e.g. `wccm2026-mlsm-shortcourse`)
2. Push this `website/` folder as the repo root (or configure Pages to serve from `/docs`)
3. In repo Settings → Pages → Source, set branch `main`, folder `/root`
4. The site will be live at `https://<username>.github.io/<repo-name>/`

## To add instructor photos
Place portrait images in `img/` and update each `<div class="instructor-photo">` in `instructors.html`:
```html
<div class="instructor-photo">
  <img src="img/chen.jpg" alt="J. S. Chen">
</div>
```
