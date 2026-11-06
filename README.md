# 1337securitynews backup

Content backup of https://1337securitynews.com (Ghost blog), taken 2026-11-05.

- `posts/<slug>/index.md` — each post as Markdown with YAML front matter (title, dates, tags, description, feature image)
- `pages/` — About page and author page, same format
- `images/` — full-size originals, mirroring Ghost's `content/images/` layout; Markdown links point here relatively
- `html/` — the original rendered HTML of every page, for reference
- `rss.xml` — the site's RSS feed (full post HTML)
- `index.json` — post metadata in one file

Most static site generators (Hugo, Jekyll, Astro, Eleventy) can import the Markdown files directly.
