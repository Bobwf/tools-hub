# Tools Hub (Static Site)
A lightweight collection of browser-only tools designed for speed, privacy, and easy hosting on **GitHub Pages**.

## Included Tools
- **JSON Formatter** (`/tools/json-formatter.html`) — Pretty print, minify, validate JSON; copy/download.
- **Base64 Encoder/Decoder** (`/tools/base64.html`) — Encode text/files to Base64 and decode; copy/download.

## Deploy to GitHub Pages
1. Create a new repository on GitHub (e.g., `tools-hub`).
2. Upload these files (or push via git).
3. In GitHub → Settings → Pages → set **Branch: `main` / folder: `/root`**.
4. Wait a minute for the site to go live at `https://<username>.github.io/tools-hub/`.

> Optional: add a `CNAME` file with your domain (e.g., `tools.homebizx.com`) and set a DNS CNAME to `<username>.github.io`.

## Affiliate/CTA sections
- You can add lightweight affiliate CTAs in `index.html` (search for "AFFILIATE SECTION")—they're commented out.

## Local usage
Just open `index.html` in a browser; tools run 100% client-side.

---
**Privacy:** No back-end. All processing happens in your browser.
