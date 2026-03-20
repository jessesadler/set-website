
# set-website

<!-- badges: start -->
<!-- badges: end -->

Instructions for publishing changes to GitHub pages.

1. Make sure to render all changes: `quarto render` or `quarto preview`
2. Add and commit and changes, including those in the `_freeze` folder.
3. Push to origin main: `git push`
4. Publish to GitHub pages: `quarto publish gh-pages`

It uses the workflow described here: https://quarto.org/docs/publishing/github-pages.html#publishing

There is a GitHub Action to make this easier but it does not work with the shiny live right now.
There is a fix, and I can work on updating the workflow so that you do not need to do step 4.
