# ALP landing pages

Seven static landing pages—one folder per domain. Each folder is a complete site (upload or connect the folder as the **publish directory** for that hostname).

## Connect to GitHub

From this directory:

```bash
git remote add origin https://github.com/YOUR_USER/YOUR_REPO.git
git branch -M main
git push -u origin main
```

Create the empty repo on GitHub first (no README), then run the commands above.

## Deploy one folder per domain

Point each domain’s project to **only** that site’s folder, for example:

| Domain (example) | Publish directory |
|-------------------|-------------------|
| `example-a.com`   | `site-01`         |
| `example-b.com`   | `site-02`         |
| …                 | …                 |

Works with Netlify, Cloudflare Pages, Vercel, GitHub Pages (one Pages site per repo per folder via workflow or separate projects), etc.

## Customize

Edit `index.html` and `styles.css` inside each `site-0X` folder. Replace titles, copy, colors in `:root`, and add images under that folder (e.g. `images/`).
