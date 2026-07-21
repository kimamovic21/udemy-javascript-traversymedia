# 03 - OS Module

This lesson introduces the Node.js `os` module for reading information about the current operating system.

## Files

- `os.js` logs operating-system details.
- `path.js` keeps the path module example from the previous lesson.
- `fs.js` keeps the file-system example from the first lesson.

## What This Covers

- Importing Node's `os` module.
- Reading CPU architecture with `arch()`.
- Detecting the platform with `platform()`.
- Branching based on operating-system type.
- Inspecting CPU details with `cpus()`.
- Reading free and total memory.
- Reading the home directory.
- Reading and formatting system uptime.
- Reading the host name.

## Things To Notice

Memory values are returned in bytes, so the lesson divides by `1024` three times to display gigabytes.
