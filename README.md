# Smart-chair Navigator (GitHub Pages)

A simple static site ready to deploy to **GitHub Pages** as a project site.

## Quick start (no command line)
1. Create a new repo on GitHub – for example: `smartchair`.
2. Upload the files from this folder (`index.html` and `static/`).
3. Go to **Settings → Pages** and set:
   - **Source**: *Deploy from a branch*
   - **Branch**: `main` (or `master`) and **/ (root)**
4. Your site will be live at `https://<username>.github.io/<repo>/`
   - e.g. `https://cooperlad92.github.io/smartchair/`

## Notes
- All asset paths are **relative** (e.g. `./static/...`) so it works under the project subpath.
- Avoid `http://` image links on GitHub Pages (it serves over HTTPS). Use HTTPS or local files.
- Vanta's globe effect needs **THREE.js** loaded first (already included).
- Replace placeholder images (`picsum.photos`) with your own under `static/` if you like.
- Your existing breadcalc site stays untouched in its own repo.
