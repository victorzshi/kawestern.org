# kawestern.org

Source for the VOO Alumni Board website, built with [Hugo](https://gohugo.io/)
and the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme.
Deployed to GitHub Pages at [kawestern.org](https://kawestern.org).

📧 [alumni@kawestern.org](mailto:alumni@kawestern.org)

## Local development

Requires [Hugo (extended)](https://gohugo.io/installation/) and
[Go](https://go.dev/dl/) (for fetching the theme as a Hugo Module).

```sh
hugo server -D
```

Then open http://localhost:1313.

## Deployment

Pushing to `main` triggers `.github/workflows/hugo.yml`, which builds the
site with Hugo and publishes it to GitHub Pages.
