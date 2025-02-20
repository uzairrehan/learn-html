# Tables in HTML are used to organize and display data in a tabular format with rows and columns. Here's a detailed explanation:

---

### **Basic Table Structure**
A table is defined using the `<table>` tag. Inside the table, you use:
- `<tr>` (Table Row): Defines a row in the table.
- `<td>` (Table Data): Defines a cell in a row.
- `<th>` (Table Header): Defines a header cell, typically bold and centered by default.

---

### **Example of a Simple Table**
```html
<table border="1">
  <tr>
    <th>Header 1</th>
    <th>Header 2</th>
    <th>Header 3</th>
  </tr>
  <tr>
    <td>Row 1, Cell 1</td>
    <td>Row 1, Cell 2</td>
    <td>Row 1, Cell 3</td>
  </tr>
  <tr>
    <td>Row 2, Cell 1</td>
    <td>Row 2, Cell 2</td>
    <td>Row 2, Cell 3</td>
  </tr>
</table>
```
**Output:**  
| Header 1       | Header 2       | Header 3       |  
|-----------------|----------------|----------------|  
| Row 1, Cell 1  | Row 1, Cell 2  | Row 1, Cell 3  |  
| Row 2, Cell 1  | Row 2, Cell 2  | Row 2, Cell 3  |  

---

### **Optional Table Tags**
1. **`<caption>` (Table Caption)**  
   - Adds a title to the table.  
   - Example:
     ```html
     <table>
       <caption>Student Grades</caption>
       <tr><th>Name</th><th>Grade</th></tr>
       <tr><td>Ali</td><td>A</td></tr>
     </table>
     ```
   - **Output:**  
     *Student Grades* (title above the table).

2. **`<thead>`, `<tbody>`, `<tfoot>`**
   - Organize table content into sections.
     - `<thead>`: Contains the header row(s).
     - `<tbody>`: Contains the body of the table.
     - `<tfoot>`: Contains footer row(s).
   - Example:
     ```html
     <table border="1">
       <thead>
         <tr><th>Name</th><th>Age</th></tr>
       </thead>
       <tbody>
         <tr><td>Uzair</td><td>21</td></tr>
         <tr><td>Abdullah</td><td>22</td></tr>
       </tbody>
       <tfoot>
         <tr><td colspan="2">End of Data</td></tr>
       </tfoot>
     </table>
     ```

---

### **Attributes for Tables**
1. **`border`**: Adds borders to the table and cells.
   - Example: `<table border="1">`
2. **`cellspacing` and `cellpadding`**: Controls spacing between and inside cells (deprecated in modern HTML, use CSS instead).
3. **`colspan` and `rowspan`**: Merge cells across columns or rows.
   - Example:
     ```html
     <table border="1">
       <tr>
         <th>Name</th>
         <th colspan="2">Contact</th>
       </tr>
       <tr>
         <td>Ali</td>
         <td>Phone</td>
         <td>Email</td>
       </tr>
     </table>
     ```

---

### **Styling Tables with CSS**
Modern HTML prefers styling tables with CSS instead of using attributes like `border`.

1. **Adding Borders:**
   ```html
   <style>
     table {
       border-collapse: collapse;
       width: 100%;
     }
     th, td {
       border: 1px solid black;
       padding: 8px;
       text-align: left;
     }
   </style>
   <table>
     <tr><th>Name</th><th>Age</th></tr>
     <tr><td>Uzair</td><td>21</td></tr>
   </table>
   ```

2. **Hover Effects:**
   ```css
   tr:hover {
     background-color: #f2f2f2;
   }
   ```

---

### **Advanced Example**
```html
<table border="1">
  <caption>Sales Report</caption>
  <thead>
    <tr>
      <th>Product</th>
      <th>Quantity</th>
      <th>Price</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Apples</td>
      <td>10</td>
      <td>$5</td>
    </tr>
    <tr>
      <td>Bananas</td>
      <td>20</td>
      <td>$3</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td colspan="2">Total</td>
      <td>$65</td>
    </tr>
  </tfoot>
</table>
```

