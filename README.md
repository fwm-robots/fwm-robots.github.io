# fwm-robots.github.io

Project page for **A Federation of World Models for Robots: Predictive Responsibility, Composition, and Evaluation**
(CoRL 2026 workshop *Do Robots Need World Models?*).

Static site, no build step: `index.html` + `assets/`. GitHub Pages serves it as is.

## Publish (once)

1. Create a GitHub **organization** named `fwm-robots` (Settings of your account → Organizations → New organization, free plan).
2. In that organization, create a public repository named exactly `fwm-robots.github.io`.
3. From this folder:

```bash
git init -b main
git add .
git commit -m "Project page"
git remote add origin git@github.com:fwm-robots/fwm-robots.github.io.git
git push -u origin main
```

4. In the repository: Settings → Pages → Source: *Deploy from a branch*, branch `main`, folder `/ (root)`.
   The site is live at https://fwm-robots.github.io/ within a minute or two.

## Update

Edit `index.html` or replace a file in `assets/`, then `git add . && git commit -m "…" && git push`.

## Contents of `assets/`

| file | what |
|---|---|
| `paper.pdf` | camera-ready paper |
| `poster_A0.pdf` | A0 poster |
| `fwm_video_4min.mp4` | the four-minute video, poster palette |
| `fwm_one_minute.mp4` | the one-minute reel |
| `video_poster.jpg` | still shown before the video plays |
| `fig_federation.png`, `fig_results.png`, `schema_*.png`, `driving_band.png` | figures |
