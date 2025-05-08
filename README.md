# 🎨 Background Color Change Project

*This is my first simple JavaScript project!*

This project demonstrates how to change the background color of a webpage using buttons. It's great for beginners learning DOM manipulation and user interaction with JavaScript.

---

## ✨ Features

- 🎯 Change background color using buttons
- 🖼️ Add images and change them dynamically
- 💡 Useful for making your UI more interactive
- 🔥 Simple and beginner-friendly JavaScript code

---

## 🔗 Live Demo

[Click Here to View Live](https://github.com/ajitmathpati/javascriptproject.git)

---

## 📸 Screenshot

![Background Color Change Preview](./backgroundcolorchange.jpg)

> Make sure the image `backgroundcolorchange.jpg` is in the same folder as this README file.

---

## 💡 Solution (JavaScript Code Example)

```javascript
let redbtn = document.querySelector('.redbtn');
let greenbtn = document.querySelector('.greenbtn');
let yellowbtn = document.querySelector('.yellowbtn');

redbtn.addEventListener('click', () => {
    document.body.style.backgroundColor = "red";
});

greenbtn.addEventListener('click', () => {
    document.body.style.backgroundColor = "green";
});

yellowbtn.addEventListener('click', () => {
    document.body.style.backgroundColor = "yellow";
});
```
---
🛠️ Technologies Used
✅ JavaScript Functions

✅ addEventListener()

✅ Click Events

✅ Image Tag (<img>) and Handling
---
📚 Learning Points
DOM selection with querySelector()

Adding event listeners to elements

Modifying CSS with JavaScript

Structuring beginner-friendly web projects
---

🙌 Contribution
This is an open beginner project. Feel free to clone, improve, or suggest changes!