# HTML Learning Repository


### 1. **HTML Basics**  
- **HTML (HyperText Markup Language):** Used to structure web content.  
- **Basic Structure:**  
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Page Title</title>
  </head>
  <body>
    <h1>Welcome</h1>
    <p>This is a paragraph.</p>
  </body>
</html>
```

---

### 2. **Elements and Tags**  
- Tags usually have an **opening tag** `<tag>` and a **closing tag** `</tag>`.  
- Example: `<p>This is a paragraph.</p>`.  
- **Self-closing tags:** `<img />`, `<br />`, `<hr />`.

---

### 3. **Headings and Text**  
- Headings: `<h1>` to `<h6>` (largest to smallest).  
- Text formatting: `<strong>`, `<em>`, `<u>`, `<mark>`, `<sub>`, `<sup>`.

---

### 4. **Links and Images**  
- Links:  
  ```html
  <a href="https://example.com" target="_blank">Visit Example</a>
  ```
- Images:  
  ```html
  <img src="image.jpg" alt="Description of image" />
  ```

---

### 5. **Lists**  
- **Ordered List:**  
  ```html
  <ol>
    <li>First</li>
    <li>Second</li>
  </ol>
  ```
- **Unordered List:**  
  ```html
  <ul>
    <li>Item 1</li>
    <li>Item 2</li>
  </ul>
  ```

---

### 6. **Tables**  
```html
<table>
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

---

### 7. **Forms**  
```html
<form action="/submit" method="POST">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" />
  <button type="submit">Submit</button>
</form>
```

---

### 8. **Semantic Elements**  
- **For better structure and SEO:**  
  `<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<footer>`, `<aside>`.

---

### 9. **Attributes**  
- Provide extra information to elements.  
  - Example:  
    ```html
    <input type="text" placeholder="Enter your name" />
    ```

---

### 10. **Best Practices**  
- Always include the `alt` attribute for images.  
- Use semantic tags for better accessibility and SEO.  
- Validate your HTML using tools like [W3C Validator](https://validator.w3.org/).


## Let’s break down the `<br>` and `<hr>` tags.

---

### **1. `<br>` (Line Break)**
- **Purpose:** Used to create a single line break, like hitting "Enter" in a text editor.
- **Usage:**  
  - Commonly used inside text or paragraphs when you need to separate lines without creating a new paragraph.
- **Example:**
  ```html
  <p>This is line 1.<br />This is line 2.</p>
  ```
  **Output:**  
  This is line 1.  
  This is line 2.

- **Self-closing Tag:**  
  `<br />` is self-closing, so it doesn't need a closing tag like `</br>`.

---

### **2. `<hr>` (Horizontal Rule)**
- **Purpose:** Used to create a horizontal line, usually to separate sections of content.
- **Usage:**  
  - Often used to visually divide sections of a page.
- **Example:**
  ```html
  <h1>Heading 1</h1>
  <hr />
  <h2>Heading 2</h2>
  ```
  **Output:**  
  A horizontal line will appear between **Heading 1** and **Heading 2**.

- **Customizing `<hr>` (with CSS):**  
  You can style `<hr>` to change its appearance:
  ```html
  <hr style="border: 1px solid #000; width: 50%;" />
  ```

---

### Key Differences  
| **Tag**  | **Function**                           | **Visual**         |
|----------|---------------------------------------|--------------------|
| `<br>`   | Adds a line break in text.             | No visible border. |
| `<hr>`   | Creates a horizontal line separator.   | Visible line.      |

---



## Here’s a detailed explanation of the text formatting tags you mentioned, Uzair, with examples:

---

### **1. `<strong>` (Strong Importance)**
- **Purpose:** Makes text bold and conveys importance or emphasis.
- **Usage:** Use when you want to highlight critical or key information.
- **Example:**
  ```html
  <p>This is a <strong>very important</strong> message.</p>
  ```
  **Output:**  
  This is a **very important** message.

---

### **2. `<em>` (Emphasis)**
- **Purpose:** Italicizes text and conveys emphasis.
- **Usage:** Use to highlight text subtly or when you want to emphasize words in a sentence.
- **Example:**
  ```html
  <p>Please <em>do not forget</em> to submit the assignment.</p>
  ```
  **Output:**  
  Please *do not forget* to submit the assignment.

---

### **3. `<u>` (Underline)**
- **Purpose:** Underlines text for visual emphasis (not as commonly used now because CSS can style text with `text-decoration`).
- **Usage:** Use sparingly to highlight specific words.
- **Example:**
  ```html
  <p>The winner is <u>John Doe</u>.</p>
  ```
  **Output:**  
  The winner is **_John Doe_**.

---

### **4. `<mark>` (Highlight/Mark Text)**
- **Purpose:** Highlights text by adding a yellow background.
- **Usage:** Use when you want to draw attention to a part of the text.
- **Example:**
  ```html
  <p>This is a <mark>very important</mark> topic.</p>
  ```
  **Output:**  
  This is a **very important** topic (with a yellow highlight).

---

### **5. `<sub>` (Subscript)**
- **Purpose:** Displays text slightly below the baseline (used in mathematical or chemical formulas).
- **Usage:** Commonly used for formulas or footnotes.
- **Example:**
  ```html
  <p>H<sub>2</sub>O is the formula for water.</p>
  ```
  **Output:**  
  H₂O is the formula for water.

---

### **6. `<sup>` (Superscript)**
- **Purpose:** Displays text slightly above the baseline (used in exponents, ordinal numbers, etc.).
- **Usage:** Commonly used for powers or ordinal suffixes.
- **Example:**
  ```html
  <p>2<sup>3</sup> = 8</p>
  ```
  **Output:**  
  2³ = 8

---

### Summary Table:
| **Tag**      | **Purpose**                | **Visual Example**             |
|--------------|----------------------------|--------------------------------|
| `<strong>`   | Bold important text        | **Bold text**                 |
| `<em>`       | Italicize/emphasize text   | *Italicized text*             |
| `<u>`        | Underline text             | **_Underlined text_**         |
| `<mark>`     | Highlight text             | Highlighted text              |
| `<sub>`      | Subscript text             | H₂O                           |
| `<sup>`      | Superscript text           | x²                            |

---


## The `target="_blank"` attribute in the `<a>` tag is used to open a link in a new browser tab or window. Let me expand on this and provide more options for the `target` attribute and other commonly used anchor (`<a>`) tag attributes.

---

### **`target` Attribute Options**
The `target` attribute specifies where to display the linked document.

1. **`_self`** (Default Behavior):
   - Opens the link in the same tab or window.
   - Example:
     ```html
     <a href="https://example.com" target="_self">Open in Same Tab</a>
     ```

2. **`_blank`**:
   - Opens the link in a new tab or window.
   - Example:
     ```html
     <a href="https://example.com" target="_blank">Open in New Tab</a>
     ```

3. **`_parent`**:
   - Opens the link in the parent frame (useful when working with iframes).
   - Example:
     ```html
     <a href="https://example.com" target="_parent">Open in Parent Frame</a>
     ```

4. **`_top`**:
   - Opens the link in the full body of the window, breaking out of frames entirely.
   - Example:
     ```html
     <a href="https://example.com" target="_top">Open in Full Window</a>
     ```

5. **Frame Name** (Custom):
   - Opens the link in a specific frame if named.
   - Example:
     ```html
     <iframe name="myFrame"></iframe>
     <a href="https://example.com" target="myFrame">Open in iframe</a>
     ```

---

### **Other Anchor Tag Attributes**

1. **`rel`** (Relationship):
   - Specifies the relationship between the current document and the linked document.
   - Common values:
     - `nofollow`: Tells search engines not to follow the link.
     - `noopener`: Prevents the new page from accessing `window.opener`.
     - `noreferrer`: Prevents the browser from sending the HTTP referrer header.
   - Example:
     ```html
     <a href="https://example.com" target="_blank" rel="noopener noreferrer">Secure Link</a>
     ```

2. **`href`** (Hyperlink Reference):
   - Specifies the URL of the page the link goes to.
   - Example:
     ```html
     <a href="https://example.com">Go to Example</a>
     ```

3. **`download`**:
   - Allows users to download the linked file instead of navigating to it.
   - Example:
     ```html
     <a href="file.pdf" download="MyFile.pdf">Download File</a>
     ```

4. **`type`**:
   - Specifies the MIME type of the linked document.
   - Example:
     ```html
     <a href="document.pdf" type="application/pdf">Open PDF</a>
     ```

5. **`title`**:
   - Adds a tooltip to the link that appears on hover.
   - Example:
     ```html
     <a href="https://example.com" title="Go to Example Website">Hover Over Me</a>
     ```

6. **`target="_blank"` with Security (Best Practice)**:
   - Add `rel="noopener noreferrer"` to improve security.
   - Example:
     ```html
     <a href="https://example.com" target="_blank" rel="noopener noreferrer">Safe New Tab</a>
     ```

---

### Full Example with Multiple Attributes:
```html
<a href="https://example.com"
   target="_blank"
   rel="noopener noreferrer"
   download="example.pdf"
   title="Click to open Example in a new tab">
   Visit Example and Download
</a>
```

---

## Tables in HTML are used to organize and display data in a tabular format with rows and columns. Here's a detailed explanation:

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

---
## Ah, you’re asking about **form attributes** in HTML. Let me explain some key form attributes, including `action` and `method`, and other related options you can use for handling form submissions.

---
