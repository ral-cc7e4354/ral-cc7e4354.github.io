# ral-cc7e4354.github.io

Project page for **Learning Robust Policies for Whole-Body Assistive Tasks via
Dynamic Human Motion Generation**, built with the
[Nerfies / academic-project-page](https://github.com/nerfies/nerfies.github.io)
Bulma template.

## Structure

```
index.html          # the page
static/css, static/js   # Bulma + FontAwesome + carousel/slider assets (do not edit)
figs/               # figures (overview.png)
videos/             # .mp4 assets referenced by the page
.nojekyll           # tells GitHub Pages to serve static/ as-is
```

Media is committed directly rather than via Git LFS — see `.gitattributes`.
GitHub Pages does not resolve LFS pointers and would serve the pointer text.

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Publishing on GitHub Pages

Push to `main`, then in **Settings → Pages** set the source to the `main`
branch, root (`/`). The site goes live at <https://ral-cc7e4354.github.io/>.
