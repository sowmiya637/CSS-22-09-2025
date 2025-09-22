#  Animated Cards Web Page

##  Features

-  **Card Layout** with images and text  
-  **Hover Animations** using CSS transitions  
-  **Responsive Design** using media queries  
-  Styled using **pure CSS** (no frameworks)

##  Technologies Used

- **HTML5**
- **CSS3 (Flexbox, Media Queries, Transitions)**

##  Responsive Behavior


##  How the Hover Animation Works

When a user hovers over a `.card`:
- The card is slightly lifted (`translateY(-10px)`)
- A subtle scale-up effect (`scale(1.03)`)
- The background color changes
- Shadow becomes more intense for a "lifted" look

```css
.card:hover {
  transform: translateY(-10px) scale(1.03);
  box-shadow: 0 15px 25px rgba(0,0,0,0.2);
  background-color: #e8faff;
}
