# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a static HTML portfolio website hosted on GitHub Pages. The site showcases three main projects:
- Korttelikommentti (korttelikommentti.fi)
- Adventur (adventur.fi) 
- GitHub profile link

## Architecture

The website is a single-page application built with vanilla HTML, CSS, and JavaScript:

- **index.html**: Main portfolio page with scroll-based navigation
- **Assets**: Three WebP images for project previews (kk.webp, adventur.webp, github.webp)
- **Styling**: Embedded CSS using VT323 Google Font for retro aesthetic
- **Navigation**: Scroll wheel and touch gestures control section transitions
- **Layout**: Three full-screen sections with background images and overlay titles

## Development Commands

Since this is a static site with no build process:

- **Local development**: Open index.html directly in a browser or use a simple HTTP server
- **Testing**: Manual testing across different devices and browsers
- **Deployment**: Automatic via GitHub Pages when pushing to main branch

## Key Technical Details

- Mobile-responsive design with media queries
- Touch and mouse wheel event handling for navigation
- CSS-only animations and transitions
- External links open in new tabs
- Background image filtering for text readability
- Fixed top/bottom bars hidden on mobile devices

## File Structure

```
/
├── index.html          # Main portfolio page
├── README.md          # Project description
├── kk.webp           # Korttelikommentti preview
├── adventur.webp     # Adventur preview
└── github.webp       # GitHub preview
```

The site is hosted at: https://pixunen.github.io/