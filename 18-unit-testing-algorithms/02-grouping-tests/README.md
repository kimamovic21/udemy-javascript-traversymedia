# 02 - Grouping Tests

This lesson expands the Jest setup by organizing related assertions with `describe()` and `it()`.

## Files

- `algo-testing/package.json` defines the Jest test script.
- `algo-testing/sum/` contains the earlier sum function and test.
- `algo-testing/fizzbuzz/fizzbizz.js` contains the FizzBuzz function.
- `algo-testing/fizzbuzz/fizzbuzz.test.js` contains grouped FizzBuzz test cases.

## What This Covers

- Grouping related tests with `describe()`.
- Writing individual specs with `it()`.
- Testing function type.
- Testing normal return values.
- Testing numbers divisible by 3, 5, and both 3 and 5.
- Keeping algorithm code and test files together in feature folders.

## Things To Notice

The implementation file is named `fizzbizz.js`, while the test file is named `fizzbuzz.test.js`. The test imports the existing filename directly.
