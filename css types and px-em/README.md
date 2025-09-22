#  CSS Types Demo: px, em, rem and Selectors

This demonstrates how to use different **CSS unit types** (like `px`, `em`, `rem`) along with multiple **CSS selectors** (`class`, `id`, `type`, and `pseudo-classes`) in a real-time example layout.


### Key Features:
- `em`, `rem`, and `px` used for sizing
- Various CSS selectors:
  -  Type selector (`body`)
  -  Class selector (`.card`, `.btn`)
  -  ID selector (`#footer`)
  -  Pseudo-class selector (`.btn:hover`)
- Use of:
  - `box-shadow`, `border-radius`, `padding`, etc.
  - Responsive layout using relative units like `em`

##  Units Breakdown

| Unit Type | Where Used                | Meaning                                 |
|-----------|---------------------------|------------------------------------------|
| `px`      | `border`, `box-shadow`    | Fixed size (pixels)                      |
| `em`      | `padding`, `margin`, `font-size` | Relative to parent element              |
| `rem`     | `.btn font-size`          | Relative to root `<html>` font-size      |

---

##  CSS Selectors Used

| Selector Type      | Example Used          | Purpose                                |
|--------------------|-----------------------|----------------------------------------|
| **Type Selector**  | `body`                | Apply style to all `body` elements     |
| **Class Selector** | `.card`, `.btn`       | Style reusable components              |
| **ID Selector**    | `#footer`             | Style a unique footer element          |
| **Pseudo-class**   | `.btn:hover`          | Change style on mouse hover            |

