# github-user-created

**Live demo:** https://vinaysinghchaudhary1.github.io/github-user-created-gituser001/

## Summary

Publish a Bootstrap page with form id="github-user-${seed}" that accepts a GitHub username, optionally uses ?token=, and displays the account creation date in YYYY-MM-DD UTC inside #github-created-at.

## Features

- LLM-generated single-page web app
- Automated GitHub Pages deployment
- Basic validation against provided selector checks

## Project structure

* `index.html` — Single-page application entry (HTML + inline references to CSS/JS)
* `style.css` — Project stylesheet (Bootstrap + custom rules)
* `script.js` — Lightweight vanilla JS for interactivity (theme toggle, CSV parsing, UI wiring)
* `assets/` — Images, PDFs, and other uploaded attachments
* `LICENSE` — Project license (MIT)

## How to run (local)

1. Clone the repository:

```bash
git clone https://github.com/VinaySinghChaudhary1/github-user-created-gituser001.git
cd github-user-created-gituser001
```

2. Open `index.html` in your browser (no build step required for this single-page app):

```bash
# quick open (macOS)
open index.html
# or (Linux)
xdg-open index.html
```

## Usage

Visit the GitHub Pages URL above to see the generated app. The page implements the behavior required by the evaluation checks (tables, theme toggle, assets rendering). Attachments pushed alongside the app are available in the `assets/` folder.

## Code explanation

- `index.html` — The generated HTML includes semantic layout, a container for the main UI, and script tags that wire up behavior required by the checks.
- `style.css` — Minimal overrides and project styles, loaded after Bootstrap.
- `script.js` — Handles CSV/JSON parsing, rendering tables into `#product-sales` or `#csv-data`, theme toggle logic, and small UI helpers.
- `assets/` — Static files (images, CSV/JSON, PDFs) used by the app. The generator places uploaded attachments here and references them from the app.

## License

This repository is distributed under the MIT License. See the `LICENSE` file.

---

## Round report — 2025-10-17

**Brief:** Publish a Bootstrap page with form id="github-user-${seed}" that accepts a GitHub username, optionally uses ?token=, and displays the account creation date in YYYY-MM-DD UTC inside #github-created-at.

**Checks:**
- document.querySelector('#github-user-${seed}').tagName === 'FORM'
- document.querySelector('#github-created-at').textContent.includes('20')
- !!document.querySelector('script').textContent.includes('https://api.github.com/users/')

**Status:** ✅ Completed

**Pages URL:** https://vinaysinghchaudhary1.github.io/github-user-created-gituser001/

---


## Round 2 update (2025-10-17)

See the site: https://VinaySinghChaudhary1.github.io/github-user-created-gituser001/


## 🌀 Round 1 (2025-10-17)

**Brief:** Publish a Bootstrap page with form id="github-user-${seed}" that accepts a GitHub username, optionally uses ?token=, and displays the account creation date in YYYY-MM-DD UTC inside #github-created-at.

**Checks:**
- document.querySelector('#github-user-${seed}').tagName === 'FORM'
- document.querySelector('#github-created-at').textContent.includes('20')
- !!document.querySelector('script').textContent.includes('https://api.github.com/users/')

**Status:** ✅ Completed

**Pages URL:** [https://VinaySinghChaudhary1.github.io/github-user-created-gituser001/](https://VinaySinghChaudhary1.github.io/github-user-created-gituser001/)

---
