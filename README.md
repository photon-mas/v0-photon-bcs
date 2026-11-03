# Photon BCS

Private project. All rights reserved (see LICENSE). This repository holds only the built site, version 1.1.0.

## Deploy (account: photon-mas)
1. Create the repository `photon-mas/photon-bcs` (Pages on a free account needs it public).
2. Upload everything in this folder, including the hidden `.github` folder and `.nojekyll`, to the `main` branch.
3. Settings → Pages → Build and deployment → Source: **GitHub Actions**. The included workflow publishes on every push.
4. The site appears at `https://photon-mas.github.io/photon-bcs/` after the first run (Actions tab).

To update: replace the files with a newer bundle and push. Search engines are asked not to index the site (robots.txt and a noindex tag).
