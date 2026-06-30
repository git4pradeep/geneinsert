# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

**geneinsert.com** is a static HTML landing page showcasing a premium domain name for sale. The site targets the biotechnology, genetic research, and life sciences industries.

**Technology:** Plain HTML5 with embedded CSS (no build tools, frameworks, or dependencies required).

## Running the Project

To view the page locally, serve it via a simple HTTP server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if available)
npx http-server -p 8000
```

Then open `http://localhost:8000` in your browser.

The `.claude/settings.local.json` is configured to allow local testing at `http://localhost:8000`.

## Structure

- **index.html** — Single-page landing site with all content, styling, and markup.
  - Header with domain branding
  - Feature grid highlighting domain benefits
  - Use cases for different industry segments
  - Call-to-action section with contact email
  - Responsive design with media queries for mobile

## Development Notes

- **No dependencies** — This is vanilla HTML/CSS. No npm install, no build step.
- **Responsive design** — Includes media query breakpoint at 768px for mobile optimization.
- **Color scheme** — Purple gradient (#667eea to #764ba2) as primary brand color.
- **Email contact** — Set to `pradeep.kothakota@gmail.com` (update if needed for domain acquisition inquiries).

## Making Changes

Edit `index.html` directly. Changes are immediately visible when the page is refreshed (no build step required). Test responsiveness with browser developer tools at mobile breakpoints.
