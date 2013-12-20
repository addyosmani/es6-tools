<img src="http://i.imgur.com/yy1sACZ.png" width="100px"/>

## Transpilers

* Google's [Traceur compiler](https://github.com/google/traceur-compiler) - large number of ES6 features > ES5/3
* Square [es6-module-transpiler](https://github.com/square/es6-module-transpiler) - ES6 modules to AMD or CJS
* [es6ify](https://github.com/thlorenz/es6ify) - browserify transform for ES6 > ES5
* [es6-transpiler](https://github.com/termi/es6-transpiler)
* Facebook's [regenerator](https://github.com/facebook/regenerator) - transform ES6 yield/generator functions to ES5
* [defs](https://github.com/olov/defs) - ES6 block scoped const and let variables to ES3 vars
* [es6_module_transpiler-rails](https://github.com/dockyard/es6_module_transpiler-rails) - ES6 Modules in the Rails Asset Pipeline

## Grunt tasks for build-time transpilation

* Tasks for Traceur: [grunt-traceur](https://github.com/aaronfrost/grunt-traceur) ES6 > ES6 transpilation, [grunt-traceur-build](https://github.com/tarruda/grunt-traceur-build)
* Task for Square's transpiler: [grunt-es6-module-transpiler](https://github.com/joefiorini/grunt-es6-module-transpiler)
* [grunt-regenerator](https://github.com/sindresorhus/grunt-regenerator) - ES6 generator functions to ES5
* [grunt-microlib](https://github.com/thomasboyt/grunt-microlib) - tools for libs using ES6 module transpiler (sample [Gruntfile](https://github.com/jakearchibald/ES6-Promises/blob/c3336087fffc52e66cf5398e5b56b23a291080fc/Gruntfile.js))
* [grunt-defs](https://github.com/EE/grunt-defs) - ES6 block scoped const and let variables, to ES3


## Module Loaders

* ES6 [Module Loader polyfill](https://github.com/ModuleLoader/es6-module-loader) (compat with latest spec and Traceur)
* [js-loaders](https://github.com/jorendorff/js-loaders) - Mozilla's spec-compliant loader prototype
* [JSPM](http://jspm.io/) - ES6, AMD, CJS module loading/package management
* Module Loader for [webpack](https://github.com/shama/es6-module-loader)
* [beck.js](https://github.com/unscriptable/beck) - toolkit for ES6 Module Loader pipelines, shim for legacy environments

## Editors

* ES6 syntax highlighting for [Sublime Text and TextMate](https://github.com/Benvie/JavaScriptNext.tmLanguage)
* DocPad [plugin](https://github.com/pflannery/docpad-plugin-traceur) for Traceur

## Code generation

* [generator-traceur](https://github.com/mikach/generator-traceur) - Yeoman generator for Traceur apps
* [grunt-init-es6](https://npmjs.org/package/grunt-init-es6) 
* [Loom generators with ES6 ember modules](https://github.com/rpflorence/loom-generators-ember)
* Brunch [plugin](https://npmjs.org/package/es6-module-transpiler-brunch) for ES6 module transpilation

## Other
* [looper](https://github.com/wycats/looper) - static analysis tools for ES6
* [es6-module-packager](https://npmjs.org/package/es6-module-packager)
