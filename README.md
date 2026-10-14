# 💼 Portfolio 2.0 — Lloyd Jefferson

A responsive single-page portfolio website for a Fullstack Developer. It presents skills, projects, client benefits and reviews, and lets visitors send a collaboration request directly from the page.

🔗 **Live demo:** [mrkorzun.github.io/portfolio/](mrkorzun.github.io/portfolio/)
🎨 **Design:** [Figma mockup](https://www.figma.com/design/IfXpaJMGJM9UVEJTWDEzrM/Portfolio-2.0--Copy-?node-id=9380-180&m=dev)
📡 **API:** [portfolio-js.b.goit.study/api-docs](https://portfolio-js.b.goit.study/api-docs)

![Preview](./assets/preview.jpg)

---

## 🛠️ Tech Stack & Tools

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=flat&logo=axios&logoColor=white)
![Swiper](https://img.shields.io/badge/Swiper-6332F6?style=flat&logo=swiper&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat&logo=vscodium&logoColor=white)

**Libraries:** [Swiper](https://swiperjs.com/) (reviews slider) · [Accordion](https://github.com/michu2k/Accordion) (FAQ) · [Axios](https://axios-http.com/) (HTTP requests) · [iziToast](https://izitoast.marcelodolza.com/) (pop-up notifications)

---

## ✨ Features

- 📱 **Responsive layout** — mobile (fluid from 320px, adaptive from 360px), tablet (768px), desktop (1280px)
- 🌗 **Light / dark theme** switcher with the choice saved in `localStorage`
- 🍔 **Mobile burger menu** — full-screen, smooth opening, page scroll locked while open
- 🧭 **Anchor navigation** with smooth scrolling between sections
- 🏃 **Running line** of tech skills
- 📂 **"Load more" projects** — loads 3 more at a time, the button hides when the list ends
- ❓ **FAQ accordion** — first item open by default, only one item open at a time
- 💬 **Reviews slider** loaded from the backend — mouse, keyboard (Tab / arrows) and touch support; "Not found" fallback and an error notification if the request fails
- 📨 **Contact form** — POST request to the API, success modal, form reset on success, values kept on error
- 🪟 **Modal window** — closes by the close button, backdrop click or `Escape`; page scroll locked while open
- ⚡ **Optimized assets** — SVG sprite, retina images, lazy loading

---

## 🗂️ Page Structure

| Section           | Content                                                                        |
| ----------------- | ------------------------------------------------------------------------------ |
| **Header**        | Text logo, navigation, theme switcher, "Order the project" button, burger menu |
| **Hero**          | Main heading, CTA to "Work together", social links                             |
| **About me**      | Photo and description                                                          |
| **Tech Skills**   | Running line of technologies (visually hidden heading)                         |
| **My projects**   | Project cards with stack and GitHub link, "Load more" button                   |
| **Benefits**      | List of benefits of working together                                           |
| **FAQ**           | Frequently asked questions (accordion)                                         |
| **Reviews**       | Reviews slider from the API                                                    |
| **Work together** | Contact form, phone and email links                                            |
| **Footer**        | Logo, social links, copyright                                                  |

---

## 🚀 Getting Started

**Requirements:** [Node.js](https://nodejs.org/) LTS

```bash
# 1. Clone the repository
git clone https://github.com/mrkorzun/portfolio.git
cd portfolio

# 2. Install dependencies
npm install

# 3. Start the dev server
npm run dev
```

The site will be available at [http://localhost:5173](http://localhost:5173).

### Scripts

| Command           | Description                               |
| ----------------- | ----------------------------------------- |
| `npm run dev`     | Start the development server              |
| `npm run build`   | Build the production version into `dist/` |
| `npm run preview` | Preview the production build locally      |

---

## 📁 Project Structure

```
portfolio/
├── public/
│   ├── favicon.svg       # site favicon
│   └── icons.svg         # SVG sprite
├── src/
│   ├── assets/           # static assets
│   ├── css/
│   │   ├── reset.css     # browser defaults reset
│   │   ├── base.css      # global styles, variables, fonts
│   │   ├── containers.css
│   │   ├── header.css
│   │   ├── hero.css
│   │   └── modal.css
│   ├── img/              # raster images (1x / 2x for retina)
│   ├── main.js           # JS entry point
│   └── style.css         # imports all CSS files
├── index.html            # page markup
├── package.json
└── README.md
```

---

## ✅ Quality

- Valid HTML and CSS ([W3C Validator](https://validator.w3.org/), [CSS Validator](https://jigsaw.w3.org/css-validator/))
- Semantic HTML5 markup
- Hover effects on all interactive elements
- Accessible controls (`aria-label`, `aria-expanded`, keyboard navigation)

---

## 👤 Author

**Romario Korzun** — [GitHub](https://github.com/mrkorzun) · [LinkedIn](www.linkedin.com/in/mrkorzun)

Project completed as part of the [GoIT](https://goit.global/) Fullstack Developer course.
