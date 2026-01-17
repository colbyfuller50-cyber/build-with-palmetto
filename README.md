# Build with Palmetto — Website Starter

A modern, tech-looking, multi-page static website for **Build with Palmetto** (Websites + Logos for service-based businesses).

## Pages
- `index.html` — Home
- `services.html` — Services
- `portfolio.html` — Portfolio (starter placeholders)
- `consultation.html` — Consultation request form (template)

## How to publish on GitHub Pages
1. Create a new repo on GitHub (example: `build-with-palmetto-site`).
2. Upload the contents of this folder to the repo (or drag & drop).
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set:
   - Source: **Deploy from a branch**
   - Branch: **main** / root
5. Your site will publish to the GitHub Pages URL.

## Connect the consultation form
The consultation form is currently a **template**.

Quick options:
- **Formspree**: create a form, copy the endpoint, then replace the `action="#"` in `consultation.html`.
- **Getform**: similar process.
- **Netlify Forms**: if you host on Netlify.

## Replace portfolio placeholders
Open `portfolio.html` and swap the titles/descriptions.
To add screenshots:
1. Drop images into `assets/img/`
2. Replace the `.mock` div with an `<img>` tag.

---
Built for: Build with Palmetto
