# Lesson 2: CSS Fundamentals

This lesson introduces basic CSS styling and shows how to connect one stylesheet to multiple HTML pages.

## Learning Objectives

By the end of this lesson, students should be able to:

- Apply simple CSS rules for colors, spacing, and typography
- Use one shared CSS file for multiple pages
- Build a basic 4-page website with a top navigation menu
- Organize files into folders (`styles/`, `images/`)

## Lesson Files

- `project/index.html`
- `project/about.html`
- `project/gallery.html`
- `project/contact.html`
- `project/styles/style.css`
- `project/images/`
- `PRACTICE.md`

## Project Requirements

- 4 pages
- A simple top menu on each page
- CSS in a separate file inside a folder
- Use photos from the `images/` folder

## Ways to Add CSS to HTML

1. Inline CSS (inside an element)

```html
<p style="color: blue;">This is inline CSS.</p>
```

2. Internal CSS (inside the `<style>` tag in `<head>`)

```html
<head>
  <style>
    p {
      color: blue;
    }
  </style>
</head>
```

3. External CSS (recommended, separate file)

```html
<head>
  <link rel="stylesheet" href="styles/style.css" />
</head>
```

For this lesson project, use the external CSS approach.

## Main Learning Resources (W3Schools)

- [W3Schools CSS Introduction](https://www.w3schools.com/css/css_intro.asp)
- [W3Schools CSS How To](https://www.w3schools.com/css/css_howto.asp)
- [W3Schools CSS Syntax](https://www.w3schools.com/css/css_syntax.asp)
- [W3Schools CSS Colors](https://www.w3schools.com/css/css_colors.asp)
- [W3Schools CSS Box Model](https://www.w3schools.com/css/css_boxmodel.asp)
- [W3Schools CSS Navigation Bar](https://www.w3schools.com/css/css_navbar.asp)

## Submission Guidance

- Keep all 4 pages linked correctly through the menu.
- Keep CSS readable and simple.
- Reuse classes instead of repeating inline styles.
