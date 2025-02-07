# JavaScript Null/Undefined Handling in Arithmetic Operations

This repository demonstrates a common error in JavaScript when performing arithmetic operations with variables that might be null or undefined.  The example shows how failing to handle these cases explicitly can lead to unexpected `TypeError` exceptions.

## The Problem

In JavaScript, attempting to add null or undefined to a number directly results in a `TypeError`.  The `bar` function exemplifies this issue. 

## The Solution

The `foo` function provides a solution by explicitly checking for null or undefined values before attempting any arithmetic operations.  This approach handles potential errors gracefully by returning 0 in these cases.

## How to run the code
1. Clone this repository.
2. Open `bug.js` and `bugSolution.js` in your favorite code editor.
3. Open your browser's console and run `node bug.js` and `node bugSolution.js`