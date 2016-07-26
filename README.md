# babel-preset-atomtech

> A babel preset for transforming your JavaScript for AtomTech.

## Install

```
npm install --save-dev babel-preset-atomtech
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["atomtech"]
}
```

### Via CLI

```sh
babel script.js --presets atomtech
```

### Via Node API

```js
require("babel-core").transform("code", {
  presets: ["atomtech"]
});
```
