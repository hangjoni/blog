# About

This is a blog deployed on Github pages. Enabled with these two packages:

## Easily create blog with Markdown file

Using @nuxt/content package

## Deploy to Github pages

- using [gh-pages](https://github.com/lucpotage/nuxt-github-pages) package
- add .nojekyll file to the directory to disable jekyll, this gets rid of issue where jekyll prevents file starting with \_ to load . See discussion [here](https://github.com/lucpotage/nuxt-github-pages/issues/5) . Remember to commit this change and re deploy
- Sometimes we also need to delete the branch gh-pages on the remote repo to force github's scripts related to pages to rerun

# Steps:

- clone the repo
- test run locally `npm run dev`
- deploy to Github pages `npm run deploy`
