# babel-preset-es2015-webpack2

> Babel preset for all es2015 plugins except es2015-modules-commonjs (because webpack2 supports it already!).

## Install

```sh
$ npm install --save-dev babel-preset-es2015-webpack2
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["es2015-webpack2"]
}
```

### Via CLI

```sh
$ babel script.js --presets es2015-webpack2
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["es2015-webpack2"]
});
```
