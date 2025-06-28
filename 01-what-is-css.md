# 🎨 What is CSS?

---

## 📌 Definition:

**CSS (Cascading Style Sheets)** is a **style sheet language** used to describe the **presentation and design** of an HTML document.

In simple terms:

> HTML is the **structure**, CSS is the **style**.

With CSS, you control how elements **look** — their colors, layout, fonts, spacing, animation, and more.

---

## 🎯 Why Use CSS?

* Separates **content** (HTML) from **design** (CSS)
* Makes your website look **modern, clean, and responsive**
* Allows consistent styling across multiple pages
* Easier to maintain and update

---

## 🧱 Syntax:

```css
selector {
  property: value;
}
```

### ✅ Example:

```css
h1 {
  color: blue;
  font-size: 24px;
}
```

This styles all `<h1>` elements with blue color and 24px font size.

---

## 🔌 How to Add CSS to HTML?

### 1. Inline CSS

```html
<h1 style="color:red;">Hello</h1>
```

**Used for quick, one-time styling. Not recommended for big projects.**

### 2. Internal CSS

```html
<style>
  p { color: green; }
</style>
```

Placed inside the `<head>` tag for styling a single page.

### 3. External CSS

```html
<link rel="stylesheet" href="style.css">
```

Links to a separate `.css` file. **Most scalable and preferred.**

---

## 💡 What Does “Cascading” Mean?

“Cascading” refers to the **priority system** CSS uses to decide which style applies when multiple rules target the same element.

### CSS Applies Rules Based on:

1. **Inline > Internal > External** (Priority)
2. **Specificity** (ID > Class > Element)
3. **Source order** (last rule wins if equal specificity)

---

## ❓ Interview Questions

### 1. What is CSS?

**Answer:**
CSS is a language used to control the style and layout of HTML content. It helps define how HTML elements look on a webpage.

---

### 2. What are the ways to apply CSS?

**Answer:**

* Inline CSS (inside elements)
* Internal CSS (inside `<style>` tag)
* External CSS (linked `.css` file)

---

### 3. Why is it called “Cascading” Style Sheets?

**Answer:**
Because when multiple styles apply, CSS uses a **priority system** to decide which rule is used — this system is called the **cascade**.

---

### 4. Why separate CSS from HTML?

**Answer:**
To keep structure (HTML) and style (CSS) **modular, reusable, and easier to manage**.

---

## 🧠 Dev Tips

* Always prefer **external CSS** for better maintainability
* Avoid inline styles in production code
* Use classes for reusable styles, IDs for unique elements
* Use semantic HTML + clean CSS for better SEO and accessibility

---

