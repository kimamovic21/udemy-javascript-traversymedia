# 08 - Prototypical Inheritance Call

This lesson demonstrates constructor inheritance with `call()` and prototype linking.

## Files

- `index.html` loads the lesson page and includes `script.js`.
- `script.js` contains the prototypical inheritance examples.

## What This Covers

- Creating a base `Shape` constructor.
- Adding methods to a base prototype.
- Calling a parent constructor with `Shape.call(this, name)`.
- Creating `Rectangle` and `Circle` constructors.
- Linking child prototypes with `Object.create()`.
- Overriding an inherited method.
- Resetting prototype constructor references.

## Things To Notice

`call()` copies parent constructor setup onto the child instance, while `Object.create()` links the child prototype to the parent prototype methods.
