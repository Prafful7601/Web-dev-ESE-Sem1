# Web Genisis – Multi-Portfolio Full-Stack Website

Web Genisis is a **multi-portfolio web platform** built with **HTML, CSS, JavaScript, and a lightweight backend**.  
It showcases multiple personal portfolios under a **single unified brand theme** and includes a **custom backend for form handling**, where submitted data is stored in JSON format.

This project demonstrates **real-world full-stack fundamentals** with clean structure, reusable UI, and backend integration.

---

## 🔹 Project Overview

Web Genisis is designed to:

- Maintain **design consistency** across multiple personal portfolios
- Serve static pages with **dynamic form handling**
- Collect and store contact and project inquiries
- Demonstrate **frontend + backend integration**
- Remain simple, readable, and deployable

The focus is on **clarity, structure, and practical implementation**, not over-engineering.

---

## 🔹 Tech Stack

### Frontend
- **HTML5** – Semantic structure
- **CSS3** – Custom theme system and layouts
- **JavaScript (Vanilla)** – Form handling and validation
- **Font Awesome** – Icons

### Backend
- **Node.js**
- **Express.js**
- **JSON file storage** (for form submissions)

No database is used; data is persisted in structured JSON files for simplicity.

---

## 🔹 Project Structure

```text
/
├── frontend/
│   ├── index.html
│   ├── about.html
│   ├── service.html
│   ├── team.html
│   ├── blog.html
│   ├── contact.html
│   ├── theme.css
│   └── portfolios/
│       ├── prafful/
│       ├── aatir/
│       ├── mahi/
│       ├── palak/
│       └── ruchika/
│
├── backend/
│   ├── server.js
│   ├── routes/
│   │   └── contact.js
│   └── data/
│       └── contacts.json
│
└── README.md
