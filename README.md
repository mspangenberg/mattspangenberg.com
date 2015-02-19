# [mattspangenberg.com](http://mattspangenberg.com/)

The Portfolio of Matthew Spangenberg - UX Designer.

## Framework

* The development code is in the [`src`](https://github.com/mspangenberg/mattspangenberg.com/tree/master/src) directory.
* The build process relies on [Grunt](http://gruntjs.com) (a [Node.js](http://nodejs.org) task runner).
* The Grunt configurations can be found in the [`Gruntfile.js`](https://github.com/mspangenberg/mattspangenberg.com/blob/master/Gruntfile.js) file.
* The boilerplate is based on [HTML5 Boilerplate](http://html5boilerplate.com/) ([GitHub](https://github.com/h5bp/html5-boilerplate)).
* Templating is handled by [Hanndlebars](https://github.com/thierryc/grunt-handlebars-layouts).
* Styles are using [stylus](http://learnboost.github.io/stylus/) with [nib](http://tj.github.io/nib/).
* The Site is using [Bootstrap](http://github.com/twbs/bootstrap/) - [v3.2.0](https://github.com/twbs/bootstrap/releases/tag/v3.2.0) for responsive design.
* The slides are controlled by [fullPage.js](https://github.com/alvarotrigo/fullPage.js).

## Setup

1. Install [Node.js and npm](http://nodejs.org/download/).
2. [Install Grunt's command line interface (CLI) globally](http://gruntjs.com/getting-started#installing-the-cli): `npm install -g grunt-cli`.
3. Run `npm install` in the repository.

## Development

1. Start by compiling the site with: `grunt build`.
2. To start developing run: `grunt dev`. This will launch the site in a new window and refresh the page for every change that is made.
3. You should be able to work almost entirely in the [`src`](https://github.com/mspangenberg/mattspangenberg.com/tree/master/src) directory.


## Deploy

`grunt deploy` will push the 'dist' folder that is created with: `grunt build` to the [gh-pages branch](http://github.com/mspangenberg/mattspangenberg.com/tree/gh-pages).

## Known Bugs

* `grunt dev` does not build the dist folder requiring `grunt build` to run before dev task.
* Live reload is watching the root directory rather than the dist directory that is built.
* New pages must be entered manually to the handlebarslayouts task in the grunt.js file.
* Folders used to compile the dist CSS from the stylus folder should be deleted after build since files are already compiled.