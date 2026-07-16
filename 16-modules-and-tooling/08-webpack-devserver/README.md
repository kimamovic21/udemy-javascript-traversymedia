# 08 - Webpack DevServer

This lesson adds Webpack Dev Server for local development with automatic serving and reload behavior.

## Files

- `webpack-starter/package.json` adds the `dev` script and dev server dependency.
- `webpack-starter/webpack.config.js` configures `devServer`.
- `webpack-starter/src/index.html` is the HTML template.
- `webpack-starter/src/index.js` imports CSS and the message module.
- `webpack-starter/src/message.js` exports the message object.
- `webpack-starter/src/css/style.css` contains sample styles.

## What This Covers

- Installing `webpack-dev-server`.
- Adding an `npm run dev` script.
- Serving files from the generated `dist` folder.
- Setting the dev server port.
- Opening the browser automatically.
- Enabling hot reloading and compression.
- Supporting history fallback.

## Things To Notice

The dev server is for development only. The production bundle still comes from `npm run build`.
