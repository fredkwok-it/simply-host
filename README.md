# simply-host

A shelf of single-file HTML explainers — markup and JavaScript, nothing else.
No build step, no dependencies, no external requests. Open a file and it plays.

## Live

Hosted with GitHub Pages: https://fredkwok-it.github.io/simply-host/

- [`index.html`](index.html) — the landing page / index
- [`jev-explained.html`](jev-explained.html) — *Jev, in motion*: how we use Jev, a System One model, inside an app. Ten chapters, one 3.4 MB file, runs offline.
- [`IBM_Motion_Reel.html`](IBM_Motion_Reel.html) — *IBM // Motion Reel 2026*: a real-time motion homage — every frame drawn live in Canvas 2D + WebGL, no video file, plays with sound.

## Adding an explainer

1. Drop the new `.html` file into this repo root.
2. Add a card for it on `index.html` — copy an existing `<a class="plate">` block and edit the title, description, and link.

Push to `main` and Pages redeploys automatically.

## Serving

GitHub Pages is deployed from the `main` branch, root (`/`). Every explainer must stay self-contained: one `.html` file with everything inline, so it also runs offline.