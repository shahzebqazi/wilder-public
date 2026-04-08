# Wilder — public site

Promotional site for **Wilder** (Gank Mid Studios). **Static** `index.html` + `assets/` — no build step.

## Content policy

- **No game source** — marketing only.
- **No spoilers** — trailer-safe copy.
- **No jokes / meme tone** — straight, professional, aligned with [gankmid.co](https://gankmid.co/).

## Assets

- **`assets/cartridge.svg`** — Fictional cartridge art (gardener + abstract nine muse pillars). Not final product.
- **`assets/shot-*.svg`** — Placeholder “screenshots” (concept art only, not real captures).

`index.html` injects a **`<base href="…/">`** so `assets/…` resolves correctly when the site is opened as `/wilder-public` **without** a trailing slash (otherwise browsers can request `/assets/…` and images 404).

## Local preview

From this directory:

`python3 -m http.server 8765`

Then open `http://127.0.0.1:8765/` — paths resolve like production.

## Contact (also on the page)

| | |
|--|--|
| Studio | [gankmid.co](https://gankmid.co/) |
| Email | [code@sqazi.sh](mailto:code@sqazi.sh) |
| Mastodon | [@willy@social.devilplan.com](https://social.devilplan.com/@willy) |
| Matrix | [@metalmasteringengineer:matrix.org](https://matrix.to/#/@metalmasteringengineer:matrix.org) |

**Live (GitHub Pages):** [sqazi.sh/wilder-public/](http://sqazi.sh/wilder-public/)

Issues: typos and broken links welcome.
