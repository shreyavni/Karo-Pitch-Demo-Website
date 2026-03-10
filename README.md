# Karo Pitch - Startup Landing Page 🚀

An investor-focused, highly interactive, and ultra-modern landing page built for **"Karo Pitch"**—a platform bridging the gap between ambitious startup founders and India's top-tier investors.

This project showcases high-end animations typical of award-winning Silicon Valley websites, engineered for high performance and smooth user experience.

---

## ✨ Key Features & Animations

This website is packed with cutting-edge UI/UX interactions:

* **🎭 Curtain Reveal:** A cinematic split-screen opening animation that greets users on page load.
* **🧲 Custom Magnetic Cursor:** A custom dot and ring cursor that acts like a magnet when hovering over interactive elements (buttons, links).
* **🖐️ "Touchable" Words:** Critical keywords pop out, tilt, and glow with a neon shadow upon hover.
* **🛸 3D Mouse Parallax:** The hero text smoothly rotates in 3D space, tracking real-time mouse movements.
* **🎫 Infinite Marquee:** A continuous, seamless scrolling text ticker highlighting key platform benefits.
* **🔢 Milestone Counters:** Dynamic numbers that rapidly count up to target values when scrolled into view.
* **💻 Hacker Scramble Reveal:** Headings creatively "decode" from random symbols (`#%*!@`) into readable text during scroll.
* **🫧 Background Parallax:** Floating neon blobs move at independent speeds to create a deep 3D atmospheric effect.
* **📱 Fully Responsive:** Pixel-perfect layout across desktops, tablets, and mobile (with graceful degradation for touch devices).

---

## 🛠️ Technology Stack

* **HTML5:** Semantic and clean document structure.
* **CSS3:** Custom properties (variables), Flexbox, CSS Grid, Glassmorphism, and complex keyframes.
* **JavaScript (ES6):** Logic for custom cursors, 3D mathematics, and coordination.
* **GSAP (GreenSock):** The core engine for smooth, industry-standard animations.
* **GSAP ScrollTrigger:** Plugin to synchronize animations with scroll progress.
* **Typography:** Outfit (Headings) & Plus Jakarta Sans (Body).

---

## 🚀 How to Run Locally

No build tools or NPM packages are required. This is a lightweight, high-performance vanilla implementation.

1.  **Clone** or download this repository to your local machine.
2.  Ensure you have the `index.html`, `style.css`, and `script.js` files in the same directory.
3.  **Double-click** `index.html` to launch it in any modern web browser (Chrome, Edge, Safari, Firefox).
4.  Interact and scroll to experience the full animation suite!

---

## 🎨 Customization Guide

### 1. Changing the Theme Color
The primary theme color is controlled via a CSS variable. Update the `--brand-red` variable in the `:root` block:

```css
:root {
    --brand-red: #45db7d; /* Neon Green Example */
}
```
### 2. Modifying the Hacker Scramble Text
To change the "decoding" effect characters, locate the chars constant in the JavaScript file:

```javascript
const chars = "01010101"; // For a binary matrix effect
// OR
const chars = "ABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789!@#$%^&*";
```
### 3. Updating the Counters
Adjust the milestone numbers directly in the HTML using the data-target attribute:

```html
<span class="counter" data-target="1000">0</span>
```

---

## 📄 License

This project is open-source and intended for demo/educational purposes. Feel free to use, modify, and adapt the code for your own startup or portfolio projects!

---

### *Built with ❤️ for the Startup Ecosystem.*
