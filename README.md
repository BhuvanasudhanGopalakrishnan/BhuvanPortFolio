# Bhuvanasudhan Gopalakrishnan — Portfolio

A modern, responsive, single-page portfolio for a **QA Engineer / Automation Test Engineer**.
Built with plain HTML, CSS, and JavaScript — no build step, no dependencies.

## Features

- Responsive layout (desktop → mobile)
- Dark / light theme toggle (remembers your choice)
- Scroll-reveal animations + animated stat counters
- Scroll progress bar and active-section nav highlighting
- SEO meta tags + JSON-LD structured data (Person schema) for higher search visibility
- Accessible: semantic HTML, ARIA labels, `prefers-reduced-motion` support
- ATS/recruiter friendly — keyword-rich content pulled from the resume

## Files

| File | Purpose |
|------|---------|
| `index.html` | Page structure and content |
| `styles.css` | All styling and theme tokens |
| `script.js`  | Theme toggle, animations, nav interactions |

## Run locally

Just open `index.html` in a browser, or serve it:

```bash
cd portfolio
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy (free options)

**GitHub Pages**
1. Push this folder to a repo.
2. Settings → Pages → deploy from branch `main`, root.
3. Live at `https://<username>.github.io/<repo>/`.

**Netlify / Vercel** — drag-and-drop the folder, or connect the repo. Zero config.

## Customize

- **Text/content:** edit `index.html`.
- **Colors/theme:** edit the `:root` CSS variables at the top of `styles.css`.
- **Add sections:** copy a `<section>` block and add a matching nav link.

## What to add next (to score even higher)

- A professional headshot in the hero.
- Links to **LinkedIn** and **GitHub** in the contact section.
- A downloadable **PDF resume** button.
- 1–2 more projects with metrics (numbers stand out to recruiters).
