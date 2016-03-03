# babel-preset-es2015-without-regenerator

> Babel preset for all es2015 plugins except transform-regenerator

## Install

```sh
$ npm install --save-dev babel-preset-es2015-without-regenerator
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["es2015-without-regenerator"]
}
```

### Via CLI

```sh
$ babel script.js --presets es2015-without-regenerator
```

### Via Node API

```javascript
require("babel-core").transform("code", {
  presets: ["es2015-without-regenerator"]
});
```
