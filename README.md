# Simple Landing Page

This is my personal website. It was built with Jekyll and the
[bay_jekyll_theme](https://github.com/eliottvincent/bay) theme. The template, however, has been
customised by me. If you delete all contents of the `_layouts` and `assets` directories, the
original layout will be restored.

Here are some useful links for maintaining the website:
- https://jekyllrb.com/docs/configuration/options/
- https://jekyllrb.com/docs/continuous-integration/github-actions/
- https://docs.github.com/en/actions/reference/workflows-and-actions/workflow-syntax

## Running on `localhost`

1. Install Ruby, for example with [rbenv](https://github.com/rbenv/rbenv).  
   Avoid using the system-installed version, as modifying it can destabilise the operating system.  
2. Install Ruby dependencies: `gem install jekyll bundler bay_jekyll_theme`
3. Serve the website: `bundle exec jekyll serve`
