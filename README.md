# 🌻 Sprout's Life Cycle Adventure

A short interactive series for Primary 3 Science — the life cycle of flowering plants (seed → seedling → adult plant). Built as plain HTML/CSS/JS, so it needs no installation and runs on any phone, tablet, or computer with a browser.

## Files

| File | What it is |
|---|---|
| `00_hub.html` | Home screen — links to everything below |
| `01_seed_structure.html` | Chapter 1: seed coat & seed leaf |
| `02_germination.html` | Chapter 2: the WOW game (water, warmth, air) |
| `03_seedling.html` | Chapter 3: seed leaf food simulation |
| `04_adult_recap.html` | Chapter 4: sequence game + recap quiz |
| `05_home_practice.html` | After-class practice games (5–10 min) |

## Put this online (GitHub Pages) — takes about 2 minutes

1. Create a new repository on GitHub (public is fine, e.g. `sprout-life-cycle`).
2. Upload all six `.html` files in this folder to the root of that repository (drag-and-drop works on github.com — click **Add file → Upload files**).
3. Commit the upload.
4. Go to the repo's **Settings → Pages**.
5. Under **Build and deployment → Source**, choose **Deploy from a branch**.
6. Under **Branch**, choose `main` and folder `/ (root)`, then **Save**.
7. Wait about a minute, then refresh that Settings → Pages screen — it will show your live link, something like:

   `https://YOUR-USERNAME.github.io/sprout-life-cycle/00_hub.html`

8. Send that link to parents. That's the whole site — the bottom navigation bar and home screen link between all chapters automatically.

## Testing notes for parents

- Works best on a phone or tablet held upright.
- Every game responds to a single tap — nothing needs to be dragged.
- Chapter 4 ends with a 5-question quiz; the after-class page (`05`) has no formal scoring pressure, it's just for practice.
- If anything doesn't respond to a tap, a screenshot of exactly where it happened is the fastest way to help fix it.

## Notes on how this is built

- No external libraries — just Google Fonts (Fredoka + Nunito) loaded over the network, so an internet connection is needed the first time a page loads.
- No data is saved between visits (no login, no progress-saving) — this is intentional for now, to keep the site simple to host. If persistent progress tracking becomes a priority later, that would need a small backend or database added.
