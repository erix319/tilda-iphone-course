# Photography Course

Online photography course — a Tilda landing page.

**Live:** https://erix319.github.io/tilda-iphone-course/

## About

Course landing page for an author-led online photography programme — organising shoots, retouching, directing models and crew, and building a portfolio. Structured around a cohort start date, an audience-fit section, module list and tutor bio.

Interface language is Russian.

## Stack

- **Tilda** — Zero Block layout, built from the platform's page builder
- **Static site** — plain HTML, CSS and JavaScript, no build step and no server
- Tilda's runtime bundle: grid, lazy-loading, forms, menu and animation modules

## Running locally

Any static file server works. From the repository root:

```bash
python -m http.server 8000
```

Then open <http://localhost:8000>.

Opening `index.html` straight off the filesystem mostly works too, but a
server is closer to how it is actually deployed.

## Layout

```
index.html   the page itself
assets/      52 files — styles, scripts, images and fonts
```
