# Lesson 1: HTML Fundamentals

This lesson introduces the foundations of HTML and the structure of a basic web page.

## Prerequisites

- A code editor (VS Code recommended)
- A modern browser
- Basic familiarity with opening files and folders

## Learning Objectives

By the end of this lesson, students should be able to:

- Create a valid HTML document structure
- Use headings, paragraphs, lists, links, and images correctly
- Organize content with semantic tags
- Write cleaner, more accessible markup

## Lesson Files

- `project/index.html` - starter page for this lesson
- `PRACTICE.md` - hands-on tasks and extra challenges

## Core Topics

### 1. HTML Document Structure

Required skeleton:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My First Web Page</title>
  </head>
  <body>
    <!-- visible content goes here -->
  </body>
</html>
```

Key points:

- `<!DOCTYPE html>` enables standards mode.
- `<head>` contains metadata, not visible page content.
- `<body>` contains all visible content.

### 2. Text and Content Elements

Common text structure:

```html
<h1>Welcome to My Page</h1>
<p>This is a short introduction paragraph.</p>

<h2>My Goals</h2>
<ul>
  <li>Learn HTML basics</li>
  <li>Practice semantic structure</li>
  <li>Build readable pages</li>
</ul>
```

Use one `<h1>` per page, then continue with `<h2>`, `<h3>`, and so on.

### 3. Links and Images

```html
<p>
  Visit
  <a href="https://www.w3schools.com/html/" target="_blank" rel="noopener noreferrer">
    HTML Tutorial
  </a>
</p>

<img src="https://picsum.photos/600/300" alt="Sample landscape placeholder" />
```

Best practices:

- Use meaningful link text (avoid "click here").
- Always include `alt` text for images.

### 4. Semantic Page Structure

```html
<header>
  <h1>Student Portfolio</h1>
</header>

<main>
  <section>
    <h2>About Me</h2>
    <p>Short background information.</p>
  </section>

  <section>
    <h2>Projects</h2>
    <article>
      <h3>Project 1</h3>
      <p>Project summary.</p>
    </article>
  </section>
</main>

<footer>
  <p>2026 Student Name</p>
</footer>
```

Semantic tags improve readability, maintainability, and accessibility.

## Recommended Lesson Flow

1. Build the HTML skeleton.
2. Add text elements (headings, paragraphs, lists).
3. Add links and images.
4. Wrap content in semantic sections.
5. Validate and review structure.

## Common Beginner Mistakes

- Skipping `<!DOCTYPE html>`
- Using multiple `<h1>` tags without reason
- Missing closing tags
- Missing `alt` attribute on `<img>`
- Putting visible text inside `<head>`

## Main Learning Resources (W3Schools)

- [W3Schools HTML Introduction](https://www.w3schools.com/html/html_intro.asp)
- [W3Schools HTML Basic](https://www.w3schools.com/html/html_basic.asp)
- [W3Schools HTML Elements](https://www.w3schools.com/html/html_elements.asp)
- [W3Schools HTML Links](https://www.w3schools.com/html/html_links.asp)
- [W3Schools HTML Images](https://www.w3schools.com/html/html_images.asp)
- [W3Schools HTML Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp)

## Submission Guidance

- Keep code properly indented and readable.
- Use meaningful text content.
- Ensure all links and images work.
- Validate markup before submission.

Optional validator:

- [W3C Markup Validation Service](https://validator.w3.org/)
