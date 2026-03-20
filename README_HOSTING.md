# VeriShort Download Page Hosting

This folder is ready to host on GitHub Pages.

## Why the APK is not included
GitHub blocks files larger than 100 MB in a repo. Your APK is larger, so it must be hosted as a **GitHub Release asset** (or on S3/R2).

## Steps
1. Create a GitHub repo (example: `Downlad-Verishort-app`).
2. Upload `index.html` and `logo.png` from this folder to the repo.
3. Go to **Settings → Pages** and enable Pages on `main` / root.
4. Create a **Release** and upload `veriShort.apk` as a release asset.
5. The download button already points to:
   `https://github.com/wifiasert/Downlad-Verishort-app/releases/latest/download/veriShort.apk`
   - If your repo name or username is different, update the link in `index.html`.

## What to edit if needed
- Download link: `index.html`
- Logo: replace `logo.png`
