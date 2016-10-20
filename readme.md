URL string handler
==================

[![Build Status](https://img.shields.io/travis/cjssdk/uri.svg?style=flat-square)](https://travis-ci.org/cjssdk/uri)
[![NPM version](https://img.shields.io/npm/v/cjs-uri.svg?style=flat-square)](https://www.npmjs.com/package/cjs-uri)
[![Dependencies Status](https://img.shields.io/david/cjssdk/uri.svg?style=flat-square)](https://david-dm.org/cjssdk/uri)
[![Gitter](https://img.shields.io/badge/gitter-join%20chat-blue.svg?style=flat-square)](https://gitter.im/DarkPark/cjssdk)
[![RunKit](https://img.shields.io/badge/RunKit-try-yellow.svg?style=flat-square)](https://runkit.com/npm/cjs-uri)


Module to parse location URLs.


## Installation ##

```bash
npm install cjs-uri
```


## Usage ##

Add to the scope:

```js
var parse = require('cjs-uri');
```

Parse current location:

```js
console.log(parse(document.location));
```


## Development mode ##

> There is a global var `DEVELOP` which activates additional consistency checks and protection logic not available in release mode.


## Contribution ##

If you have any problem or suggestion please open an issue [here](https://github.com/cjssdk/uri/issues).
Pull requests are welcomed with respect to the [JavaScript Code Style](https://github.com/DarkPark/jscs).


## License ##

`cjs-uri` is released under the [MIT License](license.md).
