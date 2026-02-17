# Caleb Portfolio & CV

Modern personal portfolio website with a dedicated CV page, WhatsApp-first contact flow, and strong visual presentation.

## Preview

### Profile Image

<img src="assets/profile.jpg" alt="Caleb profile image" width="280" />

### Website Preview

<img src="assets/web-preview.png" alt="Portfolio website preview" width="900" />

## Overview

This project contains:

- `index.html`: main portfolio site (hero, about, skills, experience, projects, blog, testimonials, contact)
- `cv.html`: standalone CV page with a print-to-PDF button
- `assets/profile.jpg`: shared profile image used across both pages

The site is built with plain HTML, CSS, and JavaScript (no framework build step required).

## Features

- English-only interface
- Responsive hero section with custom profile frame
- Project cards with `Live Demo` and `Source Code` links
- Blog and testimonials sections
- Contact form that opens WhatsApp with prefilled message
- Social channels set to GitHub, X, and WhatsApp only
- SEO-ready metadata (Open Graph, Twitter tags, JSON-LD)
- Accessibility improvements (skip links, ARIA labels, focus-visible styles)
- CV page with:
  - Back to Home button
  - Download PDF CV (browser print)
  - Expanded professional sections

## Tech Stack

- HTML5
- CSS3 (custom styles + responsive media queries)
- Vanilla JavaScript
- Tailwind CDN (present for utility support)
- Font Awesome icons
- Google Fonts

## Project Structure

```text
.
├── index.html
├── cv.html
├── assets/
│   └── profile.jpg
└── README.md
```

## Run Locally

Because this is a static site, use any local static server.

### Option 1: Python

```bash
cd /home/pabloh/Music/code
python3 -m http.server 8000
```

Open:

- Portfolio: `http://localhost:8000/index.html`
- CV: `http://localhost:8000/cv.html`

### Option 2: VS Code Live Server

Open the folder and run **Live Server** on `index.html`.

## Customization Guide

### 1. Profile Photo

Replace:

- `assets/profile.jpg`

Both `index.html` and `cv.html` will update automatically.

### 2. Social Links

Edit `SOCIAL_LINKS` in `index.html` and links in `cv.html` if needed:

- GitHub
- X
- WhatsApp

### 3. WhatsApp Contact Number

Update the number constant in `index.html`:

- `WHATSAPP_NUMBER`

Also update visible WhatsApp links/text in contact blocks if you change the number.

### 4. Project Links

Update project links in:

- `index.html` project cards (`View Project`, `View Code`, and quick links)
- `cv.html` selected projects section

### 5. CV Content

Edit `cv.html` sections:

- Profile
- Experience
- Key Achievements
- Education & Certifications
- Delivery Strengths
- Additional Information

## Deployment

You can deploy as a static site on:

- GitHub Pages
- Netlify
- Vercel (static)
- Cloudflare Pages

## Notes

- The CV PDF download uses `window.print()`. Choose **Save as PDF** in the print dialog.
- If image changes do not appear immediately, hard refresh the browser (`Ctrl + F5`).

## Contact

- GitHub: https://github.com/Kallypsoh254
- X: https://x.com
- WhatsApp: https://wa.me/254797510941

## License

Personal portfolio use. Update this section if you want to apply a specific open-source license.
