# krishkarar.github.io

1. On GitHub, create a public repo named exactly `krishkarar.github.io`.
2. Put `index.html` and `cv.pdf` at the repo root and push:
   git init && git add . && git commit -m "Personal site" && git branch -M main
   git remote add origin https://github.com/krishkarar/krishkarar.github.io.git && git push -u origin main
3. Repo Settings -> Pages -> Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
4. Live at https://krishkarar.github.io in a minute or two.

Before pushing, search index.html for TODO (email, LinkedIn, SeatScore repo link).
To update the CV, replace cv.pdf and push.

## Talks and posters
- Talk: edit talks/fse26/index.html and paste your Google Drive link where it says DRIVE_LINK (3 places).
  Set Drive sharing to "Anyone with the link -> Viewer". Your CV links to krishkarar.github.io/talks/fse26/,
  so if the Drive link ever changes, update this one file; the CV never needs reprinting.
- Poster: save it as speculate-poster.pdf in the repo root (compress it first if it's over ~20 MB).
