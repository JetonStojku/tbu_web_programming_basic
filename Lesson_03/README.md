# Lesson 3: Bootstrap 5 Basic

This lesson introduces Bootstrap 5 and focuses on understanding the main Bootstrap component groups.

## Learning Objectives

By the end of this lesson, students should be able to:

- Add Bootstrap 5 to an HTML page using CDN
- Use Bootstrap layout classes (container, row, col)
- Use common UI components (buttons, cards, alerts, badges, navbar)
- Build and style forms with Bootstrap classes
- Understand Bootstrap component groups and when to use each group

## Lesson Files

- `project/index.html`
- `project/layout.html`
- `project/components.html`
- `project/forms.html`
- `project/styles/style.css`
- `project/images/`
- `PRACTICE.md`

## Project Structure and Requirements

- 4 pages
- Top menu on all pages
- Bootstrap 5 via CDN
- Optional custom CSS in `project/styles/style.css`
- Local images in `project/images/` (copied from Lesson 2)

## Bootstrap Component Groups

1. Layout Group

- `container`, `container-fluid`
- Grid system: `row`, `col-*`
- Spacing utilities for layout tuning

2. Content Group

- Typography classes (`lead`, heading sizes)
- Tables
- Images (`img-fluid`)

3. Forms Group

- `form-control`, `form-label`, `form-select`
- Input groups
- Form validation classes

4. Components Group

- Buttons
- Cards
- Alerts
- Badges
- Navbar
- Modal / Collapse / Accordion

5. Helpers and Utilities

- Colors (`text-*`, `bg-*`)
- Spacing (`m-*`, `p-*`)
- Display (`d-*`)
- Flex (`d-flex`, `justify-content-*`, `align-items-*`)
- Borders, shadows, rounded corners

## How Bootstrap is Added

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

## Suggested Teaching Flow

1. Compare plain HTML (Lesson 2) vs Bootstrap classes.
2. Build page structure with container, rows, columns.
3. Add ready-made components (buttons, alert, card).
4. Build one form with Bootstrap form classes.
5. Let students complete `PRACTICE.md`.

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
- Navbar exists on each page.
- Bootstrap classes are used consistently.
- At least 3 different component groups are demonstrated.
- Code is clean and readable.
