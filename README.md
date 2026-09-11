# ⚡ BlogSpace — Performance & Accessibility Upgrade

<div align="center">

### 🚀 Week 3 · Task 2

**A modern, responsive and accessibility-focused upgrade of a full-stack blog platform.**

Built with a strong focus on **performance, accessibility, responsive UX, SEO and reliable content management.**

<br>

[![GitHub](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github)](https://github.com/AliZain3311/Week3-Task2-Performance-Accessibility-Upgrade)
[![Node.js](https://img.shields.io/badge/Node.js-Backend-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![Express](https://img.shields.io/badge/Express.js-API-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-Frontend-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Accessibility](https://img.shields.io/badge/Accessibility-WCAG%20Focused-4C1?style=for-the-badge)](https://www.w3.org/WAI/)
[![Responsive](https://img.shields.io/badge/Responsive-Mobile%20%7C%20Tablet%20%7C%20Desktop-blue?style=for-the-badge)](#)

</div>

---

## 🌟 Project Overview

**BlogSpace — Performance & Accessibility Upgrade** is a modern enhancement of a full-stack blogging platform developed as part of **Week 3 · Task 2**.

The project focuses on improving the overall user experience through:

- ⚡ Frontend performance optimization
- ♿ Accessibility engineering
- ⌨️ Keyboard-friendly interactions
- 📱 Responsive layouts
- 🖼️ Optimized article images
- 🔎 SEO improvements
- 🌙 Dark/light theme support
- 📝 Full article management
- 💾 Persistent data storage
- 🔐 Client-side and server-side validation
- 📊 Dynamic platform statistics

The upgrade was designed to demonstrate practical knowledge of **performance auditing, accessibility, responsive web development, REST APIs, frontend optimization and Git/GitHub workflow**.

---

# ✨ Key Highlights

| Feature | Description |
|---|---|
| ⚡ Performance | Lightweight frontend, deferred JavaScript and optimized assets |
| ♿ Accessibility | Semantic HTML, labels, focus states and skip navigation |
| ⌨️ Keyboard UX | Tab navigation, Escape-to-close and focus restoration |
| 📱 Responsive UI | Optimized for mobile, tablet and desktop |
| 🖼️ Article Images | 8 topic-relevant local SVG thumbnails |
| 🔎 SEO | Metadata, language declaration and heading hierarchy |
| 🌙 Theme | Dark/light mode with LocalStorage persistence |
| 📝 Article Management | Create, edit and delete articles |
| 🔐 Validation | Client-side and server-side validation |
| 💾 Persistence | JSON-based persistent storage |
| 📊 Statistics | Dynamic article/platform statistics |
| 📱 Image Picker | Device gallery/file picker with preview |
| 💬 Feedback | Toast notifications and live-region announcements |
| 🧹 Error Handling | Empty states and error states |
| 🎞️ Motion | Reduced-motion support |

---

# 🧩 Task 2 Improvements

## ⚡ Performance

- Deferred JavaScript execution
- Lightweight frontend assets
- Lazy-loaded article images
- Async image decoding
- Explicit image dimensions
- Static asset caching
- ETag support
- Reduced unnecessary third-party requests
- Local SVG article thumbnails

These improvements help reduce unnecessary network requests and improve the overall loading experience.

---

## ♿ Accessibility

Accessibility was treated as a core part of the interface rather than an afterthought.

### Implemented:

- Semantic HTML landmarks
- Accessible form labels
- Keyboard-visible focus states
- Skip-to-content navigation
- Keyboard-friendly modal
- Escape key support
- Focus restoration
- Live-region announcements
- Accessible feedback messages
- Reduced-motion support
- Descriptive image alternative text
- Logical heading structure

---

## ⌨️ Keyboard Experience

The interface supports keyboard-based interaction without requiring a mouse for core actions.

Supported interactions include:

- `Tab` — Navigate interactive elements
- `Shift + Tab` — Navigate backwards
- `Enter` — Activate focused controls
- `Escape` — Close modal/dialog
- Focus restoration after modal interaction

---

## 📱 Responsive Design

BlogSpace is designed for:

- 🖥️ Desktop
- 💻 Laptop
- 📱 Mobile
- 📲 Tablet

The layout uses flexible grids, responsive typography, adaptive navigation and mobile-friendly controls.

---

# 🖼️ Relevant Article Images

All **8 sample articles** include lightweight, topic-relevant local SVG thumbnails.

### Article Image Mapping

| Article | Image |
|---|---|
| Better UX Through Clear Feedback | UX Feedback |
| Practical Frontend Quality Checks | Quality |
| Responsive Interfaces That Feel Natural | Responsive Design |
| Performance Starts with Better Assets | Performance |
| Design Systems for Consistent Interfaces | Design Systems |
| From Prototype to Production | Engineering |
| Making Accessibility Part of the Workflow | Accessibility |
| Building Reliable REST APIs | REST APIs |

### Why Local SVG Images?

The project intentionally uses lightweight local assets instead of relying on external image services.

Benefits include:

- ⚡ Faster loading
- 🌐 No third-party image requests
- 📦 Small asset size
- ♿ Descriptive `alt` text
- 💤 Lazy loading
- 🔄 Async decoding
- 📐 Explicit image dimensions

---

# 🔎 SEO Improvements

The upgraded project includes basic technical SEO improvements:

- Meaningful page title
- Meta description
- HTML language declaration
- Semantic HTML
- Heading hierarchy
- `robots.txt`
- `sitemap.xml`
- Search-engine-friendly structure

> **Note:** The local `robots.txt` and `sitemap.xml` currently use the local development URL. For production deployment, these URLs should be updated to the deployed domain.

---

# 🌙 Dark / Light Theme

BlogSpace includes a theme system that allows users to switch between:

- 🌙 Dark Mode
- ☀️ Light Mode

The selected theme is stored using **LocalStorage**, allowing the preference to persist across page reloads.

---

# 📝 Article Management

The platform provides complete article management functionality.

### Create Article

Users can:

- Enter article title
- Select category
- Add author information
- Add article content
- Upload an article image
- Preview the selected image
- Submit the article

### Edit Article

Existing articles can be updated without recreating them.

### Delete Article

Articles can be removed through the management interface with appropriate user feedback.

---

# 🔐 Validation

Validation is implemented at both levels:

### Client-Side

- Required fields
- Input validation
- Image validation
- User-friendly error messages

### Server-Side

- Request validation
- Data validation
- Image validation
- Safe API handling
- Error responses

---

# 📊 Dynamic Statistics

The dashboard dynamically displays platform statistics based on stored article data.

Examples include:

- Total articles
- Categories
- Authors
- Platform activity

Statistics update as content changes.

---

# 🔌 REST API

BlogSpace uses a simple RESTful API powered by **Node.js + Express.js**.

| Method | Endpoint | Purpose |
|---|---|---|
| `GET` | `/api/posts` | Retrieve all articles |
| `GET` | `/api/posts/:id` | Retrieve a specific article |
| `POST` | `/api/posts` | Create an article |
| `PUT` | `/api/posts/:id` | Update an article |
| `DELETE` | `/api/posts/:id` | Delete an article |

---

# 💾 Data Persistence

The project uses a JSON-based persistence layer:

```text
data/posts.json