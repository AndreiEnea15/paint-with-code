# 🎨 Paint with Code: Learn JavaScript Online for Kids

**Turn code into art!** Paint with Code is an interactive, web-based platform designed to introduce young programmers (or beginners of any age) to **JavaScript** through visual creation. Type commands in the live editor and instantly see your drawings come to life on the canvas.

---

## 🔗 Live Application

You can try the fully functional editor right now:

➡️ **[Launch the Paint with Code Web App Here](https://informaticasite.com/painting-with-code/index.html)** 

---

## ✨ Features

* **Interactive Editor:** A text-based editor where students write real JavaScript code.
* **Instant Feedback:** Code runs immediately, clearing the canvas and redrawing shapes with every input change.
* **Canvas Drawing:** Uses the HTML5 Canvas API for visual output.
* **Custom Functions:** Includes a simplified library of drawing commands (`drawCircle()`, `drawSquare()`, etc.) to focus on core programming concepts like parameters and function calls.
* **Syntax Highlighting:** Integrated using `highlight.js` for improved readability.
* **Beginner-Friendly:** A low-barrier-to-entry tool perfect for exploring concepts like **loops** (`for` and `while`), **variables**, and **functions** through creative experimentation.

---

## 🚀 Getting Started

This project is a single-page static web application. You don't need any complex build tools to run it.

### **Usage**

1.  Visit the **[Live Application Link](https://informaticasite.com/painting-with-code/index.html)**.
2.  Start typing JavaScript code in the text editor.
3.  The canvas will instantly update to show your creation!

### **Basic Drawing Command Example**

The built-in function `drawCircle` is available in the editor's scope:

```javascript
function drawCircle(x, y, radius, color) {
    // ... internal Canvas drawing code ...
}

// Draw a blue circle at coordinates (300, 300) with a radius of 100
drawCircle(300, 300, 100, "blue");
