# selfmap-social-assets

Hosts the rendered JPEG images (carousel slides) for SelfMap Astrology's
daily social content pipeline, served publicly via GitHub Pages so the
Instagram Graph API can fetch them at publish time.

Populated automatically by `social/render/` in the main project repo, one
directory per day (e.g. `2026-09-10/carousel_1_slide1.jpg`), never
overwritten — each day's images get their own path so a stale CDN cache can
never serve yesterday's content under today's URL.

Not meant to be browsed directly. `.nojekyll` disables Jekyll processing so
files are served as-is.
