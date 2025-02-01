# HTML Tables
HTML tables are used to display tabular data in a structured format using rows and columns. The `<table>` element is the main container, and its content is organized using `<tr>` (table row), `<td>` (table data) and `<th>` (table header).

## Basic Table Structure
A simple HTML table consists of:

- `<table>` → Defines the table.
- `<tr>` → Defines a row.
- `<th>` → Defines a header cell (bold and centered by default).
- `<td>` → Defines a standard cell (table data).

🔹 Example:
```
<table border="1">
  <tr>
    <th>Header 1</th>
    <th>Header 2</th>
  </tr>
  <tr>
    <td>Data 1</td>
    <td>Data 2</td>
  </tr>
</table>
```
🔹 Output:
<table border="1">
  <tr>
    <th>Header 1</th>
    <th>Header 2</th>
  </tr>
  <tr>
    <td>Data 1</td>
    <td>Data 2</td>
  </tr>
</table>

## Table Attributes
```
Attribute	                    Description
border	                        Adds a border around table and cells (use CSS instead).
cellpadding	                    Adds space inside cells.
cellspacing	                    Adds space between cells.
width	                        Defines table width (better to use CSS).
```

🔹 Example using attributes:
```
<table border="1" cellpadding="5" cellspacing="5" width="50%">
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>John</td>
    <td>25</td>
  </tr>
</table>
```

## Merging Cells - colspan and rowspan
- colspan: Merges multiple columns.
- rowspan: Merges multiple rows.

🔹 Example:
```
<table border="1">
  <tr>
    <th colspan="2">Merged Column</th>
  </tr>
  <tr>
    <td rowspan="2">Merged Row</td>
    <td>Data</td>
  </tr>
  <tr>
    <td>More Data</td>
  </tr>
</table>
```
🔹 Output:
<table border="1">
  <tr>
    <th colspan="2">Merged Column</th>
  </tr>
  <tr>
    <td rowspan="2">Merged Row</td>
    <td>Data</td>
  </tr>
  <tr>
    <td>More Data</td>
  </tr>
</table>

## Table Head, Body, and Footer
To improve table structure and styling, use:
- <thead> → Table header section.
- <tbody> → Table body section.
- <tfoot> → Table footer section.
🔹 Example:
```
<table border="1">
  <thead>
    <tr>
      <th>Product</th>
      <th>Price</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Phone</td>
      <td>$500</td>
    </tr>
    <tr>
      <td>Laptop</td>
      <td>$1200</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td>Total</td>
      <td>$1700</td>
    </tr>
  </tfoot>
</table>
```

## Styling Tables with CSS
Use CSS to enhance table appearance.

🔹 Example CSS:
```
table {
  width: 100%;
  border-collapse: collapse;
}
th, td {
  border: 1px solid black;
  padding: 10px;
  text-align: left;
}
th {
  background-color: #f2f2f2;
}
```

## Responsive Tables
To make tables scrollable on small screens, use CSS overflow or flexbox/grid-based layouts.

🔹 Example using overflow-x:
```
<div style="overflow-x:auto;">
  <table border="1">
    <tr>
      <th>Name</th>
      <th>Age</th>
      <th>City</th>
      <th>Country</th>
    </tr>
    <tr>
      <td>John</td>
      <td>25</td>
      <td>New York</td>
      <td>USA</td>
    </tr>
  </table>
</div>
```
## Summary
Use `<table>` for tabular data.
Apply `border-collapse:` collapse; for a clean layout.
Use colspan and rowspan to merge cells.
Wrap tables in a `<div>` with `overflow-x: auto;` for responsiveness.
Prefer CSS styling instead of inline attributes.
