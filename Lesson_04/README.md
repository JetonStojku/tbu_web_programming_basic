# Lesson 4: Bootstrap + Custom CSS

This lesson combines Bootstrap 5 components with a custom stylesheet to create a cleaner and more unique design.

## Prerequisites

- Completed Lesson 3 (Bootstrap basics)
- Basic understanding of CSS selectors and specificity

## Learning Objectives

By the end of this lesson, students should be able to:

- Build multi-page websites with Bootstrap 5
- Add and organize a separate custom CSS file
- Override or extend Bootstrap styles safely
- Apply reusable design decisions with CSS variables

## Lesson Files

- `project/index.html`
- `project/services.html`
- `project/portfolio.html`
- `project/contact.html`
- `project/styles/style.css`
- `project/images/`
- `PRACTICE.md`

## Project Requirements

- 4 pages
- Top menu on each page
- Bootstrap 5 via CDN
- Custom CSS in `project/styles/style.css`
- Local images in `project/images/`

## Why Use Bootstrap + Custom CSS

- Bootstrap provides fast layout and reusable components.
- Custom CSS helps create your own visual identity.
- You can keep Bootstrap defaults and only customize what you need.

## Recommended Workflow

1. Build page structure and components with Bootstrap classes.
2. Define color and spacing variables in `:root`.
3. Add custom classes for sections and reusable components.
4. Override specific Bootstrap elements where needed.
5. Check consistency across all pages and screen sizes.

## Example: CSS Variables + Overrides

```css
:root {
  --brand-primary: #0d6efd;
  --brand-dark: #0b2447;
  --surface: #f8fafc;
}

body {
  background: var(--surface);
}

.navbar {
  background-color: var(--brand-dark) !important;
}

.custom-card {
  border-radius: 14px;
  border: 1px solid #dbe3ef;
}
```

## Common Pitfalls

- Overusing `!important` for every style
- Mixing many unrelated color values
- Copying inline styles instead of reusable classes
- Inconsistent spacing between sections

## Main Learning Resources (W3Schools)

- [W3Schools Bootstrap 5 Tutorial](https://www.w3schools.com/bootstrap5/)
- [W3Schools Bootstrap 5 Grid](https://www.w3schools.com/bootstrap5/bootstrap_grid_basic.php)
- [W3Schools Bootstrap 5 Navbar](https://www.w3schools.com/bootstrap5/bootstrap_navbar.php)
- [W3Schools Bootstrap 5 Cards](https://www.w3schools.com/bootstrap5/bootstrap_cards.php)
- [W3Schools CSS Variables](https://www.w3schools.com/css/css3_variables.asp)
- [W3Schools CSS Gradients](https://www.w3schools.com/css/css3_gradients.asp)

## Submission Checklist

- All 4 pages are connected and working.
- Bootstrap classes are used correctly.
- `style.css` contains clear, reusable custom styles.
- Visual style is consistent across pages.
- Code is readable and cleanly formatted.

