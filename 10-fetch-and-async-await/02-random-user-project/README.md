# 02 - Random User Project

This mini project fetches a random user from an API and renders the user's profile details on the page.

## Files

- `index.html` contains the random user page.
- `script.js` contains the fetch request, spinner logic, and rendering code.
- `spinner.css` styles the loading spinner.

## What This Covers

- Fetching data from the Random User API.
- Showing and hiding a loading spinner.
- Reading nested data from an API response.
- Rendering image, name, email, phone, location, and age values.
- Updating page background color based on user gender.
- Running a fetch on page load.
- Fetching a new user from a button click.

## Things To Notice

The API returns a `results` array, so the code reads the first user with `data.results[0]` before passing it to `displayUser()`.
