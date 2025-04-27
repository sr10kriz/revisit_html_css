This repository contains a high-level overview of important **HTML** and **CSS** concepts commonly asked in technical interviews. It serves as a quick reference and revision guide for frontend developers and interview candidates.

# 💡 HTML & CSS Interview Preparation Guide

---

## ✅ Covered Topics (High-Level)

### 🧱 HTML Structure & Basics

- **DOCTYPE declaration**
- Core HTML tags: `<html>`, `<head>`, `<body>`

### 🧩 Tags vs Elements

- **Tags**: Syntax like `<p>`, `<a>`
- **Elements**: Tags + content + closing tag

### 🔲 Block-level vs Inline Elements

- **Block**: Takes full width (`<div>`, `<section>`)
- **Inline**: Flows with text (`<span>`, `<a>`)

### 🧼 Self-Closing Tags

- Tags that don't need a closing tag (`<br>`, `<hr>`, `<img>`, `<input>`)

### 📝 Lists

- **Ordered List** (`<ol>`)
- **Unordered List** (`<ul>`)
- **Definition List** (`<dl>`, `<dt>`, `<dd>`)

### 🔗 Links & 📷 Images

- `<a href="...">` with attributes like `target`, `rel`
- `<img src="..." alt="...">` with lazy loading and accessibility

### 🚀 Script Loading

- `defer` and `async` attributes for efficient script handling

### 📋 Forms & Inputs

- `<form>` tag and its attributes: `action`, `method`, `target`, `enctype`
- HTTP methods: `GET`, `POST`
- Input types: `text`, `email`, `radio`, `checkbox`, `file`, `submit`, etc.
- Input attributes: `required`, `maxlength`, `pattern`, etc.

### 🧠 Event Handling

- HTML form events: `onsubmit`, `onchange`, `oninput`, etc.
- JavaScript functions:
  - `preventDefault()` – stops default behavior (e.g., form submission)
  - `stopPropagation()` – prevents event bubbling

### 📊 Tables

- `<table>`, `<thead>`, `<tbody>`, `<tfoot>`, `<tr>`, `<td>`, `<th>`
- Attributes like `colspan`, `rowspan`

### 📖 Semantic HTML

- Tags that describe meaning: `<article>`, `<nav>`, `<main>`, `<footer>`, etc.
- Improves accessibility, SEO, and screen reader compatibility

### 🆚 HTML vs HTML5

- HTML5 adds:
  - Semantic tags
  - Multimedia support
  - New input types
  - APIs: Canvas, Web Storage

### 📽️ Media Elements

- `<audio>`, `<video>` with controls, autoplay, muted, loop attributes

### 💾 Web Storage

- `localStorage` and `sessionStorage` for storing key-value pairs in the browser

### 🎨 Canvas API

- `<canvas>` for 2D drawing via JavaScript

### 🍪 Cookies vs Cache

- **Cookies**: Small data stored client-side, sent to server with requests
- **Cache**: Browser storage for static files (HTML, CSS, JS) to improve load speed

### ♿ Accessibility & Screen Readers

- Use of semantic tags and ARIA roles for screen reader compatibility

### DOM & BOM

- How DOM differ from BOM

---

## ✅ CSS Interview Preparation Guide

### 🔑 Key Concepts in CSS

- **CSS Basics**: Understanding of the `selectors`, `properties`, and `values`
- **CSS Box Model**: Content, padding, border, and margin
- **Positioning & Layout**: `static`, `relative`, `absolute`, `fixed`, `sticky`
- **Flexbox**: Aligning items in rows/columns
- **CSS Grid**: 2D layout system for responsive design
- **Responsive Design**: Using media queries to design for multiple screen sizes
- **Transitions & Animations**: Adding interactivity to elements
- **Colors & Backgrounds**: Use of color properties and backgrounds in CSS

### 🎨 Selectors

- **Basic Selectors**: `element`, `id`, `class`, `universal (*)`
- **Combinators**: Descendant (`A B`), Child (`A > B`), Adjacent sibling (`A + B`), General sibling (`A ~ B`)
- **Attribute Selectors**: `[attr="value"]`, `[attr^="value"]`, `[attr*="value"]`
- **Pseudo-Classes**: `:hover`, `:active`, `:focus`, `:nth-child()`
- **Pseudo-Elements**: `::before`, `::after`

### 📦 Box Model

- **Content Box**: Only the content area.
- **Border Box**: Includes padding and border in the element's width and height.

### 🧭 Positioning & Layout

- **Positioning Types**: `static`, `relative`, `absolute`, `fixed`, `sticky`
- **Z-Index**: Controls stacking order of positioned elements
- **Flexbox**: Flex containers and items for 1D layout
- **CSS Grid**: Advanced 2D layout model
- **Float**: Floating elements for text wrapping

### 🌐 Media Queries & Responsive Design

- **Media Queries**: `@media` rule to apply styles conditionally based on viewport size
- **Common Breakpoints**: Example breakpoints for different screen sizes (`320px`, `768px`, `1024px`)

### 🔄 Transitions & Animations

- **Transitions**: Smoothly change property values over time
- **Animations**: Keyframes to create more complex animations

### 🎨 Colors & Backgrounds

- **Color Methods**: Hex, RGB, RGBA, HSL
- **Background**: `background-color`, `background-image`, `background-size`

### 🛠️ Preprocessors

- **SASS** vs **SCSS**: Two syntax styles of the SASS preprocessor
- **Variables**: Storing reusable values
- **Nesting**: Nesting selectors for better structure
- **Mixins & Functions**: Reusable code blocks and logic

### 📚 Important CSS Concepts

1. **Cascading & Specificity**:

   - **Cascade**: Determines how styles are applied in the event of conflicts.
   - **Specificity**: More specific selectors override less specific ones. It's calculated by counting the number of IDs, classes, and elements in a selector.
     - Example: `#id` > `.class` > `div`

2. **Inheritance**:

   - Some CSS properties are inherited from parent elements to children (`color`, `font-family`, etc.).
   - Use `inherit`, `initial`, `unset`, and `revert` for controlling inheritance behavior.

3. **Reset CSS vs Normalize CSS**:

   - **Reset CSS**: Resets all default browser styles to create a consistent baseline across browsers.
   - **Normalize CSS**: Preserves useful default styling while standardizing how elements are displayed across browsers.

4. **Specificity Calculation**:

   - ID selectors (`#id`) have higher specificity than class selectors (`.class`), which in turn have higher specificity than element selectors (`div`).
   - Example: `div .class #id` will apply styles to `#id`.

5. **Shorthand Properties**:
   - Using shorthand properties like `margin: 10px 5px;` instead of `margin-top: 10px; margin-right: 5px;`
   - Helps keep the CSS concise and readable.

---

## 📚 Purpose

Use this guide as a revision sheet before HTML, CSS technical rounds or as a learning base for frontend development.

---

## 👨‍💻 Maintained By

**Sridharakrishnan R**  
https://github.com/sr10kriz

---
