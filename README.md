# Tailwind CSS: Unexpected Vertical Stacking of Flex Items

This repository demonstrates a common yet subtle bug in Tailwind CSS involving the unexpected vertical stacking of flex items when the parent container is missing the necessary `flex` class.

## Bug Description
The code uses Tailwind CSS classes to style two divs to be displayed side-by-side. However, due to a missing parent `flex` class, the divs instead stack vertically.

## How to Reproduce
1. Clone this repository.
2. Open `bug.html` in your browser.
3. Observe the unexpected vertical stacking of the divs.

## Solution
The solution involves adding the `flex` class to the parent container, which enables flexbox layout and allows the child divs to arrange horizontally.

Check the `bugSolution.html` file for the corrected code.