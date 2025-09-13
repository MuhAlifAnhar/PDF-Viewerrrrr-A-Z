# 📄 PDF Viewer Dashboard - View Only 🔒

A clean, secure, and interactive *PDF viewer dashboard* built with pure HTML5, JavaScript, and PDF.js.  
This app renders up to *26 PDFs inline* with *view-only mode, **page navigation, and **download protection* (no iframe or embed).

> ✅ Perfect for confidential documents, internal manuals, service part catalogs, or client reports.

---

## 🚀 Features

- 🔐 *View-only mode* — No print / download / direct access to PDF
- 🧩 **Rendered via <canvas>** using [PDF.js](https://mozilla.github.io/pdf.js/)
- 📦 *40 PDFs supported* — switch easily via dropdown
- ❌ *Right-click & text selection blocked*
- 🖼 *Dynamic watermark* — visible overlay to prevent screen recording abuse
- ⚡ *No external server needed* — runs 100% static via Base64 PDF embedding

---

## 📸 Screenshot

![screenshot](preview.png)  
(Example: Part List Toyota Raize - Rev 1)

---

## 🛠 Tech Stack

- HTML5 + JavaScript (ES6)
- PDF.js CDN v5.3.93
- Inline PDF via Base64 embedding
- Optional: Laravel backend (for advanced protected PDF streaming)

---

## 🧪 Demo Setup

Clone or download this repo, then just open index.html directly in your browser:

```bash
git clone https://github.com/MuhAlifAnhar/PDF-Viewer.git
cd PDF-Viewer
open index.html
