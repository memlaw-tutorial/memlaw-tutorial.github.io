# NeurIPS 2025 Tutorial Website

**Title:** Data Privacy, Memorization, and Copyright in Generative AI: A Practical Guide  
**Venue:** NeurIPS 2025, San Diego Convention Center, USA

This repository contains a simple static website for the NeurIPS 2025 tutorial on
data privacy, memorization, and copyright in generative AI.

## Structure

- `index.html` – single-page site with overview, outline, presenters, panel, and materials
- `style.css` – styling (no JS required)
- `assets/` – (optional) place future slides, notes, and other materials here

## Local preview

Open `index.html` directly in a browser, or run a simple HTTP server:

```bash
python -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000) in your browser.

## GitHub Pages

1. Push this repository to GitHub.
2. In **Settings → Pages**, choose:

   * Source: `main` (or `deploy`) branch
   * Folder: `/ (root)`
3. Save. The site will be available at `https://<user>.github.io/<repo>/` once built.

Update `index.html` as the tutorial schedule, materials, and links are finalized.
