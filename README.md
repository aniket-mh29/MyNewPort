# MyNewPort

A personal portfolio website for `Aniket Kumare`, built with static HTML, CSS, and JavaScript.

## Overview

This repository contains a modern portfolio landing page with a sidebar navigation layout and multiple sections including Home, About, Projects, Skills, Certifications, and Contact.

## Features

- Responsive single-page portfolio layout
- Animated typing text effect in the hero section
- Sidebar navigation with section transitions
- Preloader animation on page load
- Certifications gallery with category filtering
- Lightbox preview for certification images
- Live style switcher with color themes and dark/light body skin
- Contact form UI with name, email, subject, and message fields

## Files and Structure

- `index.html` — main portfolio page markup
- `css/style.css` — core styling and theme imports
- `css/styleSwitcher.css` — style switcher panel styling
- `js/script.js` — page behavior, navigation, filtering, and lightbox logic
- `js/styleSwitcher.js` — theme switching and body skin logic
- `js/ityped.min.js` — third-party typing animation library
- `images/` — profile photo, backgrounds, certificate images, and related assets
- `images/Resume.pdf` — downloadable resume/CV

## Usage

1. Open `index.html` directly in a browser.
2. Or serve the folder from a local web server for better results:

```bash
cd /home/aniketkumare/Projects/MyNewPort
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Customization

- Update the content in `index.html` to change text, section headings, and personal details.
- Modify skill progress, education, experience, and project cards directly in `index.html`.
- Add or replace certificate images under `images/certificates` and update the associated portfolio item markup.
- Change theme colors in `css/skins/` and adjust the style switcher options.

## Notes

- The contact form is currently a static form and does not submit to a backend.
- Font Awesome and Google Fonts are loaded via CDN in `css/style.css`.

