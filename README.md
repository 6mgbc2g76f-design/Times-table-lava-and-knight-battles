# Dragon Maths — Three Adventures

An offline-capable, tablet-friendly 12×12 multiplication game with **Practice**, **Lava Survival**, and **Knight Battle**.

## Publish with GitHub Pages

1. Create a new **public** GitHub repository.
2. Upload **all files from this ZIP directly into the repository root** (not the ZIP itself and not an enclosing folder). Commit the upload.
3. Go to **Settings → Pages → Build and deployment**. Select **Deploy from a branch**, branch **main**, folder **/(root)**, then **Save**.
4. Wait for GitHub to display the published site URL. Open it in Safari on your iPad. For a Home Screen app, use Safari's Share → Add to Home Screen.

If the branch dropdown is empty, check that the files have been **committed** on the Code tab. `index.html` must be at the top level, with lowercase spelling.

## Gameplay

- **Practice:** Select times tables, answer cells, and celebrate completed rows.
- **Lava Survival:** Lava advances at a configurable interval. Deselected table rows are empty passages, not obstacles. Correct answers become temporary stone barriers; finishing a row reinforces its barriers. Lava eventually burns through, and flows sideways. Protect five jewels.
- **Knight Battle:** Three individually selectable knights start at the bottom. Select a knight, then a square within five rows and five columns (diagonals allowed). Answer that cell's multiplication question to move; landing on an enemy defeats it with a cartoon gag. Twelve soldiers descend one row per adjustable timed surge. Defeat all twelve before any reaches the bottom row. All twelve tables are enabled in this mode so enemies can always be attacked.

## Notes

- The game is static HTML, CSS, JavaScript and locally bundled SVG artwork. No external services or assets are required.
- The first visit requires internet access; subsequent visits can work offline using the service worker.
- If a previously installed Home Screen app shows an old version, reopen the website in Safari while online and refresh it, then relaunch the app.
- To change the cached release in future, increment the `CACHE` string in `sw.js`.
