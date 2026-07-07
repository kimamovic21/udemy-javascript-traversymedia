# 11 - Flixx App Project

This project builds a movie and TV discovery app with vanilla JavaScript and data from version 3 of the TMDB API.

## Files

- `index.html` shows popular movies and the now-playing movie slider.
- `shows.html` shows popular TV shows.
- `movie-details.html` displays detailed information for a selected movie.
- `tv-details.html` displays detailed information for a selected TV show.
- `search.html` displays movie and TV search results with pagination.
- `js/script.js` contains the API requests, rendering functions, search logic, pagination, spinner behavior, and page initialization.
- `css/style.css` contains the main app styles.
- `css/spinner.css` contains the loading spinner styles.
- `images/` contains fallback, screenshot, and background images.
- `lib/` contains the Font Awesome and Swiper library files used by the app.
- `webfonts/` contains the Font Awesome font files.
- `_theme_only/` contains the static HTML/CSS theme version without the completed app JavaScript.

## What This Covers

- Fetching popular movies and TV shows from the TMDB API.
- Displaying movie and TV cards with poster fallbacks.
- Building detail pages from query string ids.
- Rendering backdrop overlays on detail pages.
- Searching movies and shows with URL parameters.
- Displaying paginated search results.
- Creating a now-playing movie slider with Swiper.
- Showing and hiding a loading spinner during API requests.
- Highlighting the active navigation link.
- Showing temporary alert messages.

## Things To Notice

The app stores the TMDB API key in the `global.api.apiKey` value inside `js/script.js`. That is fine for course practice, but a real production app should keep API keys on a server or proxy instead of exposing them in client-side JavaScript.

The `_theme_only` folder is included as a starter theme reference. The main completed app files live at the root of `11-flixx-app-project`.
