# 🎨 CSS Fonts and Colors

---

## 🖋️ Font Styling in CSS

Fonts are essential to give personality and readability to your text.

### 🔹 Common Font Properties:

| Property         | Description                                 |
| ---------------- | ------------------------------------------- |
| `font-family`    | Sets the typeface (e.g., Arial, Roboto)     |
| `font-size`      | Sets the size of the text                   |
| `font-style`     | Makes text normal, italic, or oblique       |
| `font-weight`    | Controls boldness (e.g., normal, bold, 700) |
| `line-height`    | Sets vertical spacing between lines         |
| `letter-spacing` | Sets space between characters               |
| `word-spacing`   | Sets space between words                    |
| `text-transform` | Capitalize, lowercase, uppercase            |

### ✅ Example:

```css
body {
  font-family: 'Segoe UI', sans-serif;
  font-size: 16px;
  font-weight: 400;
}
```

---

## 🌈 Color Styling in CSS

Color makes your content **vibrant** and **accessible**.

### 🔹 CSS Color Properties:

| Property           | Description           |
| ------------------ | --------------------- |
| `color`            | Text color            |
| `background-color` | Background fill color |
| `border-color`     | Color of borders      |

### 🎨 Ways to Define Colors:

| Format      | Example                     |
| ----------- | --------------------------- |
| Named color | `red`, `blue`               |
| Hex code    | `#ff5733`                   |
| RGB         | `rgb(255,0,0)`              |
| RGBA        | `rgba(255,0,0,0.5)`         |
| HSL         | `hsl(120, 100%, 50%)`       |
| HSLA        | `hsla(120, 100%, 50%, 0.3)` |

### ✅ Example:

```css
h1 {
  color: #333;
  background-color: #f0f0f0;
}
```

---

## ❓ Interview Questions

### 1. What is `font-family` in CSS?

**Answer:** It defines the typeface of the text. You can specify multiple fonts as a fallback list.

---

### 2. How can you apply custom fonts in CSS?

**Answer:** Use `@font-face` to load external fonts or use Google Fonts by importing them in your CSS.

---

### 3. What are the different ways to apply color in CSS?

**Answer:** Colors can be defined using named colors, hex codes, RGB, RGBA, HSL, or HSLA formats.

---

### 4. What’s the difference between `font-weight: bold;` and `font-weight: 700;`?

**Answer:** Both are valid. `bold` is a keyword, and `700` is its numeric equivalent.

---

## 🧠 Dev Tips

* Use web-safe or system fonts for performance and fallback
* Use `rem` or `em` for font-sizes to maintain scalability
* Keep good color contrast for readability and accessibility
* Prefer variables (`--primary-color`) when working with consistent color themes

---
