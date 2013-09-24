Scroll Table Body jQuery Plugin
===============================

Scroll Table Body is a cross-browser lightweight plugin that allows an html table body to scroll while the header and footer stay fixed.  It works with cells that span multiple columns (colspan), and with fixed width or fluid tables, even when you resize!

Usage
-----

1. Load jQuery
2. Optional: load Underscore.js or Lodash.js if you want to debounce when resizing
3. Load the Scroll Table Body plugin
4. Make sure you have a table with proper markup (`<thead>`, `<tbody>`, and `<tfoot>` if you want it)
5. Call `.scrollTableBody()` on your table element, which by default displays 10 rows of your table and scrolls the rest
6. Optional: pass `rowsToDisplay` as an option.  For example, `$('table').scrollTableBody({rowsToDisplay:5});`