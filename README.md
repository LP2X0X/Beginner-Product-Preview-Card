# Frontend Mentor - Product preview card component

![Design preview for the Product preview card component coding challenge](./design/desktop-preview.jpg)

### 🧠 What I've learned from this project:
- By applying display: flex, justify-content: center, and align-items: center to a wrapper (e.g., main), I can center a child element both vertically and horizontally without modifying the child itself. Setting min-height: 100vh ensures proper vertical centering when the child has a small height.
  ```css
  main {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh; /* Since the size of the target element is small in height, set this make it's parent's height equal the screen height which help center it */
  }
  ```

- Using overflow: hidden on a container clips any overflowing content and helps apply rounded borders cleanly for child element also.

- I used the letter-spacing property to fine-tune the spacing between characters, enhancing typography and achieving a more visually appealing style.

- I learned about mobile-first and desktop-first approach concepts and practiced the mobile-first approach by writing base styles for small screens first, then using media queries to adapt the layout for larger screens.

- I started using custom properties for defining consistent design tokens such as colors and fonts.

- I also learned that the `<img>` element still requires a `src` attribute even when using `srcset` and `sizes`, and that the `<button>` element should include a `type` attribute to ensure proper behavior.
