# Ashish Saini — Portfolio Website

> Personal portfolio of **Ashish Saini**, Full Stack Developer (PHP · Laravel · Angular · AWS)

🌐 **Live Site:** [ashishsaini.dev](https://ashishsaini.dev) *(update with your actual domain)*

---

## ✨ Features

- 🧑‍💻 Animated SVG cartoon character (dual-monitor desk setup, typing fingers, eye tracking, blinking)
- 🎨 Dark navy theme with electric cyan/teal accents
- ⚡ Scroll-reveal animations on all sections
- 🖱️ Custom animated cursor with trailing ring
- 📊 Animated skill progress bars
- 🔢 Counter animations on stats
- 📱 Fully responsive (mobile, tablet, desktop)
- 🏷️ Floating availability badge
- 💻 Decorative code snippet overlay
- 🌊 Infinite marquee tech-stack strip
- 📬 Contact form with feedback state

---

## 📁 Project Structure

```
ashish-portfolio/
├── index.html          # Main portfolio (single-file, self-contained)
├── README.md           # This file
├── .gitignore          # Git ignore rules
└── LICENSE             # MIT License
```

> **Note:** The entire portfolio is a single `index.html` file — no build tools, no dependencies, no npm install needed. Just open it in a browser.

---

## 🚀 Deploy Options

### GitHub Pages (Free — Recommended)

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)`
4. Your site will be live at `https://<your-username>.github.io/<repo-name>`

### Netlify (Free)

1. Drag & drop the project folder at [netlify.com/drop](https://app.netlify.com/drop)
2. Or connect your GitHub repo for auto-deploy on push

### Vercel (Free)

```bash
npm i -g vercel
vercel
```

### Self-hosted / VPS

```bash
# Just copy index.html to your web root
scp index.html user@yourserver.com:/var/www/html/
```

---

## 🛠️ Customisation

All content is in `index.html`. Key sections to update:

| What | Where in file |
|------|--------------|
| Name / title | `<h1 class="h-name">` in `#hero` |
| Bio text | `.h-bio` paragraph |
| Contact links | `.c-links` section + `href` values |
| Social links | Footer + contact section |
| Project details | `.pc` cards in `#projects` |
| Skills & percentages | `.sk-card` blocks + `width` on `.bar-fill` |
| Experience bullets | `.exp-list` in `#experience` |
| Availability badge | `.badge` in `<nav>` |

---

## 📦 Tech Stack Used

| Technology | Purpose |
|------------|---------|
| HTML5 / CSS3 | Structure & styling |
| Vanilla JavaScript | Animations, cursor, scroll reveals |
| SVG | Animated cartoon character |
| Google Fonts | Syne + Space Mono + Instrument Serif |
| CSS Animations | All motion effects (no libraries) |

---

## 📄 License

MIT — feel free to fork and customise for your own portfolio.

---

*Built with ☕ and precision.*
