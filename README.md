# Long Tran — Portfolio

Personal portfolio hosted at [https://longtm101898.github.io/](https://longtm101898.github.io/).

## Files

- `index.html`: the portfolio page, including its styles.
- `Long-Tran-CV.pdf`: the downloadable CV linked from the page.
- `.nojekyll`: serves the files directly without Jekyll processing.

## Local preview

Run `python3 -m http.server 8000` from this directory, then open <http://localhost:8000>.

## Deployment

GitHub Pages publishes the root directory (`/`) of the `main` branch.
In repository **Settings → Pages**, the source is **Deploy from a branch**, with **main** and **/(root)** selected.

To update the site, edit the files, commit, and push to `main`:

```sh
git add index.html Long-Tran-CV.pdf
git commit -m "Update portfolio"
git push origin main
```

GitHub automatically deploys changes. Check the repository's **Actions** tab for deployment status.
