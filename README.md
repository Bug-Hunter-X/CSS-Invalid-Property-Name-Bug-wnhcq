# CSS Invalid Property Name Bug

This repository demonstrates a subtle bug in CSS that can be difficult to debug. The bug involves using an invalid CSS property name, which causes the style rule to be completely ignored without any error messages.

## Bug Description

The bug occurs when a CSS stylesheet contains a property that is not recognized by the browser.  This often happens due to typos or the use of properties that are not part of the CSS specification.

## How to Reproduce

1. Clone this repository.
2. Open `bug.css` and observe the invalid `invalid-property` declaration.
3. Open `index.html` (or create a simple HTML file) and link to `bug.css`.
4. Observe that the `div` element's style is not affected by the `invalid-property` declaration.

## Solution

The solution is to correct the misspelled or invalid property name to a valid CSS property. See `bugSolution.css` for the corrected code.