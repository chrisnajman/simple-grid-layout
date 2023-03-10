---
permalink: /index.html
---

[Website (Git Pages)](https://chrisnajman.github.io/simple-grid-layout)

# Simple Grid Layout

## Description

Three-row template for laying out header, main and footer.

- `header`: fits content,
- `main`: takes up the remaining space,
- `footer`: fits content, always sits at the bottom of the page.

## CSS

- `grid` used for page layout.
- `100dvh` (with `100vh` as fallback) set on `.main-layout` for 100% page height.
  - (Avoids setting 100% height on `html, body` which can cause problems on mobile.)

## Testing

- Tested on:
  - Windows 10
    - Chrome
    - Firefox
    - Microsoft Edge
