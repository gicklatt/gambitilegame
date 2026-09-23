# Gambitile — Website

Landing page and privacy policy for **Gambitile — Chess Morph Puzzle**,
a game by [Gicklatt](https://gicklatt.github.io).

🔗 **Live:** [gicklatt.github.io/gambitilegame](https://gicklatt.github.io/gambitilegame)

## About the game

Become the piece you step on. Tap to move as a rook, step onto a knight
tile, and now you move like a knight. 500 fixed chess-piece
puzzles with verified solutions, across 25 collections.
Three-star ranks reward optimal
solutions.

No timers, no nudges — designed for short, satisfying sessions in
portrait, one-handed. Undo is free and unlimited. Optional rewarded videos offer extra hints.

## Tech stack

- Plain static **HTML + CSS** — no build step
- Fonts: locally hosted Fredoka + Inter (licenses in assets/fonts)
- Hosted on **GitHub Pages**

## Structure

| Path | Purpose |
|------|---------|
| `index.html` | Game landing page |
| `privacy/index.html` | Privacy policy (App Store / Google Play URL) |
| `assets/` | Icon (`icon.svg`) and screenshots |
| `robots.txt`, `sitemap.xml` | SEO |
| `.nojekyll` | Disables Jekyll processing |

## Develop

Open `index.html` in a browser, or serve locally:

```bash
python3 -m http.server 8000   # http://localhost:8000
```

## Deploy

GitHub Pages → **Settings → Pages → Deploy from a branch → `main` / root**.

## Store URLs

- Privacy Policy: `https://gicklatt.github.io/gambitilegame/privacy/`
- Support / Marketing: `https://gicklatt.github.io/gambitilegame/`

> Gambitile uses Google AdMob; the shared `app-ads.txt` covering all
> Gicklatt ad-supported games lives in the
> [`gicklatt.github.io`](https://github.com/gicklatt/gicklatt.github.io)
> repo (it is served from the root domain so AdMob's crawler finds it
> for every store listing).

---

© Gicklatt · [gicklatt@gmail.com](mailto:gicklatt@gmail.com)
