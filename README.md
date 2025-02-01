# Unhandled Non-Numeric Input in JavaScript Calculator

This repository demonstrates a common error in JavaScript:  failing to handle non-numeric input in a mathematical function. The `operate` function performs basic arithmetic operations (+, -, *, /), but it doesn't gracefully handle cases where `a` or `b` are not numbers.  The solution demonstrates how to robustly check input types.

## Bug

The original `bug.js` file contains the flawed `operate` function.  It throws a `TypeError` when given non-numeric input. This is not user-friendly.

## Solution

The `bugSolution.js` file provides an improved version of the `operate` function that uses `typeof` to check if the inputs `a` and `b` are numbers. If not, it throws a more informative `Error` message.