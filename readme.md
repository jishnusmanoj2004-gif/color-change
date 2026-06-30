## tailwind css project


# Image Hover Effect

A simple HTML, Tailwind CSS, and JavaScript project that changes the button background color when the mouse hovers over it.

## 📌 Features

- Displays an image inside a button.
- Changes the button background color to **blue** on mouse hover.
- Changes the background color back to **red** when the mouse leaves.
- Uses JavaScript event listeners (`mouseover` and `mouseout`).
- Styled using Tailwind CSS.

[live@](https://jishnusmanoj2004-gif.github.io/color-change/)

[ss2](./s1.png)
[ss2](./s2.png)

## 📂 Project Structure

```
project-folder/
│── index.html
│── scripts.js        (optional)
│── toyota-supra-5k-2025-sr.jpg
│── README.md
```

## 🚀 Technologies Used

- HTML5
- Tailwind CSS (CDN)
- JavaScript (DOM Manipulation)

## 📖 How It Works

1. The webpage displays a button containing an image.
2. When the mouse pointer enters the button:
   - The button background changes to **blue**.
3. When the mouse pointer leaves:
   - The button background changes back to **red**.

## 💻 JavaScript Used

```javascript
document.getElementById("bg").addEventListener("mouseover", function () {
    this.style.backgroundColor = "blue";
});

document.getElementById("bg").addEventListener("mouseout", function () {
    this.style.backgroundColor = "red";
});
```

## ▶️ How to Run

1. Download or clone the project.
2. Place the image (`toyota-supra-5k-2025-sr.jpg`) in the project folder.
3. Open `index.html` in any modern web browser.
4. Hover over the button to see the background color change.

## 📸 Output

- **Default:** Red background
- **On Hover:** Blue background
- **On Mouse Leave:** Red background

## 🔧 Future Improvements

- Add smooth color transition effects.
- Scale the image slightly on hover.
- Add shadow and animation effects.
- Make the layout fully responsive.

## 👨‍💻 Author

**Jishnu Manoj**

---

**Learning Concepts:**
- HTML Elements
- Tailwind CSS
- JavaScript DOM
- Event Listeners
- Mouse Events (`mouseover`, `mouseout`)
- Inline Style Manipulation