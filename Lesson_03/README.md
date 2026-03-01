# Lesson 3: Bootstrap 5 Basic

This lesson introduces Bootstrap 5 and shows how to build responsive interfaces quickly using prebuilt classes and components.

## Prerequisites

- Completed Lesson 2 (HTML + CSS fundamentals)
- Comfortable with multi-page project structure

## Learning Objectives

By the end of this lesson, students should be able to:

- Add Bootstrap 5 to an HTML page using CDN
- Use Bootstrap layout classes (container, row, col)
- Use common UI components (buttons, cards, alerts, badges, navbar)
- Build and style forms with Bootstrap classes
- Apply utility classes for spacing and alignment

## Lesson Files

- `project/index.html`
- `project/layout.html`
- `project/components.html`
- `project/forms.html`
- `project/styles/style.css`
- `project/images/`
- `PRACTICE.md`

## Project Structure and Requirements

- 4 pages with working navigation
- Bootstrap 5 loaded via CDN
- Optional custom CSS in `project/styles/style.css`
- Images loaded from `project/images/`

## Bootstrap Setup

```html
<link
  href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
  rel="stylesheet"
/>
```

Optional JavaScript bundle (for components like navbar toggler, collapse, modal):

```html
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>
```

## Core Component Groups

### 1. Layout

- `container`, `container-fluid`
- `row`, `col-*`
- Responsive breakpoints (`col-md-6`, `col-lg-4`)

Example:

```html
<div class="container py-4">
  <div class="row g-3">
    <div class="col-md-6 col-lg-4">Column 1</div>
    <div class="col-md-6 col-lg-4">Column 2</div>
    <div class="col-md-12 col-lg-4">Column 3</div>
  </div>
</div>
```

### 2. Components

- Navbar
- Alerts
- Buttons and button groups
- Cards
- Badges

### 3. Forms

- `form-label`, `form-control`, `form-select`
- `form-check` for checkboxes/radios
- Spacing helpers for better visual structure

### 4. Utilities

- Spacing (`mt-*`, `p-*`, `g-*`)
- Color (`text-*`, `bg-*`)
- Display and flex (`d-*`, `justify-content-*`, `align-items-*`)

## Suggested Teaching Flow

1. Add CDN and confirm Bootstrap is loading.
2. Build a responsive layout page with grid.
3. Add components page with cards, alerts, badges, buttons.
4. Build forms page with several input types.
5. Add light custom CSS for branding consistency.

## Main Learning Resources (W3Schools)

- [W3Schools Bootstrap 5 Tutorial](https://www.w3schools.com/bootstrap5/)
- [W3Schools Bootstrap 5 Grid](https://www.w3schools.com/bootstrap5/bootstrap_grid_basic.php)
- [W3Schools Bootstrap 5 Containers](https://www.w3schools.com/bootstrap5/bootstrap_containers.php)
- [W3Schools Bootstrap 5 Buttons](https://www.w3schools.com/bootstrap5/bootstrap_buttons.php)
- [W3Schools Bootstrap 5 Cards](https://www.w3schools.com/bootstrap5/bootstrap_cards.php)
- [W3Schools Bootstrap 5 Forms](https://www.w3schools.com/bootstrap5/bootstrap_forms.php)
- [W3Schools Bootstrap 5 Navbar](https://www.w3schools.com/bootstrap5/bootstrap_navbar.php)

## Submission Checklist

- All 4 pages open and link correctly.
- Navbar is present and usable on each page.
- Grid layout is responsive on at least two breakpoints.
- Forms include labels and proper field structure.
- Code is clean and consistently formatted.
