---
layout: post
title: "Want to learn web design but can’t understand CSS? In this post, understand CSS basics, syntax, properties, and real examples in simple language"
date: 2026-01-08 09:00:00 +0530
thumbnail: https://raw.githubusercontent.com/soumitra88875/tools-browser-blog-image/main/learn-css/image2.png
---

## 🧱 3️⃣ Basic concepts of CSS

## ⭐ (1) CSS Syntax

Every CSS rule has three parts:
```html
selector {  
property: value;  
}
```

Example:
```html
p {  
color: blue;  
font-size: 18px;  
}
```
Here

- p is the selector (which HTML element will receive the style)
- color and font-size are properties
- blue and 18px are values

## ⭐ (2) Selector

CSS defines which HTML elements styles will be applied to.

🔹 Element Selector — h1, p etc.  
🔹 Class Selector — .menu, .btn  
🔹 ID Selector — #header  
🔹 Attribute Selector, Pseudo-class etc.

## ⭐ (3) Three ways to add CSS

CSS code can be added to HTML in three ways:

**Inline CSS**  
Using the style attribute inside an HTML tag.
```html
<p style="color: red;">Hello World!</p>
```
**Internal CSS**  
Using the <style> tag inside the HTML <head>.
```html
<style> h1 { color: green; } </style>
```
**External CSS**  
Linking an external .css file.
```html
<link rel="stylesheet" href="style.css">
```
External CSS is considered good practice because the code remains separate and clean.

## 🎨 4️⃣ Common CSS Properties

**Colors and Background**
```html
body {  
background-color: lightblue;  
}  
p {  
color: #333;  
}
```
**Font**
```html
h1 {  
font-family: Arial, sans-serif;  
font-size: 32px;  
}
```
**Margin and Padding (spacing)**
```html
div {  
margin: 10px;  
padding: 20px;  
}
```
**Border**
```html
img {  
border: 2px solid black;  
}
```
These properties control the **appearance, spacing, and shape** of HTML elements.

## 📦 5️⃣ CSS Box Model

Each element behaves like a **box**, which consists of:

📍 Content  
📍 Padding  
📍 Border  
📍 Margin  

Understanding this makes spacing and layout much easier.

## 📱 6️⃣ Responsive Design (mobile and all devices)

Nowadays, websites need to look good on mobile and tablets.  
Using media queries, CSS applies different styles for different screen sizes:
```html
@media (max-width: 600px) {  
body {  
background: lightyellow;  
}  
}
```
This way, the same website looks good on different devices.

## 🧠 7️⃣ What can be done with CSS?

✅ Text styling – colors, fonts, sizes  
✅ Layout control – Flexbox, Grid  
✅ Animation and transition  
✅ Responsive design  
✅ UI elements like menus, cards, buttons  

All of these are possible using CSS.

## 📌 8️⃣ Tips for learning CSS

🔹 Always use a Code Editor  
🔹 Practice with live examples  
🔹 Test CSS effects using browser Developer Tools  
🔹 Build small projects  

## ✨ Small Example
```html
HTML + CSS
<!DOCTYPE html>  
<html>  
<head>  
<link rel="stylesheet" href="style.css">  
</head>  
<body>  
<h1>My Website</h1>  
<p>Welcome to my web page!</p>  
</body>  
</html>
```
style.css:

```html
body {  
background: #f0f0f0;  
}  
h1 {  
color: navy;  
}  
p {  
font-size: 18px;  
color: #444;  
}
```
When you run this in a browser, you will see that the HTML text is nicely styled.

## 🧾 Conclusion

Learning CSS is a fundamental skill of web design and development.  
HTML provides the structure of a website, and CSS makes that structure **alive and beautiful**.
