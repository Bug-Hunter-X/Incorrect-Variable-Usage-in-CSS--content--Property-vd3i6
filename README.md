# Incorrect Variable Usage in CSS `content` Property

This repository demonstrates an uncommon error in CSS related to the use of variables within the `content` property of the `::before` and `::after` pseudo-elements.  The primary issue is the incorrect usage of data attributes with `attr()`. The solution showcases the correct method using CSS custom properties.

## Bug

The `bug.css` file contains the erroneous code where a data attribute is incorrectly accessed within the `content` property.  This leads to the pseudo-element not displaying the expected content.

## Solution

The `bugSolution.css` file demonstrates the correct implementation using CSS custom properties. This ensures the variable is properly defined and referenced, resolving the issue.