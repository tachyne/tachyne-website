# tachyne-website

The source for **[tachyne.com](https://tachyne.com)** — the landing page for
[tachyne](https://github.com/tachyne/tachyne-world), a Minecraft-compatible
server written from scratch in pure Go with a versionless core.

It's a single, self-contained static page (`index.html`, inline CSS/JS, no
build step) served by **GitHub Pages** with a custom domain.

## Develop

Open `index.html` in a browser — that's the whole site. Edit and refresh.

## Deploy

Pushing to `main` publishes automatically via GitHub Pages. The `CNAME` file
maps the site to `tachyne.com`; DNS points the apex at GitHub Pages.

---

tachyne is an unofficial fan project — not affiliated with Mojang, Microsoft,
or Minecraft's developer/publisher in any way. Apache-2.0.
