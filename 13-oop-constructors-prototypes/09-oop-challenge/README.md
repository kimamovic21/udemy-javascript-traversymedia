# 09 - OOP Challenge

This challenge practices constructor functions and prototype methods by creating a small player experience system.

## Files

- `index.html` loads the challenge page and includes `script.js`.
- `script.js` contains the player constructor solution.
- `oop-game-challenge.md` contains the challenge instructions and example solution.

## What This Covers

- Creating a `Player` constructor.
- Setting default level and points values.
- Adding `gainXp()` to the prototype.
- Increasing points from gained experience.
- Leveling up when points reach 10 or more.
- Carrying extra points after leveling.
- Adding a `describe()` prototype method.
- Testing multiple player instances.

## Things To Notice

The level-up logic subtracts 10 points after increasing the level, so extra experience carries forward instead of being lost.
