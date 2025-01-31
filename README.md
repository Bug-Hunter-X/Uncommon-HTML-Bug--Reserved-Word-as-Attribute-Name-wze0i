# Uncommon HTML Bug: Reserved Word as Attribute Name

This repository demonstrates an uncommon HTML bug involving the use of a reserved word as an attribute name.  Specifically, the use of `presentation` as an attribute name can cause unexpected behavior in browsers and validation errors.

## Bug Description

The bug occurs when a reserved word or keyword, like 'presentation' which is used in ARIA (Accessible Rich Internet Applications), is employed as a custom attribute name within an HTML element.  This leads to inconsistencies in how browsers parse and render the HTML, potentially rendering the attribute ineffective or causing errors.

## Solution

The solution is simple: avoid using reserved words as attribute names.  Use descriptive, non-reserved words instead.  If you need to use ARIA attributes, ensure you're using them correctly and adhering to ARIA best practices.

## How to Reproduce

1. Open `bug.html` in a web browser.
2. Observe any unexpected behavior or errors reported in the browser's developer console. 
3. Open `solution.html` to see the corrected code.