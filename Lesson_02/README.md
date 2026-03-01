# Lesson 2: CSS Fundamentals

This lesson introduces CSS basics and demonstrates how one shared stylesheet can control design across multiple pages.

## Prerequisites

- Completed Lesson 1 (HTML structure and semantic tags)
- Basic familiarity with editing multiple files

## Learning Objectives

By the end of this lesson, students should be able to:

- Apply CSS rules for colors, typography, spacing, and borders
- Use an external stylesheet across multiple HTML pages
- Build and style a basic 4-page website with top navigation
- Use element, class, ID, and state selectors correctly
- Understand basic cascade and specificity behavior

## Lesson Files

- `project/index.html`
- `project/about.html`
- `project/gallery.html`
- `project/contact.html`
- `project/styles/style.css`
- `project/images/`
- `PRACTICE.md`

## Project Requirements

- 4 connected pages
- Top menu on each page
- Shared CSS file in `project/styles/style.css`
- Images loaded from `project/images/`

## Ways to Add CSS

### 1. Inline CSS

```html
<p style="color: blue;">Inline CSS example.</p>
```

### 2. Internal CSS

```html
<style>
  p {
    color: blue;
  }
</style>
```

### 3. External CSS (recommended)

```html
<link rel="stylesheet" href="styles/style.css" />
```

For this project, use external CSS as the main styling method.

## CSS Selectors You Should Practice

### Element selector

```css
p {
  color: #333;
}
```

### Class selector

```css
.menu {
  background-color: #1b4b91;
}
```

### ID selector

```css
#main-title {
  font-size: 2rem;
}
```

### Descendant and pseudo-class

```css
.menu a {
  color: white;
}

.menu a:hover {
  text-decoration: underline;
}
```

## Box Model and Spacing

Every element uses this structure:

- Content
- Padding
- Border
- Margin

Example:

```css
.card {
  padding: 16px;
  border: 1px solid #d9d9d9;
  margin-bottom: 20px;
}
```

## Simple Multi-Page Style Example

```css
body {
  font-family: Arial, sans-serif;
  margin: 0;
  background: #f7f9fc;
  color: #222;
}

.container {
  max-width: 960px;
  margin: 0 auto;
  padding: 20px;
}

.menu {
  background: #1b4b91;
  padding: 12px 20px;
}

.menu a {
  color: #fff;
  margin-right: 14px;
  text-decoration: none;
}
```

## Cascade and Specificity (Basic Rules)

- Inline styles override internal/external styles.
- ID selectors are stronger than class selectors.
- Class selectors are stronger than element selectors.
- If specificity is equal, the later rule wins.

## Main Learning Resources (W3Schools)

- [W3Schools CSS Introduction](https://www.w3schools.com/css/css_intro.asp)
- [W3Schools CSS How To](https://www.w3schools.com/css/css_howto.asp)
- [W3Schools CSS Selectors](https://www.w3schools.com/css/css_selectors.asp)
- [W3Schools CSS Specificity](https://www.w3schools.com/css/css_specificity.asp)
- [W3Schools CSS Colors](https://www.w3schools.com/css/css_colors.asp)
- [W3Schools CSS Box Model](https://www.w3schools.com/css/css_boxmodel.asp)
- [W3Schools CSS Navigation Bar](https://www.w3schools.com/css/css_navbar.asp)

## Submission Checklist

- All 4 pages open and link correctly.
- Shared stylesheet is used on all pages.
- Menu style is consistent across pages.
- Images load from the local `images/` folder.
- Code is formatted and readable.
