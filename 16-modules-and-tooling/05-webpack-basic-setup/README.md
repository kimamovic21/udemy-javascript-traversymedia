# 05 - Webpack Basic Setup

This lesson introduces a minimal Webpack setup for bundling JavaScript modules.

## Files

- `webpack-starter/package.json` defines the Webpack build script and development dependencies.
- `webpack-starter/package-lock.json` locks package versions.
- `webpack-starter/webpack.config.js` defines the entry point and output bundle.
- `webpack-starter/src/index.js` imports and logs a message module.
- `webpack-starter/src/message.js` exports the sample message object.
- `webpack-starter/src/css/` is reserved for later styling examples.

## What This Covers

- Installing Webpack and Webpack CLI.
- Defining a Webpack entry file.
- Configuring output path and bundle filename.
- Importing modules into an entry file.
- Building a bundle with `npm run build`.

## Things To Notice

Webpack uses `src/index.js` as the source entry and writes the generated bundle to a `dist` folder.
