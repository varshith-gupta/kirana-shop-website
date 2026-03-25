# Mahesh Kirana & Xerox — Website

A professional bilingual (Telugu / English) website for **Mahesh Kirana & Xerox**, a trusted neighbourhood grocery and services shop operating since 2005.

---

## 📸 Preview

| Hero section | Product cards |
|---|---|
| ![Hero](docs/preview-hero.png) | ![Cards](docs/preview-cards.png) |

> Screenshots are generated automatically — see [Taking screenshots](#taking-screenshots).

---

## 🗂️ Project structure

```
kirana-shop-website/
├── index.html            # The entire website (single HTML file)
├── shop_front_photo.jpg  # Photo of the shop front
├── shop.jpg              # Photo of the shop interior
└── README.md             # This file
```

---

## 👀 How to view the website

### Option 1 — Just open the file (simplest)

Double-click **`index.html`** in your file manager or drag it into any browser (Chrome, Firefox, Edge, Safari).  
All features work without an internet connection except the Google Maps embed and the web fonts.

---

### Option 2 — VS Code Live Server (recommended for development)

1. Install the **[Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)** extension in VS Code.
2. Open the project folder in VS Code.
3. Right-click `index.html` → **"Open with Live Server"**.
4. The browser opens at `http://127.0.0.1:5500` and auto-refreshes on every save.

---

### Option 3 — Python built-in server (no installs needed)

```bash
# Python 3 (available on most systems)
python3 -m http.server 3000
```

Then open **[http://localhost:3000](http://localhost:3000)** in your browser.

---

### Option 4 — Node.js / npm (one command)

> Requires [Node.js](https://nodejs.org) ≥ 18.

```bash
npm start
```

This runs `npx serve .` which serves the current directory at **[http://localhost:3000](http://localhost:3000)**.

---

### Option 5 — GitHub Pages (free, public hosting)

1. Push the repository to GitHub (if not already done).
2. Go to your repository → **Settings** → **Pages**.
3. Under *Branch*, choose `main` (or your branch) and leave the folder as `/ (root)`.
4. Click **Save**.
5. GitHub will give you a URL like `https://<your-username>.github.io/kirana-shop-website/`.

The site is live within a minute and updates automatically on every `git push`.

---

## 🌐 Language toggle

Click the **English / తెలుగు** button in the top-right corner of the navbar to switch between Telugu and English instantly.

---

## 📞 Contact info embedded in the site

| Field | Value |
|---|---|
| Phone | 96406 95662 |
| WhatsApp | [wa.me/919640695662](https://wa.me/919640695662) |
| Map | [Google Maps — Mahesh Kirana & Xerox](https://www.google.com/maps/place/Mahesh+Kirana+%26+Xerox/@18.0115235,83.0816276,17z) |

---

## ✏️ Customising content

All text and product data live inside the `data` object at the bottom of `index.html`.  
Edit the `te` (Telugu) and `en` (English) keys to update any text without touching the HTML or CSS.

---

## 🏗️ Tech stack

| Technology | Purpose |
|---|---|
| HTML5 + CSS3 | Structure and styling |
| Vanilla JavaScript | Language toggle, dynamic content rendering |
| [Google Fonts](https://fonts.google.com) | Noto Sans Telugu, Inter |
| [Font Awesome 6.5](https://fontawesome.com) | Icons |
| Google Maps Embed API | Location section |

No build step, no framework, no dependencies to install.

---

## 📄 License

© 2005 – 2026 Mahesh Kirana & Xerox. All rights reserved.
