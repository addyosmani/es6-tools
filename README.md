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

## Code generation

* [generator-traceur](https://github.com/mikach/generator-traceur) - Yeoman generator for Traceur apps
* [grunt-init-es6](https://npmjs.org/package/grunt-init-es6) 
* [Loom generators with ES6 ember modules](https://github.com/rpflorence/loom-generators-ember)
* Brunch [plugin](https://npmjs.org/package/es6-module-transpiler-brunch) for ES6 module transpilation

## Polyfills

* [es6-shim](http://github.com/paulmillr/es6-shim/)
* [String.prototype.startsWith](https://github.com/mathiasbynens/String.prototype.startsWith)
* [String.prototype.endsWith](https://github.com/mathiasbynens/String.prototype.endsWith)
* [String.prototype.at](https://github.com/mathiasbynens/String.prototype.at)
* [es6-promise](https://github.com/jakearchibald/ES6-Promises) - polyfill for Promises matching the ES6 API
* [WeakMap, Map, Set, HashMap - ES6 Collections](https://github.com/Benvie/ES6-Harmony-Collections-Shim)
* [ES6 Map Shim](https://github.com/eriwen/es6-map-shim) - destructive shim that follows the latest specification as closely as possible.
* [ECMAScript 6 polyfill](https://github.com/monolithed/ECMAScript-6) 
* [Function.create](https://github.com/walling/Function.create.js) 
* [String.prototype.contains](https://github.com/robertkowalski/contains.js) 
* [Object.observe() shim](https://github.com/KapIT/observe-shim)
* [ES6 shim](https://github.com/inexorabletash/polyfill/blob/master/harmony.js) 
* [ES6 Map, Set, WeakMap](https://github.com/EliSnow/Blitz-Collections)


## Editors

* ES6 syntax highlighting for [Sublime Text and TextMate](https://github.com/Benvie/JavaScriptNext.tmLanguage)
* DocPad [plugin](https://github.com/pflannery/docpad-plugin-traceur) for Traceur

## Other
* [looper](https://github.com/wycats/looper) - static analysis tools for ES6
* [es6-module-packager](https://npmjs.org/package/es6-module-packager)
