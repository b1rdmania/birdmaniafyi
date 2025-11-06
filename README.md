# Birdmania — Web3 Growth & GTM Consulting

A minimal, fast static landing page you can deploy anywhere.

## Quick edit

- Update links in `index.html`:
  - Replace `https://x.com/yourhandle` with your X handle
  - Replace `https://cal.com/yourhandle/intro` with your booking link
  - Replace `hi@birdmania.fyi` with your email
- Swap the hero image in `styles.css` by changing the `background` URL for the `.photo` rule
- Optional: add `og.jpg` and `favicon.ico` to the project root or adjust meta tags

## Run locally

Open `index.html` directly or use a static server:

```bash
# Python
python3 -m http.server 4000
# or Node
npx serve -l 4000
```

Visit `http://localhost:4000`.

## Deploy

- Vercel: import the repo, framework = "Other", output = project root.
- Netlify: drag‑and‑drop the folder or set publish directory to the root.
- GitHub Pages: enable Pages on the repo (branch: main, folder: root).

## Notes

- No build step; pure HTML/CSS. Easy to theme in `styles.css`.
- Add a real `og.jpg` (1200x630) for rich previews on X and Discord.


