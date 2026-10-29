# Simprug Park Residences — static website

Plain HTML/CSS/JS, no build step.

## Host on GitHub Pages
1. Create a repository and upload everything in this folder (keep `.nojekyll`).
2. Settings → Pages → Deploy from branch → `main` / root.
3. Site goes live at `https://<user>.github.io/<repo>/`.

## Structure
- `index.html` — page shell and the single red contact button
- `css/style.css`, `js/app.js` — styles and all page content (rooms `R`, updates `UP`, translations `D`/`UPI`)
- `assets/img/` — photos, logo, map

## Edit notes
- Updates: edit the `UP` array (and the Indonesian text in `UPI`) in `js/app.js`. Text is sample content.
- Social links: replace the Instagram URL (`https://www.instagram.com/`) in `index.html` with the real profile.
- Contact form has no server: it opens the visitor's email app or WhatsApp with the message filled in.
- Sunday is shown as "Closed" in the hours table; change `HRS` in `js/app.js` if that is wrong.
