# Manikanta Mendi — Portfolio

A single-page portfolio site. Plain HTML/CSS/JS — no build step, no dependencies to install.

## Files
- `index.html` — all content and structure
- `style.css` — all styling (palette, type, layout)
- `script.js` — scroll-reveal animation
- `assets/Manikanta_Mendi_Resume.pdf` — downloadable resume (linked from the nav bar)

## Deploy free on GitHub Pages

1. Create a new GitHub repo. For a personal site at the root domain, name it exactly:
   `your-github-username.github.io`
   (If you'd rather keep it as a project page instead, any repo name works — see step 4.)

2. Upload these four items (`index.html`, `style.css`, `script.js`, `assets/` folder) to the
   root of that repo — either via the GitHub web UI ("Add file → Upload files") or:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_USERNAME.github.io.git
   git push -u origin main
   ```

3. Go to the repo's **Settings → Pages**. Under "Build and deployment", set Source to
   **Deploy from a branch**, branch `main`, folder `/ (root)`. Save.

4. Wait 1–2 minutes. Your site will be live at:
   - `https://YOUR_USERNAME.github.io` (if you used the special repo name in step 1), or
   - `https://YOUR_USERNAME.github.io/REPO_NAME` (for any other repo name)

## Things to update before publishing
- Replace the two `href="#"` GitHub links (in the Projects section and the footer) with your
  real GitHub profile/repo URLs once you start pushing projects.
- Swap the `#` project links on each project card for the actual repo link once each project
  is uploaded.
- Update the resume PDF in `assets/` any time you tailor or refresh your master resume.
