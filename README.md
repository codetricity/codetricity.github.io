# Oda World

A personal blog built with [Quarto](https://quarto.org/).

## Quick start

```bash
# Preview locally
quarto preview

# Build the site
quarto render
```

The rendered site is output to `_site/`.

## Add a post

```bash
quarto create contents post --title "Post Title" --path posts/my-post
```

## Configuration

- `_quarto.yml` — site title, navigation, and format options
- `_brand.yml` — colors and typography
- `styles.css` — custom CSS overrides

Update `site-url` in `_quarto.yml` before deploying so the RSS feed works correctly.
