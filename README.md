# MaharlikaVerse — The Last Maharlika

Public static webtoon reader designed for GitHub Pages. English original Philippine mythology-inspired fantasy.

## Deployment

Upload **the contents** of this folder into the root of `Gumamay12/maharlika-reader` on its `main` branch. In GitHub navigate **Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save**. When GitHub Pages deploys successfully, the expected site URL is `https://gumamay12.github.io/maharlika-reader/`.

GitHub Pages deployment is not yet enabled or verified by this package. GitHub repositories alone do not publish a site.

## Chapter publishing

The site includes `assets/chapter-001/strip-01.png` to `strip-03.png` (panels 1–30 represented in three long-strip illustrations). Chapter 1 is marked *In Progress*, not finished. Future strips can be placed in the same folder and the `<div id="strips">` in `index.html` can be extended with additional `<img>` tags. Future chapters require their own assets and chapter record. It does **not** automatically capture generated ChatGPT images. That requires a separately authorized uploading workflow.

## Security

This is a public reader, not an authenticated admin dashboard. Do not put API tokens, keys, passwords, or unpublished private material in a public GitHub repository. GitHub Pages serves files publicly.
