# 06 - CSS Style Loaders

This lesson adds CSS support to the Webpack setup with `style-loader` and `css-loader`.

## Files

- `webpack-starter/package.json` adds CSS loader dependencies.
- `webpack-starter/webpack.config.js` defines a CSS loader rule.
- `webpack-starter/src/index.js` imports the CSS file.
- `webpack-starter/src/css/style.css` contains the sample page styles.
- `webpack-starter/src/message.js` exports the sample message object.

## What This Covers

- Importing CSS from JavaScript.
- Configuring Webpack module rules.
- Using `css-loader` to process CSS imports.
- Using `style-loader` to inject styles into the page.
- Keeping CSS alongside source files.

## Things To Notice

Without the CSS loader rule, Webpack does not know what to do when `index.js` imports `./css/style.css`.
