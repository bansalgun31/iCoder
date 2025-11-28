# iCoder Project

Simple static website containing a few HTML pages and AVIF images. This repository appears to be a small demo or portfolio site with several HTML pages and images in AVIF format.

## Contents
- `about.html` : About page
- `bootstrap.html` : Page that likely includes Bootstrap-based layout or examples
- `contact.html` : Contact page
- `about1.avif`, `about2.avif`, `about3.avif` : AVIF images used on the site
- `pic1.avif`, `pic2.avif`, `pic3.avif` : Additional page images
- `thumb1.avif`, `thumb2.avif`, `thumb3.avif`, `thumb4.avif` : Thumbnails

If you add more files they will appear in the same directory.

## Preview locally (recommended)

Open the files directly in a browser by double-clicking the HTML files, or serve the folder with a local HTTP server so relative links and resources load correctly.

PowerShell (Python 3):

```powershell
# from repository root
py -3 -m http.server 8000
# or if python is on PATH
python -m http.server 8000

# then open http://localhost:8000/bootstrap.html (or another page)
```

VS Code Live Server:

- Install the "Live Server" extension
- Open the workspace folder in VS Code
- Click "Go Live" in the status bar and open the page in the browser

Notes:
- AVIF images are modern and supported in recent versions of Chromium-based browsers and Firefox. If you see missing images in older browsers, consider adding WebP or JPEG fallbacks.

## Suggested next steps

- Add an `index.html` that serves as the site's entry point (currently there is no `index.html` in this root). If you intend `bootstrap.html` to be the main page, consider renaming it to `index.html`.
- Add proper metadata (title, description) and a simple navigation between pages.
- Consider adding a tiny `README` section with license/author information.
- Deploy to GitHub Pages, Netlify, or another static host for a quick public preview.

## Contributing

Feel free to open issues or PRs to improve pages, add fallbacks for AVIF, or add build/deploy scripts.

## License

Add a license file (e.g., `LICENSE`) if you plan to make this repo public.

---
Generated README for a small static HTML + AVIF image project.
