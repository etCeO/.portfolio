# My Portfolio Website
Every project here reflects my growth, adaptability, and commitment to turning ideas into functional, meaningful results. I’m excited to keep learning and building, taking on new technological challenges along the way.

**Live site:** https://etceo.github.io/.portfolio/

## About this project

A static, single-page portfolio built with plain HTML, CSS, and a little JavaScript. There is no framework and no build step, so it is easy to edit and fast to load.

- **Hosting:** GitHub Pages, deployed from the `main` branch
- **Fonts:** IBM Plex Mono and DM Sans (Google Fonts)
- **Contact form:** Formspree

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole site: markup, styles, and scripts |
| `profile.jpg` | Profile photo shown in the hero |
| `Ethan_E_Lopez_Resume.pdf` | Resume linked from the hero and the Resume section |
| `og-image.png` | Preview image shown when the link is shared |
| `favicon.svg`, `favicon-32.png`, `apple-touch-icon.png` | Browser tab and home-screen icons |

## Editing the site

- **Colors:** change the variables at the top of the `<style>` block in `index.html` (the `:root` section).
- **Add a project:** copy the project template comment above each projects grid.
- **Update the resume:** replace the PDF with a new file of the same name.
- **Preview locally:** open `index.html` in a browser, or use the VS Code Live Server extension.

## Publishing changes

1. Create a branch: `git switch -c my-change`
2. Edit, preview locally, then commit and push
3. Open a Pull Request on GitHub and review the changes
4. Merge into `main`. GitHub Pages redeploys in a minute or two.