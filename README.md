# PData Startup Website

This is a **standalone, modern landing page website** for the PData project, designed in the style of a tech startup home page. It introduces, explains, and visually showcases PData with clear sections describing features, workflows, screenshots, and company info.

---

## Project Layout
- `/pages/index.html`: Main landing page (static HTML + Bootstrap, easy to edit)
- `/assets`: Place images (screenshots, logo, etc.) for use in the website
- `/static`: CSS and JS if needed
- `/components`: Optionally put reusable HTML snippets

---

## How to Use
- **Edit content:** Simply modify `pages/index.html` for text, hero headline, features, screenshots, or add new sections as you wish.
- **Replace images:** Place PNG/JPG files into `assets`. Update the `img` tags in HTML to point to new visual assets.
- **Local preview:** Open `pages/index.html` directly in your browser; no backend is required.

---

## Features
- Modern, mobile-friendly design (based on Bootstrap)
- Hero section, features, screenshots, about, and contact/footer
- Startup-style visuals, easily customizable

---

## Deployment: GitHub Pages
### 1. Create a Public GitHub Repository
- Suggested: `pdata-website` (can be different)

### 2. Move or Copy Files
- For easiest use, copy **all files from `pdata_website/pages/` and `pdata_website/assets/`** into the root of your GitHub repository, so that `index.html` is at the top level alongside `assets/`.
- Alternative: You can rename `pages/` to `docs/` and configure GitHub Pages to use `/docs` as the publishing source in repo settings.

### 3. Push to GitHub
```bash
cd pdata_website
# if starting a new repo:
git init
git add .
git commit -m "Initial website"
git remote add origin https://github.com/YOUR-USERNAME/pdata-website.git
git push -u origin main
```

### 4. Enable GitHub Pages
- Go to your repository settings on github.com
- Find “Pages” in the sidebar
- Source: set to `main` branch, root (or `/docs` if you used the docs/ folder)
- Save changes
- Your site will be live at: `https://YOUR-USERNAME.github.io/pdata-website/`

---

## License
This site is for your project demonstration. Style, copy, and structure are freely modifiable.
