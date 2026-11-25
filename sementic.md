
# Semantic HTML Cheat Sheet

A quick reference guide to commonly used semantic HTML tags. Semantic HTML describes the meaning and purpose of content in a web page, making documents more accessible, readable, and SEO-friendly.

---

## 1. Sectioning Tags

| Tag | Description |
|---|---|
| `<header>` | Defines the header of a page or section. |
| `<nav>` | Defines navigation links. |
| `<footer>` | Defines the footer of a page or section. |
| `<main>` | Specifies the main content of a document. |
| `<aside>` | Defines secondary content, such as a sidebar. |
| `<article>` | Defines independent, self-contained content. |
| `<section>` | Defines a standalone section of related content. |
| `<details>` | Creates expandable and collapsible content. |
| `<summary>` | Defines a heading for a `<details>` element. |
| `<h1>` – `<h6>` | Define headings from highest to lowest importance. |

### Example

```html
<header>
  <h1>My Website</h1>
</header>

<nav>
  <a href="/">Home</a>
  <a href="/about">About</a>
</nav>

<main>
  <article>
    <h2>Welcome to My Blog</h2>
    <p>This is an example blog post.</p>
  </article>

  <aside>
    <p>Related articles</p>
  </aside>
</main>

<footer>
  <p>&copy; 2026 My Website</p>
</footer>
```

---

## 2. Content Tags

| Tag | Description |
|---|---|
| `<blockquote>` | Defines a block-level quotation. |
| `<dd>` | Defines a description for a term. |
| `<dl>` | Defines a description list. |
| `<dt>` | Defines a term in a description list. |
| `<figcaption>` | Defines a caption for a figure. |
| `<figure>` | Represents self-contained content, such as an image. |
| `<hr>` | Represents a thematic break. |
| `<li>` | Defines an item in a list. |
| `<menu>` | Represents a list of commands or menu items. |
| `<ol>` | Defines an ordered list. |
| `<p>` | Defines a paragraph. |
| `<pre>` | Represents preformatted text. |
| `<ul>` | Defines an unordered list. |

### Example

```html
<figure>
  <img src="html.png" alt="HTML Logo">
  <figcaption>HTML Logo</figcaption>
</figure>

<blockquote>
  HTML provides the structure of a web page.
</blockquote>

<dl>
  <dt>HTML</dt>
  <dd>HyperText Markup Language</dd>

  <dt>CSS</dt>
  <dd>Cascading Style Sheets</dd>
</dl>

<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ul>
```

---

## 3. Inline Tags

| Tag | Description |
|---|---|
| `<a>` | Creates a hyperlink. |
| `<abbr>` | Defines an abbreviation or acronym. |
| `<b>` | Draws attention to text without indicating importance. |
| `<br>` | Inserts a line break. |
| `<cite>` | Represents the title of a creative work. |
| `<code>` | Represents computer code. |
| `<data>` | Associates content with a machine-readable value. |
| `<em>` | Emphasizes text. |
| `<i>` | Represents alternate voice, mood, or technical terms. |
| `<mark>` | Highlights text. |
| `<q>` | Defines a short inline quotation. |
| `<s>` | Represents text that is no longer accurate or relevant. |
| `<samp>` | Represents sample computer output. |
| `<small>` | Represents small print or legal text. |
| `<span>` | Generic inline container for styling. |
| `<strong>` | Indicates strong importance. |
| `<sub>` | Defines subscript text. |
| `<sup>` | Defines superscript text. |
| `<time>` | Represents a date or time. |
| `<u>` | Represents text with a non-textual annotation. |
| `<var>` | Represents a variable in mathematics or programming. |

### Example

```html
<p>
  Learn <strong>HTML</strong> and
  <em>practice every day</em>.
</p>

<p>
  <abbr title="HyperText Markup Language">HTML</abbr>
  is used to structure web pages.
</p>

<p>Water formula: H<sub>2</sub>O</p>

<p>Mathematical expression: x<sup>2</sup></p>

<p>
  Current year:
  <time datetime="2026-11-25">November 25, 2026</time>
</p>

<p>
  Example code: <code>console.log("Hello World");</code>
</p>

<p><mark>Important information</mark></p>
```

---

## 4. Embedded Content and Media Tags

| Tag | Description |
|---|---|
| `<audio>` | Embeds audio content. |
| `<canvas>` | Provides a drawing area for graphics using JavaScript. |
| `<embed>` | Embeds external content. |
| `<iframe>` | Embeds another HTML page. |
| `<img>` | Embeds an image. |
| `<object>` | Embeds an external resource. |
| `<picture>` | Provides multiple image sources for responsive images. |
| `<video>` | Embeds video content. |
| `<source>` | Specifies alternative media resources. |
| `<svg>` | Defines scalable vector graphics. |

### Example

```html
<!-- Image -->
<img src="image.jpg" alt="Beautiful landscape">

<!-- Responsive image -->
<picture>
  <source media="(max-width: 600px)" srcset="mobile.jpg">
  <img src="desktop.jpg" alt="Responsive landscape">
</picture>

<!-- Audio -->
<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
  Your browser does not support audio.
</audio>

<!-- Video -->
<video controls width="400">
  <source src="video.mp4" type="video/mp4">
  Your browser does not support video.
</video>

<!-- Embedded webpage -->
<iframe
  src="https://example.com"
  title="Example website">
</iframe>

<!-- SVG -->
<svg width="100" height="100">
  <circle cx="50" cy="50" r="40" fill="blue" />
</svg>
```

---

## 5. Table Tags

| Tag | Description |
|---|---|
| `<table>` | Defines an HTML table. |
| `<thead>` | Groups table header content. |
| `<tbody>` | Groups the main table content. |
| `<tfoot>` | Groups table footer content. |
| `<tr>` | Defines a table row. |
| `<td>` | Defines a standard data cell. |
| `<th>` | Defines a header cell. |
| `<caption>` | Defines a table caption. |
| `<colgroup>` | Groups one or more columns. |
| `<col>` | Specifies properties for table columns. |

### Example

```html
<table>
  <caption>Student Information</caption>

  <colgroup>
    <col style="background-color: #f0f0f0">
    <col>
    <col>
  </colgroup>

  <thead>
    <tr>
      <th scope="col">ID</th>
      <th scope="col">Name</th>
      <th scope="col">Course</th>
    </tr>
  </thead>

  <tbody>
    <tr>
      <td>1</td>
      <td>John</td>
      <td>HTML</td>
    </tr>

    <tr>
      <td>2</td>
      <td>David</td>
      <td>CSS</td>
    </tr>
  </tbody>

  <tfoot>
    <tr>
      <td colspan="3">Total Students: 2</td>
    </tr>
  </tfoot>
</table>
```

---

## 6. Best Practices for Semantic HTML

- Use `<header>`, `<nav>`, `<main>`, and `<footer>` to create meaningful page structures.
- Use only one primary `<main>` element per document.
- Use headings (`<h1>` to `<h6>`) in a logical hierarchy.
- Use `<article>` for independent, reusable content.
- Use `<section>` to group related content.
- Use `<strong>` instead of `<b>` when indicating importance.
- Use `<em>` instead of `<i>` when indicating emphasis.
- Add descriptive `alt` attributes to meaningful images.
- Use `<button>` for actions and `<a>` for navigation.
- Use semantic HTML to improve accessibility and maintainability.
- Use tables for tabular data, not page layouts.

---

## 7. Basic Semantic HTML Page Structure

```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Semantic HTML Example</title>
</head>

<body>

  <header>
    <h1>My Website</h1>

    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>

    <section id="home">
      <h2>Welcome</h2>
      <p>Welcome to my website.</p>
    </section>

    <article id="about">
      <h2>About Us</h2>
      <p>We share knowledge about web development.</p>
    </article>

    <aside>
      <h2>Related Topics</h2>
      <p>Learn HTML, CSS, and JavaScript.</p>
    </aside>

    <section id="contact">
      <h2>Contact</h2>
      <p>Get in touch with us.</p>
    </section>

  </main>

  <footer>
    <p>&copy; 2026 My Website. All rights reserved.</p>
  </footer>

</body>
</html>
```

---

## 8. Quick Reference

| Category | Common HTML Tags |
|---|---|
| Sectioning | `<header>`, `<nav>`, `<main>`, `<footer>`, `<section>`, `<article>`, `<aside>` |
| Content | `<p>`, `<blockquote>`, `<figure>`, `<figcaption>`, `<ul>`, `<ol>`, `<li>` |
| Inline | `<a>`, `<strong>`, `<em>`, `<span>`, `<code>`, `<mark>`, `<time>` |
| Media | `<img>`, `<audio>`, `<video>`, `<picture>`, `<iframe>`, `<svg>`, `<canvas>` |
| Tables | `<table>`, `<thead>`, `<tbody>`, `<tfoot>`, `<tr>`, `<th>`, `<td>` |
| Interactive | `<details>`, `<summary>` |

---

## Reference

- [MDN Web Docs - HTML Elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)

**Remember:** Semantic HTML is not just about how content looks. It describes what the content means. Always use HTML elements according to their purpose.
