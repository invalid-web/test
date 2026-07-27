# Portfolio Website

A responsive, single-page design portfolio built with vanilla HTML, CSS, and JavaScript. No build step or dependencies required.

## Structure
- `index.html` - page content and sections (hero, work, about, skills, contact)
- `styles.css` - responsive layout using CSS Grid/Flexbox, custom properties for theming
- `script.js` - mobile nav toggle, dynamic year, scroll-in animations via IntersectionObserver

## Customize
- Replace placeholder text in `index.html` with your name, bio, and real projects.
- Swap `.placeholder-1..4` gradient backgrounds in `styles.css` with actual project images/screenshots (`<img>` inside `.card-media`).
- Update social/email links in the Contact section.
- Accent color is controlled by the `--accent` CSS variable in `:root`.

## Deploy to GitHub Pages
1. Create a new GitHub repository (e.g. `yourname.github.io` for a root-domain site, or any repo name for a project site).
2. Push these three files (`index.html`, `styles.css`, `script.js`) to the repo's default branch.
3. Go to repo Settings > Pages.
4. Under "Build and deployment", set Source to "Deploy from a branch", choose your branch (e.g. `main`) and `/ (root)` folder.
5. Save. GitHub will publish at `https://<username>.github.io/<repo>/` (or `https://<username>.github.io/` if using the special repo name).
6. Changes pushed to that branch auto-redeploy within a minute or two.
