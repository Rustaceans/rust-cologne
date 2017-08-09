# Rust Cologne Meetup Website

## Contribute

Easiest way: Add/change a file via Githubs interface, send a PR.

Each file in `_post` is one meetup event. See the example in `_drafts` to see which fields will be handled (drafts will not be rendered).

### Build it yourself

Get the correct Jekyll version with `gem install github-pages` (requires Ruby 2).

Then, start a server with `jekyll server -w --baseUrl=""`. It rebuilds your site when you change files.

You can enable drafts of posts by adding `--drafts`.

