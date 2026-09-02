# gscottwalters.github.io

This repository hosts the GitHub Pages site for gscottwalters at https://gscottwalters.org.

What's included:

- A minimal Jekyll site configured to use the Chippy theme (via `remote_theme` in `_config.yml`).
- A CNAME file pointing to `gscottwalters.org`.

Local development

1. Install Ruby and Bundler.
2. Run `bundle install` to install dependencies (the `github-pages` gem is used here).
3. Run `bundle exec jekyll serve` and open `http://localhost:4000`.

Custom domain / DNS

To complete the custom domain setup for the apex domain `gscottwalters.org`, add the following A records to your DNS provider:

- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153

(Optional) To have `www.gscottwalters.org` redirect to the apex, add a CNAME record for `www` pointing to `gscottwalters.github.io`.

After DNS changes propagate, GitHub Pages will provision HTTPS automatically.
