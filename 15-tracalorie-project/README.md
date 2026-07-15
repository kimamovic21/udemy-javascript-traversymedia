# 15 - Tracalorie Project

This project builds a calorie tracking app with vanilla JavaScript, Bootstrap, object-oriented structure, local storage, and a meal/workout dashboard.

## Files

- `index.html` contains the completed Tracalorie app UI.
- `js/app.js` contains the app classes, calorie tracking logic, storage helpers, event handlers, filtering, and reset behavior.
- `css/style.css` contains the custom app styles.
- `css/bootstrap.css` and `js/bootstrap.bundle.min.js` provide Bootstrap styling and UI behavior.
- `css/fontawesome.css` and `webfonts/` provide Font Awesome icons.
- `favicon.ico` is the browser tab icon.
- `project_diagram.png` is a reference diagram for the app structure.
- `theme_only/` contains the static starter theme, including Bootstrap CSS/SCSS, Font Awesome assets, and an empty starter `app.js`.

## What This Covers

- Building an app with multiple JavaScript classes.
- Tracking meals, workouts, consumed calories, burned calories, and remaining calories.
- Setting and saving a daily calorie limit.
- Rendering new meal and workout cards in the DOM.
- Removing meals and workouts.
- Filtering meal and workout lists.
- Persisting app state with `localStorage`.
- Loading saved meals and workouts on page load.
- Resetting totals, items, filters, and stored data.
- Using Bootstrap modals, collapse panels, cards, buttons, and utility classes.

## Things To Notice

`CalorieTracker` owns the app state and display calculations, while `Storage` handles all `localStorage` reads and writes. The `App` class wires DOM events to the tracker methods.

The `theme_only` folder is the starter UI version. The completed app lives at the root of `15-tracalorie-project`.
