# Coc0nut935's Blog

This is my personal blog, built with [Jekyll](https://jekyllrb.com/) and the [Beautiful Jekyll](https://beautifuljekyll.com/) theme. Hosted on [GitHub Pages](https://coc0nut935.github.io/).

## About

A space where I document my journey in computer science -- course notes, algorithms, backend development, AI applications, and personal projects.

## Tech Stack

- **Framework**: Jekyll
- **Theme**: Beautiful Jekyll 6.0.1
- **Hosting**: GitHub Pages
- **Comments**: (configurable via `_config.yml`)

## Blog Structure

```
_posts/          # Blog posts (YYYY-MM-DD-title.md)
_layouts/        # Page layouts
_includes/       # HTML partials
assets/          # CSS, JS, images
_config.yml      # Site configuration
aboutme.md       # About me page
tags.html        # Tag index page
```

## Local Development

```bash
# Install dependencies
bundle install

# Run local server
bundle exec jekyll serve
```

Then visit `http://localhost:4000`.

## Deployment

Push changes to the `master` branch, and GitHub Pages will automatically rebuild the site. Or use the deploy script:

```bash
bash deploy.sh
```

## Contact

- GitHub: [Coc0nut935](https://github.com/Coc0nut935)
- Blog: [coc0nut935.github.io](https://coc0nut935.github.io/)
