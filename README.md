# 📚 Full-Stack Learning Management System (LMS)

A modern Learning Management System built using **Vite + React** for the frontend and **Node.js + Express + MongoDB** for the backend. This platform allows users to view, enroll in, and manage courses, making it ideal for e-learning platforms and coaching institutes.

---

## 🚀 Features

- 🧑‍🏫 Admin & Instructor dashboards
- 📦 Course creation, editing, and management
- 🎥 Video embedding and rich content editing
- 🧾 Secure payments integration with Stripe
- 🔐 User authentication (JWT-based)
- 📊 Student progress tracking
- 📨 Email notifications

---

## 🛠 Tech Stack

| Frontend         | Backend            | Database   | Others              |
|------------------|--------------------|------------|---------------------|
| React (Vite)     | Node.js (Express)  | MongoDB    | Stripe, JWT, React-Quill |
| Tailwind CSS     | REST API           | Mongoose   | dotenv, nodemailer  |

---

## 📁 Project Structure


---

## 🧑‍💻 Getting Started

### Prerequisites
- Node.js ≥ 18
- MongoDB Atlas account
- Stripe account (for payments)

### 1. Clone the repository
```bash
git clone https://github.com/sajal-123/lms.git
cd lms

cd server
npm install

PORT=5000
MONGODB_URI=your_mongodb_connection_string
STRIPE_SECRET_KEY=your_stripe_secret_key
JWT_SECRET=your_jwt_secret

npm run dev

cd ../client
npm install
npm run dev

