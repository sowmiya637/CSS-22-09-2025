#  CSS Units Demo

This demonstrates a wide variety of **CSS units** in a single, interactive card component. It’s ideal for learning how different units like `px`, `em`, `rem`, `vw`, `vh`, `cm`, and `s` (time) behave in a real layout.


##  Units Demonstrated

| Unit Type   | Used Where                   | Description                              |
|-------------|------------------------------|------------------------------------------|
| `px`        | `box-shadow`, `margin-bottom`| Absolute pixels                          |
| `em`        | `padding`, `margin`          | Relative to parent’s font-size           |
| `rem`       | `padding`, `font-size`       | Relative to root (`html`) font-size      |
| `%`         | *Not used here*              | Relative to parent element (optional add)|
| `vw`        | `.card { width }`            | % of **viewport width**                  |
| `vh`        | `.card { height }`           | % of **viewport height**                 |
| `cm`        | `.card { border-radius }`    | Absolute physical unit (rare in web)     |
| `s`         | `transition`, `animation`    | Seconds — used for smooth effects        |
| `deg`       | `transform: rotate()`        | Degrees — rotation in animation          |

---

##  Features

-  Responsive **card component** using `vw`, `vh`, and `rem`
-  Smooth **hover animation** with rotation and scaling
-  **Pulse animation** using `@keyframes` and `box-shadow`
-  Clean, organized CSS with comments for learning


