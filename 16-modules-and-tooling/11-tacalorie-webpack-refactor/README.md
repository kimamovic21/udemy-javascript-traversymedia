# 11 - Tracalorie Webpack Refactor

This lesson refactors the Tracalorie app into a Webpack project with separate modules for app logic, items, storage, and tracking.

## Files

- `tracalorie-webpack/package.json` defines dependencies, scripts, and Webpack tooling.
- `tracalorie-webpack/webpack.config.js` configures the app entry, loaders, dev server, and HTML template.
- `tracalorie-webpack/src/app.js` wires the app together and imports dependencies.
- `tracalorie-webpack/src/Tracker.js` contains calorie tracking and rendering logic.
- `tracalorie-webpack/src/Storage.js` contains local storage helpers.
- `tracalorie-webpack/src/Item.js` exports the meal and workout item classes.
- `tracalorie-webpack/src/index.html` is the app template.
- `tracalorie-webpack/src/css/` and `tracalorie-webpack/src/webfonts/` contain Bootstrap, custom styles, and icon assets.

## What This Covers

- Refactoring a larger app into modules.
- Importing Bootstrap and Font Awesome from packages.
- Importing app CSS from JavaScript.
- Using Webpack with Babel and CSS loaders.
- Using Webpack Dev Server for the app.
- Keeping model, storage, tracker, and app controller code separate.

## Things To Notice

This folder shows the transition from a single-file Tracalorie app into a modular source structure that Webpack can bundle.
