# Gambitile — Website

Landing page and privacy policy for **Gambitile — Chess Morph Puzzle**,
a game by [Gicklatt](https://gicklatt.github.io).

🔗 **Live:** [gicklatt.github.io/gambitilegame](https://gicklatt.github.io/gambitilegame)

## About the game

Become the piece you step on. Tap to move as a rook, step onto a knight
tile, and now you move like a knight. 100 deterministic chess-piece
puzzles, every one BFS-verified solvable, across five rising tiers from
4×4 warm-ups to 8×8 boards with holes. Three-star ranks reward optimal
solutions.

No ads, no timers, no internet — designed for short, satisfying
sessions in portrait, one-handed.

## Tech stack

- Plain static **HTML + CSS** — no build step
- Fonts: Press Start 2P + Inter (Google Fonts)
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

> Gambitile ships with **no ads**, so it needs no `app-ads.txt`. The
> shared `app-ads.txt` lives in the
> [`gicklatt.github.io`](https://github.com/gicklatt/gicklatt.github.io)
> repo and serves ad-supported games only.

---

© Gicklatt · [gicklatt@gmail.com](mailto:gicklatt@gmail.com)
