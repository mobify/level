# Level

Level provides a lightweight, consistent foundation for mobile stylesheets. It is a subset of [normalize.css](https://github.com/necolas/normalize.css) with a few additions, such as `box-sizing: border-box` by default.

## Install

* [Bower](http://bower.io/): `bower install --save mobify/level`

## Usage

Assuming bower_components is a [Sass load path](https://github.com/gruntjs/grunt-contrib-sass#loadpath): `@import level/level;`. Adaptive projects are set up this way by default.

No other styles should come before Level in compiled css.

## What does it do?

* Preserves useful defaults, unlike many CSS resets.
* Normalizes styles for a wide range of elements.
* Corrects bugs and common browser inconsistencies.
* Improves usability with subtle improvements.
* Adds some styles that are defacto standards, such as border-box.
* Explains what code does using detailed comments.

## Browser support

* Chrome (latest)
* Mozilla Firefox (latest)
* iOS Safari 6+

IE Mobile is not currently supported, but can be manually added by adding IE10+ styles from [Normalize.css](https://github.com/necolas/normalize.css/blob/master/normalize.css). PRs to add support behind a configurable Sass variable are welcome.

## Acknowledgements

Normalize.css is a project by [Nicolas Gallagher](https://github.com/necolas),
co-created with [Jonathan Neal](https://github.com/jonathantneal).
