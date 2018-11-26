# Techreview

## Getting started
Developing the site requires having Ruby, Bundler, and the Jekyll gem installed. 

Once that is set up, in the root directory run `bundle exec jekyll serve`. Alternatively, execute the equivalent command by running `./script/server`. To enable livereload support, append `--livereload` to the bundle exec command.

This will compile your site for local viewing. To view, navigate to `localhost:4000` in a browser.

## Making Changes

To change the design of the site, you'll mostly be editing templates in `_layouts/` and changing SCSS files in `_sass`. At the end of the day, Jekyll will serve your styles by compiling `assets/main.scss` into `assets/main.css`, but most of the individual SCSS files reside in `_sass`.