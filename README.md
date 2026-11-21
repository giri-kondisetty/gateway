# Gateway

Public pages for Gateway: an overview, and a catalogue of the models it serves with their context
windows and published prices.

**Live site:** https://giri-kondisetty.github.io/gateway/

## About this repository

The pages are static files served by GitHub Pages. There is no backend, and nothing here calls an
API. Code examples use `https://<your-gateway>` as the host, to be replaced with the address of a
Gateway you have access to.

The files are generated from the Gateway source, which is maintained separately, and they are
replaced as a whole on each update, so this repository always holds a single commit. Issues are
disabled.

## Layout

```
README.md
docs/               the site, as served
  index.html        overview
  models/           the catalogue, and one page per model
  assets/           scripts and styles
  fonts/
  404.html
```
