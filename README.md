# Ritik Singh — Portfolio

Personal portfolio website. Built with plain HTML, CSS, and JavaScript — no frameworks, no build step.

## Files

```
portfolio/
├── index.html        ← main page
├── style.css         ← all styles
├── script.js         ← nav scroll + mobile menu
├── vercel.json       ← Vercel routing config
└── assets/
    └── ritik.jpg     ← profile photo
```

## Deploy to Vercel (via GitHub)

1. Push this folder to GitHub.
2. In Vercel, select **New Project** and import the repository.
3. Keep the framework preset as **Other** and leave the build command empty.
4. Deploy. Vercel serves `index.html` directly; `vercel.json` keeps client-side paths routed to the page.

## Add a resume later

When a resume PDF is ready, place it in `assets/resume.pdf` and add a Resume link back to the hero section in `index.html`.
