# Assignment #2: WEB Technologies | (Flexbox & Grid)

- **Student:** Rayazov Mustafa
- **Group:** SE - 2529
- **Live Demo:** https://mrreikol.github.io/WEB-Assignment-2/

---

## Project Overview
This project demonstrates modern layout techniques using **CSS Flexbox** and **CSS Grid** without external CSS frameworks or floats. The application is split into structured, dedicated pages connected via a unified responsive navigation bar.

---

## Tasks Breakdown

### Part 1: Flexbox
- **Task 0: Navigation Bar (`flexbox.html`)**
  - Semantic `<header>` container with `display: flex`.
  - Horizontal alignment with `justify-content: space-between` and vertical centering via `align-items: center`.
  - Even spacing between links using `gap`.
- **Task 1: Card Row (`flexbox.html`)**
  - Flex container displaying multiple cards in a row.
  - Consistent gap spacing and equal height across all cards (`align-items: stretch`).
  - Interactive hover effects (smooth lift and box-shadow elevation).

### Part 2: Grid System
- **Task 2: Page Layout with Grid Areas (`grid-layout.html`)**
  - Structured semantic page using `grid-template-areas`:
    - `header`: spans across the full top.
    - `sidebar`: placed on the left column.
    - `main`: placed on the right column.
    - `footer`: spans across the full bottom.
  - Custom styled dashboard-like navigation sidebar with interactive hover states.
- **Task 3: Responsive Image Gallery (`gallery.html`)**
  - CSS Grid container with equal-width columns (`repeat(3, 1fr)`) and consistent gaps.
  - 9 high-resolution images.
  - Overlay captions appearing dynamically on image hover.

### Part 3: Combining Flexbox & Grid
- **Task 4: Portfolio Page (`index.html`)**
  - Fully integrated layout combining both layout paradigms:
    - **Flexbox:** Navigation header and internal arrangement of project card contents (title, details, actions).
    - **CSS Grid:** Main page body split into a two-column structure (Projects area on the left, developer overview sidebar on the right).
    - Full-width footer pinned cleanly to the bottom.

---

## Project Structure

```text
.
├── index.html              # Task 4: Portfolio Page (Main Entry)
├── flexbox.html            # Task 0 (Navbar) & Task 1 (Card Row)
├── grid-layout.html        # Task 2 (Grid Areas Layout)
├── gallery.html            # Task 3 (Image Gallery)
├── css/
│   ├── style.css           # Global typography, reset & Task 0 Navbar
│   ├── flexbox.css         # Part 1 Flexbox styles
│   ├── grid.css            # Part 2 Grid areas & gallery styles
│   └── portfolio.css       # Part 3 Portfolio composition styles
└── README.md
