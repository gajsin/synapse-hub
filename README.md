# ⚡ Synapse Hub

**Premium Landing Page with ROI Calculator & AI Chat**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Vanilla JS](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![GSAP](https://img.shields.io/badge/GSAP-Animations-88CE02?style=flat-square)
![Vite](https://img.shields.io/badge/Vite-Bundler-646CFF?style=flat-square&logo=vite&logoColor=white)

> High-conversion B2B landing page for an AI agency. Features complex scroll-trigger animations, an interactive real-time ROI calculator, and a custom floating chat widget interface.

---

## 📸 Overview

![Synapse Hub Cover](screenshot.jpg)

---

## ✨ Key Features

### 🎬 Advanced GSAP Animations
Silky smooth 60fps animations tied to scroll percentage (ScrollTrigger). Includes parallax backgrounds, staggered text reveals, and complex SVG path drawing animations that bring the page to life.

### 🧮 Interactive ROI Calculator
A dynamic Vue-like reactive widget built with Vanilla JS. Users can move sliders for "Current Metrics" and instantly see projected ROI, cost savings, and timeline when using the automated AI solution.

### 💬 AI Chat Interface Simulation
A custom floating chat UI component that simulates real-time conversational AI. Includes typing indicators, natural delays, and dynamic response rendering to demonstrate the capabilities of the agency's chatbots.

### 📱 Responsive Design Matrix
Pixel-perfect translation from Figma. Uses CSS Grid, Flexbox, and `clamp()` for fluid typography that scales beautifully from ultra-wide 4K monitors down to 320px mobile screens.

### ⚡ Performance Optimization
Achieves 98/100 Google Lighthouse score. Optimizations include: lazy-loading for heavy assets, WebP image formats, deferred non-critical JS, and pre-loading critical fonts.

---

## 🏗️ Architecture

```
┌─────────────────────────────────────────────────┐
│                   UI Layer                       │
│  Semantic HTML5 · BEM Methodology               │
│  CSS Variables (Custom Props) · CSS Grid      │
├─────────────────────────────────────────────────┤
│                Interaction Layer                  │
│  Vanilla JavaScript (ES6 Modules)                │
│  GSAP & ScrollTrigger Plugins                    │
├─────────────────────────────────────────────────┤
│                 Widgets & Core                   │
│  Reactive ROI Calculator · Chat Widget Simulator │
│  Intersection Observers · Dynamic Loaders        │
└─────────────────────────────────────────────────┘
```

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Markup & Style** | HTML5, CSS3, SCSS (Variables, Mixins) |
| **Logic** | Vanilla JavaScript (ES Module syntax) |
| **Animations** | GSAP (GreenSock), ScrollTrigger |
| **Build Tool** | Vite |
| **Icons & Assets** | Optimized SVGs, WebP |

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/gajsin/synapse-hub.git
   cd synapse-hub
   ```
2. Start a local server (or simply open `index.html`):
   ```bash
   npx serve .
   ```

---

## 📄 License

MIT © 2026 [gajsin](https://github.com/gajsin)
