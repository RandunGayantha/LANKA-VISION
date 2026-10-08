# Lanka Vision PNG Maker

Open `index.html` or deploy the folder to Vercel/Netlify.

Features: embedded 4u-Ganganee font, live canvas preview, text-size controls, transparent center, PNG download, and **video → MP4 export**.

## Video to MP4

1. Choose a video (or drop one on the preview).
2. Drag it in the preview to position it, zoom with the slider or mouse wheel, or use Fill / Fit / Center.
3. Pick frame rate and quality, then press **Export MP4** (1080×1080, H.264 + AAC audio).

Everything runs in the browser with WebCodecs, so nothing is uploaded. It needs a recent Chrome, Edge, Safari or Firefox. The muxer is vendored in `vendor/mp4-muxer.js` ([mp4-muxer](https://github.com/Vanilagy/mp4-muxer) 5.2.2, MIT), so the app still works offline.
