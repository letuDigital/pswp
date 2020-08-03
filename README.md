# PhotoSwipe Repository 

[![Build Status](https://travis-ci.org/dimsemenov/PhotoSwipe.svg)](https://travis-ci.org/dimsemenov/PhotoSwipe) 
[![devDependency Status](https://david-dm.org/dimsemenov/PhotoSwipe/dev-status.svg)](https://david-dm.org/dimsemenov/PhotoSwipe#info=devDependencies)
[![Flattr](http://api.flattr.com/button/flattr-badge-large.png)](http://flattr.com/thing/3698358/dimsemenovPhotoSwipe-on-GitHub)

JavaScript image gallery for mobile and desktop. 

- [Documentation and getting started guide](http://photoswipe.com/documentation/getting-started.html).
- [Demo and script home page](http://photoswipe.com).
- [NPM](https://www.npmjs.com/package/photoswipe) `npm install photoswipe`.
- Bower `bower install photoswipe`.
- [Yarn](https://yarnpkg.com/en/package/photoswipe) `yarn add photoswipe`.

### Extras merged into this fork

- [dimsemenov/PhotoSwipe#1642](https://github.com/dimsemenov/PhotoSwipe/pull/1642)  
  suppressing incorrect mousedown in case of firefox android where PointerEvent not enabled by default
- [dimsemenov/PhotoSwipe#1628](https://github.com/dimsemenov/PhotoSwipe/pull/1628)  
  Fix [#1608](https://github.com/dimsemenov/PhotoSwipe/issues/1608): Overlapped Div Gets Clicked When Closing Pswp From UI Toolbar
- [dimsemenov/PhotoSwipe#1633](https://github.com/dimsemenov/PhotoSwipe/pull/1633)  
  Fix the problem which out var is always "InEnd"
- [dimsemenov/PhotoSwipe#1635](https://github.com/dimsemenov/PhotoSwipe/pull/1635)  
  Fix missing type="button" in doc
- [dimsemenov/PhotoSwipe#1638](https://github.com/dimsemenov/PhotoSwipe/pull/1638)  
  Adding `type` attribute to `button` tags to avoid form submitting
- [dimsemenov/PhotoSwipe#1639](https://github.com/dimsemenov/PhotoSwipe/pull/1639)  
  Adding HTML code between <figure> elements (This could close: [#1380](https://github.com/dimsemenov/PhotoSwipe/issues/1380))
- [dimsemenov/PhotoSwipe#1573](https://github.com/dimsemenov/PhotoSwipe/pull/1573)  
  When the image loaded error,it should not set image size
- [dimsemenov/PhotoSwipe#1572](https://github.com/dimsemenov/PhotoSwipe/pull/1572)  
  Fix [#1390](https://github.com/dimsemenov/PhotoSwipe/issues/1390): 'TypeError Cannot read property 'updateScrollOffset' of null'
- [dimsemenov/PhotoSwipe#1611](https://github.com/dimsemenov/PhotoSwipe/pull/1611)  
  deletes double rule and merges selector
- [dimsemenov/PhotoSwipe#1488](https://github.com/dimsemenov/PhotoSwipe/pull/1488)  
  Ensure correct image aspect ratio
- [dimsemenov/PhotoSwipe#1516](https://github.com/dimsemenov/PhotoSwipe/pull/1516)  
  it may be more logic if the class `pswp__caption__center` align the text to center instead of left
- [dimsemenov/PhotoSwipe#1520](https://github.com/dimsemenov/PhotoSwipe/pull/1520)  
  using parseInt() to be sure the _currentItemIndex is interpreted as an integer and the increment and decrements are numbers and not string
- [dimsemenov/PhotoSwipe#1497](https://github.com/dimsemenov/PhotoSwipe/pull/1497)
  Add Yarn install
- [dimsemenov/PhotoSwipe#1489](https://github.com/dimsemenov/PhotoSwipe/pull/1489)  
  Fix example: Added msrc to get the thumbnail to animate
- [dimsemenov/PhotoSwipe#1694](https://github.com/dimsemenov/PhotoSwipe/pull/1694)  
  Init from DOM – click handler defers to Anchor elements
- [dimsemenov/PhotoSwipe#1702](https://github.com/dimsemenov/PhotoSwipe/pull/1702)  
  Automatically detect image width and height after loading
- Partially [dimsemenov/PhotoSwipe#1687](https://github.com/dimsemenov/PhotoSwipe/pull/1687)  
  Change markdown processor to kramdown.
- [dmxforce/PhotoSwipe#2](https://github.com/dmxforce/PhotoSwipe/pull/2)  
  Fixing right click bug and removing minified dist files for now.
- [dimsemenov/PhotoSwipe#1557](https://github.com/dimsemenov/PhotoSwipe/pull/1557)  
  Indefinite article is added for dummy captions
- [dimsemenov/PhotoSwipe#1563](https://github.com/dimsemenov/PhotoSwipe/pull/1563)  
  Fix closing when thumbnail bounds are unknown
- [dimsemenov/PhotoSwipe#1585](https://github.com/dimsemenov/PhotoSwipe/pull/1585)  
  Fix screen zooming on touch devices when share option selected.
- [dimsemenov/PhotoSwipe#1476](https://github.com/dimsemenov/PhotoSwipe/pull/1476)  
  [UI] Added Download Button
- [dimsemenov/PhotoSwipe#1472](https://github.com/dimsemenov/PhotoSwipe/pull/1472)  
  [UI] Tap/click show next image if non zoomable
- [dimsemenov/PhotoSwipe#1309](https://github.com/dimsemenov/PhotoSwipe/pull/1309)  
  Remove html contents more gracefully
- [dimsemenov/PhotoSwipe#1413](https://github.com/dimsemenov/PhotoSwipe/pull/1413)  
  define root in strict mode for browsers
- Partially [dimsemenov/PhotoSwipe#1455](https://github.com/dimsemenov/PhotoSwipe/pull/1455)  
  Various fixes
- delay unbind of scroll listener until close animation finish  
  Fix from [dimsemenov#1492 comment](https://github.com/dimsemenov/PhotoSwipe/issues/1492#issuecomment-447886917), Fixes [dimsemenov#1492](https://github.com/dimsemenov/PhotoSwipe/issues/1492)

## Location of files

- Compiled PhotoSwipe JS and CSS files, SVG and PNG sprites are in the [dist/](https://github.com/dimsemenov/PhotoSwipe/tree/master/dist) folder.
- Source files (.JS and .SCSS) are in the [src/](https://github.com/dimsemenov/PhotoSwipe/tree/master/src) folder.  Note that PhotoSwipe uses Autoprefixer when compiling SASS files.
- Demo website is in the [website/](https://github.com/dimsemenov/PhotoSwipe/tree/master/website) folder.
- Documentation markdown files are in [website/documentation/](https://github.com/dimsemenov/PhotoSwipe/tree/master/website/documentation).

## Plugins / extensions / addons

- [Ruby gem](https://rubygems.org/gems/photoswipe-rails).
- Ember.js addons: [ember-photoswipe](https://github.com/kaermorchen/ember-photoswipe), [ember-cli-photoswipe](https://github.com/poetic/ember-cli-photoswipe).
- [Eager app](https://eager.io/app/DvuKIoU8iTOt).
- [Koken CMS plugin](https://github.com/DanielMuller/koken-plugin-photoswipe).
- [Orchard CMS module](https://gallery.orchardproject.net/List/Modules/Orchard.Module.Cascade.PhotoSwipe).
- [Yellow CMS plugin](https://github.com/datenstrom/yellow-plugins/tree/master/gallery).
- [Kirby CMS plugin](https://github.com/SiteMarina/guggenheim).
- [Drupal CMF module](https://www.drupal.org/project/photoswipe).
- [ProcessWire CMS module](https://github.com/blynx/MarkupProcesswirePhotoswipe).
- [SPIP CMS module](https://plugins.spip.net/photoswipe.html).
- [Fork CMS MediaLibrary widget](https://github.com/forkcms/forkcms).

Coded something useful? <a href='mailto:diiiimaaaa@gmail.com?subject="PhotoSwipe Plugin"'>Email me</a> and I’ll post a link to it here.

## Build 

To compile PhotoSwipe by yourself, make sure that you have [Node.js](http://nodejs.org/), [Grunt.js](https://github.com/cowboy/grunt), [Ruby](http://www.ruby-lang.org/) and [Jekyll](https://github.com/mojombo/jekyll/) installed, then:

1) Clone the repository

	git clone https://github.com/dimsemenov/PhotoSwipe.git

2) Go inside the PhotoSwipe folder that you fetched and install Node dependencies

	cd PhotoSwipe && npm install

3) Run `grunt` to generate the JS and CSS files in the `dist` folder and the site in the `_site/` folder

	grunt

Optionally:

- Run `grunt watch` to automatically rebuild files (JS, CSS, demo website and documentation) when you change files in `src/` or in `website/`.
- Run `grunt nosite` to build just JS and CSS files (output is folder `dist/`).
- Run `grunt pswpbuild` to build just JS files. Param `--pswp-exclude` allows to exclude modules, for example `grunt pswpbuild --pswp-exclude=history` will exclude history module.

## Using PhotoSwipe?

If you’ve used PhotoSwipe in some interesting way, or on the site of a popular brand, I’d be very grateful if you <a href='mailto:diiiimaaaa@gmail.com?subject="Site that uses PhotoSwipe"'>shoot me</a> a link to it.

## License

Script is licensed under MIT license with one exception: Do not create a public WordPress plugin based on it, as I will develop it. If you need to use it for a public WordPress plugin right now, please ask me by email first. Thanks!

Attribution is not required, but much appreciated, especially if you’re making a product for developers.

## About

PhotoSwipe 4.0+ is developed by [Dmitry Semenov](http://twitter.com/dimsemenov). But initially script was created in 2011 by [Code Computerlove](http://www.codecomputerlove.com/), a digital agency in Manchester, they [passed](https://twitter.com/PhotoSwipe/status/444134042787930113) on development in March 2014. You can view [source and documentation](https://github.com/dimsemenov/PhotoSwipe/tree/v3.0.3) of old PhotoSwipe (<4.0) in history of this repo.


