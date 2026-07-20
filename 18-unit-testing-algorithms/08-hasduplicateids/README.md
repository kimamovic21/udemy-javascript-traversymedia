# 08 - Has Duplicate IDs

This lesson adds a DOM tree algorithm that detects whether any elements share the same `id`.

## Files

- `algo-testing/package.json` defines the Jest test script and includes `jest-environment-jsdom`.
- `algo-testing/jest.config.js` sets the test environment to `jsdom`.
- `algo-testing/hasduplicateids/hasduplicateids.js` exports the recursive `hasDuplicateIds()` function.
- `algo-testing/hasduplicateids/hasduplicateids.test.js` builds test DOM trees and checks duplicate-id behavior.
- The other algorithm folders keep the earlier examples in the same project.

## What This Covers

- Using a `Set` to track IDs that have already been seen.
- Recursively walking a DOM tree.
- Returning false when no root is provided.
- Detecting duplicate IDs.
- Confirming unique IDs do not count as duplicates.
- Using Jest `beforeEach()` and `afterEach()` hooks.
- Testing DOM behavior with `jsdom`.

## Things To Notice

The same `Set` is passed through recursive calls, so every visited element can be checked against IDs found earlier in the tree.
