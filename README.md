# JustInLovewithME

This repository contains a simple static Valentine's landing page.

## Local Testing

You can serve the site locally with a quick HTTP server:

```bash
cd /workspaces/JZKCWEB
python -m http.server 8000
# open http://localhost:8000 in your browser
```

## Deployment via GitHub Pages

A GitHub Actions workflow is already configured to automatically publish the contents
of the `main` branch to the `gh-pages` branch whenever you push. Pages will serve
whatever lives in `gh-pages`.

1. Ensure the files (`index.html`, `styles.css`, `script.js`) are committed.
2. Push `main` to GitHub.
3. Go to the repository's **Settings > Pages**, select the `gh-pages` branch as the
   source, and save. The site will be available at
   `https://<owner>.github.io/<repo>/`.

You can optionally customize a domain by editing the workflow or adding a `CNAME`
file.
