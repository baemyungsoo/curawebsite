# cura — marketing website

The public landing page for **cura**, a Flutter/Dart medication companion app for families.

This is a static, single-page site (`index.html` + `assets/`) with no build step —
open `index.html` directly in a browser, or serve the folder with any static
file host (GitHub Pages, Netlify, Vercel, etc.).

## Structure

```
index.html              The entire page: markup, theme CSS, and vanilla JS
assets/images/           Logo mark, wordmark, and family-avatar illustrations
assets/fonts/             GoogleSansFlex variable font used across the page
```

## Features

- Light/dark theme toggle matching cura's actual in-app palette (`lib/theme/cura_palette.dart`)
- Section-to-section scroll snapping with a scroll-triggered reveal animation
  (respects `prefers-reduced-motion`)
- A self-contained alpha-testimonials carousel
- Responsive layout from phone through desktop widths
