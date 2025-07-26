
# 💼 DataFlow – Responsive SaaS Landing Page with Dark Mode Toggle

A modern, responsive **marketing landing page** for a fictional SaaS product called **DataFlow**, built using **HTML**, **CSS**, and **JavaScript**. Includes a **theme toggle** (Light/Dark mode), responsive layout, and all major marketing sections.

---
**DataFlow** is a sleek, fully responsive **marketing landing page** crafted using **HTML**, **CSS**, and **JavaScript** to promote a fictional tech product or SaaS tool. The design follows modern layout practices using **Flexbox and CSS Grid**, delivering a consistent user experience across mobile, tablet, and desktop devices.

The site includes all essential marketing sections: a bold **hero** with a clear call-to-action (CTA), a **features** grid showcasing product benefits with icons, a **testimonials** section for user trust-building, and a **pricing** section with styled plans. At the end of the page, a strong **CTA banner** nudges users to sign up or get started.

A bonus feature is the **Light/Dark theme toggle**, implemented with pure JavaScript. This toggle enhances usability and user control, storing preferences in `localStorage` for persistence across sessions.

DataFlow serves as an ideal example of professional UI layout, UX copywriting, theme customization, and responsive design — perfect for product marketing websites and developer portfolios.
---
## ✨ Features

- 🎯 **Hero Section** with a bold message and CTA button
- 💡 **Features Grid** with icons and short descriptions
- 💬 **Testimonials** to build credibility and trust
- 💸 **Pricing Plans** in styled cards (Free, Pro, Enterprise)
- 🎯 **Call-to-Action Banner** to drive conversions
- 🌙 **Dark Mode Toggle** (saved in localStorage)
- 📱 Fully responsive design across mobile, tablet, desktop

---

## 🧰 Technologies Used

| Technology | Purpose                            |
|------------|------------------------------------|
| HTML5      | Markup structure                   |
| CSS3       | Styling & layout                   |
| JavaScript | Interactivity (theme toggle, CTA)  |
| Flexbox / Grid | Layout management              |
| Font Awesome / Lucide Icons | Icons             |
| Optional: Tailwind / Bootstrap (if used)        |


---

## 🌗 Dark Mode Support

The site includes a **theme switcher** that toggles between light and dark modes. It stores user preference using `localStorage`.

```html
<!-- Theme toggle button -->
<button id="themeToggle">🌙</button>
````

```js
// script.js
const toggleBtn = document.getElementById('themeToggle');
toggleBtn.addEventListener('click', () => {
  document.body.classList.toggle('dark');
  localStorage.setItem('theme', document.body.classList.contains('dark') ? 'dark' : 'light');
});

// Set theme on load
if (localStorage.getItem('theme') === 'dark') {
  document.body.classList.add('dark');
}
```

```css
/* style.css */
body.dark {
  background-color: #121212;
  color: #f3f4f6;
}
```

---

## 📐 Responsive Design

* ✅ CSS Grid + Flexbox used for adaptive layouts
* ✅ Media queries ensure mobile-first responsiveness
* ✅ Icons and buttons resize properly
* ✅ Call-to-action remains visible on all screens

---

## 🧪 Topics Covered

* Semantic HTML5
* Responsive Layouts (Grid/Flex)
* Theme Toggle with JS
* UX Copywriting
* Clean Component Layout
* Card UI with hover/transition effects

---

## ⚙️ How to Run Locally

1. Clone the repository

```bash
git clone https://github.com/your-username/dataflow-landing.git
cd dataflow-landing
```

2. Open in browser

You can use a local live server (like VS Code Live Server), or open `index.html` directly.

---

## 🔗 Use Cases

* Marketing pages for SaaS products
* Landing pages for tech startups
* UI portfolio projects
* Theme toggle functionality demo

---

## 👤 Author

**Saad Khan**
📧 [saado652004@gmail.com](mailto:saado652004@gmail.com)
🌐 [GitHub – saadoxyz](https://github.com/saadoxyz)

---
