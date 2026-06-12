# 08 - JSON Intro

This lesson introduces JSON as a data format and shows how JavaScript objects and arrays can be converted to and from JSON strings.

## Files

- `index.html` loads the lesson page and includes `script.js`.
- `script.js` contains JSON stringify and parse examples.
- `todo.json` is a small sample JSON file with a todo item.

## What This Covers

- Creating a normal JavaScript object.
- Converting an object to a JSON string with `JSON.stringify()`.
- Understanding that a JSON string does not expose object properties directly.
- Converting a JSON string back to an object with `JSON.parse()`.
- Converting an array of objects into a JSON string.
- Seeing what JSON data looks like in a `.json` file.

## Things To Notice

After `JSON.stringify(post)`, `str` is a string, so `str.id` does not work like `post.id`. After `JSON.parse(str)`, the result is an object again.
