# 🧮 CSS Depends on 4 Factors (Cascade Priority)

---

## 📌 What Determines Which CSS Rule is Applied?

When multiple CSS rules target the same element, the **final style applied** is determined by these 4 key factors:

---

## 🔢 1. Source Order (Last Rule Wins)

If two rules have **equal specificity**, the **rule that comes later** in the code wins.

```css
p { color: blue; }
p { color: red; } /* Red wins */
```

---

## 🧮 2. Specificity

Specificity is a scoring system based on how detailed a selector is:

| Selector Type             | Specificity Score |
| ------------------------- | ----------------- |
| Inline style (`style=""`) | 1000              |
| ID selector (`#id`)       | 100               |
| Class, pseudo-class       | 10                |
| Element selector          | 1                 |

> The higher the specificity, the more weight the rule has.

---

## 🚨 3. `!important`

The `!important` keyword **overrides all other rules**, even more specific ones — unless another `!important` is also used with higher specificity.

```css
p { color: green !important; } /* This wins */
```

> Use with caution. Overusing `!important` can make debugging very difficult.

---

## 🧬 4. Inheritance

Some CSS properties are **inherited by default** from parent to child, like:

* `color`
* `font-family`
* `line-height`
* `visibility`

Others like `margin`, `padding`, `border`, etc. **are not inherited**.

> You can force inheritance with `inherit`, or stop it with `initial` or `unset`.

---

## ❓ Interview Question:

### What are the 4 factors that affect which CSS rule is applied?

**Answer:**

1. **Source Order** – later styles override earlier ones
2. **Specificity** – more specific selectors have higher weight
3. **`!important`** – overrides all other rules
4. **Inheritance** – some styles pass from parent to child elements

---

## 🧠 Dev Tips

* Avoid `!important` unless absolutely necessary
* Keep specificity low and consistent to avoid battles
* Use dev tools to inspect computed styles and understand cascade

---

