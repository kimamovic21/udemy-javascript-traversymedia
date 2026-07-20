# 04 - Palindrome

This lesson adds a palindrome algorithm that checks whether a string reads the same forward and backward.

## Files

- `algo-testing/package.json` defines the Jest test script.
- `algo-testing/sum/`, `algo-testing/fizzbuzz/`, and `algo-testing/reversestring/` keep the earlier algorithm examples.
- `algo-testing/palindrome/palindrome.js` exports the `palindrome()` function.
- `algo-testing/palindrome/palindrom.test.js` tests palindrome behavior.

## What This Covers

- Comparing characters from the beginning and end of a string.
- Using `split()` and `every()` to test each character.
- Returning boolean values from an algorithm.
- Testing true palindrome cases.
- Testing false non-palindrome cases.
- Testing edge cases such as strings with spaces.

## Things To Notice

The test file is named `palindrom.test.js` in the current course files. The algorithm does not normalize spaces, so a string like ` wow` returns false.
