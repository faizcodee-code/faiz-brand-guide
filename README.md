# Faiz UI/UX Brand Guide

The Faiz design system: colour, typography, 214 soft frosted icons, components and UX structure, so every Faiz project looks and behaves the same.

Open `index.html` for the full guide.

## What's inside

| File | Purpose |
| --- | --- |
| `index.html` | The brand guide (works offline, no build step) |
| `tokens.css` | Colour, type, space, radius, shadow and motion variables, with light and dark themes |
| `tokens.json` | The same tokens for Figma and build tools |
| `components.css` | Buttons, fields, switches, badges, alerts, cards, tabs, toast, skeleton |
| `icons/` | All 214 icons as standalone SVG files |
| `icons.json` | Icon names, files and groups |

## Quick start

```html
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:wght@600&family=DM+Sans:wght@400;500&display=swap">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/USERNAME/faiz-brand-guide@v1.0.0/tokens.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/USERNAME/faiz-brand-guide@v1.0.0/components.css">

<button class="fz-btn fz-btn-primary">Save changes</button>
```

Replace `USERNAME` with your GitHub username. Pin a release tag in production.

## Publish the guide with GitHub Pages

1. Push this folder to a public repository named `faiz-brand-guide`.
2. Go to Settings, then Pages. Under Build and deployment, choose Deploy from a branch, pick `main` and `/ (root)`, then select Save.
3. The guide goes live at `https://USERNAME.github.io/faiz-brand-guide/`.

## License

MIT. See `LICENSE`.
