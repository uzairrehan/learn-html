
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
