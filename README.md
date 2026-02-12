# Berry AI Bible

**Official website for the Berry AI Bible iOS app** — a minimalist marketing, support, and policy site hosted on GitHub Pages.

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen?style=flat-square)](https://gitberryz.github.io/berry-ai-bible/)  
**Live site:** [gitberryz.github.io/berry-ai-bible](https://gitberryz.github.io/berry-ai-bible)

---

## Overview

This repository contains the static, public-facing site for **Berry AI Bible**: an AI-powered scripture companion for iPhone and iPad. The site provides:

- **Home** — App overview, features, FAQ, and App Store download
- **Support** — Contact info, troubleshooting guides, and bug-report guidance
- **Privacy** — Full privacy policy and data practices

The site is built with plain HTML and CSS, has no build step, and is optimized for SEO and fast loading.

---

## Tech Stack

| Layer    | Choice              |
| -------- | ------------------- |
| Hosting  | GitHub Pages        |
| Markup   | HTML5               |
| Styling  | CSS (custom, no framework) |
| Scripts  | Minimal (e.g. year in footer) |

---

## Project Structure

```
berry-ai-bible/
├── index.html          # Home / marketing
├── support.html        # Support & troubleshooting
├── privacy.html        # Privacy policy
├── robots.txt          # Crawler rules + sitemap reference
├── sitemap.xml         # SEO sitemap for search engines
├── README.md
└── assets/
    ├── css/
    │   └── styles.css  # Site-wide styles (light/dark)
    └── img/
        ├── app-icon.png
        └── app-icon-light.png
```

---

## Deployment (GitHub Pages)

1. Push this repository to GitHub (e.g. `gitberryz/berry-ai-bible`).
2. Open **Settings → Pages**.
3. Under **Source**, select the **main** branch.
4. Choose **/ (root)** as the folder and save.

The site will be available at:

- **Home:** `https://<username>.github.io/berry-ai-bible/`
- **Support:** `https://<username>.github.io/berry-ai-bible/support.html`
- **Privacy:** `https://<username>.github.io/berry-ai-bible/privacy.html`

Redeploys automatically on push to `main`.

---

## SEO & Discoverability

The site is set up so search engines and social platforms can index and preview it correctly:

- **Meta descriptions** on every page
- **Canonical URLs** to avoid duplicate-content issues
- **Open Graph** and **Twitter Card** tags for link previews
- **Structured data** (JSON-LD) for the app on the home page
- **robots.txt** and **sitemap.xml** for crawlers

No extra tooling is required; all of this is in the HTML and static files.

---

## Making Updates

1. Edit the relevant `.html` or `assets/css/styles.css` file.
2. Commit and push to `main`:
   ```bash
   git add .
   git commit -m "Brief description of change"
   git push origin main
   ```
3. GitHub Pages will rebuild and publish within a few minutes.

---

## Links

- **Website:** [gitberryz.github.io/berry-ai-bible](https://gitberryz.github.io/berry-ai-bible)
- **App Store:** [Berry AI Bible on the App Store](https://apps.apple.com/us/app/berry-ai-bible/id6751311486)
- **Support email:** [berryaibible@gmail.com](mailto:berryaibible@gmail.com)

---

## License & Copyright

Copyright © 2025 Berry Labs. All rights reserved.  
This repository is for the Berry AI Bible website only; the app and branding are proprietary.
