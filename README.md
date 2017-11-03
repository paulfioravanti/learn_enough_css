# Learn Enough CSS & Layout to Be Dangerous

This is a sample repo I did for the
[Learn Enough CSS & Layout to Be Dangerous](https://www.learnenough.com/css-and-layout-tutorial)
tutorial.

## Changes from Tutorial

- Changed the CSS code to be SCSS and configured Jekyll to serve those files
  out of the `_scss` directory via the `_config.yml` file.
- Use [`scss-lint`](https://github.com/brigade/scss-lint) to bring the CSS
  up to community standards.
- Minor Jekyll syntax changes to use `include` variable in `post_excerpt.html`
  so that re-use of that partial is easier between the pages that use it.
- Registered for an account on [Font Awesome](http://fontawesome.io/) and got
  [a CSS embed code](http://fontawesome.io/get-started/), referenced it in the
  `<head>` (simliar to the way the Google fonts are referenced), and got rid
  of the `fonts` folder to lighten up the app a little.
- Rather than Github pages, deploy the blog to Heroku
  [here](http://learn-enough-css.herokuapp.com/). Deploy it for yourself with
  the button below.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Social

[![Contact](https://img.shields.io/badge/contact-%40paulfioravanti-blue.svg)](https://twitter.com/paulfioravanti)

<a href="http://stackoverflow.com/users/567863/paul-fioravanti">
  <img src="http://stackoverflow.com/users/flair/567863.png" width="208" height="58" alt="profile for Paul Fioravanti at Stack Overflow, Q&amp;A for professional and enthusiast programmers" title="profile for Paul Fioravanti at Stack Overflow, Q&amp;A for professional and enthusiast programmers">
</a>
