# on-build-webpack
> Updated for Webpack 4, for lower version, check [old version of this project](https://github.com/kossnocorp/on-build-webpack).

[Webpack](http://webpack.github.io/) plugin that gives ability to add callback
after build.

## Installation

```
npm install --save-dev on-build-webpack2
```

## Usage

In config file:

``` javascript
var WebpackOnBuildPlugin = require('on-build-webpack2');

// ...
  module: {
    plugins: [
      new WebpackOnBuildPlugin(function(stats) {
        // Do whatever you want...
      }),
    ]
  },
// ...
```

