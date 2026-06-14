# Umbrella Pandemonium — Capstone Portfolio

**The Umbrella Pandemonium** by the Umbrella Pandemonium team  
PLTW Engineering Design & Development · Monroe Township High School · 2025–26

> A barrel CAM–driven origami umbrella inspired by NASA's StarShade coronagraph deployment mechanism.

---

## Team

| Member | Role |
|--------|------|
| **Kavin Padma** | CAD Lead & Cost Analysis |
| **Suniti Suresh** | Performance & Aesthetics Lead |
| **Caprice Simon** | Customer Needs & Safety Lead |

Facilitator: Ms. Vanitha Gaurishanker

---

## Site Structure

```
skc-portfolio/
├── index.html              ← Home (landing page)
├── pages/
│   ├── problem.html        ← 01 · Problem Statement
│   ├── research.html       ← 02 · Survey Data & Patent Analysis
│   ├── design.html         ← 03 · CAD Process & Specifications
│   ├── prototype.html      ← 04 · Prototype Build & BOM
│   ├── testing.html        ← 05 · Test Results
│   ├── simulation.html     ← 06 · Interactive Simulator
│   └── team.html           ← 07 · Team
├── css/
│   ├── global.css          ← Shared styles (nav, buttons, footer, utils)
│   ├── home.css            ← Home page specific
│   └── pages.css           ← Inner page layouts
└── js/
    ├── nav.js              ← Injects shared nav + footer; handles mobile menu
    ├── home.js             ← Hero rain canvas & scroll animations
    ├── cam-anim.js         ← Live barrel CAM cross-section animation
    └── simulator.js        ← 3-tab interactive simulator
```

---

## Hosting on GitHub Pages

1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Set source to **Deploy from a branch → main → / (root)**
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/`

No build step, no dependencies, no Node.js required. Pure HTML, CSS, and JavaScript.

---

## Key Design Facts

- **Mechanism:** 3-start helical barrel CAM replaces the traditional sliding-runner (unchanged since 1880)
- **Prototype:** Barrel CAM v9 — Ø104mm, 263mm tall, 34,340 mesh triangles
- **Survey:** 124 respondents — 41.9% reported umbrella inversion as #1 failure mode
- **Patents analyzed:** 9 prior art patents reviewed
- **CAD iterations:** 17 versions in Fusion 360 via Python API scripting
- **Inspiration:** NASA StarShade coronagraph two-phase petal deployment mechanism
- **Target price:** $10–$20 retail
- **Design life:** 5–6 years

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox) |
| Animation | Canvas API (vanilla JS) |
| Fonts | Google Fonts (Orbitron, Rajdhani, Inter) |
| Hosting | GitHub Pages |

No frameworks. No build tools. No dependencies.
