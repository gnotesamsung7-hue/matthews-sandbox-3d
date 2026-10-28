# Matthew's Sandbox 3D

A 3D voxel ragdoll sandbox for phones (three.js + cannon.js). The characters are built from the same pixel art as the pixel edition: every pixel becomes a little cube.

- `www/index.html` - the game inside the APK (works offline with the local `three.min.js` and `cannon.min.js`)
- `docs/index.html` - the same game for GitHub Pages
- `.github/workflows/main.yml` - builds the APK on every push to `main`

Download the APK from **Releases > apk-latest**.
To update the game, replace `www/index.html` and `docs/index.html` (in `www/` keep the local `three.min.js` and `cannon.min.js` script tags).
