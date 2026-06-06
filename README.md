# Thea Ishida — Portfolio

Personal portfolio website. Live at [thea-ishida.vercel.app](https://thea-ishida.vercel.app).

## Structure

```
portfolio/
└── index.html   ← entire site lives here
└── README.md
```

## Editing the site

Open `index.html` in VS Code (or any text editor). Use **Ctrl+F / Cmd+F** to search for the section you want:

| What to edit | Search for |
|---|---|
| Name & tagline | `hero-name` |
| Bio text | `about-bio` |
| Stats block | `stat-num` |
| Skills | `skills-grid` |
| Work experience | `exp-item` |
| Pinned projects | `project-card featured` |
| Contact / links | `thea.ishida@gmail.com` |
| Colors & fonts | `:root {` |
| GitHub username | `thea-ishida/repos` |

## Deploying changes

This repo is connected to Vercel. Every time you push a commit to `main`, your site redeploys automatically.

```bash
# Make your edits to index.html, then:
git add .
git commit -m "update bio / projects / etc"
git push
```

Vercel picks it up in ~30 seconds and your live site updates.

## Running locally

No build step needed — just open `index.html` directly in your browser, or use the VS Code **Live Server** extension for auto-refresh on save.
