# 🎙️ Solophone Poster Studio

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-CDN-06B6D4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![html2canvas](https://img.shields.io/badge/html2canvas-1.4-FF6B6B)](https://html2canvas.hertzen.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![No Build Step](https://img.shields.io/badge/Build_Step-None-success)](https://github.com/Fahad-BA/solophone)

> **A browser-based poster designer for the SOLOPHONE podcast.**
>
> Upload a background, tweak the text, pick a neon accent color, and export a print-ready 1:1 square cover — all client-side, no installation needed.

---

## ✨ Features

- **🖼️ Custom Background Upload** — Drop in any image, see it applied instantly
- **✏️ Full Typography Control** — Edit every text element on the poster (title, tagline, footer, metadata)
- **🎨 4 Neon Accent Themes** — Cyan, Purple, Emerald, and Amber with matching glow effects
- **📱 Two Preview Modes** — Switch between a standalone square poster and an iPhone podcast player mockup
- **🔞 Explicit Content Badge** — Toggle the classic parental advisory sticker
- **🎞️ Cinematic Noise Overlay** — Optional analog film grain texture
- **📥 High-Res PNG Export** — Download at 3× scale (~1350×1350px) via html2canvas
- **⚡ Zero Setup** — Single HTML file, no dependencies to install, no build step

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Tailwind CSS** (CDN) | Layout & styling |
| **html2canvas** | Client-side poster-to-PNG rendering |
| **FontAwesome 6** | Iconography |
| **Poppins** (Google Fonts) | Typography |
| **Vanilla JavaScript** | All interactivity & state |

---

## 🚀 Usage

### Run Locally

```bash
git clone https://github.com/Fahad-BA/solophone.git
cd solophone
open index.html   # Or just double-click the file
```

That's it. No `npm install`, no build step.

### Deploy

Upload `index.html` to any static host (GitHub Pages, Netlify, Vercel, your own server).

---

## 🎨 Customization Guide

| Control | What It Does |
|---------|-------------|
| **Background Image** | Upload your own photo/artwork |
| **Main Title** | The large headline text (default: SOLOPHONE) |
| **Top Header Text** | Small uppercase label at the top |
| **Middle Divider Text** | Thin divider subtitle |
| **Bottom Tagline** | Accent-colored tagline below the title |
| **Bottom Footer** | Small metadata text (default: SEASON 1 • UNFILTERED) |
| **Accent Color** | Cyan / Purple / Emerald / Amber |
| **Explicit Sticker** | Show/hide parental advisory badge |
| **Noise Overlay** | Toggle film grain effect |
| **Preview Mode** | Poster square or iPhone mockup |

---

## 📁 Project Structure

```
solophone/
├── index.html    # The entire app — HTML, CSS, and JS in one file
└── README.md
```

---

## 🌐 Live Demo

**[Solophone Poster Studio →](https://fhidan.com/solophone/)**

---

## 📜 License

MIT License — see [LICENSE](LICENSE).

---

<p align="center">
  <em>Made with ❤️ by <a href="https://github.com/Fahad-BA">Fahad Alhuqaili</a></em>
</p>
