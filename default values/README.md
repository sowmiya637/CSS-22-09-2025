#  CSS Default Values Demo

This visually demonstrates the difference between **default browser styles** and **custom CSS overrides** using common HTML elements like paragraphs, headings, buttons, and lists.

##  Sections Demonstrated

| Section                 | Element(s) Used              | Explanation                               |
|-------------------------|------------------------------|--------------------------------------------|
| Default Paragraph        | `<p>`                        | Uses browser’s default font and spacing    |
| Custom Paragraph         | `<p class="custom">`         | Overrides font, color, spacing, etc.       |
| Default Button           | `<button>`                   | Default style varies by browser            |
| Custom Button            | `<button class="custom">`    | Styled with background, padding, etc.      |
| Default Heading          | `<h3>`                       | Default large size and bold text           |
| Custom Heading           | `<h3 class="custom">`        | Customized font, color, and background     |
| Default Unordered List   | `<ul><li></li></ul>`         | Browser adds bullets, spacing              |
| Custom Unordered List    | `<ul class="custom">`        | Styled to remove bullets and match design  |

---

##  Optional: CSS Reset

You can **uncomment** the CSS reset block at the top to remove all default margins and paddings:

```css
/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
