# I-Cost Group Static Website

This project is split into multiple HTML pages while keeping the original visual design, fonts, and theme from the initial single-file version.

## Pages

- `index.html` — hero/home
- `about.html` — about section
- `companies.html` — companies + comparison section
- `sectors.html` — sectors section
- `contact.html` — contact CTA section

## Shared assets

- `assets/css/main.css` — original CSS moved out of inline `<style>`
- `assets/js/main.js` — original JavaScript moved out of inline `<script>`
- `assets/media/` — media files for hero backgrounds (home page video)

## Hosting on Hestia

1. Upload the entire repository contents to your site document root.
2. Keep the `assets/` folder structure unchanged.
3. Ensure `index.html` is at the document root.

## Home page background video

Current home page video source (Cloudinary):

- `https://res.cloudinary.com/drjk3faqc/video/upload/v1776355100/8319687-hd_1280_720_25fps_x5puqu.mp4`

If you prefer local hosting instead, upload your MP4 file to:

- `assets/media/home-hero.mp4`

Optional fallback poster image:

- `assets/media/hero-fallback.jpg`

Only `index.html` uses this video background.
