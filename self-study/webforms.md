# Practice Editing Simple Web Forms with HTML, CSS, and JavaScript

Creating and styling web forms is a fundamental skill for web development. Here’s a simple guide to get you started:

### HTML:
```HTML

  <form action="/submit" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name"><br><br>
    <label for="email">Email:</label>
    <input type="email" id="email" name="email"><br><br>
    <label for="message">Message:</label><br>
    <textarea id="message" name="message"></textarea><br><br>
    <input type="submit" value="Submit">
  </form>
```

### CSS:
```CSS

form {
  width: 300px;
  margin: 0 auto;
}

label {
  display: block;
  margin-top: 10px;
}

input, textarea {
  width: 100%;
  padding: 8px;
  margin-top: 5px;
}

input[type="submit"] {
  width: auto;
  background-color: #4CAF50
```