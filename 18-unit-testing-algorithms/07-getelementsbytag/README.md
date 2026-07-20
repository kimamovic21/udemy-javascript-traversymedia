# 07 - Get Elements By Tag

This lesson adds a DOM-focused recursive algorithm and configures Jest to run with a browser-like `jsdom` environment.

## Files

- `algo-testing/package.json` defines the Jest test script and includes `jest-environment-jsdom`.
- `algo-testing/jest.config.js` sets the test environment to `jsdom`.
- `algo-testing/getelementsbytag/getelementsbytag.js` exports the recursive `getElementsByTag()` function.
- `algo-testing/getelementsbytag/getelementsbytag.test.js` creates DOM elements and tests the search behavior.
- The other algorithm folders keep the earlier examples in the same project.

## What This Covers

- Configuring Jest with `testEnvironment: 'jsdom'`.
- Creating DOM elements inside tests.
- Returning an empty array when no root is provided.
- Returning the root when no tag name is provided.
- Recursively walking child elements.
- Matching tag names case-insensitively.
- Testing DOM traversal output.

## Things To Notice

The algorithm uses recursion to search through each child element and concatenate matching results.
