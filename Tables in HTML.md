
Tables are used to display data in rows and columns. They consist of three main components: the table itself, table rows, and table cells (or data).

#### Table

The `<table>` tag defines a table in HTML. It serves as the container for all the table's rows and columns.

```html
<table border="1">
  <!-- Table rows and columns go here -->
</table>
```

#### Table Row

The `<tr>` tag defines a row within a table. It contains one or more table cells.

```html
<table border="1">
  <tr>
    <td>Row 1, Column 1</td>
    <td>Row 1, Column 2</td>
  </tr>
  <tr>
    <td>Row 2, Column 1</td>
    <td>Row 2, Column 2</td>
  </tr>
</table>
```

#### Table Column (Data)

The `<td>` tag defines a single cell within a table row. It represents data or content within the table.

```html
<table border="1">
  <tr>
    <td>Data 1</td>
    <td>Data 2</td>
  </tr>
  <tr>
    <td>Data 3</td>
    <td>Data 4</td>
  </tr>
</table>
```

Tables can also include additional structural elements like headers (`<th>`), table captions (`<caption>`), and grouping elements (`<thead>`, `<tbody>`, `<tfoot>`), providing further organization and context to the table's content.

---