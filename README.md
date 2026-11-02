<div align="center">

# Ashish Saini — Portfolio

> Full Stack Engineer · Node.js · Next.js · React · Laravel · Integrations · AI Agents

[![Live Site](https://img.shields.io/badge/Live_Site-ashishsaini101.github.io-0d9488?style=for-the-badge&labelColor=101315)](https://ashishsaini101.github.io/ashish-portfolio/)
[![HTML](https://img.shields.io/badge/HTML5-Single_File-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![License](https://img.shields.io/badge/License-MIT-6366f1?style=for-the-badge)](LICENSE)

</div>

---

## Live

**https://ashishsaini101.github.io/ashish-portfolio/**

---

## Features

- **Light / Dark / System themes** — persisted per visitor, follows the OS setting in System mode
- **Scroll-driven background morph** — soft tints change section by section
- **Preloader, smooth scrolling and text reveals** — GSAP + ScrollTrigger + Lenis
- **12 core strengths with animated concept diagrams** — microservices, queues, database relations, CI/CD pipeline, observability and more, each in its own colour with 3D tilt on hover
- **Areas of expertise as doors** — scroll through five domains, open a door to see the detailed scope
- **3D WebGL globe** (three.js) — worldwide flight routes for the travel booking platform case study
- **Live system architecture diagram** — draws on scroll, then animates request flow between services
- **Stacked project cards**, experience timeline with an animated year counter
- **Brand-coloured tech logos** — Simple Icons via CDN
- **Interactive CLI** — type `help`, `whoami`, `stack`, `projects`, `experience`, `contact`
- Fully responsive; respects `prefers-reduced-motion`

---

## Project structure

```
ashish-portfolio/
├── index.html        ← the whole site (HTML, CSS and JS in one file)
├── assets/
│   ├── ashish.jpg         ← hero photo
│   └── ashish-casual.jpg  ← contact avatar
├── README.md
├── LICENSE
└── .gitignore
```

No build step. Open `index.html` in a browser, or serve the folder with any static server.
Libraries load from CDNs (GSAP, ScrollTrigger, Lenis, three.js, Simple Icons, Google Fonts); without them the content still renders, only the animations are skipped.

---

## Editing content

All content is data at the top of the `<script>` block in `index.html`:

| What | Constant |
|------|----------|
| Rotating hero roles | `ROLES` |
| Areas of expertise (doors) | `DOORS` |
| Core strengths | `STRENGTHS` |
| Selected work | `PROJECTS` |
| Experience & education | `JOURNEY` |
| Technical skills | `SKILLS` |
| Logo strip | `LOGOS1`, `LOGOS2` |

Colours live in the CSS tokens at the top of the `<style>` block (`:root` for light, `[data-theme="dark"]` for dark).

---

## Deployment

Hosted on **GitHub Pages** from the `main` branch (root). Every push to `main` redeploys the site.

---

## About

**Ashish Saini** — Full Stack Developer & Production Support Engineer, Gurugram, India.

- Travel booking platform — worldwide flights, hotels, rail and cabs, built and deployed end-to-end
- PayGlocal payment gateway, Google APIs and SerpAPI integrations
- 9-module recruitment and crew-deployment platform for oil & gas clients (Laravel, Angular, Elasticsearch)
- AI agents with Claude and ChatGPT — tool use, Skills, sub-agents, MCP
- Open to full-time roles at product-based companies

---

## License

MIT

<div align="center">
<sub><a href="mailto:saini.ar96@gmail.com">saini.ar96@gmail.com</a></sub>
</div>
