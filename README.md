# PIXEL PERFECT

A pixel-art online photobooth. Static site, no build step, no dependencies.

## Features
- Live pixelated camera preview (front/back camera, mirror toggle)
- 6 layouts: Strip x4, Strip x3, Grid 2x2, Duo, Polaroid, Single
- 12 filters (Game Boy, Mono, Sepia, Sunset, Ice, Neon, Arcade, VHS, Poster, Invert, Warm) plus optional dithering
- Adjustable pixel size, countdown timer (3/5/10s or none), flash and sound effects
- Frame colors, custom color, caption, date stamp, stickers
- Download PNG, share (mobile), upload photos instead of using a camera
- Space bar to start

## Deploy
1. Create a GitHub repo and push `index.html` and this README.
2. On vercel.com choose **Add New > Project**, import the repo.
3. Framework preset: **Other**. Leave build command and output directory empty. Deploy.

The camera only works on HTTPS (Vercel provides it) or on `localhost`.
