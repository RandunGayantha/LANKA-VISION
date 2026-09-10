# Lanka Vision Video Maker — Mobile Edition

A static Vercel/Netlify-ready browser video editor.

## Features
- Uses the uploaded **4u-Ganganee** font for text and final rendering.
- Separate top-text and headline size controls.
- Upload a video and preview it inside the template.
- Drag the video with mouse or touch to manually crop/reposition it.
- Crop zoom from 1× to 3×.
- Reset/center crop controls.
- 1080×1080 MP4 export using FFmpeg WebAssembly in the browser.
- Mobile-first responsive UI with a fixed Generate button.
- No server/database required.

## Deploy
Upload the folder to GitHub and import it into Vercel or Netlify. No build command is required; `index.html` is the entry point.

For larger/longer videos, browser rendering can be slow because the rendering happens on the user's device.
