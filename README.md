# Xianyu Yang Academic Website

This repository hosts the personal academic website for Xianyu Yang:

https://xianyu-yang.github.io/

The site is built with Jekyll and GitHub Pages, based on the AcadHomepage template.

## Main Content Files

- `_config.yml`: site metadata, SEO description, author profile, and social links.
- `_pages/about.md`: homepage introduction, research focus, and news.
- `_pages/publications.md`: working papers and peer-reviewed publications.
- `_pages/cv.md`: professional experience, education, service, and conferences.
- `_pages/Gallery.md`: life and fieldwork gallery.
- `images/`: profile image, research figure, favicon, and gallery images.

## Common Updates

Edit the relevant Markdown file, then commit and push:

```bash
git add .
git commit -m "Update website content"
git push
```

GitHub Pages will rebuild the website automatically after each push to `main`.

## Local Preview

Install Ruby and Bundler, then run:

```bash
bundle install
bash run_server.sh
```

Open http://127.0.0.1:4000 in a browser.

## Notes

- Keep public contact information limited to professional channels.
- Add DOI, code, data, or preprint links when available.
- Compress large images before committing them.
- Avoid committing local preview files, sync metadata, or generated `_site/` output.
