# ES6M Plus Exports

> A standard contract for modules to declare their "exports".

If there's other ways i can walk my own exports (for var i in exports) or indirectly lookup (exports[anExport]) hmu, let me know

https://twitter.com/rektide/status/860522692969193472

Well there's not so here's a way to do it when you write your module: export an "exports" object with your exports.

# Contract

By example:

```
export const myExport1 = 42
export const myOtherExport2 = 6*9

// this fulfills the contract of ES6M-Plus
export exports = {
	myExport1,
	myOtherExport2
}
```
