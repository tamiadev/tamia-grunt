### 2015-07-15 v0.5.1

* Make pngquant optional.
* Modernizr: match community tests.

### 2015-05-20 v0.5.0

* Uglify: enable screwIE8 option.
* Do not run concat task by default.
* Do not require pngquant if there are no images.
* stylesDestFile option.
* Allow empty string as source or destination directory.
* Update requirements.

### 2015-03-23 v0.4.2

* Do not depend on copy-paste npm module.

### 2015-03-18 v0.4.1

* Fix grunt watch and browserSync: they can work together.
* BrowserSync: options for all subtasks.

### 2015-03-09 v0.4.0

* LiveReload → BrowserSync.
* Images: update, tweak config.

### 2015-01-30 v0.3.3

* Scripts: ability to override auto detection.
* Modernizr: always analyze Tâmia’s JavaScripts.

### 2015-01-28 v0.3.1

* Scripts: check every type of scripts (regular, inlines, bower) separately.
* Images: optimize images in nested folders.
* Doctor: check superfluous npm dependencies.

### 2015-01-20 v0.3.0

* Images: grunt-svgmin not needed anymore; grunt-contrib-imagemin now supports SVG.
* Scripts: JSHint should check all JS files in `js` foler.
* Scripts: uglify inlines (JS files in `js/inlines` folder).
* Modernizr: ability to disable Modernizr.
* Update stylobuild and other deps: Autoprefixer 4.0 and css-clean 3.0.

### 2015-01-17 v0.2.0

* Styles: remove IE8 from Autoprefixer config.
* Modernizr: remove html5shiv, sorry IE8.
* Modernizr: check JS only inside `js` and `tamia` folders to decrease number of unnecessary tests in build.

### 2015-01-12 v0.1.8

* Styles: really fix Tamia custom path.
* Better debug (`grunt --verbose`) output.

### 2015-01-12 v0.1.7

* Styles: fix custom path for Tamia.
* Styles: remove Wordpress detection. Use stylesDest instead.

### 2015-01-10 v0.1.6

* Configurable source and destination for all modules.
* Ability to configure Stylobuild.
* Images: add JPEG to the list of available extensions.

### 2015-01-08 v0.1.5

* Scripts: source maps.

### 2015-01-05 v0.1.4

* Fix banners.

### 2015-01-03 v0.1.3

* Move Modernizr custom build to a separate module. Will run automatically for either styles or scripts tasks.

### 2014-12-26 v0.1.2

* CSSO → CleanCSS.
* Fix images module check (do not require to install image optimizers when there’s no images).

### 2014-12-16 v0.1.1

* Do not stop installation on npm postinstall.

### 2014-12-03 v0.1.0

* New modules: doctor, images.
* Styles: renamed from stylus.
* Styles: CSSO → CleanCSS.
* Styles: WordPress theme support.
* Scripts: run bower_concat only if bower.json exists.
* Scripts: .jshintrc auto search.
* Scripts: add bower_concat to watch.
* Update deps.

### 2014-06-07 v0.0.1

* First release.
