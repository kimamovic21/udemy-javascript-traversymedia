# 06 - Anagrams

This lesson adds an anagram checker that compares two strings by counting their characters.

## Files

- `algo-testing/package.json` defines the Jest test script and includes `jest-environment-jsdom`.
- `algo-testing/sum/`, `algo-testing/fizzbuzz/`, `algo-testing/reversestring/`, `algo-testing/palindrome/`, and `algo-testing/arraychunk/` keep earlier examples.
- `algo-testing/anagram/anagram.js` exports the `anagram()` function.
- `algo-testing/anagram/anagram.test.js` tests matching and non-matching anagrams.

## What This Covers

- Building character maps from strings.
- Normalizing strings with `toLowerCase()`.
- Comparing character-map key counts.
- Comparing character frequencies.
- Returning boolean results.
- Testing positive and negative anagram cases.

## Things To Notice

The helper function `buildCharMap()` counts each character, then `anagram()` compares the two maps to decide whether both strings contain the same letters.
