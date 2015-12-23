# babel-preset-es2015-loose-rollup
> Babel ES2015 Loose mode to be used with rollup

This combines [babel-preset-loose](https://github.com/bkonkle/babel-preset-es2015-loose) with [babel-preset-es2015-rollup](https://github.com/rollup/babel-preset-es2015-rollup).

## Install
```sh
$ npm install babel-preset-es2015-loose-rollup --save-dev
```

## Usage

### Via `.babelrc` (Recommended)

**.babelrc**

```json
{
  "presets": ["es2015-loose-rollup"]
}
```

### Via CLI

```sh
$ babel script.js --presets es2015-loose-rollup
```

### Via Node API

```javascript
require('babel-core').transform('code', {
  presets: ['es2015-loose-rollup']
});
```
