# Brian Yee — Personal Website

A single-page personal site built with plain HTML, CSS, and JavaScript — no build step, no dependencies.

## Files

- `index.html` — all content (hero, experience, projects, research, about, contact)
- `styles.css` — styling, with automatic light/dark mode via `prefers-color-scheme`
- `script.js` — scroll-reveal animation

## Preview locally

```sh
python3 -m http.server 4173
# then open http://localhost:4173
```

## Deploy (GitHub Pages)

1. Create a repo named `<your-username>.github.io` on GitHub
2. Push these files to it:
   ```sh
   git init && git add index.html styles.css script.js README.md
   git commit -m "Personal website"
   git remote add origin git@github.com:<your-username>/<your-username>.github.io.git
   git push -u origin main
   ```
3. The site goes live at `https://<your-username>.github.io` within a minute or two.

Also works as-is on Netlify, Vercel, or Cloudflare Pages — just point them at this folder.
