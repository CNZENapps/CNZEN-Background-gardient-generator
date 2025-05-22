A **gradient background in CSS** is a smooth transition between two or more colors. Instead of using a single solid color, you can use gradients to create more attractive and modern-looking backgrounds.

---

### 🎨 **Types of CSS Gradients:**

1. **Linear Gradient** – colors blend in a straight line

   ```css
   background: linear-gradient(to right, red, yellow);
   ```

   ✅ This creates a gradient from **red to yellow**, going **left to right**.

2. **Radial Gradient** – colors spread out in a circle or ellipse

   ```css
   background: radial-gradient(circle, blue, white);
   ```

   ✅ This creates a gradient from **blue in the center** to **white on the edges**.

3. **Conic Gradient** – colors rotate around a center point (CSS level 4)

   ```css
   background: conic-gradient(from 0deg, red, yellow, green, red);
   ```

---

### 🌈 **You Can Also:**

* Use **more than two colors**:

  ```css
  background: linear-gradient(to bottom, red, orange, yellow);
  ```
* Set **direction**:

  * `to right`
  * `to bottom left`
  * or by degree: `90deg`, `180deg`, etc.

---

### 💡 Example in CSS:

```css
body {
  background: linear-gradient(to right, #ff7e5f, #feb47b);
}
```

This creates a beautiful warm sunset-style background.
