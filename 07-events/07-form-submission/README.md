# 07 - Form Submission

This lesson demonstrates form submission handling and two ways to read form values.

## Files

- `shopping-list/index.html` contains the shopping list form used for submission practice.
- `shopping-list/script.js` contains the submit event examples.
- `shopping-list/style.css` styles the shopping list page.
- `shopping-list/images/` contains the image assets used by the page.

## What This Covers

- Listening for the form `submit` event.
- Preventing the default page reload with `preventDefault()`.
- Reading input values with `.value`.
- Validating required form fields.
- Using `alert()` for simple validation feedback.
- Reading form data with the `FormData` object.
- Looping through form entries.

## Things To Notice

The active listener uses the `FormData` version. The direct `.value` version is still useful to compare because it makes each selected field explicit.
