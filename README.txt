CASVA RESEARCH WEBSITE — GITHUB PAGES UPLOAD GUIDE
===================================================
Prepared from four MP4 files and the Word manuscript supplied by the author.

WHAT IS INCLUDED
- index.html: the complete website
- styles.css: colors, typography, mobile layout
- assets/videos/: the four ORIGINAL MP4 files (no external video hosting required)
- assets/posters/: preview stills taken from the videos, and manuscript thumbnail
- assets/paper/: a PDF of the provided manuscript
- .nojekyll: tells GitHub Pages to publish the site directly

HOW TO PUBLISH WITH GITHUB (WEB BROWSER)
1. Open https://github.com/new and create a new PUBLIC repository, for example:
   casva-goupil-research
   (On GitHub Free, Pages requires a public repository.)
2. On your computer, unzip CASVA_Goupil_Research_Website.zip.
3. In the NEW repository, choose "uploading an existing file" or Add file > Upload files.
4. Drag the CONTENTS of the unzipped folder (index.html, styles.css, assets,
   .nojekyll) into the upload screen. IMPORTANT: index.html must be at the
   repository root, NOT inside a second folder.
5. Commit the uploaded files to your main branch. A browser upload supports
   files up to 25 MiB; each included video is below this threshold.
6. Go to repository Settings > Pages. Choose "Deploy from a branch",
   Branch: main, Folder: /(root), then Save.
7. The published address will usually be:
   https://YOUR-GITHUB-USERNAME.github.io/casva-goupil-research/
8. Test the URL in a private/incognito window to verify that all four videos
   play and the paper PDF opens.

IMPORTANT
- The source manuscript has a few bracketed editorial placeholders in the
  notes. The PDF was converted without substantive edits. Review the PDF
  before publishing or treating this as the final application text.
- A public GitHub Pages site and its paper/videos are PUBLIC to anyone with
  the URL (and potentially discoverable). Do not upload confidential material.
- This website is a supplement. Whether CASVA considers a linked website is
  controlled by that fellowship's application instructions.
- No advertising, external fonts, trackers, or third-party video hosting.
- File names use ASCII-only URLs for reliable links across browsers.
- You can replace any MP4 or the PDF later, preserving its path/name.

LOCAL TEST (optional)
Run a local web server inside the unzipped website folder:
  python -m http.server 8000
Then open http://localhost:8000 in a browser.

Website content may be edited directly in index.html.
