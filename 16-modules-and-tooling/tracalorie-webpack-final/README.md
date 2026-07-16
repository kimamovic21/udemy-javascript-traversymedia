# Tracalorie Webpack Final

This is the final Webpack version of the Tracalorie app. It tracks calories, meals, and workouts with modular JavaScript, Bootstrap, Font Awesome, local storage, and a Webpack build pipeline.

## Files

- `package.json` defines build and dev scripts, dependencies, and dev dependencies.
- `webpack.config.js` configures Webpack, Babel, CSS extraction, HTML generation, and the dev server.
- `src/app.js` initializes the app and wires DOM events.
- `src/Tracker.js` contains the calorie tracking and rendering logic.
- `src/Storage.js` contains local storage helpers.
- `src/Item.js` exports the meal and workout item classes.
- `src/index.html` is the HTML template used by Webpack.
- `src/css/` contains Bootstrap and custom styles.
- `src/webfonts/` contains Font Awesome font assets.

## Usage

Install dependencies:

```bash
npm install
```

Run the dev server:

```bash
npm run dev
```

Build production files:

```bash
npm run build
```

## Things To Notice

This final version extracts CSS into a separate file and keeps the application split into focused modules, which makes it closer to a real-world frontend build setup.
