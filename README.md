# gdglab.ch — Global Digital Governance Lab

Static website for the **Global Digital Governance Lab**, a platform initiative of the [Global Governance Centre](https://www.graduateinstitute.ch/research-centres/global-governance-centre) at the Geneva Graduate Institute.

## Structure

```
.
├── index.html          Landing page
├── about.html          About: mission, leadership, advisory board, context
├── activities.html     Activities: research, projects, events, publications, fellowships
├── css/
│   └── style.css       Shared stylesheet (GI-complementary palette, Inter + Playfair Display)
├── js/
│   └── main.js         Mobile nav, scroll effects, reveal animations
└── images/
    └── portrait-placeholder.svg
```

## Design

- **Colours**: institutional navy (`#1C3268`) complementary to the Geneva Graduate Institute and Global Governance Centre, with a teal accent (`#0D9E90`) evoking the Lab's digital-governance focus, and warm gold (`#C09A4A`) tying to GI's warmer tones.
- **Fonts**: [Playfair Display](https://fonts.google.com/specimen/Playfair+Display) (serif headings — academic authority) + [Inter](https://fonts.google.com/specimen/Inter) (sans-serif — modern, legible).
- **Digital feel**: subtle dot-grid and line-grid background patterns, geometric decorative elements, smooth scroll-reveal animations.
- **Responsive**: mobile-first layout with a hamburger menu below 768 px.

## Pages

| Page | Purpose |
|------|---------|
| `index.html` | Landing page — hero, challenge/gap context, vision, three pillars, Why Geneva, activities teaser, GI institutional context |
| `about.html` | About — mission & vision, challenge & gap, why Geneva/why now, leadership placeholders, advisory board (incl. Ambassador Muhammadou Kah), partners, contact |
| `activities.html` | Activities — six research areas, project cards, events calendar, publications list, visiting fellowship programme |

## Development

This is a plain HTML/CSS/JS static site with no build step required. Open any `.html` file in a browser, or serve locally:

```bash
# Python
python3 -m http.server 8000

# Node (npx)
npx serve .
```

## Deployment

Deploy to any static hosting provider (Netlify, GitHub Pages, Cloudflare Pages, etc.) by pointing it at the repository root.
