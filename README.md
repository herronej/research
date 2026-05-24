# research

Personal research website — [herronej.github.io/research](https://herronej.github.io/research)

## Structure

```
.
├── _config.yml          Jekyll site config (no theme — custom layout)
├── _layouts/
│   └── default.html     HTML shell (fonts, head, body, scripts)
├── assets/
│   ├── style.css        All styling
│   └── script.js        Scroll-spy nav + reveal animations
├── index.html           Main page content (uses default layout)
└── CV_FY26.pdf          Current CV
```

## Editing content

Edit `index.html` — the structure is broken into clearly-commented `<section>` blocks
(About, Research, Projects, Publications, Experience, Education, Talks, Skills,
Service & Awards). The sidebar nav in the same file lists the section anchors.

## Local preview

```bash
bundle exec jekyll serve
```

Then open http://localhost:4000/research/

## Updating the CV

Replace `CV_FY26.pdf` (or add a new file and update the link in `index.html`
inside the `.contact-strip`).
