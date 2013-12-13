Light-O
=======

[![Build Status](https://travis-ci.org/robotlolita/light-o.png)](https://travis-ci.org/robotlolita/light-o)
[![Dependencies Status](https://david-dm.org/robotlolita/light-o.png)](https://david-dm.org/robotlolita/light-o.png)
[![NPM version](https://badge.fury.io/js/light-o.png)](http://badge.fury.io/js/light-o)
[![stable](http://hughsk.github.io/stability-badges/dist/stable.svg)](http://github.com/hughsk/stability-badges)


[![browser support](http://ci.testling.com/robotlolita/light-o.png)](http://ci.testling.com/robotlolita/light-o)


Minimally minimal prototypical OO library.


## Example

```js
var Base = require('light-o')

var Thing = Base.clone(function() {
  this.compute = function() {
    return 42;
  }
})

var newThing = Thing.clone()
newThing.compute()
// => 42
```


## Installing

Grab it from NPM:

    $ npm install light-o
    

## Platform support

This library assumes an ES5 environment, but can be easily supported in ES3
platforms by the use of shims. Just include [es5-shim][] :3

[es5-shim]: https://github.com/kriskowal/es5-shim


## Licence

Copyright (c) 2013 Quildreen Motta.

Released under the [MIT licence](https://github.com/robotlolita/light-o/blob/master/LICENCE).


