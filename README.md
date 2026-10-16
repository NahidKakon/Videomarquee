# Standalone Video Marquee

## Files
- `index.html` — standalone HTML/CSS/JavaScript webpage.

## Add your videos
Place these two MP4 files in the same folder as `index.html`:
- `Dignity, choice & person-centred care.mp4`
- `Dignity, choice and person-centred care .mp4`

The second filename includes a space immediately before `.mp4`, matching the path you supplied.

The HTML uses URL-encoded paths for punctuation and spaces. If you rename either video, update the matching `src` in `index.html`.

## Preview
Open `index.html` in a browser. For best results, serve the folder with a local web server rather than opening it directly from disk.

## GitHub Pages
Upload `index.html` and both MP4 files to a repository. Enable GitHub Pages in the repository settings if you want to host it as a static webpage. Large MP4 files may exceed GitHub's ordinary file-size limits; use Git LFS or video hosting/storage for larger files.
