# AURA Pro — Premium Headphone Landing Page

A luxury product landing page showcasing GSAP ScrollTrigger storytelling. Built as a portfolio piece demonstrating scroll-driven animation, progressive enhancement, and responsive design.

![AURA Pro](img/hero.jpg)

## Features

- **Pinned scroll story** — Three-stage product narrative (Form → Craft → Technology) with smooth crossfades and interactive hotspots
- **GSAP ScrollTrigger** — Single source of truth for scroll distance, scoped cleanup, and graceful failure handling
- **Progressive enhancement** — Full content visible without JavaScript; reduced-motion users get a clean stacked layout
- **Responsive** — Pinned layout on desktop (960px+), stacked on mobile/touch
- **Accessible** — Native `<dialog>`, skip link, keyboard-navigable mobile menu, focus management

## Tech Stack

- HTML, CSS, vanilla JavaScript (no build step)
- GSAP 3.12.5 + ScrollTrigger (loaded locally)
- Google Fonts (Inter + Playfair Display)

## Live Demo

[View on Vercel →](https://aura-pro-landing.vercel.app)

## Run Locally

```bash
# Clone the repo
git clone https://github.com/Datrik-sai/aura-pro-landing.git
cd aura-pro-landing

# Serve with any static server
python3 -m http.server 8080
# or
npx serve .
```

Open [http://localhost:8080](http://localhost:8080)

## Project Structure

```
├── index.html      # Single-page app (CSS + JS inline)
├── js/
│   ├── gsap.min.js
│   └── ScrollTrigger.min.js
└── img/
    ├── hero.jpg     # Hero product shot
    ├── front.jpg    # Stage I — Form
    ├── side.jpg     # Stage III — Technology (hotspots)
    └── detail.jpg   # Features section
```

## Concept Disclaimer

AURA Pro is a **fictional product** created for portfolio demonstration purposes. All specifications, features, and claims are concept design targets, not measured results.

## License

MIT

---

*Built by [Sai](https://github.com/Datrik-sai)*
