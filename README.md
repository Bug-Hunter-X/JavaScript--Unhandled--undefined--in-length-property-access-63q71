# JavaScript: Unhandled 'undefined' in length property access

This repository demonstrates a common JavaScript error related to accessing the `length` property of an undefined value.

## The Bug

The `foo` function attempts to access the `length` property of its input `x`. While it correctly handles `null` values, it fails to handle the case where `x` is `undefined`, leading to a `TypeError`.

## The Solution

The solution involves adding a check for `undefined` before accessing the `length` property.  This ensures that the function doesn't throw an error when encountering an undefined value.

## How to Run

1. Clone this repository.
2. Open `bug.js` to see the erroneous code.
3. Open `bugSolution.js` to see the corrected code.
4. Run both files in a JavaScript environment (e.g., Node.js) to observe the difference in behavior.