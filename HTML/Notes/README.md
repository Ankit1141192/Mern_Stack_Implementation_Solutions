

# HTML Complete Notes (Beginner → Pro)

---

# 🌐 Web Development Structure

```
HTML → Structure / Layout
CSS  → Styling / Design
JS   → Logic / Functionality
```

---

# LEVEL 1 – HTML Basics

## 🔹 What is HTML?

**HTML (Hyper Text Markup Language)** is the code used to structure a web page and its content.

The components used to design website structure are called **HTML Tags**.

---

## 🔹 First HTML File

```
index.html
```

It is the default name for a website's homepage.

---

## 🔹 What is an HTML Tag?

An HTML tag is a container for content or other HTML tags.

Example:

```html
<p>This is a paragraph</p>
```

* `<p>` → Opening tag
* `</p>` → Closing tag
* Text inside → Content
* Full structure → Element

---

## 🔹 Basic HTML Page Structure

```html
<!DOCTYPE html>
<html>
<head>
    <title>My First Page</title>
</head>
<body>
    <p>Hello World</p>
</body>
</html>
```

### Explanation:

* `<!DOCTYPE html>` → Tells browser you are using HTML5
* `<html>` → Root of HTML document
* `<head>` → Container for metadata
* `<title>` → Page title
* `<body>` → Contains all visible content
* `<p>` → Paragraph tag

---

## 🔹 Quick Points

* `<html>` tag is parent of `<head>` and `<body>`
* Most HTML elements have opening & closing tags
* Some tags have no closing tag (e.g. `<br>`)
* We can use **Inspect Element / View Page Source**
* HTML comments are ignored by browser
* HTML is NOT case sensitive

Example:

```html
<p> = <P>
<html> = <HTML>
```

---

## 🔹 Comments in HTML

```html
<!-- This is an HTML Comment -->
```

---

# LEVEL 2 – Basic HTML Tags

---

## 🔹 HTML Attributes

Attributes add extra information to tags.

```html
<html lang="en">
```

---

## 🔹 Heading Tags (h1–h6)

Used to display headings.

```html
<h1>Main Heading</h1>
<h2>Sub Heading</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

* `<h1>` → Most important
* `<h6>` → Least important

---

## 🔹 Paragraph Tag

```html
<p>This is a sample paragraph</p>
```

---

## 🔹 Anchor Tag

Used to add links.

```html
<a href="https://google.com">Google</a>
```

Open in new tab:

```html
<a href="https://google.com" target="_blank">Google</a>
```

Clickable image:

```html
<a href="https://google.com">
  <img src="image.png">
</a>
```

---

## 🔹 Image Tag

```html
<img src="image.png" alt="Random Image">
```

Set height & width:

```html
<img src="image.png" height="50px">
<img src="image.png" width="50px">
```

---

## 🔹 Line Break Tag

```html
<br>
```

---

## 🔹 Bold, Italic & Underline

```html
<b>Bold</b>
<i>Italic</i>
<u>Underline</u>
```

---

## 🔹 Big & Small Tags

```html
<big>Big</big>
<small>Small</small>
```

---

## 🔹 Horizontal Rule

```html
<hr>
```

---

## 🔹 Subscript & Superscript

```html
H<sub>2</sub>O
A + B<sup>n</sup>
```

---

## 🔹 Pre Tag

Displays text as it is.

```html
<pre>
This
   is a sample
text.
</pre>
```

---

# LEVEL 3 – Page Layout & Semantic Tags

---

## 🔹 Page Layout Using Semantic Tags

```html
<header></header>
<main></main>
<footer></footer>
```

---

## 🔹 Inside `<main>` Tag

### Section Tag

```html
<section></section>
```

Used for sections.

### Article Tag

```html
<article></article>
```

Used for blog/article content.

### Aside Tag

```html
<aside></aside>
```

Used for side content (ads, links).

---

## 🔹 Div Tag

* Container for other elements
* Block Element (takes full width)

```html
<div></div>
```

---

## 🔹 Span Tag

* Container for inline elements
* Inline Element (takes width as needed)

```html
<span></span>
```

---

# 🔴 LEVEL PRO – Advanced HTML

---

# 📌 Lists in HTML

## Unordered List

```html
<ul>
  <li>Apple</li>
  <li>Mango</li>
</ul>
```

## Ordered List

```html
<ol>
  <li>Apple</li>
  <li>Mango</li>
</ol>
```

---

# 📌 Tables in HTML

```html
<table>
  <caption>Student Data</caption>
  <thead>
    <tr>
      <th>Name</th>
      <th>Roll No</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Shradha</td>
      <td>1664</td>
    </tr>
  </tbody>
</table>
```

### Important Tags:

* `<table>`
* `<tr>` → Table row
* `<th>` → Table header
* `<td>` → Table data
* `<caption>`
* `<thead>`
* `<tbody>`

### Colspan

```html
<td colspan="2">Data</td>
```

---

# 📌 Forms in HTML

Forms collect user data.

```html
<form action="/action.php">
</form>
```

---

## 🔹 Input Field

```html
<input type="text" placeholder="Enter Name">
```

---

## 🔹 Radio Button

```html
<input type="radio" name="class" id="id1">
<label for="id1">Class X</label>
```

---

## 🔹 Checkbox

```html
<input type="checkbox" id="id1">
<label for="id1">Option 1</label>
```

---

## 🔹 Textarea

```html
<textarea placeholder="Add feedback"></textarea>
```

---

## 🔹 Select Dropdown

```html
<select name="city">
  <option value="Delhi">Delhi</option>
  <option value="Mumbai">Mumbai</option>
  <option value="Bangalore">Bangalore</option>
</select>
```

---

## 🔹 Class & ID

```html
<div id="id1" class="group1"></div>
```

* `id` → Unique
* `class` → Reusable

---

# 📌 Iframe Tag

Website inside website.

```html
<iframe src="https://example.com"></iframe>
```

---

# 📌 Video Tag

```html
<video src="myVid.mp4" controls width="300"></video>
```

### Video Attributes:

* `controls`
* `height`
* `width`
* `loop`
* `autoplay`

---

