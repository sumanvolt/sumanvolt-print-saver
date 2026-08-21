# ⚡ SumanVolt — Print Saver

> **Lossless, client-side N-up PDF page merger engineered for economical printing.** Save up to 75% on paper and printing costs with zero compromise on text or vector quality.

[![Live Demo](https://img.shields.io/badge/Live-Demo-D6FF3F?style=for-the-badge&logo=githubpages&logoColor=0B0B0C)](https://<your-username>.github.io/<your-repo-name>/)
[![PWA Ready](https://img.shields.io/badge/PWA-Installable-blue?style=for-the-badge&logo=pwa&logoColor=white)](#)
[![Zero Uploads](https://img.shields.io/badge/Privacy-100%25%20Local-success?style=for-the-badge&logo=shield&logoColor=white)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](#)

---

## ✨ Features

* **True Vector Lossless Output**: Unlike traditional converters that rasterize documents into low-resolution images, SumanVolt embeds native PDF vector paths and fonts directly using `pdf-lib`. Text remains 100% crisp and selectable at any printer DPI.
* **Flexible N-Up Layouts**: Merge 2-up, 4-up, 6-up, 9-up, or 16-up pages per sheet in both Portrait and Landscape orientations.
* **Zero Server Uploads (100% Private)**: All computations happen in-memory inside the client's browser. Sensitive PDFs never touch an external server or API.
* **Progressive Web App (PWA)**: Installable as a standalone app on iOS, Android, macOS, and Windows.
* **Full Offline Support**: Bundled Service Worker caches all assets, making the app function seamlessly without an active internet connection.
* **Custom Sheet Adjustments**: Real-time margin slider controls (0–20mm) and automated paper sheet calculators.

---

## 🚀 Live Demo

Access the live web app directly on GitHub Pages:  
👉 **[https://<your-username>.github.io/<your-repo-name>/](https://<your-username>.github.io/<your-repo-name>/)**

---

## 🛠️ Tech Stack

* **Core Engine:** [PDF-Lib](https://pdf-lib.js.org/) (Client-side PDF manipulation)
* **Architecture:** Vanilla HTML5, CSS3, JavaScript (No build steps required)
* **PWA & Caching:** Web App Manifest & Service Worker Cache API
* **Typography:** Space Grotesk & JetBrains Mono

---

## 📂 Project Structure

```text
├── index.html        # App UI, vector layout calculation & install prompt
├── manifest.json     # PWA manifest metadata & branding
├── sw.js             # Service Worker for offline asset caching
└── README.md         # Documentation
