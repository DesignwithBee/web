Bijoya Deb — Product Design Portfolio · GitHub export (separate files)
========================================================================

This is the portfolio as separate files (not one big single file), so every
piece stays well under GitHub's 25 MB web-upload limit.

TOTAL SIZE: 28.4 MB uncompressed (index.html + 64 files in assets/)
LARGEST SINGLE FILE: assets/hub-style-guide.pdf — 3.0 MB
Every individual file is under 25 MB. Nothing was compressed or resized.

WHAT'S IN EACH ZIP
------------------
github-export-1.zip  (11.8 MB)
  - index.html            <- the whole page; goes at the repo root
  - README.txt            <- this file
  - assets/ with 30 files: the resume PDF (bijoya-deb-resume.pdf),
    all BrewBase images + the loading video (brewbase-*),
    and all Chitrok images + the case-study PDF (chitrok-*)

github-export-2.zip  (15.2 MB)
  - assets/ with the remaining 34 files: MyManagement / Hub images and
    PDFs (hub-*), illustrations (illus-*), photography (photo-*),
    pixel art (pixel-*), the deck pages (cool-girl-literature-deck.jpg,
    toronto-flower-market-deck.jpg) and the postcard stamp
    (postcard-stamp-leaves.png)

HOW TO PUT IT ON GITHUB
-----------------------
1. Download BOTH zips and unzip them into the SAME folder on your computer.
   You should end up with one folder containing:
       index.html
       assets/   (with all 64 files inside)
2. In your GitHub repo, use "Add file -> Upload files" and drag in
   index.html together with the whole assets folder. GitHub keeps the
   folder structure, so the page finds its images at assets/...
   (If the web uploader is awkward with folders, upload index.html first,
   then open/create the assets folder in the repo and upload its files —
   each zip is under the 25 MB per-upload limit either way.)
3. Turn on Pages: repo Settings -> Pages -> "Deploy from a branch" ->
   main branch, / (root) folder -> Save.
4. Your site goes live at https://designwithbee.github.io/<repo-name>/
   The contact postcard form still works from there — it sends through
   the form service directly, no server needed.

Notes
-----
- Keep the filenames exactly as they are; index.html refers to them by
  these names with relative paths (assets/...).
- This export matches the current portfolio, including the restored
  postcard contact section and the new 2-page resume.
