# ELEE 4710 – Magnetic Circuit Analysis (interactive lecture prototype)

This is a static GitHub Pages website. No server, npm, or MATLAB installation is needed.

## Contents
- `index.html` — homepage and interactive lecture
- `styles.css` — responsive layout
- `app.js` — slide navigation, interactive models, chart, practice quiz
- `assets/slides/slide-01.jpg` through `slide-36.jpg` — rendered from the instructor-provided **Magnetic Circuit.pdf** lecture (36 pages)

## Publish with GitHub Pages
1. Create a **public** repository named `elee4710` on GitHub.
2. Extract this ZIP file on your computer.
3. Upload **the contents of the extracted folder** (not the folder itself, and not the ZIP file) to the root of the repository. `index.html` must be visible at the repository root.
4. Commit the uploaded files.
5. Open **Settings → Pages → Build and deployment**. Choose **Deploy from a branch**, branch **main**, folder **/(root)**. Save.
6. Visit `https://YOUR-GITHUB-USERNAME.github.io/elee4710/` after deployment finishes.

## Local preview
Double-click `index.html` in your file explorer to open it in a browser. All website assets are local; no external libraries are required.

## Notes for instructor
- This is a **first-chapter prototype**, not the entire ELEE 4710 website.
- Slide images preserve the instructor's original lecture figures and equations.
- Magnetic-core simulator assumes uniform linear material, constant permeability, no saturation, and no leakage.
- Air-gap experiment uses a simplified series-reluctance model with a 0.5 m core path and 0.005 m² area; fringing, saturation and leakage are neglected.
- Practice questions are ungraded and do not transmit student responses or store personal information.
- Review third-party figures embedded in the original lecture before publishing the repository publicly. If necessary, replace figures or restrict access using a university-approved platform. GitHub Pages public repositories are accessible to anyone.
