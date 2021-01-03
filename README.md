Personal website and blog, see it at [patrickbuergin.com](https://www.patrickbuergin.com).

## Development

### Initial setup

1. Setup [Ruby](https://www.ruby-lang.org/en/documentation/installation/) and [Bundler](https://bundler.io). Make sure to match the Ruby version listed on [GitHub Pages' dependency versions page](https://pages.github.com/versions/), f.ex. by running `brew install ruby@2.7` instead of `brew install ruby` (macOS).
1. Install project dependencies: `bundle install`
1. Run the page locally: `bundle exec jekyll serve`

### Verify changes

Manual testing steps are documented under [Testing your GitHub Pages site locally with Jekyll](https://docs.github.com/en/free-pro-team@latest/github/working-with-github-pages/testing-your-github-pages-site-locally-with-jekyll).

Missing automated checks: [Issue #1](https://github.com/patrickbuergin/patrickbuergin.github.io/issues/1)

### Update project dependencies

- All: `bundle update --all`
- Just GitHub pages: `bundle update github-pages`
