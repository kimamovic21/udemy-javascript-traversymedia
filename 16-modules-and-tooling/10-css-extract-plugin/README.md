# 10 - CSS Extract Plugin

This lesson replaces style injection with extracted CSS output using Mini CSS Extract Plugin.

## Files

- `webpack-starter/package.json` adds `mini-css-extract-plugin`.
- `webpack-starter/webpack.config.js` configures CSS extraction.
- `webpack-starter/src/index.html` is the HTML template.
- `webpack-starter/src/index.js` imports CSS and the message module.
- `webpack-starter/src/message.js` exports the message object.
- `webpack-starter/src/css/style.css` contains sample styles.

## What This Covers

- Installing Mini CSS Extract Plugin.
- Importing the plugin in Webpack config.
- Replacing `style-loader` with `MiniCssExtractPlugin.loader`.
- Extracting CSS into a separate output file.
- Keeping Babel and HTML plugin configuration in place.

## Things To Notice

`style-loader` injects CSS into JavaScript at runtime, while Mini CSS Extract Plugin writes CSS as its own file during the build.
