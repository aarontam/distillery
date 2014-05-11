distillery
==========

A collection of tests and reproduction cases distilled to raw HTML/CSS/JS to demonstrate issues with specific flavors (usually) of WebKit. These tests/cases are independent and stand-alone, and as such are each encapsulated in their own HTML file that can be viewed on a case-by-case basis.

Currently, the tests involve:
* Performance issues related to CSS animations
  * Delay in starting and stopping a CSS animation involving absolutely positioned, subsequent sibling elements (with a fixed version to demonstrate before and after)
  * Delay in starting and stopping a CSS animation involving clipped elements
  * Delay in beginning a transition involving an element containing complex DOM nodes (both by quantity and intricacy)
* Daylight savings time (DST) errors with certain timezones (Germany, Austria)
* Truncation of the display of an ellipsis when using text-overflow styling for non-Latin text
* Incorrect measurement of scrolling dimensions for clipped elements
