# Tailwind CSS Unexpected Color Rendering Bug

This repository demonstrates a bug where Tailwind CSS unexpectedly renders colors incorrectly due to a conflict in class order or CSS rules.  The expected behavior is for the first div to be red and the second div to be blue. Instead, both divs render with the same, unexpected color.

## Bug Reproduction

1. Clone this repository.
2. Open `bug.html` in your browser.

## Solution

The solution is provided in `solution.html`. This often involves carefully reviewing the order of your Tailwind directives or identifying and removing conflicting CSS rules.