# Chirag's Portfolio 🎨

> **Digitally drained, but still shipping.**

A personal portfolio website built from scratch with plain HTML & CSS — no frameworks, no build tools, no dependencies. Just clean, brutalist-inspired design with a retro-paper aesthetic.

🔗 **Live Site:** [chirag982.github.io/Chirag-Portfolio-Website](https://chirag982.github.io/Chirag-Portfolio-Website/)

---

## 📖 About

This is my personal developer portfolio. I built it from the ground up to showcase my work as a **Full-Stack & AI Developer**. The design leans into a **brutalist, retro-paper** aesthetic — cream backgrounds, heavy black borders, red accents, and a mix of serif and sans-serif typography. It's meant to feel raw, honest, and a little unpolished — just like the person who built it.

The site is fully static, hosted on **GitHub Pages**, and works on mobile, tablet, and desktop.

---

## ✨ Features

- 🎨 **Custom brutalist design** — bold borders, hover effects that create physical "shift + shadow" illusions
- 📱 **Fully responsive** — mobile-first media queries for phones, tablets, and desktops
- ⚡ **Zero dependencies** — no React, no Tailwind, no npm. Just HTML + CSS + Font Awesome icons
- 🧩 **Modular sections** — Hero, Skills, Services, Projects, Timeline, Beyond the Code, About, Connect
- 🎴 **Grid-based project cards** — auto-fit CSS Grid that scales from 1 to N columns
- 🕹️ **Pixel art hero** — personal touch with a hand-drawn "try new things" illustration
- 🚀 **Fast loading** — single HTML file, minimal external assets

---

## 🧱 Sections

| Section | What it does |
|---|---|
| **Hero** | Name, role, pitch, tagline, and call-to-action button |
| **Technical Skills** | Categorized skill cards (Languages, Frameworks, AI & Data, Tools) |
| **What I Do** | Three service pillars — Full-Stack, AI & Automation, Desktop Apps |
| **Projects** | Card grid with 5 featured projects + "More on GitHub" CTA |
| **Experience & Education** | Vertical timeline with milestone dots |
| **Beyond the Code** | Personal hobbies — Writing, Piano, Reading, Running |
| **About the Builder** | Short bio + personal stamp image |
| **Let's Connect** | Contact box with email, GitHub, LinkedIn, YouTube links |

---

## 🛠️ Tech Stack

- **HTML5** — semantic structure
- **CSS3** — Flexbox, CSS Grid, custom properties (variables), media queries
- **Font Awesome 6.7.2** — icon library (loaded via CDN)
- **Google Fonts (system fallbacks)** — `Georgia` for body, `Franklin Gothic Medium` for headings
- **GitHub Pages** — free static hosting

No JavaScript. No frameworks. No build step.

---

## 📂 Project Structure

```
Chirag-Portfolio-Website/
│
├── index.html          # The entire portfolio (HTML + CSS inline)
├── image1.jpg          # Hero pixel art illustration
├── image.jpg           # Secondary image (unused in current version)
├── stamp.png           # Personal stamp image (About section)
└── README.md           # You're reading this
```

> 💡 **Note:** All CSS is embedded inside a `<style>` tag in `index.html`. If you want to split it out, create a `styles.css` file and link it with `<link rel="stylesheet" href="styles.css">`.

---

## 🚀 Run Locally

1. **Clone the repo**
   ```bash
   git clone https://github.com/chirag982/Chirag-Portfolio-Website.git
   cd Chirag-Portfolio-Website
   ```

2. **Open the site**
   - Easiest: double-click `index.html`
   - Or with VS Code: install **Live Server** extension → right-click `index.html` → *Open with Live Server*
   - Or with Python:
     ```bash
     python -m http.server 5500
     ```
     Then visit `http://127.0.0.1:5500`

---

## 🎨 Customization Guide

Want to fork this and make it your own? Here's where to change things:

### 1. Colors
At the top of the `<style>` block:
```css
:root {
  --bg-color: #CDC6BE;    /* Paper cream */
  --text-color: #060504;  /* Ink black */
  --accent-color: #D1462F;/* Retro red */
}
```
Change these three hex codes and the entire site updates.

### 2. Content
- **Name & role** → search for `<h1 class="hero-name">` and `<h2 class="hero-role">`
- **Projects** → each project is inside a `<div class="project-card">` block. Copy-paste to add more.
- **Timeline** → add/remove `<div class="timeline-item">` blocks
- **Hobbies** → edit the four `.beyond-card` divs

### 3. Images
Replace `image1.jpg` and `stamp.png` with your own. Keep the same filenames to avoid editing HTML.

---

## 🧭 Design Decisions

- **No JavaScript** — proves you can build a polished, interactive-feeling site without a framework. Hover effects, responsive grids, and typography do the heavy lifting.
- **Brutalist aesthetic** — heavy borders, hard shadows, and high contrast. It stands out against the sea of generic gradient-and-glass portfolios.
- **Single-file approach** — makes it easy to host anywhere, deploy instantly, and share without build steps.
- **Grid-based layout** — `repeat(auto-fit, minmax(...))` keeps every section responsive without a single media query for the grids themselves.

---

## 🗺️ Roadmap

Things I might add later:

- [ ] Downloadable resume button (currently links to GitHub)
- [ ] Dark mode toggle
- [ ] Blog section for writing samples
- [ ] Filterable projects by tech stack
- [ ] Animated scroll reveal
- [ ] Project detail pages

---

## 📬 Connect With Me

- **GitHub:** [@chirag982](https://github.com/chirag982)
- **LinkedIn:** [in/chiraggxg](https://www.linkedin.com/in/chiraggxg)
- **YouTube:** [@chiraggxg](https://www.youtube.com/@chiraggxg)
- **Email:** [chirag178g@gmail.com](mailto:chirag178g@gmail.com)

I'm currently **open to full-time roles** in Full-Stack Development, AI Engineering, or Backend Engineering. If you're hiring or want to collaborate, reach out!

---

## 📄 License

This project is open source and available for **personal inspiration and learning**. If you fork it, please:

- Swap out my name, images, projects, and links for your own
- Don't claim the content as yours
- A credit link back is appreciated but not required

```
MIT License — free to use, modify, and learn from.
```

---

<p align="center">
  <em>Built from scratch with code and coffee. ☕</em>
</p>
