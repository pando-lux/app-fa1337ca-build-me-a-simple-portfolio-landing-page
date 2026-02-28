# Portfolio Landing Page

## Overview
A single-page dark-themed portfolio landing page built with vanilla HTML, CSS, and minimal JavaScript.

## Architecture
- **Type**: Tier 1 — Static site (S3 deployment)
- **Stack**: HTML5, CSS3, vanilla JS
- **External deps**: Google Fonts (Inter)

## Structure
- `index.html` — Single file containing all markup, styles, and scripts

## Sections
1. **Navigation** — Fixed top bar with smooth-scroll links and mobile hamburger menu
2. **Hero** — Name, tagline, two CTA buttons
3. **About** — Bio text with photo placeholder
4. **Skills** — 14 technology pill badges
5. **Projects** — 3 project cards with thumbnail placeholders
6. **Contact** — Email CTA button and social media links
7. **Footer** — Copyright notice

## Features
- Dark theme (#0a0a0a base, #6c63ff accent)
- Responsive layout (mobile breakpoint at 768px)
- Scroll-triggered fade-in animations via IntersectionObserver
- Hover effects on cards, buttons, and skill tags
- Backdrop-blur glass nav bar
- No external JS dependencies

## Key Decisions
- Used Google Fonts (Inter) for clean modern typography instead of system fonts for visual consistency
- IntersectionObserver for scroll animations (no scroll event listeners) for performance
- CSS custom properties for easy theme customization
- All styles inline in `<style>` tag — no build step needed
