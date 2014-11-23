# [mattspangenberg.com](http://mattspangenberg.com/)

The personal portfolio of Matthew Spangenberg. 

## Framework

* The development code is in the
  [`src`](https://github.com/mspangenberg/mattspangenberg.com/tree/master/src)
  directory.
* The build process relies on [Grunt](http://gruntjs.com) (a
  [Node.js](http://nodejs.org) task runner).
* The Grunt configurations can be found in the
  [`Gruntfile.js`](https://github.com/mspangenberg/mattspangenberg.com/blob/master/Gruntfile.js)
  file.
* The boilerplate is based on [HTML5 Boilerplate](http://html5boilerplate.com/) ([GitHub](https://github.com/h5bp/html5-boilerplate)).
* The Site is using [Bootstrap](http://github.com/twbs/bootstrap/) - [v3.2.0](https://github.com/twbs/bootstrap/releases/tag/v3.2.0) for responsive design.

## Setup

1. Install [Node.js and npm](http://nodejs.org/download/).
2. [Install Grunt's command line interface (CLI)
   globally](http://gruntjs.com/getting-started#installing-the-cli):
   `npm install -g grunt-cli`.
3. Run `npm install` in the repository.

## Development

You should be able to work almost entirely in the
[`src`](https://github.com/mspangenberg/mattspangenberg.com/tree/master/src) directory.

While developing run `grunt dev; grunt watch` as this will automatically update it whenever 
changes are made to the page or any of the files contained in the page. You will need to open
the index after it is built from the dist folder directory.


## Build

When you have finished your changes, make sure that the distribution package is
correct by running `grunt test` and then checking the output.