# Project Instructions

This repository contains a standalone static training and meal guide.

- The public site is `site/index.html`; edit that file directly.
- Preview from the repository root with `python3 -m http.server 8000 --directory site`.
- Cloudflare Pages is connected to GitHub; production branch is `main`, build command is `exit 0`, and output directory is `site`.
- Branch model: daily work goes to `dev` (Cloudflare builds a Preview); `main` changes only through a `dev`→`main` PR merged with a merge commit (no squash, no rebase), and that merge is the production deploy. Never push to `main` directly.
- Treat all content in `site/` as public. Do not add personal identifiers, medication lists, medical history, or private notes.
