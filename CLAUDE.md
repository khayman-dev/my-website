# CLAUDE.md

Kimberly Hayman's personal website: a single static page published with GitHub Pages.

## Project layout
- `index.html` holds all the content and CSS (inline). There is no build step and there are no dependencies.
- `photo.jpg` is the profile photo. `README.md` has editing instructions for Kim.
- `favicon.ico`, `favicon-32.png` and `apple-touch-icon.png` are the site icons.

## Publishing
- Commit and push straight to `main`. GitHub Pages publishes from `main`, and changes go live in a couple of minutes.
- Don't create extra branches; `main` is the only branch on purpose.

## Photo
- The page loads `photo.jpg` automatically. If the file is missing, the image removes itself (`onerror`) and the "KH" initials show instead.
- To replace the photo, overwrite `photo.jpg` with a square JPG. Keep it small (about 480×480, under 500 KB). No HTML change is needed.

## Favicon
- A cream "K" (`#faf8f5`) on deep teal (`#2f5d62`, the site's `--accent`) in a rounded square with a corner radius of about 22%.
- Font: Fraunces, weight 700, `font-variation-settings: 'opsz' 9` for sturdy strokes at small sizes. The letter is about 70% of the icon's height.
- A single "K" is used because "KH" blurs at 16 px.
- To regenerate, render a 512×512 master (Playwright works well), then export a 16/32/48 `favicon.ico`, a 32 px `favicon-32.png` and a 180 px `apple-touch-icon.png`.

## Copy preferences
- Keep the wording people-centered: lead with solving real-life problems for people, not with the technology itself.
- Avoid repeating "people" in nearby lines. The tagline, the About lead line and the bio sit close together.
- Keep the footer credit in the third person: "Kim used Claude Code, Anthropic's AI coding assistant, to design and build this page."
- Keep sentences short and plain. Kim edits the text directly, so avoid clever phrasing that needs a second read.
