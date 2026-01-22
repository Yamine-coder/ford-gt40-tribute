<div align="center">
  <img src="images/Ford gt 40 vue haut v2.png" alt="Ford GT40" width="420"/>
  <h1>Ford GT40 — Tribute</h1>
  <p><em>Jun 18–19, 1966 &nbsp;·&nbsp; Le Mans 24H &nbsp;·&nbsp; First American Victory &nbsp;·&nbsp; 1-2-3 Finish</em></p>
  <br/>
  <img src="https://img.shields.io/badge/HTML-E34F26?style=flat&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS-1572B6?style=flat&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/Status-Complete-success?style=flat"/>
</div>

---

## About

Static tribute page dedicated to the **Ford GT40**, the car born from Henry Ford's obsession to defeat Ferrari at Le Mans. In 1966, it delivered — dominating the race with a historic **1-2-3 finish**, ending Ferrari's six-year winning streak.

The page is structured in 4 sections — History, Design, Performance, and Legacy — with scroll-triggered animations, a teaser for the coming Ferrari 250 GTO chapter, and a fully animated popup.

---

## Screenshots

| Hero | Design |
|------|--------|
| <img src="images/Ford gt 40 vue haut v2.png" width="300"/> | <img src="images/_pb_preview/ford gt vu gauche.png" width="300"/> |

| Legacy | Ferrari Popup |
|--------|--------------|
| <img src="images/_pb_preview/ford gt derniere vue.png" width="300"/> | <img src="images/_pb_preview/ferrari vu haut.png" width="300"/> |

---

## Specs

| | |
|---|---|
| **Engine** | 4.7L V8 |
| **Top Speed** | 330 km/h |
| **0 – 100 km/h** | 3.8 sec |
| **Max Power** | 485 BHP |
| **Weight** | 1 014 kg |
| **Drivetrain** | Mid-engine · RWD |
| **Gearbox** | 5-speed Manual |
| **Height** | 1 016 mm (40 inches) |

---

## Features

- Scroll-triggered entrance animations (Webflow IX2)
- Section progress bar
- Sticky navigation
- Specs grid with hover interactions
- **Ferrari 250 GTO teaser** with animated popup (coming soon)
- Fully responsive — mobile slide-up popup
- No external CSS framework

---

## Structure

```
ford-gt40-tribute/
├── index.html              # Main page
├── ferrari-250-gto.html    # Coming soon placeholder
├── css/                    # Webflow base styles
├── js/                     # IX2 + jQuery
├── images/
│   ├── Ford gt 40 vue haut v2.png
│   ├── ford gt cartoon.png
│   └── _pb_preview/        # Section car photos
└── server.js               # Local dev server
```

---

## Run Locally

```bash
node server.js
# → http://localhost:3001
```

---

## Coming Next

<div align="center">
  <img src="images/_pb_preview/ferrari vu haut.png" alt="Ferrari 250 GTO" width="280"/>
  <br/><br/>
  <strong>Ferrari 250 GTO</strong> — The Rival &nbsp;·&nbsp; <em>Coming Soon</em>
</div>
