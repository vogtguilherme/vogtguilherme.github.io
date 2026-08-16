## vogtguilherme.github.io

Personal portfolio site, built with [Jekyll](https://jekyllrb.com/) and hosted on [GitHub Pages](https://pages.github.com/). Layout and styling are custom (no pre-built theme).

### Local development

Requires Ruby and Bundler. Gems install into `vendor/bundle` so no `sudo` is needed:

```bash
bundle install                # first time, or after Gemfile changes
bundle exec jekyll serve      # preview at http://localhost:4000, live reload
```

To do a one-off build without starting a server:

```bash
bundle exec jekyll build      # outputs to _site/
```

### Deployment

Pushes to `master` are built and deployed automatically by the GitHub Actions workflow at `.github/workflows/pages.yml`.
