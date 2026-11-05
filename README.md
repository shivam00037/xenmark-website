# XENMARK — Custom Apparel Website

A responsive, mobile-friendly static website for XENMARK custom apparel, DTF printing, embroidery, and bulk orders.

## Project structure

```text
.
├── index.html       # Website entry point
├── images/          # All local website images (WebP)
├── README.md        # Project notes and deployment steps
└── .gitignore       # Common local/editor files to ignore
```

## Run locally

No build step or package installation is required. Keep the `images/` folder beside `index.html`, then open `index.html` in a browser. For local development, a simple static server is also fine.

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html`, the complete `images/` folder, `README.md`, and `.gitignore` to the repository root.
3. Push/commit to the `main` branch.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and the `/ (root)` folder, then save.
6. Wait for GitHub Pages to publish the site, then open the URL shown on the Pages settings screen.

## Business links

- Instagram: [@xenmark_](https://www.instagram.com/xenmark_/)
- WhatsApp: `+91 6387731661`

The website's forms prepare a WhatsApp message for the visitor to review and send. This static site does not store submitted enquiries in a database.

## Images

All product and apparel photos are bundled locally in `images/`. The page references these files using relative paths, so the project can be hosted as a static GitHub Pages site without a separate image host.
