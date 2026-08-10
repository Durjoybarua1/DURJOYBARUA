# Durjoy Barua — Portfolio Website

Official portfolio website for **Durjoy Barua** — Singer, Musician & Composer.

Live site: `https://<your-username>.github.io/<repo-name>/` (link active after Pages setup below)

## What's Inside

- **Hero** — intro with featured artwork
- **About** — bio and background
- **Music** — 3 featured YouTube videos
- **Work With Me** — beat sales & project hire info
- **Connect** — Facebook, Instagram, YouTube, WhatsApp, and Gmail links

Built with plain HTML, CSS, and JavaScript — no build tools, no dependencies, no installation needed.

## File Structure

```
durjoy-website/
├── index.html          # main website file
├── assets/
│   └── logo.jpg         # hero artwork/logo/photo
└── README.md
```

## How to Publish on GitHub Pages

1. **Create a new repository** on GitHub (e.g. `durjoy-barua-website`).
2. **Upload the files**, keeping the exact folder structure:
   - `index.html` in the root
   - `assets/logo.jpg` inside an `assets` folder
3. Go to your repo's **Settings → Pages**.
4. Under **Build and deployment**, set:
   - Source: `Deploy from a branch`
   - Branch: `main`, folder: `/ (root)`
5. Click **Save**. GitHub will give you a live URL — usually ready within 1–2 minutes:
   ```
   https://<your-username>.github.io/<repo-name>/
   ```

## Editing the Site

Everything lives in a single `index.html` file:

- **Text/copy** — edit directly inside the `<section>` tags (About, Videos, Work, Connect).
- **Colors** — change the hex values at the top of the `<style>` block under `:root` (`--bg`, `--red`, `--gold`, `--teal`, `--cream`).
- **Videos** — replace the YouTube links and thumbnail IDs inside the `.video-card` blocks in the **Music** section.
- **Social links** — update the `href` values inside the `.social-card` blocks in the **Connect** section.
- **Hero photo** — replace `assets/logo.jpg` with a new image of the same filename, or update the `src` path in the `<img>` tag inside `.hero-art`.

No build step is required — just edit and save, then re-upload (or `git push`) to update the live site.

## Local Preview

Open `index.html` directly in any browser — double-click the file, or right-click → **Open with** → your browser of choice.

---

© Durjoy Barua. All rights reserved.
