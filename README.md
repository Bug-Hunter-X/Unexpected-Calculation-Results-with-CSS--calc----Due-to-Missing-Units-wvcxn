# Unexpected Calculation Results with CSS `calc()`

This repository demonstrates a common, yet easily overlooked, error when using the CSS `calc()` function.  The issue arises from omitting units when subtracting or adding values within the `calc()` expression.

## The Problem
The `calc()` function requires units to be specified for all values.  Omitting units leads to unpredictable results depending on the browser's interpretation.

## Reproducing the Bug
1. Clone this repository.
2. Open `bug.css` to see the incorrect implementation.
3. Open `bugSolution.css` to see the correct implementation.

## Solution
Always ensure that all values within a `calc()` expression have units (e.g., `px`, `%`, `em`, `rem`).