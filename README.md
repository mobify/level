# Level

Level is a mobile-specific version of [normalize.css](https://github.com/necolas/normalize.css) written in Sass for projects using Mobify’s AdaptiveJS. It makes WebKit-based browsers render all elements more consistently and in line with modern standards.

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
* Explains what code does using detailed comments.

## Browser support

* Chrome (latest)
* Mozilla Firefox (latest)
* Apple Safari 6+

IE Mobile is not currently supported, but can be manually added by pulling from [Normalize.css](https://github.com/necolas/normalize.css/blob/master/normalize.css). PRs to add support behind a configurable Sass variable are welcome.

## Acknowledgements

Normalize.css is a project by [Nicolas Gallagher](https://github.com/necolas),
co-created with [Jonathan Neal](https://github.com/jonathantneal).
