# Task 02 — Product Grid

## Scenario
An e-commerce category page needs to display a list of products as equal-size cards that reflow automatically as the screen resizes.

## Task
Using **CSS Grid**, lay out `.product-grid` so each `.product-card` (image, name, price, button) sits in an equal-size cell. Use `repeat(auto-fill, minmax(...))` on `grid-template-columns` so the number of columns adjusts automatically without any media queries.

## Acceptance Criteria
- Layout built with CSS Grid (no floats, no absolute positioning)
- Cards are equal size and reflow automatically using `auto-fill` / `minmax()`
- No media queries used to control column count
- Matches the mockup provided by the instructor

## Palette
- Background: `#f7f7f8`
- Card background: `#ffffff`
- Text: `#1a1a1a`
- Secondary text: `#1f2937`
- Border: `#e5e7eb`
- Accent/button: `#2563eb`
