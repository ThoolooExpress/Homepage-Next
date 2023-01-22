# You probably want [thoolooexpress.com](https://thoolooexpress.com)

This repo's site is published there. While you're here, some notes about how
all this works:

- I build my site locally with Jekyll because Github Pages' version is so badly
  out of date that trying to get my site to render locally with the same
  versions of everything for testing was giving me an aneurism... EVEN WITH
  DOCKER!! If you want to do this yourself:

    1. Add a file called `.nojekyll` that contains anything at all in the root of
       your repo.

    2. In your `_config.yml` set `destination: docs/`.

    3. Switch GH Pages to serve from `docs/`.

    4. Find some way to remember to run `bundle exec jekyll build` before every
       commit / push or you'll be wondering where the hell your new post is
       every time you try and push one.

- I basically never post here.

- For when you inevitably forget the commands:

   1. Install Ruby / Gem on your system, and then install Bundler globally.

   2. Run `bundle install` in the repo root. (The config file `.bundle/config`
      will tell Bundler to install the gems to `.gems`, which is already
      Git-ignored.)
   
   3. Run `bundle exec jekyll serve` to preview the site.

   4. See above to publish.

- When you get in dependency hell and `bundle install` won't work, try deleting
  `Gemfile.lock` and `.gems/...` and running the command again. Bundler will
  regenerate everything for you.
    