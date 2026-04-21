# Vanilla CSS Glassmorphism 🪟✨

![CSS Size](https://img.shields.io/badge/CSS-Zero_Dependencies-blue?style=flat-square)
![License](https://img.shields.io/github/license/RanaAhmar/vanilla-css-glassmorphism?style=flat-square)
![Design Trend](https://img.shields.io/badge/Design-Glassmorphism-ff69b4?style=flat-square)

**A scalable, premium vanilla CSS module providing instantly beautiful glassmorphism design tokens and utility classes.**

Glassmorphism is a modern UI design trend featuring semi-transparent backgrounds, subtle borders, and background blur to create a frosted glass effect. This repository provides an ultra-lightweight, drop-in CSS file that you can use on any project—no frameworks required.

## 🌟 Key Features
- **Zero Dependencies**: Pure CSS. No preprocessors, no JavaScript.
- **Customizable via Variables**: Powered completely by CSS custom properties (variables) so you can tweak the blur, opacity, and color in one place.
- **Dark & Light Mode Support**: Instantly adapts depending on the underlying variable configurations.
- **Hardware Accelerated**: Uses CSS filters optimized for modern browsers to ensure silky smooth 60fps scrolling.

## 📚 Table of Contents
- [Installation](#-installation)
- [How to Use](#-how-to-use)
- [Available Classes](#-available-classes)
- [Browser Support](#-browser-support)
- [License](#-license)

## 📦 Installation
Simply download `glassmorphism.css` and link it in the head of your HTML document:

```html
<link rel="stylesheet" href="path/to/glassmorphism.css">
```

## 🚀 How to Use

To use it, just add the `.glass` class to any container:

```html
<div class="glass glass-card">
  <h2>My Glass Card</h2>
  <p>This content floats above a blurred background.</p>
</div>
```

If you want to tweak the exact look, override the variables in your own CSS:
```css
:root {
  --glass-blur: 20px;
  --glass-opacity: 0.15;
  --glass-border-color: rgba(255, 255, 255, 0.3);
}
```

## 🛠 Available Classes

| Class | Description |
| :--- | :--- |
| `.glass` | The base class that applies the `backdrop-filter` and transparent background. |
| `.glass-card` | Adds padding, border-radius, and the subtle white border top/left highlight. |
| `.glass-panel` | A larger variant designed for full-screen overlapping sidebars or modals. |
| `.glass-button`| Interactive frosted glass button with hover states. |

## 🌐 Browser Support
The core effect relies on `backdrop-filter`. It is supported in:
- Chrome 76+
- Safari 9+ 
- Edge 79+
- Firefox 103+

*Note: For unsupported browsers, it falls back to a slightly less transparent background color without the blur.*

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).


---
### 🏢 About Stackaura
This project is proudly maintained backed and sponsored by **[Stackaura](https://www.stackaura.com/)**.
We specialize in building high-performance web applications, scalable SaaS architectures, and premium digital solutions.
👉 **[Visit Stackaura to supercharge your next project!](https://www.stackaura.com/)**


---

## 🚀 Discover More from Stackaura

If you found this tool useful, check out our other high-performance web utilities and follow **Ahmar Hussain** for more open-source excellence.

### 🌟 Featured Projects
- **[Free LLM APIs](https://github.com/RanaAhmar/free-llm-apis)** - A curated list of zero-cost AI endpoints.
- **[Awesome MCP Servers](https://github.com/RanaAhmar/awesome-mcp-servers)** - The ultimate collection of Model Context Protocol implementations.
- **[System Design Cheatsheet](https://github.com/RanaAhmar/system-design-cheatsheet)** - Master complex architectures in minutes.
- **[Next.js SaaS Starter](https://github.com/RanaAhmar/nextjs-saas-starter)** - The fastest way to launch your next product.

### 🔗 Stay Connected
- **Website:** [stackaura.com](https://www.stackaura.com/)
- **Author:** [Ahmar Hussain](https://github.com/RanaAhmar)

---
