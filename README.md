# Mengfei Li Academic Homepage

This is a lightweight static academic homepage designed for GitHub Pages. It does not require Jekyll, Hugo, npm, or a build step.

## Files

- `index.html` - main homepage content.
- `assets/css/styles.css` - visual styling and responsive layout.
- `assets/js/main.js` - mobile navigation and footer year.
- `assets/img/selfie.png` - profile photo.
- `.nojekyll` - tells GitHub Pages to serve the site as plain static files.

## Deploy to GitHub Pages

1. Create a GitHub repository named `murphylmf.github.io` for a personal homepage, or any repository name for a project homepage.
2. Upload all files from this folder to the repository root.
3. In GitHub, open `Settings` -> `Pages`.
4. Select `Deploy from a branch`, choose `main`, and set the folder to `/root`.
5. Save. The site should appear at `https://murphylmf.github.io/` after GitHub finishes deploying.

## Customize

- Replace `assets/img/selfie.png` if you want to use a different profile photo.
- Update the GitHub link if your username is not `murphylmf`.
- Add paper PDFs, code links, BibTeX, teaching, service, or news sections as your academic profile grows.
- If you want citation numbers on the page, add them manually from Google Scholar because Scholar blocks reliable automatic scraping.

## Template Direction

The design is intentionally closer to a clean single-page academic profile than a heavy framework. It uses ideas common in academic homepage templates such as project highlights, publication cards, compact navigation, and GitHub Pages compatibility, while keeping the deployment path simple.
