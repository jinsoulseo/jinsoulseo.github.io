# jinsoulseo.github.io

Source for <https://jinsoulseo.github.io>. Plain HTML and CSS, no build step.
GitHub Pages serves the `main` branch as-is.

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole site. One page. |
| `style.css` | All styling. Light and dark themes. |
| `photo.jpg` | Header portrait. Replace the file to change it; the page hides the slot if it is missing. |
| `.nojekyll` | Tells Pages to skip Jekyll processing. |

## The CV is not in this repo

The CV lives in <https://github.com/jinsoulseo/cv>, which is linked to the Overleaf
project `overleaf.com/project/654db14e836ece70d4c17339` through Overleaf's GitHub sync.
That repo compiles its own `main.tex` in GitHub Actions and publishes the result to its
own Pages site, so the current CV is always at <https://jinsoulseo.github.io/cv/>.
This page just links there.

To update the CV: edit in Overleaf, then **Menu > GitHub > Push Overleaf changes**.
The live PDF refreshes about a minute later. Nothing to do in this repo.

The two repos are kept separate so that no access token is needed anywhere: each one
publishes only its own Pages site.

## Editing the site

Edit `index.html`, commit, push. Pages redeploys in under a minute.
