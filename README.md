# Live Matter

Generative artworks by Valentina Contini that run live in the browser and answer to touch, sound and streams of data.

**Gallery:** https://valenrg.github.io/live-matter/

| No. | Work | Inputs |
|---|---|---|
| 01 | [Aphelion Drift](aphelion-drift/) | Microphone, touch, music file |
| 02 | [Tide of Edits](tide-of-edits/) | Live Wikipedia edits ([Wikimedia EventStreams](https://stream.wikimedia.org/v2/stream/recentchange)), touch |

## How it's built

Each work is a single self-contained `index.html` with hand-written WebGL 2 shaders: no build step, no libraries, no AI or paid services. The site is plain static files served by GitHub Pages.

## Adding a work

1. Make a folder named after the work, with its `index.html` and a `thumb.jpg` (960 × 640).
2. Add a `← Live Matter` link back to `../` in the work's controls.
3. Add an entry to the `works` list in the root `index.html`, and a row to the table above.
4. Commit and push to `main`; GitHub Pages republishes in a minute or two.

© 2026 Valentina Contini. All rights reserved.
