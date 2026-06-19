# Modern JavaScript From The Beginning 2.0

## Traversy Media

### Course link: [https://www.udemy.com/course/modern-javascript-from-the-beginning]

This repository tracks my practice files while following the Traversy Media Udemy course. The code is organized by course section, and each lesson folder keeps the original `index.html` and `script.js` examples.

## Sections

### 01 - Intro & Getting Started

This opening section introduces the course, explains what JavaScript is, sets up the development tools, and shows the first ways to run JavaScript in the browser.

### 02 - Variables and Data Types

The `01-variables-data-types` folder covers the beginning JavaScript foundations: using the browser console, comments, variables, primitive and reference data types, stack vs heap behavior, type conversion and coercion, operators, strings, numbers, the `Math` object, and the basics of dates and times.

Most examples are meant to be opened in the browser and inspected in the developer console. The challenge folders include small exercises that apply the lessons from the previous topics.

### 03 - Arrays and Objects

The `02-arrays-and-objects` folder builds on the basics by introducing arrays, array methods, nested arrays, concatenation, the spread operator, object literals, object methods, destructuring, property naming, JSON, and small array/object challenges.

Like the first section, these examples are mostly console-based. Open each lesson's `index.html` file in the browser and inspect the output in DevTools.

### 04 - Functions and Scope

The `03-functions-scope` folder introduces JavaScript functions, parameters, arguments, return values, global/function/block scope, nested scope, function declarations vs expressions, arrow functions, IIFEs, execution context, and the call stack.

These lessons are still focused on browser console practice. Some scope examples intentionally demonstrate errors when a variable is accessed outside its scope, so read the comments before uncommenting or running those lines.

### 05 - Logic and Control Flow

The `04-logic-control-flow` folder covers JavaScript decision-making with `if`, `else if`, nested conditionals, `switch` statements, truthy and falsy values, logical operators, logical assignment operators, and ternary expressions.

These examples continue the console-based practice style. The calculator challenge applies control flow by choosing an arithmetic operation from an operator value and returning a result or fallback message.

### 06 - Iteration and Array Methods

The `05-iteration-array-methods` folder introduces loops and array iteration patterns: `for`, `while`, `do...while`, `break`, `continue`, `for...of`, `for...in`, `forEach()`, `filter()`, `map()`, and `reduce()`.

These lessons show both traditional loop syntax and modern array methods. The challenge folders apply the same ideas with FizzBuzz and small data transformation exercises.

### 07 - Document Object Model

The `06-document-object-model` folder introduces browser DOM work: reading the `document` object, selecting elements, traversing elements and nodes, creating and inserting elements, replacing and removing elements, and changing styles and classes from JavaScript.

These lessons move beyond console-only examples into visible page manipulation. Several lessons use the shopping list page as a shared DOM practice app, and the custom `insertAfter()` challenge applies traversal and insertion concepts together.

### 08 - Events

The `07-events` folder covers browser events and user interaction: click handlers, mouse events, the event object, keyboard events, input and form events, event bubbling, event delegation, and window events.

These lessons continue using the shopping list page for hands-on DOM practice, then add a small keycode project and window event examples to show how JavaScript responds to user actions and browser-level changes.
