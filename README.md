# Day 10: Dynamic Stats Counter 📊

Part of my **30 Days of JavaScript** challenge. This project features an animated counter that increments numbers from zero to a specific target value, perfect for "Our Achievements" or "Company Stats" sections.

🔗 **Live Demo:** [View Project](https://animate-counter-js-ferdous.netlify.app/)

## 🚀 Features
- **Dynamic Increments:** Uses JavaScript recursion to calculate and display real-time counting.
- **Data-Driven Logic:** Targets are pulled directly from `data-target` HTML attributes.
- **Polished UI:** Features a smooth CSS entry animation (fade & slide) and a responsive grid layout.
- **Glassmorphism Design:** A stylish semi-transparent overlay against a vibrant linear gradient.

## 🛠️ Tech Stack
- **HTML5:** Semantic markup and custom data attributes.
- **CSS3:** Flexbox, Grid, and `@keyframes` animations.
- **JavaScript:** DOM selection, arrow functions, and asynchronous timing.

## 💡 Key Concept: The Math
The animation speed is consistent regardless of the target number because of this logic:
$Step = \frac{Target}{Speed}$

This ensures that a counter going to 100 and a counter going to 10,000 finish at roughly the same time.
