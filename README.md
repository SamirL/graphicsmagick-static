# graphicsmagic-static

Grpahicsmagick static binaries for Windows, Mac OSX and Linux not implemented yet

Thanks to @eugeneware, this package is based on the ffmpeg-static package.

## Installation

This module is installed via npm:

``` bash
$ npm install graphicsmagick-static
```

## Example Usage

Returns the path of a statically linked graphicsmagick on the local filesystem.

``` js
var graphicsmagick = require('grpahicsmagick-static');
console.log(graphicsmagick.path);

```

Currently supports Windows (32 and 64-bit).

Pull Requests are welcome !
