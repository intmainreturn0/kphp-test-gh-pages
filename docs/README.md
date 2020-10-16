# My compiler website

This repository is a My compiler website, available at todo.

It is based on Jekyll and works on Github Pages.


## How to launch the site locally

1. Make sure **ruby** and **bundle** are installed
2. Navigate with `cd` to `docs/` folder
3. Install all dependencies in the site folder: `gem install jekyll bundler && bundle install`
4. Launch:
```bash
bundle exec jekyll server --livereload --incremental --config _config.yml
```
5. Wait until "Generating..." stage is done and proceed to *http://127.0.0.1:4000*
