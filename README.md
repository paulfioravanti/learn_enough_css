# Learn Enough CSS & Layout to Be Dangerous

This is a sample repo I did for the
[Learn Enough CSS & Layout to Be Dangerous][learn-enough-css] tutorial.

## Changes from Tutorial

- Changed the CSS code to be SCSS and configured Jekyll to serve those files
  out of the `_scss` directory via the `_config.yml` file.
- Use [`scss-lint`][scss-lint] to bring the CSS up to community standards.
- Minor Jekyll syntax changes to use `include` variable in `post_excerpt.html`
  so that re-use of that partial is easier between the pages that use it.
- Registered for an account on [Font Awesome][font-awesome] and got
  [a CSS embed code][font-awesome-get-started], referenced it in the
  `<head>` (simliar to the way the Google fonts are referenced), and got rid
  of the `fonts` folder to lighten up the app a little.
- Rather than Github pages, deploy the blog to Heroku
  [here][project-deploy-url]. Deploy it for yourself with the button below.

[![Deploy][heroku-deploy-badge]][heroku-deploy-url]

## Social

[![Contact][twitter-badge]][twitter-url]<br />
[![Stack Overflow][stackoverflow-badge]][stackoverflow-url]

[font-awesome]: http://fontawesome.io/
[font-awesome-get-started]: http://fontawesome.io/get-started/
[heroku-deploy-badge]: https://www.herokucdn.com/deploy/button.svg
[heroku-deploy-url]: https://heroku.com/deploy
[learn-enough-css]: https://www.learnenough.com/css-and-layout-tutorial
[project-deploy-url]: http://learn-enough-css.herokuapp.com/
[scss-lint]: https://github.com/brigade/scss-lint
[stackoverflow-badge]: http://stackoverflow.com/users/flair/567863.png
[stackoverflow-url]: http://stackoverflow.com/users/567863/paul-fioravanti
[twitter-badge]: https://img.shields.io/badge/contact-%40paulfioravanti-blue.svg
[twitter-url]: https://twitter.com/paulfioravanti
