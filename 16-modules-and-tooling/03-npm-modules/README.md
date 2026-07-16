# 03 - NPM Modules

This lesson introduces npm packages by using Axios and Nodemon in a small Node project.

## Files

- `app.js` imports Axios and requests a JSONPlaceholder post.
- `package.json` defines project metadata, scripts, dependencies, and dev dependencies.
- `package-lock.json` locks installed package versions.
- `.gitignore` excludes generated dependency files.

## What This Covers

- Installing npm dependencies.
- Importing a third-party package with `require()`.
- Making an HTTP request with Axios.
- Reading response data.
- Defining `start` and `dev` scripts.
- Using `nodemon` as a development dependency.

## Things To Notice

`dependencies` are packages the app needs to run, while `devDependencies` are mostly for development tools like Nodemon.
