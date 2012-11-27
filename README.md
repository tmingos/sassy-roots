# Sassy Roots

Roots is my Wordpress base theme of choice, but I've made several changes to reflect my personal workflow and preferences.

## Features
* Bootstrap Less has been converted to Sass
* Bootstrap Glyphicons replaced with [/gregoryloucas/Font-Awesome-More](Font Awesome More)
* Utilizes Compass
* Optimized for use with CSS and JS preprocessors (i.e., CodeKit)

## Documentation
**CSS**
* CSS for screen compiled from /sass/screen.scss and output to /assets/css/screen.css 
* CSS for print compiled from /sass/print.scss and output to /assets/css/print.css
* Roots editor-styles also editable at /sass/editor-styles.scss
**Javascript**
* Two files called:
	1. code(/assets/js/plugins-min.js)
	2. code(/assets/js/main-min.js)
* code(plugins.js) includes Bootstrap scripts, as well as any additional plugins
* code(main.js) 
* Setup your preprocessor to output these files with code(-min.js) appended
* These filenames can be modified at code(lib/scripts.php)

## Installation
* Clone repo - `git clone git://github.com/jaredhughes/sassy-roots.git`
* Reference the [theme activation](/retlehs/roots/blob/master/doc/activation.md) documentation to understand everything that happens once you activate Roots

## Planned
* Add theme options for javascript source file names
* Strip Bootstrap design elements
* Add basic print stylesheet

## [Roots Theme](http://www.rootstheme.com/)

Original project information:

* Source: [https://github.com/retlehs/roots](https://github.com/retlehs/roots)
* Documentation: [/retlehs/roots/blob/master/doc/TOC.md](/retlehs/roots/blob/master/doc/TOC.md)
* Web: [http://www.rootstheme.com/](http://www.rootstheme.com/)
