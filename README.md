# Competitor Price & Stock Intelligence Service

Static landing page testing demand for a done-for-you service offer.

**Live page:** https://mattbusel.github.io/autocoder-offers-competitor-price-stock-intelligence-serv/

## The offer

A monitoring service for small and mid-size e-commerce brands: it tracks competitor prices and stock levels and sends a weekly intelligence report (PDF/CSV), so the owner stops checking competitor sites by hand.

Price on the page: $49/month.

## What is in this repo

| Path | What it is |
|---|---|
| `index.html` | The offer page: headline, description, and two calls to action |
| `free-tool/index.html` | "The Competitor Vulnerability Audit", a lead-in page with one input field |
| `.nojekyll` | Tells GitHub Pages to serve the files as-is |

Both pages are plain HTML with inline CSS and no dependencies. The paid pilot link goes to Gumroad checkout (https://mattitude8861.gumroad.com/l/ywvda).

The free diagnostic is a front-end stub: it inserts the input into a fixed message template in the browser and does not fetch or analyze anything. Treat it as a placeholder, not a working tool.

## Status

One of several offer pages published in July 2026 to test whether anyone would pay before building the service. The service itself is not part of this repo.

## Deploy

GitHub Pages serves the `gh-pages` branch from the root. Push to `gh-pages` and the site redeploys. To preview locally, open `index.html` in a browser or run `python -m http.server`.
