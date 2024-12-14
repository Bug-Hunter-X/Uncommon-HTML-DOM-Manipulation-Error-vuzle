# Uncommon HTML DOM Manipulation Error

This repository demonstrates an uncommon error in HTML where you try to interact with a DOM element before the browser has fully parsed and rendered the HTML.  This often results in the script failing silently or producing unexpected results. The solution shows how to correctly handle this using DOMContentLoaded.

**Bug:** The script attempts to modify the style of the `#myDiv` element before the browser has completed parsing the HTML, resulting in the element not being found.