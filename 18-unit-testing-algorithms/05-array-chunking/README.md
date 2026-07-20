# 05 - Array Chunking

This lesson adds an array chunking algorithm that splits an array into smaller arrays of a chosen size.

## Files

- `algo-testing/package.json` defines the Jest test script.
- `algo-testing/sum/`, `algo-testing/fizzbuzz/`, `algo-testing/reversestring/`, and `algo-testing/palindrome/` keep earlier examples.
- `algo-testing/arraychunk/arraychunk.js` exports the `chunk()` function.
- `algo-testing/arraychunk/arraychunk.test.js` tests chunked array output.

## What This Covers

- Building a nested array result.
- Iterating through an input array with `for...of`.
- Checking the last chunk before adding a value.
- Starting a new chunk when the current chunk reaches the target size.
- Testing nested arrays.
- Using Node's `assert.deepEqual()` in a Jest test.

## Things To Notice

The final chunk can be shorter than the requested size when the input array does not divide evenly.
