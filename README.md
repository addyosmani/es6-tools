<img src="http://i.imgur.com/yy1sACZ.png" width="100px"/>

## Transpilers

* [Traceur compiler](https://github.com/google/traceur-compiler) - ES6 features > ES5/3. Includes classes, generators, promises, destructuring patterns, default parameters & more. 
* [es6ify](https://github.com/thlorenz/es6ify) - Traceur compiler wrapped as a Browserify v2 transform
* [es6-transpiler](https://github.com/termi/es6-transpiler) - ES6 > ES5. Includes classes, destructuring, default parameters, spread
* Square's [es6-module-transpiler](https://github.com/square/es6-module-transpiler) - ES6 modules to AMD or CJS
* Square's [es6-arrow-function](https://github.com/square/es6-arrow-function) - ES6 arrow functions to ES5
* Facebook's [regenerator](https://github.com/facebook/regenerator) - transform ES6 yield/generator functions to ES5
* [defs](https://github.com/olov/defs) - ES6 block-scoped const and let variables to ES3 vars
* [es6_module_transpiler-rails](https://github.com/dockyard/es6_module_transpiler-rails) - ES6 Modules in the Rails Asset Pipeline
* [Some Sweet.js macros](https://github.com/jlongster/es6-macros) that compile from ES6 to ES5

## Build-time transpilation

### Grunt Tasks 
* Traceur: [grunt-traceur](https://github.com/aaronfrost/grunt-traceur) ES6 > ES6 transpilation, [grunt-traceur-build](https://github.com/tarruda/grunt-traceur-build)
* ES6 Module Transpiler: [grunt-es6-module-transpiler](https://github.com/joefiorini/grunt-es6-module-transpiler)
* Regenerator: [grunt-regenerator](https://github.com/sindresorhus/grunt-regenerator) - ES6 generator functions to ES5
* [grunt-microlib](https://github.com/thomasboyt/grunt-microlib) - tools for libs using ES6 module transpiler (sample [Gruntfile](https://github.com/jakearchibald/ES6-Promises/blob/c3336087fffc52e66cf5398e5b56b23a291080fc/Gruntfile.js))
* [grunt-defs](https://github.com/EE/grunt-defs) - ES6 block scoped const and let variables, to ES3
* es6-transpiler: [grunt-es6-transpiler](https://github.com/sindresorhus/grunt-es6-transpiler) - ES6 → ES5

### Gulp Plugins
* Traceur: [gulp-traceur](https://github.com/sindresorhus/gulp-traceur)
* Regenerator: [gulp-regenerator](https://github.com/sindresorhus/gulp-regenerator)
* ES6 Module Transpiler: [gulp-es6-module-transpiler](https://github.com/ryanseddon/gulp-es6-module-transpiler)
* es6-transpiler: [gulp-es6-transpiler](https://github.com/sindresorhus/gulp-es6-transpiler) - ES6 → ES5

## Module Loaders

* ES6 [Module Loader polyfill](https://github.com/ModuleLoader/es6-module-loader) (compat with latest spec and Traceur)
* [js-loaders](https://github.com/jorendorff/js-loaders) - Mozilla's spec-compliant loader prototype
* [JSPM](http://jspm.io/) - ES6, AMD, CJS module loading/package management
* Module Loader for [webpack](https://github.com/shama/es6-module-loader)
* [beck.js](https://github.com/unscriptable/beck) - toolkit for ES6 Module Loader pipelines, shim for legacy environments

## Code generation

* [generator-traceur](https://github.com/mikach/generator-traceur) - Yeoman generator for Traceur apps
* [grunt-init-es6](https://npmjs.org/package/grunt-init-es6) - scaffold node modules with unit tests, authored in ES6
* [Loom generators with ES6 ember modules](https://github.com/rpflorence/loom-generators-ember)
* Brunch [plugin](https://npmjs.org/package/es6-module-transpiler-brunch) for ES6 module transpilation

## Polyfills

* [es6-shim](http://github.com/paulmillr/es6-shim) - almost all new ES6 methods — from Map, Set, String, Array, Object, Object.is and more.
* [WeakMap, Map, Set, HashMap - ES6 Collections](https://github.com/Benvie/ES6-Harmony-Collections-Shim)
* Polymer's [WeakMap shim](https://github.com/Polymer/WeakMap)
* [`String.prototype.startsWith`](https://github.com/mathiasbynens/String.prototype.startsWith)
* [`String.prototype.endsWith`](https://github.com/mathiasbynens/String.prototype.endsWith)
* [`String.prototype.at`](https://github.com/mathiasbynens/String.prototype.at)
* [`String.prototype.repeat`](https://github.com/mathiasbynens/String.prototype.repeat)
* [`String.prototype.contains`](https://github.com/mathiasbynens/String.prototype.contains)
* [`String.prototype.codePointAt`](https://github.com/mathiasbynens/String.prototype.codePointAt)
* [`String.fromCodePoint`](https://github.com/mathiasbynens/String.fromCodePoint)
* [`Array.prototype.find`](https://github.com/paulmillr/Array.prototype.find)
* [`Array.prototype.findIndex`](https://github.com/paulmillr/Array.prototype.findIndex)
* [`Array.from`](https://github.com/mathiasbynens/Array.from)
* [`Array.of`](https://github.com/mathiasbynens/Array.of)
* [`Object.assign`](https://github.com/sindresorhus/object-assign)
* [es6-promise](https://github.com/jakearchibald/ES6-Promises) - polyfill for Promises matching the ES6 API
* [ES6 Map Shim](https://github.com/eriwen/es6-map-shim) - destructive shim that follows the latest specification as closely as possible.
* [ECMAScript 6 polyfill](https://github.com/monolithed/ECMAScript-6) 
* [`Function.create`](https://github.com/walling/Function.create.js) 
* [ES6 shim](https://github.com/inexorabletash/polyfill/blob/master/harmony.js) 
* [ES6 Symbol polyfill](https://github.com/medikoo/es6-symbol)
* [ES6 Map, Set, WeakMap](https://github.com/EliSnow/Blitz-Collections)
* [harmony-reflect](https://github.com/tvcutsem/harmony-reflect) - ES6 [reflection module](http://wiki.ecmascript.org/doku.php?id=harmony:reflect_api) (contains the [Proxy API](http://soft.vub.ac.be/~tvcutsem/proxies/))


## Editors

* ES6 syntax highlighting for [Sublime Text and TextMate](https://github.com/Benvie/JavaScriptNext.tmLanguage)
* DocPad [plugin](https://github.com/pflannery/docpad-plugin-traceur) for Traceur


## Other

* [ES.next showcase](https://github.com/sindresorhus/esnext-showcase) - real-world usage examples of ES6 features
* [looper](https://github.com/wycats/looper) - static analysis tools for ES6
* [es6-module-packager](https://npmjs.org/package/es6-module-packager)
* [es6-import-validate](https://github.com/sproutsocial/es6-import-validate) and [grunt-es6-import-validate](https://github.com/sproutsocial/grunt-es6-import-validate) - validate matching named/default import statements in ES6 modules.
* [let-er](https://github.com/getify/let-er) - transpiles [let-block block-scoping](http://wiki.ecmascript.org/doku.php?id=proposals:block_expressions#let_statement) (not accepted into ES6) into either ES3 or ES6
* [Esprima Harmony branch](https://github.com/ariya/esprima/tree/harmony) - Experimental branch of the Esprima parser which can parse ES6 features.
* [Recast](https://github.com/benjamn/recast) - Esprima-based JavaScript syntax tree transformer, conservative pretty-printer, and automatic source map generator. Used by several of the transpilers listed above, including [regenerator](https://github.com/facebook/regenerator) and [es6-arrow-function](https://github.com/square/es6-arrow-function).