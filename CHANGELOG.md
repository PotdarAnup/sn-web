# Changelog

All notable changes to the Structura Nordic AB company website are documented here.

Format follows [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

---

## [1.0.0] — 2026-06-25

### Added

**Site-wide**
- Fixed glassmorphism navigation bar with scroll-state transition (transparent → frosted glass)
- 4-language switcher (EN / SV / DE / IT) with `localStorage` persistence via Alpine.js
- Responsive mobile menu with hamburger/close toggle
- Scroll-triggered reveal animations (fade-up, fade-left, fade-right) using `IntersectionObserver`
- `prefers-reduced-motion` support — all animations disabled for accessibility
- Shared color palette: navy (`#0F1E35`) + gold (`#F0A500`) + brand cyan (`#00B4D8`)
- Google Fonts: Plus Jakarta Sans (headings) + Inter (body)
- Tailwind CSS v3 (CDN) with custom theme extension
- Alpine.js v3 (CDN) for reactive state

**`index.html` — Home**
- Full-viewport hero with dark BIM-grid overlay, building photo, and floating LOD 500 badge
- Hero stats row: 20+ Years Experience, 6+ Software Platforms, 100% BIM Ready, 5+ Countries
- "Who We Are" section with 2-column layout and software proficiency grid (Revit, AutoCAD, Rhino, Navisworks, Tekla, Inventor)
- 6-card services grid (Façade Design, BIM & 3D Modeling, Drafting, Engineering, Project Support, Automation)
- "Why Choose Us" section with 5 numbered differentiators
- 5-step process timeline on dark navy background
- 3-card featured projects section (AMRF Bringelly, The One Toronto, Red Sea Marine Life Institute)
- CTA section with dual-button layout
- Full-width footer with address, phone, email, navigation links, and services list

**`about.html` — About**
- Page hero with logo watermark background
- Company overview with key stat cards (HQ: Sweden, LOD 500, 5+ Countries, 6+ Platforms)
- Director profile: Premchand Potdar — photo, blockquote, bio paragraphs, 4-stat grid
- 3-entry career timeline (Structura Nordic AB 2023–present, WSP India 2021–2023, Greens Façade Engineering 2017–2021)
- Software skills section with 9 animated progress bars (Revit 98%, AutoCAD 95%, Navisworks 90%, Rhino 85%, Flixo 88%, SolidWorks 80%, Karamba 82%, Inventor 78%, Tekla 75%)
- 8 core façade strengths checklist
- Education cards: Master in Integrated Design (OWL University, 2023–present) + BE Mechanical (CCET, 2017)
- Dark CTA section with logo watermark

**`services.html` — Services**
- Page hero with logo watermark
- LOD level strip (LOD 100–500) on dark navy background
- 6 detailed service sections:
  1. Façade Design & Engineering — 10-type system grid
  2. BIM & 3D Modeling — LOD bar chart visualization, 6-item deliverables list
  3. Drafting & Documentation — 6 document types, SVG fabrication drawing mockup
  4. Engineering & Structural Analysis — 6 calculation type cards (U-value, Wind Load, Glass Load, FEM, Deflection, Thermal)
  5. Project Support Services — 6-item checklist
  6. Automation & Digital Engineering — dark card, 6-item parametric/iLogic list
- 8-card façade system expertise grid (Unitized CW, Stick System, Structural Glazing, Timber, Bracket, Skylight, Rainscreen, Bygghandling)
- Dark CTA section

**`projects.html` — Projects**
- Façade Engineering project portfolio with images from actual delivered projects:
  - AMRF First Building, Bringelly, Australia (Timber Façade, 6★ Green Star)
  - Northvolt Office, Sweden (First Timber Façade, Stick Built)
  - NIbe Project, Sweden (Timber Façade System)
  - The One, One Bloor West, Toronto, Canada (Unitized Curtain Wall, LOD 500)
  - Andaz Doha by Hyatt, Qatar (Hospitality Façade)
  - 201 Brookline Ave, Boston, USA
  - Vapenrocken Projekt, Sweden (Modular Timber Structure)
  - Red Sea Marine Life Institute, Riyadh (Foster+Partners, Custom Glazing)
- Mechanical Engineering project portfolio (Fixture & SPM, Material Movement)

**`contact.html` — Contact**
- Contact form (Name, Email, Company, Service Interest, Project Brief)
- Company contact details panel (address, phone, email)
- Response time and working hours information

---

## [1.1.0] — 2026-07-06

### Added

**`newsletter.html` — Newsletter**
- New page archiving company newsletter issues (static content, no email service)
- Issue No. 01 — "Structura Nordic AB Is Now Live Online": website launch, project portfolio, SEO/analytics behind-the-scenes, what's-next CTA
- "Newsletter" link added to desktop nav, mobile nav, and footer navigation on all 7 existing pages

---

## Unreleased

- [ ] Case study detail pages (per project)
- [ ] Form backend / email integration (currently static form)
