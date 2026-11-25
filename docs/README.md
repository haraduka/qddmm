# QDD-MM project website

This directory is the GitHub Pages source for the `haraduka/qddmm` repository. The repository README lives one level above it and links to the hardware files on Google Drive.

## Preview

From the repository root:

```sh
python3 -m http.server 8000 --directory docs
```

Visit http://localhost:8000. No build step is required. An HTTP preview supplies the referrer needed by the embedded YouTube player.

## Publication

In GitHub Settings → Pages, choose **Deploy from a branch**, **main**, and **/docs**. `.nojekyll` enables serving the static files directly.

Canonical URL, social image URLs, `robots.txt`, and `sitemap.xml` are configured for https://haraduka.github.io/qddmm/. If the repository owner or name changes, update all of these URLs together.

## Content

- `index.html`: research overview, Humanoids 2026 venue, figures, videos, citation, and contact.
- `assets/css/main.css`: responsive styles.
- `assets/img/`: figures rendered from the manuscript and `banner.png` used for social sharing.
- `assets/videos/`: QDD-MM assembly (`whole-assembly-x32.mp4`, 32× speed), module connection (`assembly-1-x8.mp4` and `assembly-2-x8.mp4`, 8× speed), and shoulder–arm demonstration videos.
- `assets/paper.pdf`: manuscript PDF.

The overview video embeds https://youtu.be/09xRhZO497k. The GitHub link points to https://github.com/haraduka/qddmm; the Design Files button links to the [Google Drive package](https://drive.google.com/drive/folders/1PGDll5MoJPhwdC_somhJeLg_bphG-0lB?usp=drive_link).

The original materials came from the paper workspace's `main.tex`, `main.pdf`, `figs/`, and `videos/`. Keep the citation in `index.html` synchronized with `../README.md`. The arXiv version is available at https://arxiv.org/abs/2611.24279. Add the conference DOI and page numbers when available.
