# Learn Enough CSS & Layout to Be Dangerous

This is a sample repo I did for the
[Learn Enough CSS & Layout to Be Dangerous](https://www.learnenough.com/css-and-layout-tutorial)
tutorial.

## Changes from Tutorial

- Changed the CSS code to be SCSS and configured Jekyll to serve those files
  out of the `_scss` directory via the `_config.yml` file.
- Minor Jekyll syntax changes to use `include` variable in `post_excerpt.html`
  so that re-use of that partial is easier between the pages that use it.
- Registered for an account on [Font Awesome](http://fontawesome.io/) and got
  [a CSS embed code](http://fontawesome.io/get-started/), referenced it in the
  `<head>` (simliar to the way the Google fonts are referenced), and got rid
  of the `fonts` folder to lighten up the app a little.
