# 09 - Babel Loader

This lesson adds Babel to the Webpack setup so modern JavaScript can be transpiled for broader browser support.

## Files

- `webpack-starter/package.json` adds Babel dependencies.
- `webpack-starter/webpack.config.js` adds a JavaScript loader rule.
- `webpack-starter/src/index.html` is the HTML template.
- `webpack-starter/src/index.js` imports CSS and the message module.
- `webpack-starter/src/message.js` exports the message object.
- `webpack-starter/src/css/style.css` contains sample styles.

## What This Covers

- Installing Babel core and preset packages.
- Configuring `babel-loader`.
- Excluding `node_modules` from Babel processing.
- Using `@babel/preset-env`.
- Keeping Babel inside the Webpack pipeline.

## Things To Notice

Babel transforms source JavaScript during the Webpack build, which helps support browsers that do not understand newer syntax.
