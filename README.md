# Ruang Aneh Shorts Studio

Static browser-based Shorts maker. No backend/API required.

## Run locally
Open `index.html` in a modern browser.

## Deploy to Netlify
1. Create a GitHub repository and upload `index.html` and `netlify.toml`.
2. In Netlify choose **Add new site → Import an existing project**.
3. Connect the repository.
4. Build command: leave blank. Publish directory: `.`.
5. Deploy.

## Current free MVP
- Split script into scene cards.
- Edit each scene caption.
- Upload one image per scene.
- Animate images with slow zoom/pan on a 9:16 canvas.
- Preview and record a WebM video in the browser.

## Limitations
This version does not generate AI images/video or AI voice. It uses images you upload and browser canvas animation. Export is WebM (not MP4); import it into CapCut to add narration/music and export MP4. Browser support for MediaRecorder is required. Keep the tab open while exporting.
