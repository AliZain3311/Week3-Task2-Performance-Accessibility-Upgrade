# ⚡ BlogSpace — Performance & Accessibility Upgrade

## Week 3 · Task 2

A modern, responsive and accessibility-focused upgrade of the BlogSpace full-stack blog platform.

### ✨ Highlights
- ⚡ Performance-focused frontend
- ♿ Accessibility improvements
- ⌨️ Keyboard-friendly interactions
- 📱 Mobile / tablet / desktop responsive UI
- 🖼️ Lazy-loaded article images
- 🔎 Basic SEO metadata
- 🌙 Dark/light theme with LocalStorage
- 📝 Create, edit and delete API
- 💾 Persistent JSON data
- 🔐 Client + server validation
- 📊 Dynamic statistics
- 📱 Device image picker + preview
- 💬 Toast and live-region feedback

## 🧩 Task 2 Improvements

| Area | Implementation |
|---|---|
| Performance | Deferred JS, lightweight frontend, lazy images, async decoding, static caching |
| Accessibility | Skip link, semantic landmarks, labels, focus states, keyboard modal |
| Keyboard UX | Tab support, Escape close, focus restoration |
| Responsive | Fluid grids and mobile navigation |
| Images | `loading="lazy"` and `decoding="async"` |
| SEO | Title, meta description, language, heading hierarchy |
| Backend | Disabled Express signature, ETag/cache headers, validation |
| UX | Empty/error states, toast feedback, live announcements |
| Motion | `prefers-reduced-motion` support |

## 🧪 Before vs After
Do not invent Lighthouse scores. Run Chrome DevTools Lighthouse on the original project and this upgraded project using the same device/settings, then record:
- Performance
- Accessibility
- Best Practices
- SEO

## 🚀 Run
```bash
npm install
npm start
```
Open `http://localhost:3000`.

## 🔌 API
- `GET /api/posts`
- `GET /api/posts/:id`
- `POST /api/posts`
- `PUT /api/posts/:id`
- `DELETE /api/posts/:id`

## 📁 Structure
```text
Week3-Task2-Performance-Accessibility-Upgrade/
├── data/posts.json
├── public/
│   ├── css/style.css
│   ├── js/main.js
│   └── index.html
├── package.json
├── server.js
└── README.md
```

## 🧠 Learning Outcomes
Performance auditing, accessibility engineering, semantic HTML, keyboard UX, responsive design, image optimization, SEO basics, REST APIs, validation, persistence, testing and Git/GitHub workflow.

## 🔮 Future Improvements
WebP/AVIF conversion, CDN, database storage, authentication, automated accessibility tests, CI/CD, rate limiting, compression, cloud image storage, sitemap/robots.txt and PWA support.

## 👨‍💻 Developer
**Ali Zain** — BS Information Technology | Flutter / Mobile Application Developer

GitHub: https://github.com/AliZain3311  
LinkedIn: https://www.linkedin.com/in/alizain3311


## 🖼️ Relevant Article Images

All 8 sample articles now use lightweight local SVG thumbnails matched to their topics. Local assets avoid third-party image requests and support the performance-focused Task 2 goals. Images use lazy loading, explicit dimensions, and descriptive alternative text.
