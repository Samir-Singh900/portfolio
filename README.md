# Samir Singh | Portfolio '25 🚀

![Portfolio Preview](preview.png)

> **"I don't just write code. I engineer logic."**

A high-performance, dark-themed personal portfolio website featuring interactive 3D elements, architectural design, and smooth animations. This project demonstrates a mastery of frontend technologies, featuring a custom **CSS-only 3D Robot** that tracks the user's cursor.

[![Live Demo](https://img.shields.io/badge/demo-live%20view-gold?style=for-the-badge&logo=vercel)](https://samir-singh900.github.io/portfolio/)

## ✨ Key Features

- **🤖 Interactive 3D Robot:** A custom-coded CSS/JS robot (TV-Head style) that tracks mouse movement in 3D space with parallax effects.
- **🏗️ Architectural Typography:** Massive "SAMIR" text layer integrated behind the robot for a depth-rich footer.
- **🎨 Luxury Aesthetic:** "Black & Gold" theme with architectural grid overlays and smooth reveal animations.
- **⚡ Zero-Build Setup:** Uses Tailwind CSS via CDN for instant editing without Node.js dependencies.
- **🧊 Spline 3D Integration:** Embedded 3D abstract scenes using `@splinetool/viewer`.
- **🖱️ Custom Cursor:** Reactive custom cursor with blend-mode effects (Desktop only).

## 🛠️ Tech Stack

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Spline](https://img.shields.io/badge/Spline-3D-purple?style=for-the-badge)

## 📂 Project Structure

```text
/
├── index.html          # Main application file (All CSS/JS included)
├── preview.png         # Screenshot for README (Upload your own!)
└── README.md           # Documentation

```

## 🚀 Getting Started

Since this project uses the CDN version of Tailwind, you don't need `npm` or complex build steps.

1. **Clone the repository:**
```bash
git clone [https://github.com/Samir-Singh900/portfolio.git](https://github.com/Samir-Singh900/portfolio.git)

```


2. **Open the project:**
Simply open `index.html` in any modern browser.
*Recommendation:* Use the **Live Server** extension in VS Code for the best experience.

## 🤖 The Robot Logic

The robot located at the footer is built entirely using CSS shapes (no images) and JavaScript for the `transform: rotate3d` logic.

```javascript
// Logic snippet for 3D Head Tracking
const rotateY = (x - centerX) / 25; 
const rotateX = (centerY - y) / 25;
robotHead.style.transform = `rotateY(${clampedY}deg) rotateX(${clampedX}deg)`;

```

## 🎨 Customization Guide

### 1. Changing the Big Name

To change the massive text behind the robot, search for the class `.footer-big-text` in `index.html`:

```html
<div class="footer-big-text">SAMIR</div> 

```

### 2. Updating Links

Update the `href` attributes in the `<nav>` and Footer sections to point to your specific profiles:

* LinkedIn
* GitHub
* WhatsApp / Email

### 3. Theme Colors

The theme is controlled via the Tailwind config script in the `<head>`:

```javascript
colors: {
    black: '#050505',
    gold: '#D4AF37', // Change this hex code to change the accent color
}

```

## 📄 License

This project is open source and available under the [MIT License](https://www.google.com/search?q=LICENSE).

---

<p align="center">
Developed by <a href="https://www.google.com/search?q=https://github.com/Samir-Singh900">Samir Singh</a> © 2025
</p>

```

Would you like me to help you modify any specific section of the website content next?

```
