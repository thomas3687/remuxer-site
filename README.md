# Remuxer website

The website for [Remuxer](https://apps.apple.com/app/id1516147963), a lossless video remuxer for iPhone and iPad.

The site is plain static HTML in `html/`. Pushing to `main` deploys it to GitHub Pages through `.github/workflows/pages.yml`.

To preview it locally:

```
python3 -m http.server --directory html
```
