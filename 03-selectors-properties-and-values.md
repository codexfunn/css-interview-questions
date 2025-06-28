# 🎯 CSS: Selectors, Properties, and Values

---

## 📌 What are Selectors, Properties, and Values in CSS?

When you write CSS, you're essentially giving rules to HTML elements using this format:

```css
selector {
  property: value;
}
```

Let’s break down what each part means:

---

## 🏷️ 1. **Selectors**

Selectors define **which HTML elements** you want to style.

### 🔹 Types of Selectors:

| Type               | Example            | What It Selects               |
| ------------------ | ------------------ | ----------------------------- |
| Element Selector   | `p`                | All `<p>` tags                |
| Class Selector     | `.box`             | All elements with class="box" |
| ID Selector        | `#header`          | The element with id="header"  |
| Grouping Selector  | `h1, p, div`       | All h1, p, and div elements   |
| Universal Selector | `*`                | All elements                  |
| Attribute Selector | `input[type=text]` | All text input fields         |
| Pseudo-class       | `a:hover`          | Anchor tags when hovered      |
| Pseudo-element     | `p::first-line`    | First line of every paragraph |

> Use selectors to **target the right elements** in your HTML.

---

## ⚙️ 2. **Properties**

Properties define **what aspect of the element** you want to style.

### 🔹 Common CSS Properties:

| Property           | Description               |
| ------------------ | ------------------------- |
| `color`            | Text color                |
| `background`       | Background color/image    |
| `font-size`        | Size of text              |
| `margin`           | Space outside the element |
| `padding`          | Space inside the element  |
| `border`           | Adds borders              |
| `width` / `height` | Size of the element       |
| `display`          | Controls layout behavior  |
| `position`         | Sets element position     |

> Properties are **the things you're changing**.

---

## 🎨 3. **Values**

Values define **how much or what kind** of style should be applied for each property.

### 🔹 Example:

```css
p {
  color: red;
  font-size: 16px;
  margin: 20px;
}
```

Here:

* `color` = property, `red` = value
* `font-size` = property, `16px` = value
* `margin` = property, `20px` = value

> Values vary depending on the property — they could be **keywords**, **colors**, **length units**, **percentages**, etc.

---

## ❓ Interview Questions

### 1. What are the three parts of a CSS rule?

**Answer:**
**Selector**, **Property**, and **Value**. The selector targets the HTML element; the property defines what to style; the value sets how to style it.

---

### 2. What is the difference between class and ID selectors?

**Answer:**

* Class selectors (`.class`) target multiple elements
* ID selectors (`#id`) target a single, unique element

---

### 3. What kind of values can CSS properties accept?

**Answer:**

* Keywords (`auto`, `inherit`, `center`)
* Colors (`red`, `#ff0000`, `rgb(255,0,0)`)
* Lengths (`px`, `em`, `%`, `vh`, `rem`)
* URLs (`url(image.jpg)`, used in background or content)

---

## 🧠 Dev Tips

* Use **classes** for reusable styling across multiple elements
* IDs are best for **unique elements** (like modals or navbars)
* Always write **meaningful, readable selectors** to avoid confusion
* Keep your values consistent with a defined scale (like spacing, colors, fonts)

---
