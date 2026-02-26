# Lesson 2: CSS Fundamentals

This lesson introduces basic CSS styling and shows how to connect one stylesheet to multiple HTML pages.

## Learning Objectives

By the end of this lesson, students should be able to:

- Apply simple CSS rules for colors, spacing, and typography
- Use one shared CSS file for multiple pages
- Build a basic 4-page website with a top navigation menu
- Organize files into folders (`styles/`, `images/`)
- Target HTML elements using different CSS selectors

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

## Recommended Lesson Flow

1. Explain what CSS is and why separation of structure (HTML) and style (CSS) is useful.
2. Show the 3 ways to include CSS.
3. Teach selectors (how to target tags/elements).
4. Edit `project/styles/style.css` together in class.
5. Let students complete `PRACTICE.md` tasks.

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

## How to Target Elements in CSS (Selectors)

1. Element selector (targets all tags of one type)

```css
p {
  color: #333;
}
```

2. Class selector (reusable style for multiple elements)

```css
.menu {
  background-color: #1b4b91;
}
```

3. ID selector (single unique element)

```css
#main-title {
  font-size: 28px;
}
```

4. Group selector (same style for multiple selectors)

```css
h1,
h2,
h3 {
  font-family: Arial, sans-serif;
}
```

5. Descendant selector (element inside another element)

```css
.menu a {
  color: white;
}
```

6. Child selector (direct child only)

```css
nav > a {
  margin-right: 10px;
}
```

7. Pseudo-class selector (state-based style)

```css
a:hover {
  text-decoration: underline;
}
```

## Cascade and Specificity (Basic Rules)

- Inline CSS has higher priority than internal/external CSS.
- ID selectors are more specific than class selectors.
- Class selectors are more specific than element selectors.
- If specificity is equal, the last rule in the file wins.

## Common CSS Properties for This Lesson

- Text: `color`, `font-size`, `font-family`, `text-align`
- Box model: `margin`, `padding`, `border`, `width`, `max-width`
- Background: `background-color`
- Layout basics: `display`, `gap`

## Main Learning Resources (W3Schools)

- [W3Schools CSS Introduction](https://www.w3schools.com/css/css_intro.asp)
- [W3Schools CSS How To](https://www.w3schools.com/css/css_howto.asp)
- [W3Schools CSS Selectors](https://www.w3schools.com/css/css_selectors.asp)
- [W3Schools CSS Specificity](https://www.w3schools.com/css/css_specificity.asp)
- [W3Schools CSS Colors](https://www.w3schools.com/css/css_colors.asp)
- [W3Schools CSS Box Model](https://www.w3schools.com/css/css_boxmodel.asp)
- [W3Schools CSS Navigation Bar](https://www.w3schools.com/css/css_navbar.asp)

## Submission Checklist

- All 4 pages open correctly.
- Top menu links work on every page.
- Styles are stored in `project/styles/style.css`.
- Images are loaded from `project/images/`.
- Code is clean and consistently indented.
