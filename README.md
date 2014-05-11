distillery
==========

A collection of tests and reproduction cases distilled to raw HTML/CSS/JS to demonstrate issues with specific flavors (usually) of WebKit. These tests/cases are independent and stand-alone, and as such are each encapsulated in their own HTML file that can be viewed on a case-by-case basis.

Currently, the tests involve:
- Performance issues related to CSS animations (with a fixed version to demonstrate before and after)
- Daylight savings time (DST) errors with certain timezones (Germany, Austria)
- Truncation of the display of an ellipsis when using text-overflow styling for non-Latin text
- Incorrect measurement of scrolling dimensions for clipped elements
