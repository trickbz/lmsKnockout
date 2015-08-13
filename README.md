# lmsKnockout

## Installation

TODO

## Requirements from Kostik

1. Create an HTML page.
2. That page must be using Knockout JS for model management.
3. Add several data-controls to the page, two-way bind them to Knockout JS (JQuery UI controls: date picker, drop-down, combo-box with autocomplete, text box, number editor, tag editor like in Salary Review in LMS).
4. Add a Slick Grid to the page, two way bind it to the model.
5. In the grid VIEW mode there must be columns of such types: buttons (edit + delete), checkbox (or check that the grid supports selection), hyperlink.
6. In the grid, clicking Edit in a row must lead to activating row edit mode (Save + Cancel buttons appear instead of Edit/Delete). Cells in the row must get data-controls activated, but the values from these controls must get to the KnockoutJS model just after user clicks the Save button and the data was successfully validated and saved on the server-side.
7. Enable maximum features in the Slick Grid control (client-side grouping, sorting, filtering).
8. Make sure we have full programmatic control over the current Slick Grid settings.