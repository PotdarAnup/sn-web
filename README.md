# Structura Nordic AB — Company Website

Corporate website for **Structura Nordic AB**, a specialized façade engineering and mechanical design firm headquartered in Gothenburg, Sweden.

---

## Overview

A static multi-page website delivering company information, services, project portfolio, and contact details. Built with no build tools or frameworks — open any `.html` file directly in a browser.

**Owner & Director:** Premchand Potdar  
**Contact:** info@structuranordic.se · +46 761 715 919  
**Address:** Häradsdomarevägen 86, 42244, Gothenburg, Sweden

---

## Pages

| File | Description |
|---|---|
| `index.html` | Home — hero, services overview, why-us, process, featured projects, CTA |
| `about.html` | Director profile, company overview, experience timeline, software skills |
| `services.html` | Full service catalogue (6 services + 8 façade system types), LOD levels |
| `projects.html` | Project portfolio — Façade and Mechanical Engineering projects |
| `contact.html` | Contact form and company details |

---

## Tech Stack

| Layer | Technology |
|---|---|
| Styling | [Tailwind CSS v3](https://tailwindcss.com) via CDN |
| Interactivity | [Alpine.js v3](https://alpinejs.dev) via CDN |
| Fonts | [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans) (headings) + [Inter](https://fonts.google.com/specimen/Inter) (body) via Google Fonts |
| Language | Vanilla HTML5 / CSS3 / JavaScript (ES6) |
| Build | None — no bundler, no package manager |

---

## Project Structure

```
Company website/
├── index.html
├── about.html
├── services.html
├── projects.html
├── contact.html
├── README.md
├── CHANGELOG.md
├── Image/
│   └── Building image.png          # Hero and project card image
├── Facade Engg. Projects/          # Façade project photos
│   ├── 201 Brookline Ave,Boston, USA.jpeg
│   ├── Andaz Doha, by Hyatt , Qatar.jpeg
│   ├── NIbe, Timber Facade System, Stick Built, Sweden.jpeg
│   ├── Nothvolt Office, First Timber Facade system, Stick Built, Sweden.jpeg
│   ├── Vapenrocken Projekt, Sweden, First Module Project using Timber Structure.jpeg
│   ├── WhatsApp Image 2026-06-24 at 12.27.52 AM.jpeg
│   ├── WhatsApp Image 2026-06-24 at 12.36.06 AM.jpeg
│   ├── WhatsApp Image 2026-06-24 at 12.36.19 AM.jpeg
│   └── image-117-2048x1366.jpg
└── Mechanical Engg. Projects/      # Mechanical project photos
    ├── Fixture and SPM/
    └── Material movement/

../Company Logo/                    # One level up — shared logo assets
├── Logo Structura Nordic AB.png
└── Prem photo.jpeg
```

---

## Multi-Language Support

The site supports **4 languages**, toggled via the nav language picker. The selection persists in `localStorage` under the key `sn-lang`.

| Code | Language |
|---|---|
| `en` | English (default) |
| `sv` | Svenska |
| `de` | Deutsch |
| `it` | Italiano |

Translations are inline via Alpine.js `t(en, sv, de, it)` helper calls — no external translation files.

---

## Running Locally

No server required. Open any page directly:

```
# Windows
start "D:\Web Apps\Structura Nordic AB\Company website\index.html"
```

Or drag `index.html` into any browser. An internet connection is needed to load Tailwind, Alpine.js, and Google Fonts from CDN.

---

## Design Tokens

| Token | Value | Usage |
|---|---|---|
| `navy-800` | `#0F1E35` | Primary dark background, buttons |
| `navy-900` | `#0A1628` | Footer, dark sections |
| `gold-500` | `#F0A500` | Labels, CTA buttons, accent |
| `brand.cyan` | `#00B4D8` | Process steps, BIM accents |

---

## Browser Support

Targets modern evergreen browsers (Chrome, Firefox, Edge, Safari). `prefers-reduced-motion` is respected — all animations and transitions are disabled for users who have this preference enabled.
