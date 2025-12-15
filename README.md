# JsonToTable (v3.x)

A lightweight **vanilla JavaScript** table component that renders JSON arrays into a **Bootstrap 5** styled table with:

- ✅ Fluent API (`config()`, `load()`, `fetch()`)
- ✅ Global search (supports multi-word AND + `-word` exclude)
- ✅ Modal filters (checkbox / radio / text / sign / number-range / date-range)
- ✅ Column sorting with header arrows (ASC/DESC) + initial sort
- ✅ Per-column disable sort (`sortable: false`)
- ✅ Actions column (view/edit/delete) with sorting disabled by default
- ✅ State save/restore/reset (localStorage)
- ✅ CSV export (no external libs)

> Created by **Malek Alhafi** — www.MalekAlhafi.com

---

## Demo / Docs

- https://malekalhafi.com/JsonToTable/ → documentation page
- https://malekalhafi.com/JsonToTable/examples.html → examples page (with sticky grouped sidebar + active section highlight)

---

## Requirements

- **Bootstrap 5** (CSS + JS Bundle)  
  Required for modal behavior and styling.

Optional:
- **Font Awesome** (icons)

---

## Installation

### Option A) Local file
1. Copy `JsonToTable.js` into your project.
2. Include Bootstrap 5 and the class file:

```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

<script src="JsonToTable.js"></script>
