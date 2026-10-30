# DIDE GitHub Pages documentation extension

## Contents
- `docs/index.html` — full landing page with GitHub release download, existing Cloudflare Worker tracking, PDF guide, animated walkthrough, support link
- `docs/assets/DIDE_User_Guide.pdf` — printable user documentation
- `docs/assets/DIDE_Animated_Walkthrough.mp4` — 32-second silent animation (illustrative screens, not live capture)
- `docs/assets/tutorial-poster.png` — poster image

## Install on GitHub Pages
1. In the public `sudhirpagare-9/DIDE` repository, upload / replace `docs/index.html`.
2. Add the three files under `docs/assets/` with exactly these names.
3. Commit changes to `main`. Settings > Pages should already publish the `/docs` folder.
4. Visit https://sudhirpagare-9.github.io/DIDE/ and press Ctrl+F5; verify PDF/video links and direct or tracked installer download.

## Notes
This package does not replace the desktop application, change the Cloudflare Worker, publish secrets, or upload anything automatically. The animation is a general feature walkthrough, not an actual video capture of a Windows application. Tesseract configuration varies by installer build. The user guide is based on the DIDE v2.0 source archive and highlights beta limitations.
