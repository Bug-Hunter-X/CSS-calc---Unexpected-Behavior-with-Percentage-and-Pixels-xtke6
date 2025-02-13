# CSS calc() Unexpected Behavior with Percentage and Pixels

This repository demonstrates an uncommon issue with the CSS `calc()` function when combining percentage and pixel values.  The expected behavior may not be consistent across all browsers or situations.

The `bug.css` file shows the erroneous code, while `bugSolution.css` provides a potential workaround.

## Problem

The `calc()` function in CSS is powerful, but it can produce unexpected results if not handled carefully. This example showcases unexpected width calculations when using percentage and pixel values together.

## Solution

The solution file offers alternate approaches. For example, using viewport units (`vw`) or explicitly setting container widths could be more reliable than relying solely on `calc()` with percentages.