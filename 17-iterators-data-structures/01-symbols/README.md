# 01 - Symbols

This lesson introduces JavaScript symbols as unique primitive values that can be used as object property keys.

## Files

- `index.html` loads the lesson script in the browser.
- `script.js` demonstrates symbol creation, symbol descriptions, symbol-keyed object properties, global symbols, and symbol helper methods.

## What This Covers

- Creating symbols with `Symbol()`.
- Reading a symbol description.
- Understanding why two symbols with the same description are still unique.
- Using computed symbol keys on objects.
- Seeing why symbol properties are not included in normal object enumeration.
- Finding symbol properties with `Object.getOwnPropertySymbols()`.
- Creating shared global symbols with `Symbol.for()`.
- Looking up global symbol names with `Symbol.keyFor()`.

## Things To Notice

The symbol-keyed `id` property cannot be overwritten by assigning a normal `id` property. Both properties can exist on the same object because the symbol key is unique.
