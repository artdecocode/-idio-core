# @idio/core

[![npm version](https://badge.fury.io/js/@idio/core.svg)](https://npmjs.org/package/@idio/core)

`@idio/core` is a new Node.js npm package. The core idio functionality and middleware, excluding jsx.

```sh
yarn add -E @idio/core
```

## Table Of Contents

- [Table Of Contents](#table-of-contents)
- [API](#api)
  * [`idioCore(arg1: string, arg2?: boolean)`](#mynewpackagearg1-stringarg2-boolean-void)

## API

The package is available by importing its default function:

```js
import idioCore from '@idio/core'
```

### `idioCore(`<br/>&nbsp;&nbsp;`arg1: string,`<br/>&nbsp;&nbsp;`arg2?: boolean,`<br/>`): void`

Call this function to get the result you want.

```js
/* yarn example */
import idioCore from '@idio/core'

(async () => {
  await idioCore()
})()
```

---

(c) [Art Deco Code][1] 2018

[1]: https://artdeco.bz
