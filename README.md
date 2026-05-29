# Netflix India — Homepage Clone

A pixel-perfect, responsive clone of the **Netflix India** homepage built with pure HTML and CSS — no frameworks, no JavaScript.

---

## 🖥️ Preview

> Hero section with background image, feature sections with embedded videos, FAQ accordion layout, and a full footer — all matching the real Netflix India landing page.

---

## ✨ Features

- **Hero Section** — Full-viewport background image with dark overlay, email sign-up form, and Sign In button
- **Feature Sections** — Four alternating image/text sections highlighting TV, mobile downloads, multi-device, and kids profiles
- **Embedded Videos** — Autoplay, muted, looping `.m4v` videos overlaid on device mockups
- **FAQ Section** — Expandable question cards with hover effects
- **Responsive Design** — Fully adapts across desktop, tablet, and mobile (breakpoints at 959px, 599px, and 450px)
- **Language Selector** — English / हिन्दी toggle in both navbar and footer
- **Footer** — Multi-column link grid matching the real Netflix footer layout

---

## 📁 Project Structure

```
Netflix Clone 3/
├── index.html
├── style.css
├── favicon.ico
└── Assets/
    ├── Icons/
    │   ├── logo.svg
    │   ├── lang-logo.svg
    │   └── plus-icon.svg
    ├── Images/
    │   ├── bg.jpg
    │   ├── tv.png
    │   ├── tv (2).png
    │   ├── mobile-0819.jpg
    │   └── AAAABVr8n...png
    └── Videos/
        ├── video1.m4v
        └── video2.m4v
```

---

## 🚀 Getting Started

No build tools or dependencies required.

1. Clone or download the repository
2. Open `index.html` in any modern browser

```bash
git clone https://github.com/your-username/netflix-clone.git
cd netflix-clone
# Open index.html in your browser
```

---

## 🛠️ Built With

| Technology | Usage |
|---|---|
| HTML5 | Page structure and semantic layout |
| CSS3 | Styling, Flexbox layout, media queries |
| CSS Custom Properties | Responsive typography and spacing |

---

## 📱 Responsive Breakpoints

| Breakpoint | Changes |
|---|---|
| `≤ 959px` | Smaller logo, centered text, stacked footer columns |
| `≤ 599px` | Collapsed language selector in navbar |
| `≤ 450px` | Adjusted video overlay positions on device mockups |

---

## 🎨 Design Highlights

- Font stack mirrors Netflix's own: `Netflix Sans, Helvetica Neue, Segoe UI, Roboto, Ubuntu`
- Netflix red (`#E50914`) used consistently for buttons and focus outlines
- Floating label animation on the email input field
- Dark semi-transparent overlay (`rgba(0,0,0,0.7)`) on the hero background
- Section separators using `rgb(46, 44, 44)` dividers

---

## ⚠️ Disclaimer

This project is built **for educational and practice purposes only**. All Netflix branding, logos, images, and trademarks are the property of **Netflix, Inc.** This clone is not affiliated with or endorsed by Netflix.
