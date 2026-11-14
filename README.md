# naeyoo.github.io

## GitHub Pages

This repository publishes a static site with GitHub Actions. The deployment
workflow copies `index.html` and `zones.json` to the Pages artifact, where the
JSON is served at `/zones.json`.

In the repository settings, set **Pages → Build and deployment → Source** to
**GitHub Actions**. Each push to `main` then publishes the site. The data is
also available from the repository's GitHub Pages URL at `/zones.json`.

Some zone coordinates are approximate placeholders. See the warning in
`zones.json`; do not rely on the data until the zones have been verified.
