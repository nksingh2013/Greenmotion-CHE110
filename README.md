# GreenMotion — CHE110 Group 11

A responsive, single-page sustainable mobility project website inspired by the clear project storytelling of the RE-FIBRE reference. This is an original GreenMotion design, not a copy of the reference site.

## Files
- `index.html` — all styling and JavaScript are embedded, so there are no separate CSS/JS paths to break.
- `assets/project-video.mp4` — Group 11 project video.
- `assets/video-poster.jpg` — video poster image.

## Preview locally
Open `index.html` in a modern browser. For the most reliable video playback, serve the folder through a local web server or publish it online.

## Publish on GitHub Pages
1. Create/open your repository and upload `index.html` and the entire `assets` folder at the repository root.
2. In repository Settings → Pages, choose deploy from the `main` branch and `/ (root)`.
3. Wait for the Pages URL to become available. Keep the assets folder and filename unchanged.

## Publish on Netlify
Extract this ZIP and upload the extracted folder contents (the `index.html` file and `assets` folder together) to Netlify Drop. Do not upload only `index.html`.

## Video troubleshooting
The player loads `./assets/project-video.mp4` using a relative path, which works for root domains and GitHub Pages project paths. If the video does not load, check that the deployed file exists at `assets/project-video.mp4`, that the upload completed, and that the browser/network can download the full MP4. The page also offers a direct video link.

## Academic notes
The calculator's emission factors are illustrative demonstration assumptions, not official averages. Replace them with locally sourced values if used for a formal calculation. Statistics and context have source links on the page. Do not present illustrative calculator outputs as measured project results.
