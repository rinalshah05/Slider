# AnythingZoomer jQuery Plugin

Zoom in on images or content.

[![Bower Version][bower-image]][bower-url] [![NPM Version][npm-image]][npm-url] [![devDependency Status][david-dev-image]][david-dev-url] [![MIT][license-image]][license-url]

[npm-url]: https://npmjs.org/package/anythingzoomer
[npm-image]: https://img.shields.io/npm/v/anythingzoomer.svg
[bower-url]: http://bower.io/search/?q=jquery.anythingzoomer
[bower-image]: https://img.shields.io/bower/v/jquery.anythingzoomer.svg
[david-dev-url]: https://david-dm.org/CSS-Tricks/AnythingZoomer?type=dev
[david-dev-image]: https://img.shields.io/david/dev/CSS-Tricks/AnythingZoomer.svg
[license-url]: https://github.com/CSS-Tricks/AnythingZoomer/blob/master/LICENSE
[license-image]: https://img.shields.io/badge/license-MIT-blue.svg

* Latest [AnythingZoomer demo](https://css-tricks.github.io/AnythingZoomer/).
* [Documentation](https://css-tricks.github.io/AnythingZoomer/use.html).
* [JSFiddle playground](http://jsfiddle.net/Mottie/KwvjL/).
* [Original post](https://css-tricks.com/anythingzoomer-jquery-plugin/) at CSS-Tricks.
* Have an issue? Submit it [here](https://github.com/CSS-Tricks/AnythingZoomer/issues).

## Dependencies

* jQuery v1.3.2+

## Download

* Get all files: [zip](https://github.com/CSS-Tricks/AnythingZoomer/archive/master.zip) or [tar.gz](https://github.com/CSS-Tricks/AnythingZoomer/archive/master.tar.gz).
* Use [bower](https://bower.io/search/?q=anythingzoomer): `bower install jquery.anythingzoomer`.
* Use [npm](https://www.npmjs.com/package/anythingzoomer): `npm install anythingzoomer`.

## Known issues

* In the [text demo](https://css-tricks.github.io/AnythingZoomer/text.html), you can resize the large area content dynamically. At 2x, the top left corner of the large content matches the top left corner of the small content. But as the size increases (up to 4x), the spacing of the content from the top left corner increases. This happens with any content. I'm still looking for a fix.

## Recent Changes

View the [complete change log here](change-log.md)

### Version 2.2.7 (11/5/2016)

* Fix misspelling. See [pull #38](https://github.com/CSS-Tricks/AnythingZoomer/pull/38); thanks [@draber](https://github.com/draber)!
* Bower: Fix bower.json.
* Readme:
  * Add links to bower & npm.
  * Add download links.

### Version 2.2.5 & 2.2.6 (8/26/2016)

* Add UMD wrapper.
* Add bower package & fix name.

### Version 2.2.4 (8/26/2016)

* Remove ID from large clone.
* Prevent zoom window showing on re-enable. See [issue #37](https://github.com/CSS-Tricks/AnythingZoomer/issues/37).
* Fix callback function names ('zoom' & 'unzoom' are supported).
* Update all documentation links to use `github.io`.
* Add build process & dist folder.
