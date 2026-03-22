# Jayasri Priyadharshini — Portfolio Website

Personal portfolio website for **Jayasri Priyadharshini** — Spatial Designer, Material Explorer, and Founder of Urbanpots, Pondicherry.

Built as part of the BBA (Digital Business & Entrepreneurship) programme at **IIM Bangalore**.

🌐 **Live Site:** [https://your-username.github.io/your-repo-name](https://your-username.github.io/your-repo-name)

---

## About

This is a fully responsive, multi-page portfolio website built from scratch using only HTML and CSS — no frameworks, no templates, no libraries. Every layout, colour choice, and typographic decision was made to reflect Jayasri's design identity: material-led, craft-rooted, and grounded in the philosophy of re-seeing what already exists.

---

## Pages

| File | Page | Description |
|---|---|---|
| `index.html` | Homepage | 6-panel image grid — one per portfolio category, each clickable |
| `about.html` | About | Origin story, values, education, and personal section |
| `portfolio.html` | Portfolio | 6 sections: Interiors, Landscape, Furniture, Lighting, Wall Art, Products |
| `materials.html` | Material Library | 9 material categories with process philosophy |
| `urbanpots.html` | Urbanpots | Brand story, services, project types, and AMC |
| `nad.html` | NAD Village | Nature · Art · Design ecosystem vision |
| `services.html` | Services | Full service offering across 3 categories |
| `contact.html` | Contact | Contact form and project enquiry |

---

## Structure

```
portfolio-website/
├── index.html
├── about.html
├── portfolio.html
├── materials.html
├── urbanpots.html
├── nad.html
├── services.html
├── contact.html
├── README.md
└── images/
    ├── jayasri-portrait.jpg
    ├── panel-interiors.jpg
    ├── panel-landscape.jpg
    ├── panel-lighting.jpg
    ├── panel-wallart.jpg
    ├── panel-furniture.jpg
    ├── panel-materials.jpg
    ├── int-vibe-house.jpg
    ├── int-cafe.jpg
    ├── int-restobar.jpg
    ├── int-residential.jpg
    ├── int-resort.jpg
    ├── land-resort.jpg
    ├── land-garden.jpg
    ├── land-cafe-outdoor.jpg
    ├── land-private.jpg
    ├── furn-wood-table.jpg
    ├── furn-chair.jpg
    ├── furn-cabinet.jpg
    ├── furn-console.jpg
    ├── light-brass-pendant.jpg
    ├── light-driftwood.jpg
    ├── light-sconce.jpg
    ├── wall-lippan.jpg
    ├── wall-warli.jpg
    ├── wall-tanjore.jpg
    ├── prod-vessel.jpg
    ├── prod-dhokra.jpg
    ├── prod-macrame.jpg
    ├── prod-pyrography.jpg
    ├── mat-salvage.jpg
    ├── mat-doors.jpg
    ├── mat-pillars.jpg
    ├── mat-wood-slab.jpg
    ├── mat-roots.jpg
    ├── mat-brass.jpg
    ├── mat-stone.jpg
    ├── mat-fragments.jpg
    └── mat-offcuts.jpg
```

---

## Design System

**Fonts**
- `Cormorant Garamond` — display serif, all headings and quotes
- `DM Sans` — geometric sans, all body text and UI

**Colour Palette**
| Variable | Hex | Use |
|---|---|---|
| `--ivory` | `#F4EFE6` | Light page backgrounds |
| `--cream` | `#EBE3D5` | Secondary backgrounds |
| `--terracotta` | `#A85840` | Primary accent — links, labels, highlights |
| `--rust` | `#7A3828` | Darker accent — hover states, nav |
| `--sage` | `#6E8060` | Green accent |
| `--dark-sage` | `#4A5C40` | Deep green |
| `--charcoal` | `#28271F` | Near-black, dark sections |
| `--ink` | `#1A1914` | Deepest dark, page backgrounds |
| `--mid` | `#5A5448` | Body text on light backgrounds |
| `--gold` | `#B8942C` | Decorative accent |

**CSS Techniques Used**
- CSS custom properties (`--variables`) for the entire design system
- CSS Grid — primary layout tool across all pages
- Flexbox — nav, buttons, inline groups
- `position: fixed` — navigation bar
- `position: sticky` — about page portrait
- `backdrop-filter: blur()` — frosted glass effects
- `@keyframes` animations with `animation-delay` staggering
- `clamp()` for fluid responsive typography
- `aspect-ratio` on image and card containers
- `::before` / `::after` pseudo-elements for decorative details
- `@media` queries at `max-width: 900px` for full mobile responsiveness
- SVG noise texture overlay on all pages

---

## Running Locally

No build step required. Open `index.html` directly in any modern browser.

```bash
# Clone the repo
git clone https://github.com/your-username/your-repo-name.git

# Open in browser
open index.html
```

All internal links use relative paths — everything works locally and on GitHub Pages without any configuration.

---

## Deploying to GitHub Pages

1. Push all files to a public GitHub repository
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch → main → / (root)**
4. Your site will be live at `https://your-username.github.io/your-repo-name`

---

## Images

All images go in the `images/` folder. See the file structure above for the complete list of required filenames. Images are referenced directly in CSS as `background-image` — no `<img>` tags needed.

Recommended: compress all images at [squoosh.app](https://squoosh.app) before uploading. Aim for under 300KB per image.

---

## Built With

- HTML5
- CSS3 (no frameworks)
- Google Fonts — Cormorant Garamond + DM Sans
- No JavaScript frameworks
- No build tools

---

## Author

**Jayasri Priyadharshini**
Founder, Urbanpots · Pondicherry, India
BBA (DBE), IIM Bangalore

---

*© 2025 Jayasri Priyadharshini. All rights reserved.*
