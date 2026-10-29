# QOVES Wedding Day Protocol landing page (couple photo version)

Static site, no build step. Open `index.html` in a browser to preview.

## Publish on GitHub Pages

1. Open your repository on github.com (or create one, e.g. `qoves-wedding`).
2. Upload everything inside this folder (`index.html`, `README.md` and the `assets` folder), replacing the old files, then commit.
3. Settings > Pages: Source "Deploy from a branch", branch `main`, folder `/ (root)`, save.

Live at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## Files

- `index.html`: the page, styles and the script for the slider, recommendations zoom, profile card, countdown and advisor carousel
- `assets/fonts`: PP Neue Montreal and Zagma
- `assets/img`: couple hero photo, before/projection photos, makeup trial photo, facial area thumbnails, advisor headshots

## Phone and desktop versions

- `index.html` is the desktop page. `phone/index.html` is the phone page.
- Screens under 768px wide are sent to `phone/` automatically, and wider screens are sent back to the desktop page, so each version only shows on its own device type.
- Share the main link only. Both pages use the same `assets` folder.

## Still to fill in before launch

- Replace the 3 "Sample review" cards with real customer reviews
- Login and button links (currently point to sections on the page)
- Photo count: countdown and FAQ say eight photos, How it works says 6
- Nav "Your plan" link points to a section that is hidden on this version
