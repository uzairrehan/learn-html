# The **`<kbd>`**, **`<code>`**, **`<samp>`**, and **`<var>`** tags are all semantic HTML elements used for specific purposes in programming or technical content. Let’s dive into each tag, its use case, and examples:

---

### 1. **`<kbd>`: Keyboard Input**
- **Purpose**: Represents user input from a keyboard or other input devices.
- **Use Case**: Used when you want to show keys or combinations of keys a user should press.

**Example**:
```html
<p>To save the document, press <kbd>Ctrl</kbd> + <kbd>S</kbd>.</p>
```

**Rendered Output**:
To save the document, press **Ctrl + S**.

---

### 2. **`<code>`: Code Snippet**
- **Purpose**: Represents a fragment of computer code.
- **Use Case**: Used for displaying inline code or small snippets of programming languages.

**Example**:
```html
<p>To print a message in JavaScript, use <code>console.log("Hello, world!");</code>.</p>
```

**Rendered Output**:
To print a message in JavaScript, use **`console.log("Hello, world!");`**.

---

### 3. **`<samp>`: Sample Output**
- **Purpose**: Represents output from a program or a system.
- **Use Case**: Used when you want to show the result of executing code or a program.

**Example**:
```html
<p>When you run the code, the output will be: <samp>Hello, World!</samp></p>
```

**Rendered Output**:
When you run the code, the output will be: **Hello, World!**

---

### 4. **`<var>`: Variable**
- **Purpose**: Represents a variable in a mathematical expression or programming context.
- **Use Case**: Used when referring to variables in code or formulas.

**Example**:
```html
<p>The formula for the area of a circle is <code>A = πr<sup>2</sup></code>, where <var>r</var> is the radius.</p>
```

**Rendered Output**:
The formula for the area of a circle is **`A = πr²`**, where **_r_** is the radius.

---

### When to Use Each Tag:

| Tag       | Use Case                                                                                          | Example                                                                 |
|-----------|--------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------|
| **`<kbd>`** | Input from a user, like pressing keys or entering data                                           | `<kbd>Ctrl</kbd> + <kbd>C</kbd>` for copy                              |
| **`<code>`** | Inline or block code snippets                                                                   | `<code>if (x > 10) { ... }</code>`                                     |
| **`<samp>`** | Program output or system messages                                                               | `<samp>404 Not Found</samp>`                                           |
| **`<var>`** | Variables in programming, mathematics, or logical expressions                                   | `<var>x</var> + 10 = 20`                                               |

---

### Example Combining All Tags:
```html
<p>To run the script, press <kbd>Ctrl</kbd> + <kbd>R</kbd>.</p>
<p>The code to print a message is: <code>console.log("Hello, World!");</code>.</p>
<p>The program output will be: <samp>Hello, World!</samp></p>
<p>The formula for the area of a circle is <code>A = πr<sup>2</sup></code>, where <var>r</var> is the radius.</p>
```

**Rendered Output**:
- To run the script, press **Ctrl + R**.
- The code to print a message is: **`console.log("Hello, World!");`**.
- The program output will be: **Hello, World!**.
- The formula for the area of a circle is **`A = πr²`**, where **_r_** is the radius.

---

By using these semantic tags, you enhance the accessibility, readability, and semantic correctness of your HTML documents, especially for technical documentation or tutorials.