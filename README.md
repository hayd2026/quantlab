# Quant Lab — iPhone PWA (v1)

An offline-first, static progressive web app with 10 starter lessons, 20 knowledge questions, adaptive review scheduling, curriculum, research notes, progress tracking, and JSON export/import.

## Try locally

From this directory run `python3 -m http.server 8000`, then open `http://localhost:8000` on the same computer. For testing on iPhone, use an HTTPS hosting provider. A plain file:// URL will not install as a PWA or register its offline service worker.

## Publish to iPhone

Upload all files in this folder to a static HTTPS host (GitHub Pages, Cloudflare Pages, or Netlify). Open the resulting HTTPS URL in **Safari** on your iPhone. Tap **Share → Add to Home Screen**. Open once while connected to cache content for offline use.

## Important

- Progress is stored locally in Safari/installed-app storage via localStorage, not synced or backed up automatically. Use Settings → Export backup periodically.
- The built-in adaptive review is simple interval scheduling, not an AI tutor.
- Curriculum contains 10 fully written starter lessons; quarters 3–4 are roadmap placeholders, not complete course content.
- No backend, accounts, paid APIs, or analytics. This is a working prototype, not a deployed public site.
