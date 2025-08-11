# EasyDog — Modern, Responsive Bootstrap Website

A fast, mobile‑first starter using Bootstrap 5.3 (CDN), custom design, and minimal JS. Built for great performance on laptop and mobile. Includes dedicated pages: Home, Features, Pricing, About, and Contact.

## What’s included
- Bootstrap 5.3 via CDN (no build tooling required)
- Unique design: gradient hero, brand colors, shadowed cards
- Performance: lazy‑loaded images, deferred JS, preconnect
- A11y: proper semantics, focus styles, reduced‑motion friendly

## Quick start (Windows)
Open the `index.html` file directly, or run one of the following in PowerShell from the project folder:

```powershell
# Open the site in your default browser
start .\index.html
```

Optional: Serve with a simple dev server for proper routing/CORS behavior if you add APIs later. For example, using Python 3:

```powershell
# If Python 3 is installed
python -m http.server 8080
# Then open http://localhost:8080
```

## Customize
- Update colors in `assets/css/styles.css` under `:root`.
- Replace `assets/img/placeholder.svg` with your own images.
- Edit content in `index.html` (sections: Hero, Features, Showcase, Pricing, About, Contact).

## Notes
- This is a static site—no build step is required.
- Keep images sized correctly and compressed for best Lighthouse scores.
