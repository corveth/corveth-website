# corveth.ai

This repository contains the source for [corveth.ai](https://corveth.ai) — a philanthropy
ministry that builds and applies AI systems to improve the lives of ordinary people. The
site is a single static HTML page served directly via GitHub Pages, no build step required.

## Live Site

https://corveth.ai

## Stack

Plain HTML/CSS, no framework, no build tooling. Everything needed to serve the site lives
in this repository.

## Local Preview

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080 in a browser.

## Contributing Content

1. Fork this repository.
2. Branch from `main`.
3. Edit `index.html` directly.
4. Preview locally and confirm the page renders correctly.
5. Open a pull request against `main`.

## Deployment

GitHub Pages serves this repository's `main` branch directly — there is no build step.
Pushes to `main` go live automatically. The `CNAME` file pins the custom domain to
`corveth.ai`; DNS must point at GitHub Pages separately.

<!-- trigger initial Pages build -->
<!-- rebuild trigger after visibility change to public -->
