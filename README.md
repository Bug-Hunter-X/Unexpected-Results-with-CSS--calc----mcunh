# Unexpected Results with CSS `calc()`

This repository demonstrates an uncommon bug related to the CSS `calc()` function.  The bug arises from inconsistencies in units used within the calculation or excessive complexity, leading to unpredictable rendering behavior.  The solution demonstrates how to resolve such issues to ensure consistent and expected layout.

## Bug Description

The CSS `calc()` function is a powerful tool but can produce unexpected results if not used carefully.  Mixing units (e.g., percentages and pixels) within a single `calc()` expression can sometimes cause problems. Similarly, highly complex `calc()` expressions might also be improperly interpreted by different browsers.

## Reproduction

The `bug.css` file contains the problematic CSS code. Observe how the layout differs from what might be expected, particularly in different browsers or viewport sizes.

## Solution

The `bugSolution.css` file showcases the corrected code. This involves carefully managing units and simplifying the calculations to ensure consistent and predictable layout across browsers and screen sizes.

## Lesson Learned

This demonstrates the importance of rigorous unit consistency and avoidance of overly complex expressions when utilizing CSS `calc()`.  Simple and well-defined calculations greatly improve the reliability of the outcome.
