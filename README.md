# Greta Li — Portfolio Website

A professional single-page application (SPA) portfolio showcasing compliance analytics work, nonprofit contributions, publications, and research interests in AI safety and financial systems.

## Overview

This is a responsive, client-side portfolio built with vanilla HTML, CSS, and JavaScript. The site emphasizes clean design, accessibility, and seamless navigation across desktop and mobile devices.

## Key Features

- **Single-Page Application (SPA)**: Client-side navigation with smooth section switching
- **Responsive Design**: Optimized for three distinct viewport tiers:
  - Full desktop (>1200px)
  - Minimized desktop (769px-1024px)
  - Mobile (≤768px)
- **Animated Elements**: 
  - Rotating greeting carousel in 12 languages
  - Scroll indicator arrow animation
  - Rocket gamification on CV page (4-click unlock)
- **Accessibility**: Native PDF viewer with mobile fallback for CV download
- **SEO Optimized**: JSON-LD schema, Open Graph tags, sitemap, and robots.txt

## Sections

- **Home**: Hero section with animated greeting, introduction, and CTA buttons
- **About**: Professional background and interests
- **Publications**: Timeline-styled research publications and blog posts
- **Collaborations**: ALDN reports and nonprofit work
- **CV**: Interactive CV with native PDF viewing and gamified download

## Tech Stack

- **Frontend**: Vanilla HTML5, CSS3 (with custom properties), JavaScript
- **Typography**: Outfit font (Google Fonts)
- **Deployment**: Cloudflare Pages
- **Version Control**: GitHub (g-codes4good/website-portfolio)

## Design System

- **Colors**: Primary #003d82 → #6495ED gradient on #fff5ff background
- **Typography**: Fluid sizing with CSS `clamp()` for responsive scaling
- **Spacing**: CSS custom properties for consistent, scalable spacing
- **Transitions**: 0.3s ease for smooth interactions

## Deployment

Hosted on **Cloudflare Pages** at https://greta-li.pages.dev

Changes pushed to GitHub automatically trigger redeploy via Cloudflare's integration.

## Files

- `index.html` — Complete SPA with all HTML, CSS, and JavaScript
- `robots.txt` — Search engine directives
- `sitemap.xml` — XML sitemap for SEO
- `embedded-files/` — PDF, images, and assets directory

## Asset Directory

All assets should be placed in `embedded-files/`:
- `profilephoto.jpg` — Sidebar profile image
- `cv.pdf` — Curriculum vitae (must be <25MB for Cloudflare Pages)
- `*.png` — Icon assets (sun, smile, lightbulb, rocket, paper-plane)
- `*.pdf` — ALDN reports and publications

---

Built with vanilla web technologies. No build step required.
