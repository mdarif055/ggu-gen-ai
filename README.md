# Publishing this site to GitHub Pages

This folder contains a ready-to-publish static site rendering the Acentra
solution design document.

```
index.html
assets/
  architecture.png
  flow.png
```

## Steps

1. **Add the files to your repo** (`https://github.com/mdarif055/ggu-gen-ai`):
   - Easiest: on GitHub, click **Add file → Upload files**, drag in `index.html`
     and the `assets/` folder (with both PNGs inside), then commit directly to
     the `main` branch.
   - Or via git locally:
     ```bash
     git clone https://github.com/mdarif055/ggu-gen-ai.git
     cd ggu-gen-ai
     # copy index.html and assets/ into this folder
     git add .
     git commit -m "Add Acentra solution design site"
     git push
     ```

2. **Enable GitHub Pages**:
   - Go to the repo → **Settings → Pages**.
   - Under **Build and deployment → Source**, select **Deploy from a branch**.
   - Branch: `main`, folder: `/ (root)`. Click **Save**.

3. **Visit your site** (usually live within a minute or two):
   ```
   https://mdarif055.github.io/ggu-gen-ai/
   ```

No build step is required — this is plain HTML/CSS/JS with two image assets.
