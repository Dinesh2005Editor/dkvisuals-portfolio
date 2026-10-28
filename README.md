# DKVisuals.mov — Cinematic Portfolio Starter

A responsive, static portfolio starter for Dinesh Kumar. It is designed to run without Node.js or a build step and can be hosted for free on GitHub Pages or Netlify.

## Files
- `index.html` — portfolio content and page structure
- `styles.css` — streaming-inspired dark theme, responsive layout, subtle motion
- `script.js` — mobile menu, category filters, project detail dialogs and reveal animations
- `assets/dk-logo-icon.png` — cropped icon from the supplied DKVisuals logo image

## Before publishing
1. The header now uses the blue triangular pen mark cropped from your supplied logo image. The screenshot cuts off the right side of the wordmark, so the site keeps a clean text wordmark beside the icon.
2. Replace the three portfolio artwork placeholders with your actual exported Canva designs and real project descriptions. The current cards are explicitly labelled as placeholders, not claimed client work.
3. Check Instagram, LinkedIn and email links in `index.html`.
4. Preview `index.html` in a browser on mobile and desktop.

## Add real portfolio images
Create `assets/work/` and add images such as `poster-01.jpg`. In `index.html`, replace a placeholder `.project-art` block with an image, for example:

```html
<span class="project-art"><img src="assets/work/poster-01.jpg" alt="Description of the actual design" style="width:100%;height:100%;object-fit:cover"></span>
```

Use compressed JPG/WebP images and meaningful alt text. Keep original artwork files as backups.

## Free publishing option: GitHub Pages
1. Sign in to GitHub and create a **public** repository, e.g. `dkvisuals-portfolio`.
2. Upload the contents of this folder (upload the files and folders, not the ZIP itself).
3. Open the repository's **Settings → Pages**.
4. Under the build/deployment section, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. Wait for GitHub Pages to publish the site. Its URL will appear in Settings → Pages.

Do not put passwords, private documents or private contact information in a public repository. The email address included in the site is intentionally a public contact address supplied for this portfolio.
