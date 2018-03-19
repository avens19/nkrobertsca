# Nicole Roberts' Personal Website

[![CircleCI](https://circleci.com/gh/avens19/nkrobertsca.svg?style=svg)](https://circleci.com/gh/avens19/nkrobertsca)

This is the website that is available at https://nkroberts.ca.
It is a simple site written on Bootstrap.
Initial template from: https://startbootstrap.com/template-overviews/agency/

## Development

- `npm install`
- `gulp dev`

### Gulp Tasks

- `gulp` the default task that builds everything
- `gulp dev` browserSync opens the project in your default browser and live reloads when changes are made
- `gulp sass` compiles SCSS files into CSS
- `gulp minify-css` minifies the compiled CSS file
- `gulp minify-js` minifies the themes JS file
- `gulp copy` copies dependencies from node_modules to the vendor directory