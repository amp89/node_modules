# invert-kv [![Build Status](https://travis-ci.org/sindresorhus/invert-kv.svg?branch=master)](https://travis-ci.org/sindresorhus/invert-kv)

> Invert the key/value of an object. Example: `{foo: 'bar'}` → `{bar: 'foo'}`


## Install

```
$ npm install invert-kv
```


## Usage

```js
const invertKv = require('invert-kv');

invertKv({foo: 'bar', unicorn: 'rainbow'});
//=> {bar: 'foo', rainbow: 'unicorn'}
```


## License

MIT © [Sindre Sorhus](https://sindresorhus.com)
