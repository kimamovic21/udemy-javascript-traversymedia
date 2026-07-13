# 07 - Private Properties Convention

This lesson demonstrates the older underscore naming convention for private-like properties and methods.

## Files

- `index.html` loads the lesson page and includes `script.js`.
- `script.js` contains the wallet example using underscore-prefixed members.

## What This Covers

- Creating a class with internal balance and transaction data.
- Using underscore-prefixed property names as a convention.
- Adding public `deposit()` and `withdraw()` methods.
- Using internal helper methods.
- Preventing withdrawals when funds are too low.
- Exposing read-only access through getters.

## Things To Notice

The underscore prefix communicates "treat this as internal," but it does not actually make the property private. Code outside the class can still access it.
