# 🚀 Inter State Traders

## 📌 Overview

**Inter State Traders** is a multi-vendor e-commerce platform that connects buyers and sellers across different states. It allows users to list products, make secure transactions, and track orders in real time.

---

## 🎯 Features

* 🔐 User Authentication (JWT आधारित सुरक्षित लॉगिन)
* 🛍️ Multi-Vendor Marketplace (Buyer & Seller roles)
* 📦 Product Management (Add, Update, Delete)
* 🛒 Order System with Tracking (Processing → Shipped → Delivered)
* 💳 Payment Integration Ready (Razorpay)
* 🧾 Invoice Generation (PDF Support)
* 🌐 REST API Architecture

---

## 🛠️ Tech Stack

* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **Authentication:** JWT
* **Encryption:** bcryptjs
* **API Testing:** Postman

---

## 📁 Project Structure

```
inter-state-traders/
│
├── config/
├── models/
├── routes/
├── middleware/
├── server.js
├── package.json
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```
git clone https://github.com/your-username/inter-state-traders.git
cd inter-state-traders
```

### 2️⃣ Install Dependencies

```
npm install
```

### 3️⃣ Configure Environment

Create a `.env` file and add:

```
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
```

### 4️⃣ Run Server

```
node server.js
```

---

## 🚀 API Endpoints

### 🔐 Auth

* POST `/api/auth/register`
* POST `/api/auth/login`

### 🛍️ Products

* GET `/api/products`
* POST `/api/products` (Protected)

### 📦 Orders

* POST `/api/orders` (Protected)
* GET `/api/orders` (Protected)

---

## 🔒 Security

* Password hashing using bcrypt
* Token-based authentication (JWT)
* Protected routes for authorized users

---

## 📈 Future Enhancements

* 📱 Mobile App (Android/iOS)
* 🤖 AI-based recommendations
* 💬 Chat between buyers & sellers
* 📊 Admin dashboard

---

## 👨‍💻 Author

Developed by **Priyansh Rajput**

---

## 📄 License

This project is licensed under the MIT License.
