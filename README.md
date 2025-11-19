# Berry AI Bible Static Site

This repository contains the public marketing, support, and privacy policy pages for the Berry AI Bible iOS app. The entire site is static and ready to publish with GitHub Pages.

## Folder Structure

```
berry-ai-bible/
├── index.html
├── support.html
├── privacy.html
├── assets/
│   ├── css/
│   │   └── styles.css
│   └── img/
│       ├── app-icon.png
│       └── screenshots/
└── README.md
```

- Replace `assets/img/app-icon.png` with your real icon.
- Add App Store screenshots to `assets/img/screenshots/`.

## GitHub Pages Deployment

1. Push this folder to your GitHub repository.
2. In GitHub, open **Settings → Pages**.
3. Under **Source**, choose the `main` branch.
4. Select the `/ (root)` folder and save.

GitHub Pages URLs once published:

- Marketing URL → `/`
- Support URL → `/support`
- Privacy Policy URL → `/privacy`

## Updating Contact Info

- Replace `support@example.com` in `support.html` and `privacy.html` with your active support inbox.

## Adding Screenshots

- Place PNG or JPEG files inside `assets/img/screenshots/`.
- Update `index.html` when you are ready to showcase them.

## Making Updates

1. Edit the HTML or CSS files as needed.
2. Run `git status` to review changes.
3. Commit and push to the `main` branch.
4. GitHub Pages will automatically redeploy within a few minutes.
