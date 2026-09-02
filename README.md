# Yun Wei Academic Website

This is a Quarto personal website designed for GitHub Pages.

## Preview locally

Install [Quarto](https://quarto.org/docs/get-started/) and run:

```sh
quarto preview
```

Quarto will render the `.qmd` source files and open a live local preview.

## Publish with GitHub Pages

1. Create a GitHub repository named `<your-github-username>.github.io`.
2. Push the source files, including `.github/workflows/publish.yml`, to the `main` branch.
3. In GitHub, open **Settings > Pages** and choose **GitHub Actions** as the source.

Each push to `main` renders the site and publishes it to the `gh-pages` branch automatically.

Your website will be available at `https://<your-github-username>.github.io`.