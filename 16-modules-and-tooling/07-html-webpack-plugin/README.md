# 07 - HTML Webpack Plugin

This lesson adds `html-webpack-plugin` so Webpack can generate an HTML file for the bundled app.

## Files

- `webpack-starter/package.json` adds the HTML Webpack Plugin dependency.
- `webpack-starter/webpack.config.js` configures the plugin.
- `webpack-starter/src/index.html` is the HTML template.
- `webpack-starter/src/index.js` is the app entry file.
- `webpack-starter/src/message.js` exports the sample message object.
- `webpack-starter/src/css/style.css` contains sample styles.

## What This Covers

- Installing and importing `html-webpack-plugin`.
- Creating an HTML template.
- Passing template options into generated HTML.
- Setting generated filename and title.
- Including the bundled script automatically.

## Things To Notice

The template uses `<%= htmlWebpackPlugin.options.title %>` so the title can come from the Webpack plugin configuration.
