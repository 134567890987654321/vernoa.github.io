# vernoa.github.io

Static site for Vernoa notes and references (AP Macro, AP Physics EM, AP Stats, Linear Algebra, and general pages like About/Contact).

## Structure
- `index.html` and `docs/` are the main entry points.
- Topic content lives in `docs/notes/<subject>/` (e.g., `ap-macro`, `ap-physics-em`).
- Shared styles: `docs/styles.css`.

## Quick Start
```bash
# Serve locally (Python 3)
python -m http.server 8000
# then open http://localhost:8000/docs/index.html
```

## Editing Content
- Edit pages directly in `docs/…/*.html`.
- Keep math/plain text in HTML; avoid adding heavy JS.
- Prefer plain ASCII; only add non-ASCII if already present or truly needed.

## Navigation Notes
- Use relative links that mirror the current folder structure.
- Update adjacent page buttons (`Back`, `Next`, etc.) when adding or moving lessons.

## Deployment
- Branches are built via GitHub Pages; `main` is the source. Merge changes there to publish.

## Style Guide (lightweight)
- Reuse existing panel/button classes from `styles.css`.
- Keep headings semantic (`h1` per page, then `h2+`).
- Favor concise sentences and bullet lists for study notes.
