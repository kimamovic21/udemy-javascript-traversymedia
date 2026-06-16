# 04 - FizzBuzz Challenge

This challenge practices loops and conditionals by printing numbers from 1 to 100 with special output for multiples of 3 and 5.

## Files

- `04-fizzbuzz-challenge.md` contains the challenge instructions and example solutions.
- `index.html` loads the lesson page and includes `script.js`.
- `script.js` contains the FizzBuzz solution.

## What This Covers

- Looping from 1 through 100.
- Using the modulus operator `%` to check divisibility.
- Checking the most specific condition first.
- Printing `Fizz`, `Buzz`, or `FizzBuzz` based on the number.
- Solving the same challenge with either a `for` loop or a `while` loop.

## Things To Notice

The check for multiples of `15` comes before the checks for `3` and `5`. That matters because numbers like `15`, `30`, and `45` should print `FizzBuzz`, not just `Fizz` or `Buzz`.
