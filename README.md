# SpendWise Dashboard

## Project Overview

This project is the visual shell of the SpendWise personal finance dashboard.

It demonstrates modern CSS layout techniques using Grid and Flexbox while following responsive web design principles.

---

## Features

### Dashboard Layout

The page contains:

- Sidebar Navigation
- Header
- Six Financial Cards

### CSS Grid

Grid is used to create the overall dashboard layout consisting of:

- Sidebar
- Main Content

Grid is also used for arranging the dashboard cards.

### Flexbox

Flexbox is used inside:

- Sidebar navigation
- Header
- Dashboard cards

### CSS Variables

The project uses CSS Custom Properties for:

- Brand color
- Accent color
- Background color
- Surface color
- Primary text
- Secondary text

### Responsive Design

A media query activates below **768px**.

Changes include:

- Sidebar becomes horizontal.
- Header stacks vertically.
- Dashboard becomes a single-column layout.

### Micro-interactions

Cards include:

- Hover animation
- Keyboard focus animation

Animations use:

- Transform
- Box Shadow

Duration:

250ms

### Stretch Goal

A Dark Theme is implemented using:

```css
@media (prefers-color-scheme: dark)
```

Only the CSS variables are overridden.

---

## Technologies Used

- HTML5
- CSS3
- CSS Grid
- Flexbox
- CSS Variables
- Responsive Design

---

## Author

Saiton
