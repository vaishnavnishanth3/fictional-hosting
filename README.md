# uHost - Fictional Hosting Website

A static multi-page hosting website built with HTML, CSS, and vanilla JavaScript.

## Overview

This project includes:

- A landing page with plan cards and key features
- A packages page
- A customers page
- A start-hosting signup page
- Shared navigation with desktop/mobile behavior
- A modal interaction for selecting plans

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript (no framework)

## Project Structure

- `index.html` - Landing page
- `main.css` - Landing page styles
- `shared.css` - Common layout/components across pages
- `shared.js` - Shared interactions (mobile nav + modal handling)
- `customers/` - Customers page
- `packages/` - Packages page
- `start-hosting/` - Signup page
- `images/` - Image assets
- `svg/` - SVG example files

## Run Locally

Because this is a static site, you can run it directly in a browser.

### Option 1: Open directly

1. Open `index.html` in your browser.

### Option 2: Serve with VS Code Live Server

1. Install the Live Server extension (if not installed).
2. Right-click `index.html`.
3. Select **Open with Live Server**.

## Notes

- Navigation links are relative and set up for folder-based pages.
- Plan selection opens a modal dialog handled in `shared.js`.
- Mobile navigation is toggled via the hamburger button and backdrop.
