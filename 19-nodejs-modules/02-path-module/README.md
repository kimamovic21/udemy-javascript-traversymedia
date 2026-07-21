# 02 - Path Module

This lesson introduces the Node.js `path` module for working with file and folder paths.

## Files

- `path.js` demonstrates common `path` helpers and Node path globals.
- `fs.js` keeps the file-system example from the previous lesson.

## What This Covers

- Importing Node's `path` module.
- Reading a filename with `basename()`.
- Removing an extension from a basename.
- Reading an extension with `extname()`.
- Reading a directory path with `dirname()`.
- Building paths with `join()`.
- Resolving absolute paths with `resolve()`.
- Inspecting `__dirname` and `__filename`.

## Things To Notice

`path.join()` builds a normalized relative path, while `path.resolve()` returns an absolute path from the current working directory.
