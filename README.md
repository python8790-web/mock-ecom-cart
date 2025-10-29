# 🛍️ Vibe Commerce — Mock E-Commerce Cart

A full-stack mock shopping cart application built for the **Vibe Commerce Internship Screening Assignment**.  
This project demonstrates **React frontend**, **Express backend**, and **SQLite database integration** with complete add-to-cart, remove, and checkout flows.

---

## 📖 Overview

The app simulates a simple e-commerce cart experience:

- Displays a list of products.
- Allows adding/removing items from the cart.
- Calculates total price dynamically.
- Mock checkout (no real payments) — generates a receipt with total and timestamp.

---

## ⚙️ Tech Stack

| Layer | Technology Used |
|-------|-----------------|
| Frontend | React (Vite) + Tailwind CSS |
| Backend | Node.js + Express |
| Database | SQLite (via `better-sqlite3`) |
| API Communication | REST APIs using Axios |

---

## 🧩 Features

✅ Product listing (5–10 mock products)  
✅ Add/Remove items to/from the cart  
✅ View total price in real-time  
✅ Checkout form (name/email)  
✅ Mock receipt generation (total + timestamp)  
✅ Responsive design (works on mobile & desktop)  
✅ Clean, minimal UI with Tailwind CSS  

---

## 🗂️ Folder Structure

mock-ecom-cart/
├─ backend/
│ ├─ index.js # Express server entry point
│ ├─ db.js # SQLite setup + seeding
│ ├─ routes/
│ │ ├─ products.js # /api/products
│ │ ├─ cart.js # /api/cart
│ │ └─ checkout.js # /api/checkout
│ └─ data/
│ └─ products_seed.json # Mock product data
│
├─ frontend/
│ ├─ src/
│ │ ├─ main.jsx
│ │ ├─ App.jsx
│ │ ├─ api.js
│ │ ├─ components/
│ │ │ ├─ Products.jsx
│ │ │ ├─ Cart.jsx
│ │ │ └─ CheckoutModal.jsx
│ └─ public/
│
├─ README.md
└─ demo_script.txt

## 🎥 Demo Video
Watch the demo: https://youtu.be/7_1j1fzJH24
