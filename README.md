# Md. Mahadi Hasan — Academic Portfolio

Personal research portfolio of **Md. Mahadi Hasan**, Ph.D. researcher in Electrical & Computer Engineering at Clarkson University.

All results on the site are quoted directly from the published papers.

## Publish on GitHub Pages (free)

1. Sign in to GitHub and create a **new public repository** named exactly `YOUR-USERNAME.github.io`
   (replace `YOUR-USERNAME` with your GitHub username).
2. Click **Add file → Upload files** and drag in everything from this folder:
   `index.html`, `README.md`, `.nojekyll` and the `assets/` folder (photo + CV) (keep the folder structure).
3. Click **Commit changes**.
4. Open **Settings → Pages**. Under *Build and deployment*, set **Source: Deploy from a branch**,
   **Branch: `main`**, folder **`/ (root)`**, then **Save**.
5. After a minute or two the site is live at `https://YOUR-USERNAME.github.io`.

> `.nojekyll` is a hidden file. On macOS press `Cmd+Shift+.` in Finder to see it. If it gets left out, the site still works.

## Updating

- Edit `index.html` directly on GitHub (pencil icon) and commit; the site redeploys automatically.
- Replace `assets/headshot.jpg` to change the photo (square, about 480×480 px).
- Replace `assets/CV_Md_Mahadi_Hasan.pdf` with your latest CV (keep the same file name), and update the month on the Home tab button.
- The site has four tabs (Home, Research, Teaching, Highlights); each is a `<section class="page">` in `index.html`.
- Publications live in the `J` (journals) and `C` (conferences) lists near the bottom of `index.html`.

## Structure

```
index.html          single-page site (no build step, no frameworks)
assets/headshot.jpg profile photo
.nojekyll           tells GitHub Pages to serve files as-is
```
