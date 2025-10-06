# Aftab Alam — Portfolio

A simple, responsive front-end portfolio website showcasing projects, skills, and contact information.

This repository contains a static HTML/CSS portfolio built with semantic HTML, custom CSS, Font Awesome icons, and Bootstrap for responsive utilities.


# Live-link
 https://aftabalam999.github.io/My-Portfolio/


## Demo

Open `index.html` in any modern browser to view the site locally. No build step is required.

## Features

- Hero section with background and decorative assets
- About section with stats cards
- Skills section showcasing technologies
- Projects section with cards and tech tags
- Contact form (static) and contact details
- Responsive layout with mobile styles

## Project files

- `index.html` — main HTML file
- `style.css` — custom styles (located in the project root)
- `assets/` — images and icons used by the site

You can find the full source in the repository root. The layout uses Google Fonts (Poppins), Font Awesome icons, and Bootstrap (CDN).

## Run / Preview locally

Option 1 — Quick preview (open file):

1. In File Explorer, double-click `index.html` or right-click and choose "Open with" → your browser.

Option 2 — Serve via a simple HTTP server (recommended for accurate routing and local testing):

PowerShell (works on Windows):

```powershell
# from project root
python -m http.server 8000
# then open http://localhost:8000 in your browser
```

If you prefer Node.js and have `http-server` installed:

```bash
# install once: npm install -g http-server
# then from project root:
http-server -c-1
# open the printed local URL in your browser
```

## Development notes

- The contact form is static and does not submit to a backend. Connect a form service (Formspree, Netlify Forms, or custom server) to receive messages.
- CSS is authored in a single `style.css`. You can migrate to SCSS/Sass or a CSS framework if you want to extend the design.
- Images are in `assets/` and referenced from `index.html` using relative paths.

## Deployment suggestions

This is a static site, so it's easy to deploy:
- GitHub Pages: push to a repository and enable Pages in the repo settings.
- Netlify / Vercel: drag-and-drop the folder or connect the repo for CI/CD.

## Customize

- Change the name in the navbar and footer (`index.html`).
- Update `style.css` to tweak colors, spacing, and typography.
- Replace images in `assets/` with your own visuals and update the `src` attributes in `index.html`.

## License

This project is provided as-is. You may reuse or adapt the code for your portfolio. If you'd like a specific license, add a `LICENSE` file (MIT is a common choice for portfolios).

## Contact

If you want help improving or deploying this site, open an issue or contact the author: aftabalam@gmail.com

---

Made with ❤️ — simple, responsive, and easy to extend.# My-Portfolio
