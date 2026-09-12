# Studio Cut

In-browser AI background remover for **images, GIFs, and video**.
Nothing is uploaded. Models run locally with ONNX (RMBG-1.4 + optional MODNet).

## Live app

**https://tbenitz.github.io/studio-cut/**

If that 404s for a minute after the first deploy, wait for GitHub Pages, or open:

1. Repo **Settings → Pages**
2. Source: **GitHub Actions** (or Deploy from branch `main` / `/` root)
3. Save

You can also open `index.html` from this repo in any modern Chrome/Edge tab.

## Use

1. Drop a photo, GIF, or video
2. Wait for models (first visit caches ~44MB)
3. Click **Remove background**
4. Fix edges with the eraser / keep brush
5. For video: scrub the filmstrip, hit **Play**, set **Playback FPS**
6. Export PNG, GIF, WebM, or a ZIP of transparent frames

If WebGPU errors, set **Device → WASM / CPU**.
