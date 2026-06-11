# 05 - Stack vs Heap

This lesson explains the difference between copying primitive values and copying references to objects.

## Files

- `index.html` loads the lesson page and includes `script.js`.
- `script.js` compares a copied string with a copied object reference.

## What This Covers

- Primitive values such as strings and numbers are copied by value.
- Objects are copied by reference.
- Reassigning a copied primitive does not change the original value.
- Mutating an object through one reference affects every variable pointing at that same object.

## Things To Notice

`newName` becomes `"Jonathan"` while `name` stays `"John"`. By contrast, changing `newPerson.name` also changes `person.name` because both variables point to the same object.
