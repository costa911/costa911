# Portfolio v2 review notes

Static GitHub Pages site: open `index.html` locally; no build step or JavaScript is required. `styles.css` contains the layout and visual design. Keep stylesheet URLs relative for GitHub Pages project hosting.

## Content evidence — reviewed 21 October 2026

- Existing portfolio and README: name, University of Derby IT graduate, data stack, interests and LinkedIn address.
- https://github.com/costa911/kitchen-loop-community — confirmed public. Repository description supports a self-hosted recipe book, cooking logs, dinner planning, shopping lists, local JSON storage and documented setup paths for Linux, macOS and Windows through Docker Desktop or WSL2. No private backend, accounts or employer data are included.
- https://github.com/costa911/f1-analysis — confirmed public. README supports the 2005–2025 non-champion analysis, Jolpica API source, comparison metrics, Python/pandas/Jupyter stack, charts and datasets. Featured as project 02 after The Kitchen Loop; no ranking or statistical validity claims added.
- https://github.com/costa911/ht-opportunity-scanner-portfolio — confirmed public. README supports a Python football betting-exchange opportunity scanner using Betfair, odds-based filters, Telegram alerts and a curated portfolio snapshot. Featured as project 03; keep the wording descriptive and avoid presenting it as financial advice or a recommendation.

Only these three evidenced projects are featured. Public repository descriptions can age; recheck them before publishing. No employer data, project metrics, credentials, internal URLs or private repository links were added.

## Design and accessibility

Snow Crash-inspired pink/cyan palette, city silhouette and perspective grid; decorative artwork is hidden from assistive technology. Semantic landmarks and headings, skip link, visible keyboard focus, generous link targets, responsive single-column layouts, and reduced-motion support. No external fonts, tracking or third-party contribution widgets.

## Validation

- HTML structure checks: single H1, unique IDs, valid internal targets, local stylesheet and HTTPS external links.
- Firefox headless visual review at 1440px desktop and 375px mobile.
- Git whitespace check.
- Chromium automation could not launch because of environment sandbox restrictions. Full interactive keyboard and assistive-technology testing remains a manual review step.

Changes are for local branch review only. Do not push or deploy without explicit approval.
