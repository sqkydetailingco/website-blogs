# SQKY blog-writer

Working folder for new /articles pages. Process doc and skill are being finalised - see the main process document.

## Folder layout
- `_template/` - copy this for every new article
- `articles/YYYY-MM-<slug>/article.md` + `images/` - one folder per article (copy, alt text, carousel, FAQ, web-ready photos)
- `_originals/` - raw camera files. Git-ignored, never published.

## Image rules (before they enter an article's images/ folder)
- Name: `<vehicle>-<service>-<what-it-shows>-<suburb>-<nn>.jpg`, lowercase, hyphens. Hero: `...-hero-desktop.jpg` / `...-hero-mobile.jpg`
- ~2000px wide, well under 500KB. Strip EXIF/location. Blur plates.
- Alt text lives in the article's article.md next to the file name.

## Git
Only web-ready images and article.md files are committed. Image URLs for Squarespace code blocks are served from the repo (see process doc).
