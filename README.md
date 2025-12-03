byt
====

Convert arbitrary unit strings into byte counts.

[![CI](https://github.com/dstokes/byt/actions/workflows/ci.yml/badge.svg)](https://github.com/dstokes/byt/actions/workflows/ci.yml)  
[![NPM](https://nodei.co/npm/byt.png?downloads=true)](https://nodei.co/npm/byt/)  

example
=======
``` js
var b = require('byt');

b(1024);   // => 1024
b('1k');   // => 1024
b('2.5m'); // => 2621440
b('1GB');  // => 1073741824
```

install
=======

With [npm](http://npmjs.org) do:

```
npm install byt
```
