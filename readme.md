# mode-grammar-builder

> Build a jison grammar for a mode-grammar-builder mode

This is an internal binary tool used by the bash-parser build toolchain
to compile a json grammar to a javascript file.

You usually don't need to use it directly if you are not developing
Vorpal.


# Usage

```bash
mgb <mode folder path>
```

E.g., to build posix grammar:

```bash
mgb modes/posix
```


[![Travis Build Status](https://img.shields.io/travis/vorpaljs/mode-grammar-builder/master.svg)](http://travis-ci.org/vorpaljs/mode-grammar-builder)
[![NPM module](https://img.shields.io/npm/v/mode-grammar-builder.svg)](https://npmjs.org/package/mode-grammar-builder)
[![NPM downloads](https://img.shields.io/npm/dt/mode-grammar-builder.svg)](https://npmjs.org/package/mode-grammar-builder)


# License

The MIT License (MIT)

Copyright (c) 2017 vorpaljs
