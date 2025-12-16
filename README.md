# LuckyJet static preview (GitHub Pages)

This folder contains a prebuilt static frontend extracted from the original project (`nginx/build`).

## How to publish on GitHub Pages

### Option A (recommended): project pages
1. Create a GitHub repo (e.g. `luckyjet-preview`).
2. Upload **all files from this folder** to the repo root.
3. In GitHub: Settings → Pages → "Build and deployment" → Source: "Deploy from a branch".
4. Select branch `main` and folder `/ (root)`.

### What works / what doesn't
- UI / animations / layout load as static assets.
- Anything that needs the backend API or Socket.IO will not work unless you also run the backend somewhere and update the frontend bundle accordingly.
