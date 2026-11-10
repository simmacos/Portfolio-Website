# Portfolio Website

Personal portfolio, static site. Hosted on AWS (S3 + CloudFront + Route 53).

## Structure

- `index.html` — home (about, contacts, link to projects)
- `progetti.html` — projects page, cards grouped in sections (Web Apps, AI & IoT)
- `style.css` — single shared stylesheet
- `404.html` — empty
- `favicon.ico`

## Philosophy

- Simpler is better. Simplicity and readability first.
- Vanilla HTML/CSS only. No frameworks, build tools, dependencies, or JS unless really needed.
- Keep current style: code-editor look (One Dark colors, Source Code Pro, `<Title/>` bracket headings).
- No big changes (redesign, restructure, new tooling) unless decided together first. Ask.
- Small, focused edits. Match existing markup and naming.

## Conventions

- New project = new `.card` in the right section of `progetti.html`, same markup as other cards (title, description, `.tech-stack`, `.links`).
- Headings use `<span class="bracket">&lt;</span>Text<span class="bracket">/&gt;</span>`.
- Reuse existing CSS classes and colors before adding new ones.
- No build or tests. Check by opening the HTML in a browser.

## Git

- Never add `Co-Authored-By` or any Claude attribution to commits.
- Always tell me before committing. Never commit without confirmation.
- Concise commit messages.
