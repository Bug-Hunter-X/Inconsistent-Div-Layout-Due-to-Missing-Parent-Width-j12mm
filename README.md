# Inconsistent Div Layout Due to Missing Parent Width

This repository demonstrates an uncommon CSS bug related to div layout and missing parent container width. The bug is characterized by unexpected vertical stacking of divs that are intended to be side-by-side.

## Bug Description

The `bug.css` file contains CSS that attempts to make two divs occupy 50% of the width each and sit side-by-side. However, the parent container's width is not explicitly set. This leads to inconsistent behavior across different browsers, with some rendering the divs vertically stacked while others might render them correctly.

## Solution

The `bugSolution.css` file demonstrates a solution to this problem by explicitly setting the width of the parent container.  This ensures consistent layout across browsers.