# 📏 CSS Units: px, em, rem, % and More

---

## 📌 What Are CSS Units?

CSS **units** determine the **size**, **position**, and **spacing** of elements. Units are attached to values like font-size, width, margin, padding, etc.

There are two types of units:

1. **Absolute Units** (fixed)
2. **Relative Units** (based on other elements)

---

## 🔸 Absolute Units

These units do **not change** based on screen size or parent elements.

| Unit | Description          |
| ---- | -------------------- |
| `px` | Pixels (most common) |
| `pt` | Points (print media) |
| `cm` | Centimeters          |
| `mm` | Millimeters          |
| `in` | Inches               |

> 🔧 `px` is the most used absolute unit for screens.

---

## 🔹 Relative Units

These units **scale** depending on the parent element or root element.

| Unit   | Relative To                      | Description                              |
| ------ | -------------------------------- | ---------------------------------------- |
| `%`    | Parent element                   | Percentage of the parent’s value         |
| `em`   | The element's **own** font-size  | 2em = 2 × current element's font size    |
| `rem`  | The **root** element's font-size | 1rem = 1 × root font size (usually 16px) |
| `vw`   | 1% of the **viewport width**     | Used for responsive design               |
| `vh`   | 1% of the **viewport height**    | Used for full-screen elements            |
| `vmin` | The smaller of vw or vh          | Useful for aspect ratio control          |
| `vmax` | The larger of vw or vh           | Useful for flexible containers           |

---

## 🧪 Example:

```css
html {
  font-size: 16px; /* base size */
}

h1 {
  font-size: 2rem; /* 32px */
}

p {
  font-size: 1.5em; /* relative to parent's font-size */
}
```

---

## ❓ Interview Questions

### 1. What is the difference between `em` and `rem`?

**Answer:**

* `em` is relative to the **current element’s** font-size.
* `rem` is relative to the **root element’s** font-size.

---

### 2. When should you use `rem` instead of `px`?

**Answer:**
Use `rem` for **scalable and accessible** design, especially when users change browser font size settings.

---

### 3. What is `vw` and `vh` in CSS?

**Answer:**

* `vw` = 1% of the **viewport width**
* `vh` = 1% of the **viewport height**
  Used in **responsive** and **full-screen** layouts.

---

## 🧠 Dev Tips

* Use `rem` for fonts for accessibility and consistency
* Use `em` for padding/margin relative to font size
* Combine `vh`, `vw`, and `%` for responsive layouts
* Avoid using `px` for text in responsive designs

---

