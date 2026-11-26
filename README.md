# Bhavy Harshal Poladia — portfolio

Static site: `index.html` plus `resume.pdf`. No build step.

## Publish on GitHub Pages

1. On GitHub, create a public repository named exactly `thenerdpoint60.github.io`.
2. Upload `index.html`, `resume.pdf`, `.nojekyll` and this README to it (Add file → Upload files), or push with git:

   ```bash
   git init
   git add .
   git commit -m "Portfolio site"
   git branch -M main
   git remote add origin https://github.com/thenerdpoint60/thenerdpoint60.github.io.git
   git push -u origin main
   ```

3. In the repository go to Settings → Pages, set Source to "Deploy from a branch", branch `main`, folder `/ (root)`.
4. After a minute the site is live at https://thenerdpoint60.github.io

## Updating

- New resume: replace `resume.pdf` with the new export (same file name).
- Text: edit `index.html` directly; each section is marked with an `id` (`suri`, `experience`, `skills`, `projects`, `about`, `contact`).
