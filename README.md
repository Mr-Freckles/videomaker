# Devotion Video Maker

A single-page, self-contained web app for making Instagram devotional videos:
verse text with word-by-word captions, a narration audio upload, procedurally
generated backgrounds and custom text overlays, your own background music with
a waveform scrubber, and video export.

Everything lives in **`index.html`** — no build step, no dependencies, no server.

## Put it on GitHub Pages

1. Create a new GitHub repo (public, so Pages can serve it for free).
2. Upload `index.html` to the root of the repo.
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to "Deploy from a branch",
   branch `main`, folder `/ (root)`. Save.
5. GitHub will give you a URL like `https://yourusername.github.io/your-repo-name/`
   — that's your app, live, shareable, and free to host.

Changes: just edit `index.html` and push — Pages redeploys automatically
within a minute or two.

## Notes

- Works best in Chrome or Firefox (MediaRecorder/export support varies by browser — Safari can export MP4 natively, other browsers export `.webm`).
- Nothing is uploaded anywhere — audio, images, and video all stay in your own browser.
- "Save as default" (font panel) uses your browser's local storage, so it's per-device/per-browser, not synced.
